**Introdução ao Linux** 

Principais tópicos abordados:

* Arquitetura do Linux;  
* Diferentes distribuições;  
* Shell;

Linux é um sistema operacional de código aberto. Foi criado em duas partes. No início da década de 1990, duas pessoas diferentes estavam trabalhando separadamente em projetos para melhorar a engenharia de computadores. A primeira pessoa foi Linus Torvalds, Na época, o sistema operacional UNIX já estava em uso. Ele queria melhorá-lo e torná-lo de código aberto e acessível. O que foi revolucionário foi a introdução do kernel linux. 

Na mesma época, Richard Stallman começou a trabalhar no GNU. O GNU também era um sistema operacional baseado em UNIX.

Os dois decidiram compartilhar a ideia de criar um software gratuito e aberto a qualquer pessoa. Depois de trabalhar no GNU por alguns anos, o elemento que faltava para o software do kernel. 

A característica que torna o Linux único, é o fato de ser de código aberto, assim, qualquer pessoa pode ter acesso ao sistema operacional e ao código fonte. O Linux e muitos dos outros programas que vêm com o Linux licenciados sob os termos da Licença Pública GNU, que permite que todos possam utilizá-lo, compartilhá-lo e modificá-lo livremente.  Graças a um conjunto de recursos robusto, toda uma comunidade de desenvolvedores adotou o sistema operacional. 

O papel do analista de segurança diante da utilização do Linux é usar ferramentas e programas no trabalho do dia-a-dia. O analista pode examinar diferentes tipos de registros para identificar o que está acontecendo no sistema. Você pode se deparar com registros de erros ao investigar um problema. Outro local em que o Linux é utilizado, é na verificação de acesso e a autorização em um sistema de gerenciamento de identidade e acesso. Em segurança, gerenciar acesso é fundamental para garantir um sistema seguro. 

**Arquitetura do Linux**

Os componentes do Linux incluem o usuário, os aplicativos, o shell, o Filesystem Hierarchy Standard, o kernel e o hardware. 

O usuário é a pessoa que interage com o computador, ele é responsável por iniciar as tarefas ou os comandos que o sistema operacional executará. O Linux é um sistema multiusuário. Isso significa que mais de um usuário pode usar os recursos do sistema ao mesmo tempo. 

As aplicações são responsáveis por executar tarefas específicas, como um processador de texto ou uma calculadora. Os aplicativos linux são distribuídos por gerenciadores de pacotes.

Shell é o meio pelo qual o usuário se comunica com o sistema. O shell interpreta a linha de comando, processando comandos e gerando resultados. 

O responsável por organizar os dados dentro do sistema operacional é o Filesystem Hierarchy Standard, ou FHS. FHS é como os dados são armazenados em um sistema. É uma forma de organizar os dados para que possam ser encontrados quando os dados forem acessados pelo sistema.

O kernel é o componente que gerencia processos e memória, ele se comunica com o hardware para executar comandos enviados pelo shell. O kernel usa drivers para permitir que os aplicativos executem tarefas. O kernel linux ajuda a garantir que o sistema aloque recursos com mais eficiência e faça com que o sistema funcione mais rápido. 

O último componente é o hardware, esses são os componentes físicos de um computador. 

**Kali Linux**

O kali é uma distribuição do Linux usada para segurança da informação. O Kali Linux é uma marca registrada da Offensive Security e é derivada do Debian. Essa distribuição de código aberto foi feita especificamente com o objetivo de testes de penetração e perícia digital. O kali linux possui diversas ferramentas pré instaladas. É recomendado que o seu uso seja feito por meio de VMs, pois isso evita danos à sua máquina.

* **Metasploit:** projeto de segurança que fornece informações sobre vulnerabilidades de segurança e auxilia em testes de penetração e desenvolvimento de assinaturas IDS. Ele é propriedade da empresa de segurança **Rapid7.**    
    
  Seu subprojeto mais conhecido é o Metasploit Framework de código aberto, uma ferramenta para desenvolver e executar código de exploração contra uma máquina alvo remota. Outros subprojetos importantes incluem o Opcode Database, o arquivo shellcode e pesquisas relacionadas. O projeto metasploit inclui ferramentas anti-forenses e de evasão, algumas das quais são construídas no Metasploit Framework. Em vários sistemas operacionais, ele vem pré-instalado.

