# **Verificando a Integridade de Arquivos com Linux**

## **Objetivo: Demonstrar como criar valores de hash para arquivos e comparar as diferenças entre eles manualmente.**

## **1. Acessando a pasta a pasta do usuário analyst e listando o conteúdo com o comando "ls", é possível visualizar dois arquivos que estão alocados no diretório.**

```bash  
/home/analyst/:~$ ls

file1.txt file2.txt  
```  
Arquivos identificados 

* file1.txt  
* file2.txt

## **2. Como o objetivo é comparar o conteúdo dos arquivos, listamos os conteúdos de ambos para verificá-los.**

```bash  
/home/analyst/:~$ cat file1.txt  
X5O!P%@AP[4PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*

/home/analyst/:~$ cat file2.txt  
X5O!P%@AP[4PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*  
```  
Analisando os arquivos e visualmente, eles não apresentam diferenças. 

## **3. Apesar da similaridade, é viável realizar algumas validações para verificar a integridade desses arquivos. Usando o comando sha256sum para calcular os resumos criptográficos dos arquivos.**

```bash  
/home/analyst/:~$ sha256sum file1.txt  
131f95c51cc819465fa1797f6ccacf9d494aaaff46fa3eac73ae63ffbdfd8267  file1.txt  
/home/analyst/:~$ sha256sum file2.txt  
2558ba9a4cad1e69804ce03aa2a029526179a91a5e38cb723320e83af9ca017b  file2.txt  
```  
      
Ao visualizar os resumos criptográficos, podemos validar que os arquivos são diferentes. 

## **4. Para uma melhor validação da integridade dos dois arquivos, é possível anexar a saída do comando sha256 em arquivos para compará-los.**

```bash  
/home/analyst/:~$ sha256sum file1.txt > file1hash.txt  
/home/analyst/:~$   
/home/analyst/:~$ sha256sum file2.txt > file2hash.txt  
/home/analyst/:~$  
```  
Comparando os arquivos usando o comando cmp, que compara os arquivos do conteúdo e indica a diferença entre eles.

```bash  
/home/analyst/:~$ cmp file1hash.txt file2hash.txt  
file1hash.txt file2hash.txt differ: char1, line 1  
```  
Comparando os arquivos usando o diff, que compara os arquivos e caso eles tenham alguma diferença, exibe o conteúdo na tela.

```bash  
/home/analyst/:~$ diff file1hash.txt file2hash.txt   
1c1  
< 131f95c51cc819465fa1797f6ccacf9d494aaaff46fa3eac73ae63ffbdfd8267  file1.txt  
---  
> 2558ba9a4cad1e69804ce03aa2a029526179a91a5e38cb723320e83af9ca017b  file2.txt  
```