* **Burp Suite:** ferramenta de testes de segurança de aplicações web, o Burp suite atua como um proxy, permitindo interceptar e capturar as solicitações e respostas trocadas entre o navegador e a aplicação. Dessa forma, os profissionais de segurança da informação conseguem analisar detalhadamente os dados enviados e recebidos, identificando possíveis vulnerabilidades com precisão. 

* John the Ripper é uma ferramenta de hacking para crackear senhas durante exercícios de pentest. 

Como analista de segurança, seu trabalho pode envolver análise forense digital. A perícia digital é o processo de coleta e análise de dados para determinar o que aconteceu após o ataque. Por exemplo, você pode fazer uma análise investigativa dos dados relacionados à atividade da rede. O Kali Linux também é uma distribuição útil para profissionais de segurança envolvidos no trabalho forense digital. Tem um grande número de ferramentas que podem ser usadas para isso. Ex: o tcpdump é um analisador de pacotes de linha comando. É usado para capturar o tráfego da rede. Outra ferramenta comumente usada na profissão de segurança é o Wireshark. Ele tem uma interface gráfica de usuário que pode ser usada na profissão de segurança é o Wireshark.

**Gerenciadores de pacotes para instalar**

Um pacote de software é um software que pode ser combinado com outros pacotes para formar um aplicativo. Alguns pacotes podem ser grandes o suficiente para formar os aplicativos por conta própria. Os pacotes contêm os arquivos necessários para que um aplicativo seja instalado. Esses arquivos incluem dependências, que são arquivos suplementares usados para executar um aplicativo. Os gerenciadores de pacotes é uma ferramenta que ajuda os usuários a instalar, gerenciar e remover pacotes ou aplicativos. O Linux usa vários gerenciadores de pacotes. 

Observação: é importante usar a versão mais recente de um pacote sempre que possível. A versão mais recente tem as correções de erros e os patches de segurança mais atualizados. Isso ajuda a manter o sistema mais seguro. 

**Tipos de gerenciadores de pacotes** 

Algumas distribuições usadas derivam da mesma distribuição principal. O Kali, o Ubuntu e o Parrot são todos provenientes do Debian. O CentOS vem do Red hat.  
Esse conhecimento é útil ao instalar aplicativos porque determinados gerenciadores de pacotes funcionam com certas distribuições. Por exemplo, o Red Hat Package Manager (RPM) pode ser usado para distribuições Linux derivadas da Red Hat, e gerenciadores de pacotes como o dpkg podem ser usados para distribuições Linux derivadas do Debian. 

Gerenciadores de pacotes diferentes normalmente usam extensões de arquivos diferentes. Por exemplo, o gerenciador de pacotes red hat (RPM) tem arquivos que usam a extensão de arquivo .rpm, como Package-Version-Release Architecture.rpm. Os gerenciadores de pacotes para distribuições Linux derivadas do Debian, como o dpkg, têm arquivos que usam a extensão de arquivo .deb, como Package\_Version-Release\_Architecture.deb.

**Ferramentas de gerenciamento de pacotes**

Além dos gerenciadores de pacotes, como o RPM e o dpkg, há também ferramentas de gerenciamento de pacotes que permitem trabalhar facilmente com pacotes por meio do shell. Às vezes, as ferramentas de gerenciamento de pacotes são utilizadas em vez dos gerenciadores de pacotes porque permitem que os usuários executem tarefas básicas com mais facilidade, como a instalação de um novo pacote. Duas ferramentas notáveis são a Advanced Package Tool (APT) e o Yellowdog Updater Modified (YUM). 

**Ferramentas de Pacotes Avançados (APT)**

O APT é uma ferramenta usada nas distribuições derivadas do Debian. Ele é executado a partir da interface de Linha de comando para gerenciar, pesquisar e instalar pacotes. 

**Yellowdog Updater Modified**

 O YUM é uma ferramenta usada nas distribuições derivadas do Red Hat. É executada a partir da interface de Linha de Comando para gerenciar, pesquisar e instalar pacotes. O YUM trabalha com arquivos .rpm.

Tarefa prática  
1 \- validar pacotes instalados  
2 \- instalar pacotes  
3 \- remover pacotes instalados  
4 \- verificar pacotes instalados  
comando: `apt list --installed`

5 \-  

**Shell** 

É um interpretador da linha de comando. Isso significa que ele ajuda você a se comunicar com o sistema operacional por meio de linha de comando. Anteriormente, discutimos uma interface de linha de comando. O shell fornece a interface de linha de comando para você interagir com o sistema operacional. Para dizer ao sistema operacional. Para dizer ao sistema operacional o que fazer, você insere comandos nessa interface. Um comando é uma instrução que diz ao computador que faça alguma coisa. O shell se comunica com o kernel para executar comandos.

O shell é a parte do sistema operacional que permite fazer isso. Pense nisso com computador ou binário, não pode se comunicar diretamente com seu sistema. O sistema não precisa do shell para a maior parte do trabalho, mas é uma interface entre o usuário e o que o sistema pode oferecer. 

**Diferentes tipos de Shell**

* Bourne-Again Shell (bash)  
* C++ Shell (csh)  
* Korn Shell (ksh)  
* Shell em C aprimorado (tcsh)  
* Z Shell (zsh)

Todos os shells do Linux usam linhas de comando comuns no Linux, mas podem diferir em outros recursos. Por exemplo, o ksh e o bash usam o cifrão ($) para indicar onde os usuários digitam seus comandos. Outros shells, como o zsh, usam o sinal de porcentagem (%) para essa finalidade. 

**Bash**

É o shell padrão na maioria das distribuições Linux. É considerado um shell fácil de usar. Você pode usar o bash para comandos básicos do Linux, bem como para projetos maiores. 

O Bash também é o shell mais popular na profissão de segurança cibernética. Você usará o bash ao longo deste curso para aprender e praticar os comandos do Linux.

**Principais Lições**

Os shells são uma parte fundamental do sistema operacional Linux. Os shell permitem que você dê comandos ao computador e receba respostas dele. Eles podem ser considerados como um tradutor entre você e o sistema do computador. Há muitos tipos diferentes de shells, mas o shell bash é o mais comumente usado na profissão de segurança cibernética.  

**Entrada e Saída no Shell**

A entrada padrão consiste em informações recebidas pelo sistema operacional por meio de linha de comando. É como se o usuário fizesse uma pergunta a um amigo durante uma conversa. As informações são inseridas no teclado no shell. Se o shell puder interpretar a solicitação, ele solicitará ao kernel os recursos necessários para executar a tarefa relacionada. 

O comando Echo é um comando Linux que gera uma sequência de texto especificada. Dados de string são dados que consistem em uma sequência ordenada de caracteres.

Saída padrão é a informação retornada pelo sistema operacional por meio do shell.  

**Comandos do Linux via Shell Bash**

Bash é o shell padrão na maioria das distribuições Linux. Na maioria das vezes, os principais comandos Linux que você aprenderá nesta seção são os mesmos em todos os shells. A comunicação com sistema operacional é como uma conversa. O usuário digita comandos e o sistema operacional responde  com uma resposta ao comando. Um comando é uma instrução que diz ao computador que faça alguma coisa.

**Comandos principais para navegação e leitura de arquivos** 

Um dos mais importantes componentes do Linux é o Filesystem Hierarchy Standard, ou FHS, é o componente do sistema operacional Linux que organiza os dados. Esses sistema de arquivos é uma parte muito importante do Linux porque tudo o que fazemos no Linux é considerado um arquivo em algum lugar no diretório do sistema. O FHS é um sistema hierárquico e, assim como uma árvore, tudo cresce e se ramifica da raiz. O diretório raiz é o diretório de nível mais alto no Linux. É designado por uma única barra. Os subdiretórios se ramificam do diretório raiz. Os subdiretórios se ramificam cada vez mais longe do diretório raiz. Ao descrever a estrutura de diretórios no Linux, barras são usadas ao rastrear essas ramificações até a raiz. 

Alguns comandos são mais usados no Linux, ex: pwd, que exibe a atual localização onde o usuário está no subdiretório, o ls, é utilizado para listar os arquivos e diretórios que estão em um diretório e cd, é usado para navegar entre os diretórios. Alguns outros comandos utilizados são: o cat, que mostra um conteúdo de um arquivo, caso não queira visualizar o arquivo por completo, pode-se usar o complemento head junto com o cat, para visualizar somente o início(10 linhas).

**Padrão de Hierarquia do sistema de arquivo (FHS)**

O FHS é importante porque define como os diretórios, o conteúdo dos diretórios e outros armazenamentos são organizados no sistema operacional. A estrutura dos diretórios no Linux:

**Diretório Raiz:**  
   
É o diretório de nível mais alto no Linux e é sempre representado por uma barra (/). Todos os subdiretórios se ramificam a partir do diretório raiz. Os subdiretórios podem continuar se ramificando em quantos níveis forem necessários.

**Diretórios padrão da FHS**

Diretamente abaixo do diretório raiz, você encontrará os diretórios padrão da FHS. No diagrama, home, bin e etc são diretórios padrão do FHS. Aqui estão alguns exemplos do que os diretórios padrão contém:

* /home \- cada usuário do sistema tem seu próprio diretório pessoal.  
* /bin \- esse diretório quer dizer binário e contém arquivos binários e outros executáveis. Executáveis são arquivos que contém uma série de comandos que os computadores precisam seguir para executar programas e realizar outras funções.   
* /etc \- este diretório armazena os arquivos de configuração do sistema.   
* /tmp \- Esse diretório armazena muitos dos arquivos temporários. O diretório /tmp é comumente usado por atacantes porque qualquer pessoa no sistema pode modificar os dados nesses arquivos.  
* /mnt \- esse diretório significa “montagem” e armazena mídia, como unidades USB e discos rígidos.

**Dica importante:** para saber mais sobre FHS e seus diretórios padrão, pode-se usar o comando “man hier”

**Subdiretórios específicos do usuário** 

Em “home” há subdiretórios para usuários específicos. Quando um caminho leva abaixo do diretório inicial do usuário pode ser representado pelo “\~”.

A navegação em subdiretórios pode ser feita por dois meios, usando o caminho relativo e usando o caminho absoluto. O caminho absoluto é quando o usuário descreve todas as subpastas até chegar ao arquivo que ele deseja acessar, já o caminho relativo, ele navega a partir da pasta que ele está, atualmente. 

**Obs:**  os caminhos relativos podem usar um ponto para representar o diretório atual, ou dois para identificar o diretório que vem antes do diretório atual. 

**Comandos Chaves para navegar em sistemas de arquivos**

Os principais comandos são o pwd, ls e cd. 

* **pwd** \- imprime o diretórios de trabalho na tela. A saída do comando oferece o caminho absoluto para o diretório.

**Obs:** Para saber qual é o nome do usuário, usa-se o comando **whoami.**

* **ls \-** O comando **ls** exibe os nomes dos arquivos e diretórios que estão no diretório atual  
* **cd \-**  navega entre os diretórios. para retornar ao diretório anterior, utiliza-se o ponto duplo  e barra: **“../”**

**Comandos Comuns para leitura de arquivos** 

* **cat \-**  exibe o conteúdo de um arquivo.  
* **head** \- exibe apenas o início do conteúdo do arquivo.

  Para mudar o número de linhas retornadas só usar o parâmetro: \-n com a quantidade de linhas.

* **Tail \-**  exibe as últimas linhas de um arquivo.  
* **less \-** retorna o conteúdo, mas uma página de cada vez.

Dicas importantes: O analista de segurança de informação tem o papel de filtrar informações que são necessárias. Isso significa pesquisar em sistema informações específicas que possam ajudar a resolver problemas complexos. Ex: Imagine que a equipe determina que um malware contém uma sequência de caracteres. O analista pode ter a tarefa de encontrar outros arquivos com a mesma string para determinar se esses arquivos contêm o mesmo malware. 

**grep \-**  o comando grep pesquisa um arquivo especificado e retorna todas as linhas do contendo uma string especificada. Digamos que existe um arquivo chamado updates.txt e, no momento, estamos procurando linhas que contenham a palavra: OS. Se o arquivo for grande, levaria muito tempo para digitalizá-lo visualmente. Em vez disso, depois de navegar até o diretório que contém o updates.txt, digitarmos o comando: grep OS updates.txt no shell. A estrutura do comando grep, tem como primeiro argumento a string desejada, depois, o nome do arquivo.

**ex: grep OS updates.txt**  
**ex: ls /home/analyst/reports | grep users**

**Piping \-** é um comando do Linux que pode ser usado para diversas finalidades. O comando pipe envia uma saída padrão de um comando como entrada padrão para outro comando para processamento adicional. É representado pelo carácter da barra vertical. 

**find \-**  procura diretórios e arquivos que atendam aos critérios especificados. Há uma grande variedade de critérios que podem ser especificados com find. Ex: pesquisar arquivos e diretórios que:

* contenham uma cadeia de caracteres específica no nome;  
* tenham um determinado tamanho de arquivo;  
* foram modificados pela última vez em um determinado período de tempo.

Ao usar o find, o primeiro argumento após o find indica onde começar a pesquisa. Por exemplo, digitando find /home/analyst/projects, você procura tudo o que começa no diretório projects.

Após esse primeiro argumento, você precisa indicar seus critérios para a pesquisa. Se você não incluir um critério de pesquisa específico com o segundo argumento, a pesquisa provavelmente retornará a muitos diretórios e arquivos. 

* **\-name e \-iname \-**  um dos principais critérios que os analistas podem usar       com find é encontrar nomes de arquivos ou diretórios que contenham uma string específica. A cadeia de caracteres específica que está sendo procurada deve ser inserida entre aspas após as opções \-name ou \-iname. A diferença entre essas duas opções é que \-name indica diferencia maiusculas de minúsculas e \-iname não.    
    
  Ex: Pesquisar por todos os arquivos no diretório project que contenha a palavra “log” no nome do arquivo.   
    
  **comando:**  find /home/analyst/projects \-name “\*log\*”  
    
  obs: o asterisco é usado para representar caracteres desconhecidos.  
    
* **\-mtime** \- analistas podem usar o find para encontrar arquivos ou diretórios que foram modificados em um intervalo de tempo, para isso usam a opção \-mtime.  
    
  Ex: Pesquisar um arquivo ou  diretório que foi modificado nos últimos 3 dias.  
    
  **comando:** find /home/analyst/projects \-mtime \-3 

**Criar e modificar diretórios e arquivos**

Quando se trata de trabalhar com dados de segurança, a organização é fundamental. Se soubermos onde as informações estão localizadas, será mais fácil detectar problemas e manter as informações seguras. No Linux, temos diretórios. Os diretórios ajudam a organizar informações. No Linux, temos diretórios. Os critérios ajudam a organizar arquivos e subdiretórios. Ex: um diretório para relatórios, um analista pode precisar criar dois subdiretórios: um para rascunhos e outro para relatórios finais. 

mkdir \- comando para criar um novo diretório.   
rmdir \- comando para remover um diretório.

Um recurso muito útil desse comando é o aviso embutido que permite que você saiba que um diretório não está vazio. Isso evita a exclusão de arquivos acidentalmente. 

touch \- cria um novo arquivo.  
rm \- remova um arquivo.  
mv \- move um arquivo.  
cp \- copia um arquivo ou diretório em um novo local.

Redirecionamento de saída padrão

Além do piping, é possível utilizar operadores de colchete de ângulo reto (\>) e colchete de ângulo reto duplo (\>\>) para redirecionar a saída padrão. 

Quando usados em echo, os operadores \> e \>\> podem ser usados para enviar a saída de echo para um arquivo especificado em vez de para a tela. A diferença entre os dois é que \> sobrescreve o arquivo existente e \>\> adiciona seu conteúdo ao final do arquivo existente em vez de sobrescrevê-lo. O operador \> deve ser usado com cuidado, pois não é fácil recuperar arquivos sobrescritos. 

**Autenticação e autorização de usuários**

As permissões são o tipo de acesso concedido a um arquivo ou diretório. As permissões estão relacionadas à autorização. Autorização é o conceito de conceder acesso a recursos específicos em um sistema. A autorização permite limitar o acesso a arquivos ou diretórios específicos. Uma boa regra a seguir é que o acesso aos dados é feito com base na necessidade de conhecimento. O risco de segurança que isso imporia se alguém pudesse acessar ou modificar qualquer coisa que quisesse em um sistema.

Há três tipos de permissões no Linux que um usuário autorizado pode ter. O primeiro tipo de permissão é de leitura. 

Em um arquivo, as permissões de leitura significam que o conteúdo do arquivo pode ser lido. Em um diretório, essa permissão significa que você pode ler todos os arquivos nesse diretório.

 Em seguida, estão as permissões de gravação. As permissões de gravação em um arquivo permitem modificações no conteúdo do arquivo. Em um diretório, as permissões de gravação indicam que novos arquivos podem ser criados nesse diretório.

Por fim, também existem permissões de execução. Permissões de execução em arquivos significam que o arquivo pode ser executado se for um arquivo executável. As permissões de execução em diretórios permitem que os usuários entrem em um diretório e acessem seus arquivos. 

As permissões são concedidas para três tipos diferentes de proprietários. O primeiro tipo é o usuário. O usuário é o proprietário do arquivo. Ao criar um arquivo, você se torna o proprietário do arquivo, mas a propriedade pode ser alterada. Grupo é o próximo tipo. Cada usuário faz parte de um determinado grupo. Um grupo consiste em vários usuários, e essa é uma forma de gerenciar um ambiente multiusuário. Finalmente, há outro. Outros podem ser considerados todos os usuários do sistema. Basicamente, qualquer outra pessoa com acesso ao sistema pertence a esse grupo. No Linux, as permissões são representadas por uma string de 10 caracteres. Para um diretório com permissões completas para o grupo de usuários, essa string seria drwxrwxrwx.

O primeiro caractere indica o tipo de arquivo. Conforme mostrado neste exemplo, “d“ é usado para indicar que é um diretório. Se, em vez disso, esse caractere contivesse um hífen, seria um arquivo normal. O segundo, terceiro e quarto caracteres indicam as permissões de leitura, “w” indica que o usuário tem permissões de gravação e x indica que o usuário tem permissões de execução. Se uma dessas permissões estivesse ausente, haveria um hífen em vez da letra. Da mesma forma, o quinto, o sexto e o sétimo carácter indicam permissões para o próximo grupo de tipos de proprietários. Finalmente, do oitavo ao décimo caractere indicam permissões para o  último tipo de proprietário: o outro. Eles também têm permissões de leitura, gravação e execução neste exemplo. 

Garantir que os arquivos e diretórios sejam configurados com as permissões de acesso apropriadas é fundamental para proteger arquivos confidenciais e manter a segurança geral de um sistema. Ex: os departamentos de folha de pagamento lidam com informações confidenciais. Se alguém fora do grupo de folha de pagamento pudesse ler esse arquivo, isso seria uma preocupação com a privacidade. Outro exemplo é quando o usuário, o grupo e outros podem gravar em um arquivo. Esse tipo de arquivo é considerado um arquivo gravável mundialmente. Arquivos graváveis em todo o mundo podem representar riscos de segurança significativos. 

Para verificar as permissões, é interessante entender quais são as opções. As opções modificam o comportamento do comando. As opções para um comando podem ser uma única letra ou uma palavra inteira. A verificação de permissões envolve a adição de opções ao comando ls.”**ls \-l”** exibe as permissões para arquivos e diretórios. Talvez você também queira exibir arquivos ocultos e identificar suas permissões. Arquivos ocultos, que começam com um antes do nome, normalmente não aparecem quando você usa “ls” para exibir o conteúdo do arquivo.  Digitar **“ls \-a”**  exibe arquivos ocultos. Em seguida, você pode combinar essas duas opções para fazer as duas coisas. Digitar “ls \-la” exibe as permissões para arquivos e diretórios, incluindo arquivos ocultos.

**Mudanças de permissões** 

Ao trabalhar como analista de segurança, pode haver vários motivos para alterar permissões de um usuário. Um usuário pode ter mudado de departamento ou ter sido atribuído a um grupo de trabalho diferente. Um usuário pode simplesmente não estar mais trabalhando em um projeto que exige determinadas permissões. Essas alterações são necessárias para proteger os arquivos do sistema de serem acidentalmente ou deliberadamente alterados ou excluídos. 

**chmod \-** altera as permissões em arquivos e diretórios. O comando chmod significa modo de segurança. 

Com o chmod, é necessário identificar para qual arquivo ou diretório deseja ajustar as permissões. Esse é  o argumento final, neste caso, um arquivo chamado: access.txt. O primeiro argumento, adicionado diretamente após o comando chmod, indica como alterar as permissões. 

Existem três tipos de usuários: usuário, grupo, outros. Para identificá-lo com chmod, usamos “u” para representar o usuário, “g” para representar o grupo e “o” para representar os outros. 

**Ex: chmod g+w, o-r access.txt**

Neste exemplo, “g” indica que faremos algumas alterações nas permissões do grupo e “o” nas permissões de outros. Esses tipos de proprietários são separados por uma vírgula nesse argumento.

Há possibilidade de retirar ou conceder permissões, com isso são usados os operadores matemáticos. O sinal de mais depois do “g” significa que está concedendo a permissão de gravação e  sinal de menos depois do “o” significa que está sendo retirada a permissão de leitura. 

**Adicionar e excluir usuários**

**Tipos diferentes de usuários**  
Os usuários que podem ser usuário raiz ou superusuário. Esse usuário possui privilégios elevados para modificar o sistema. Usuários regulares têm limitações, enquanto o usuário raiz ou “root” não.

Indivíduos que precisam realizar tarefas específicas podem ser temporariamente adicionados como usuários root. Os usuários root podem criar, modificar ou excluir qualquer arquivo e executar qualquer programa. Somente usuários root ou contas com privilégios root podem adicionar novos usuários. 

Executar comandos como usuário root é potencialmente perigoso, pois pode gerar problemas de registro como root e isto é um risco de segurança. Atores maliciosos sempre tentarão violar a conta root. Como é a conta que possui mais privilégios, as autenticações como usuário root devem ser desativadas, outro erro, é que é fácil cometer erros irreversíveis. 

É muito fácil digitar o comando errado na CLI, se você estiver executado como usuário raiz, corre um risco maior de cometer um erro irreversível, como excluir permanentemente um diretório. Finalmente, há a preocupação com a responsabilidade. Em um ambiente multiusuário como o Linux, existem muitos usuários. Se um usuário estiver executando como root, não há como rastrear quem exatamente executou um comando. Uma solução para ajudar a resolver esse problema é o sudo.

sudo é o comando que concede temporariamente permissões elevadas a usuários específicos. Isso fornece uma abordagem mais controlada em comparação com  root, que executa todos os comandos com privilégios de root. O sudo resolve muitos problemas associados à execução como root. 

O sudo vem do super usuário e permite que você execute comandos como usuários elevados sem precisar entrar e sair de outra conta. A execução do sudo solicitará que você insira a senha do usuário com o qual você está conectado no momento. Nem todos os usuários de um sistema podem se tornar super usuário. Os usuários devem ter acesso ao sudo por meio de um arquivo de configuração chamado sudoers. 

O comando é useradd adiciona um usuário ao sistema. Somente usuários root ou com privilégios sudo podem usar um comando useradd. Vejamos um exemplo específico no qual precisamos adicionar um usuário. 

Comando para adicionar um usuário:

**sudo useradd salesrep7**

Comando para excluir um usuário:  
   
**sudo userdel salesrep7**

**Autenticação e autorização com o sudo**

Você pode usar o **sudo**  com muitas tarefas de autenticação e gerenciamento de autorização. Como lembrete, autenticação é o processamento de verificação de identidade de alguém e autorização é o conceito de concessão de acesso a recursos em um sistema. Alguns dos principais comandos usados para essas tarefas sãos os seguintes:

useradd

o comando useradd adiciona um usuário ao sistema. Para adicionar um usuário fgarcia com sudo, digite sudo useradd garcia. Há opções adicionais que podem ser usadas com useradd:

\-g:  Define o grupo padrão do usuário, também chamado de grupo primário.

\-G: Adicionar o usuário a grupos adicionais, também chamados de grupos suplementares ou secundários. 

Para usar a opção \-g, o grupo primário deve ser especificado após \-g.   
Por exemplo, digitar 

**sudo useradd \-g security fgarcia** 

adiciona fgarcia como um novo usuário e atribui a seu grupo  primário o endereço security.

 **usermod**   
O comando usermod modifica as contas usuário existentes. As mesmas opções \-g e \-G do comando useradd podem ser usadas com usermod se já existir um usuário.

Para alterar o grupo principal de um usuário existente, é necessária a opção \-g. Por exemplo, digitar sudo usermod \-g executive fgarcia alteraria  grupo primário de fgarcia para o grupo executive. 

Para adicionar um grupo suplementar a um usuário existente, é necessária a opção \-G. Também é necessária a opção \-a, que anexa o usuário a um grupo existente e só é usada com a opção \-G. Ex: sudo usermod \-a \-G marketing fgarcia adicionaria o usuário fgarcia existente ao grupo suplementar marketing. 

Obs: ao mudar o grupo suplementar de um usuário existente, se você não incluir a opção \-a, \-G substituirá todos os grupos suplementares existentes pelos grupos especificados após usermod. O uso de \-a com \-G garante que os novos grupos sejam adicionados, mas que os grupos existentes não sejam  substituídos.

Há outras pções que podem ser usadas com usermod para especificar como deseja modificar o usuários incluindo:

\-d: Mudança do diretório inicial do usuário.  
\-l:  Mudança do nome de login do usuário.   
\-L:  Bloqueia a conta para que o usuário não possa registrar. 

A opção sempre vem depois do comando usermod. Ex: para mudar o diretório inicial de fgarcia para /home/garcia\_f, digite sudo usermod \-d /home/garcia\_f    fgarcia. A opção \-d segue diretamente o comando usermod antes dos outros dois argumentos necessários. 

**chown** 

O comando muda a propriedade de um arquivo ou diretório. É possível usar chown para alterar a propriedade do usuário ou do grupo. Para alterar o proprietário do usuário do arquivo access.txt para garcia, usar o comando:  sudo chown garcia access.txt. Para alterar o proprietário do grupo de access.txt para security, digite chown :security access.txt.  

**Suporte Integrado ao Linux**

**man**

O comando man exibe informações sobre outros comandos e como eles funcionam. É a abreviação de “manual” procurar informações sobre um comando, digite o comando após man. Por exemplo, digitar  **man chown** retorna informações detalhadas sobre **chown,** incluindo as várias opções que podem ser usadas com ele. A saída do comando **man**  também é chamada de página manual.  

**apropos**

 O comando apropos pesquisa as descrições das páginas de manual em busca de uma string especificada. As páginas de manual podem ser longas e difíceis de pesquisar se você estiver procurando uma palavra chave específica. Para usar apropos, digite a palavra-chave após apropos. 

O usuário também pode incluir a opção \-a para pesquisa várias palavras. Por exemplo, digitar **apropos \-a graph editor**  gera páginas de manual que contenham as palavras “graph” e “editor” em suas descrições. 

**whatis**

O comando whatis exibe a descrição de um comando em uma única linha. 

Para mais informações:   
[https://unix.stackexchange.com/](https://unix.stackexchange.com/)  
https://docs.google.com/document/d/1flGzGBZBo8vtX6Wiphf0K78yeL9OhQ-o9ShCX8K58CA/template/preview