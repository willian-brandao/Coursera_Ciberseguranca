**Introdução a sistemas operacionais** 

Principais Objetivos

* Descrever as funções principais de um sistemas operacional.  
* Reconhecer o uso mais comum de um sistema operacional.  
* Explicar a relação entre sistemas operacionais, aplicações e hardware.  
* Comparar o uso de interfaces gráficas e interfaces de linha de comando. 

**O que é um sistema operacional?**

É uma interface entre o hardware do computador e o usuário. O sistema operacional, ou SO, é responsável por fazer o computador funcionar da maneira mais eficiente possível enquanto faz com que o uso seja fácil. Hardware também se refere a parte física dos componentes do computador. 

A interface do sistema operacional em que agora confiamos todos dias é algo que os primeiros computadores não possuíam.  Nos anos 1950’s, o grande desafio com os primeiros computadores era  o tempo que eles levavam para rodar um programa. Naquele tempo, computadores não eram capazes de rodar múltiplos programas simultaneamente. Ao invés disso, as pessoas tinham que esperar o programa terminar de rodar, resetar o computador, e carregar um novo programa. Imagine ter que ligar e desligar um programa a cada momento para abrir uma nova aplicação. Isso poderia levar muito tempo para completar uma simples tarefa como enviar um email. Desde então, os sistemas operacionais evoluíram e não temos mais que nos preocupar com isso. 

Outra razão do porquê sistemas operacionais são importantes é que eles ajudam os humanos e computadores a se comunicarem uns  com os outros, Computadores se comunicam com a linguagem chamada como binário, que consiste em 0s e 1s. O sistema operacional provê uma interface para conectar o gap de comunicação entre usuário e computador, disponibilizando a interação entre usuário e computadores em caminhos complexos. 

Sistemas operacionais são essenciais para o uso de computadores. Da mesma forma, a segurança de sistemas operacionais também é crítica para para a segurança de um computador. Isso envolve arquivos de segurança, acesso a dados e autenticação de usuários para ajudar a proteger e prevenir contra ameaças como vírus, vermes e malwares. Saber como os sistemas operacionais trabalham é essencial para completar tarefas relacionadas à segurança. Por exemplo, como analista de segurança, a pessoa é responsável por configurar e fazer a manutenção da segurança do sistema operacional administrando o acesso. Você também será responsável por administrar e configurar firewalls, configurar políticas de segurança, habilitando proteção antivírus, fazendo auditorias, contabilidade e autenticação para detectar comportamentos incomuns. 

**Comparando Sistemas Operacionais**

Sistemas operacionais comuns: windows, macOS, Linux, chromeOS. android e IOS.  
**Windows e Mac**

O Windows foi introduzido em 1985, e o Mac foi introduzido em 1984\. Todos os dois sistemas operacionais são utilizados em computadores pessoais e corporativos. Windows é um sistema operacional fechado, isso significa que o código fonte não é disponibilizado gratuitamente para o público. O mac é parcialmente open source. 

**Linux** 

A primeira versão do Linux foi lançada em 1991, e outros principais lançamentos foram feitos nos anos 90\. Linux é completamente open-source, isso significa que qualquer um pode acessar seu código fonte. Linux é particularmente importante para a indústria de segurança. Existem várias distribuições que são especificamente desenhadas para segurança. 

**ChromeOs** 

Lançado em 2011\. Esse sistema operacional é parcialmente open-source e é derivado do Chromium OS, que é completamente open-source. Esse sistema operacional é utilizado no campo da educação. 

**Android e IOS**

Android e IOS são sistemas operacionais desenhados para dispositivos móveis. Diferente dos outros sistemas operacionais mencionados, os sistemas operacionais móveis são usados em dispositivos móveis, como smartphones, tablets e relógios.  
    
**Sistemas operacionais e vulnerabilidades**

Problemas de segurança são inevitáveis com todos sistemas operacionais. Uma importante parte de proteção dos sistemas operacionais é manter todos os componentes atualizados. 

**Sistemas Operacionais Legado**

É um sistema operacional que é desatualizado mas ainda é utilizado. Algumas organizações continuam a usar sistemas operacionais legados porque o software em que eles confiam não é compatível com sistemas operacionais mais novos. Isso é comum de acontecer com equipamentos que requerem softwares embarcados, 

**Dentro dos Sistemas Operacionais** 

O papel do sistema operacional é ajudar o computador a rodar programas eficientemente. O sistema operacional faz isso cuidando de todos os detalhes complicados relacionados ao controle de hardware do computador, para que você não precise fazer isso. 

Algumas coisas acontecem quando você liga o computador. Quando você pressiona o botão power, você interage com o hardware. Isso ativa o computador e inicia o sistema operacional. Inicializar o computador significa que um micro chip especial chamado BIOS está ativado. Em muitos computadores construídos após 2007, o chip foi substituído pelo UEFI.

Tanto o BIOS quanto o UEFI contêm instruções de inicialização que são responsáveis por carregar um programa especial chamado carregador inicialização. Em seguida, o carregador de inicialização é responsável por iniciar o sistema operacional. Sem mais nem menos, seu computador está ligado.

Como analista de segurança, entender processos pode ser útil para você. Vulnerabilidades podem ocorrer em algo como um processo de inicialização, Frequentemente, o BIOS não é verificado pelo software antivírus, portanto, pode ficar vulnerável à infecção por malware. 

O processamento começa com o usuário. E para concluir tarefas, o usuário utiliza aplicativos no computador. Um aplicativo é um programa que executa uma tarefa específica. Quando o usuário faz isso, o aplicativo envia a solicitação ao sistema operacional. A partir daí, o sistema operacional interpreta essa solicitação e a direciona para o componente apropriado do hardware do computador. 

O hardware consiste em todos os componentes físicos do computador. O hardware também enviará informações de volta ao sistema operacional. E isso, por sua vez, é enviado de volta ao aplicativo.

Solicitações ao Sistema Operacional 

Os sistemas operacionais são um componente essencial de um computador. Eles fazem conexões entre aplicativos e hardware para permitir que os usuários realizem tarefas. 

**Inicializando o computador**

Quando o computador, um micro chip BIOS ou UEFI é ativado. O Basic Input/Output System (BIOS) é um microchip que contém instruções de carga para o computador e é predominante em sistemas mais antigos. A UEFI (Unified Extensible Firmware Interface) é um microchip que contém instruções de carga para o computador e substitui o BIOS em sistemas mais modernos. 

Os chips BIOS e UEFI executam a mesma função para inicializar o computador. O BIOS era o chip padrão até 2007, quando os chips UEFI começaram a ser mais usados. Atualmente, a maioria dos computadores novos inclui um chip UEFI. A UEFI oferece recursos de segurança aprimorados. 

Os microchips BIOS ou UEFI contêm uma variedade de instruções de carga para o computador seguir. Por exemplo, uma das instruções de carga é verificar a integridade do hardware do computador. 

A última instrução do BIOS ou da UEFI ativa o carregador de inicialização. O carregador de inicialização é um software que inicializa o sistema operacional. Após a inicialização do sistema operacional, o computador estará pronto para uso. 

**Integridade de uma tarefa**

Depois do processo de inicialização, a conclusão da tarefa em um computador é um processo de quatro partes. 

**user \-\> aplicação \-\> sistema operacional**   
   
**Usuário**

A primeira parte do processamento é o usuário. O usuário inicia o processamento quando tem algo que deseja realizar no computador. Neste momento, você é um usuário\! Você iniciou o processo de acesso a esta leitura. 

**Aplicativo**

O aplicativo é o software com o qual os usuários interagem para concluir uma tarefa. Por exemplo, se quiser calcular algo, o aplicativo utilizado seria a calculadora. Essa é a segunda parte do processamento.

**Sistema Operacional**

O sistema operacional recebe a solicitação do usuário do aplicativo. O trabalho do sistema operacional é interpretar a solicitação e direcionar seu fluxo. Para concluir a tarefa, o sistema operacional a envia para os componentes aplicáveis do hardware. 

**Hardware**

O hardware é onde todo o processamento é feito para concluir as tarefas iniciadas pelo usuário. Por exemplo, quando um usuário deseja calcular um número, a CPU calcula a resposta. Como outro exemplo, quando um usuário deseja salvar um arquivo, outro componente do hardware, o disco rígido, processa a tarefa. Depois que o hardware faz o trabalho, ele envia a saída de volta ao aplicativo por meio do sistema operacional para que ele possa exibir os resultados para o usuário. 

**O sistema operacional em ação nos bastidores** 

Há processos que não podem ser observados diretamente ao operar um carro, mas eles o sentem avançar quando pressionam o pedal do acelerador. O mesmo acontece com um computador. Dentro de um computador, ocorre um trabalho importante que não é observado diretamente. Esse trabalho envolve o sistema operacional.

**Alocação de recursos por meio do sistema operacional** 

O sistema operacional não apenas interage com outras partes do computador, ele também é responsável por gerenciar recursos do sistema. Essa é uma grande tarefa que exige muito equilíbrio para garantir que todos os recursos do computador sejam usados com eficiência. Pense nisso como o conceito de energia. Uma pessoa precisa de energia para realizar tarefas diferentes. Algumas tarefas demandam mais energia, enquanto outras demandam menos. Ex: Correr exige mais energia que assistir TV. O sistema operacional de um computador também precisa garantir que ele tenha energia suficiente para funcionar corretamente em determinadas tarefas. Executar um antivírus consumirá mais energia do que usar a calculadora. 

Em um computador, um sistema operacional é o condutor. O sistema operacional lida com o gerenciamento de recursos e memória para garantir que a capacidade limitada do computador seja usada onde ela é necessária. Uma variedade de programas, tarefas e processos estão constantemente competindo pelos recursos da unidade central de processamento, ou CPU. Todos eles têm seus próprios motivos pelos quais precisam de memória, armazenamento e largura de banda de entrada/saída. O sistema operacional é responsável por garantir que cada programa esteja alocando e desalocando recursos. Tudo isso ocorre no seu computador ao mesmo tempo para que o sistema funcione com eficiência. 

O gerenciador de tarefas lista todas as tarefas a serem processadas, junto com o uso da memória e CPU.

**Virtualização**

**O que é uma máquina virtual?**

É uma versão virtual de um computador físico. As máquinas virtuais são um exemplo de virtualização. A virtualização é o processamento de uso de software para criar apresentações virtuais de várias máquinas físicas. O termo virtual refere-se a máquinas que não existem fisicamente, mas que operam como se existissem porque seu software simula o hardware físico. Os sistemas virtuais não usam hardware físico dedicado. Em vez disso, eles usam versões definidas por software do hardware físico. Isso significa que uma única máquina virtual tem uma CPU virtual, um armazenamento virtual e outro hardware virtual. Os sistemas virtuais são apenas códigos. 

É possível executar várias máquinas virtuais usando o hardware físico de um único computador. Isso envolve a divisão dos recursos do computador host para serem compartilhados entre todos os componentes físicos e virtuais. A RAM é um componente de hardware usado para memória de curto prazo. Se um computador tiver 16GB de RAM, ele poderá hospedar três máquinas virtuais, de modo que o computador físico e as máquinas virtuais tenham 4GB de RAM cada. Além disso, cada uma dessas máquinas virtuais teria seu próprio sistema operacional e funcionaria de forma semelhante a um computador comum.

**Segurança**

Um dos benefícios é que a virtualização pode fornecer um ambiente isolado, ou um sandbox, na máquina hospedeira física. Quando um computador tem várias máquinas virtuais, essas máquinas são convidadas do computador. Especificamente, elas são isoladas do computador host e de outras máquinas virtuais convidadas. Isso proporciona uma camada de segurança, pois as máquinas virtuais podem ser mantidas separadas dos outros sistemas. Ex, se uma máquina virtual individual for infectada por malware, ela poderá ser tratada com mais segurança porque está isolada das outras máquinas. Um profissional de segurança também pode colocar intencionalmente um malware em uma máquina virtual para examiná-la em um ambiente mais seguro. 

**Observação:** embora o uso de máquinas virtuais seja útil na investigação de máquinas potencialmente infectadas ou na execução de malware em um ambiente restrito, ainda há alguns riscos. Por exemplo, um programa mal-intencionado pode escapar da virtualização e acessar a máquina host. É por isso que você nunca deve confiar totalmente nos sistemas de virtualização.

**Eficiência**

O uso de máquinas também pode ser uma maneira eficiente e conveniente de realizar tarefas de segurança. Você pode abrir várias máquinas virtuais de uma só vez e alternar facilmente entre elas. Isso lhe permite simplificar as tarefas de segurança, como testar e explorar vários aplicativos. 

É possível comparar a eficiência de uma máquina virtual com a de ônibus urbano. Um único ônibus urbano tem muito espaço e é uma forma eficiente de transportar muitas pessoas. Se os ônibus urbanos não existissem, todos os ônibus teriam que dirigir seus próprios carros. Isso usa mais gasolina, carros e outros recursos do que andar de ônibus urbano. 

**Gerenciamento de máquinas virtuais**

As máquinas virtuais podem ser gerenciadas com um software chamado hipervisor. Os hipervisores ajudam os usuários a gerenciar várias máquinas virtuais e a conectar o hardware virtual e o físico. Os hipervisores também ajudam a alocar os recursos compartilhados da máquina hospedeira física para uma ou mais máquinas virtuais.   
Um hipervisor que é útil para você conhecer é a máquina virtual baseada em kernel (KVM). O KVM é um hipervisor de código aberto compatível com a maioria das principais distribuições Linux. Ele é incorporado ao kernel do Linux, o que significa que pode ser usado para criar uma máquina virtual em qualquer máquina que esteja executando um sistema operacional Linux sem a necessidade de software adicional.

**GUI versus CLI**

O usuário se comunica com o sistema operacional por meio de uma interface. Uma interface de usuário é um programa que permite ao usuário controlar as funções do sistema operacional. Duas interfaces de usuário que discutiremos são a interface gráfica do usuário, ou GUI, e a interface de linha de comando, ou CLI. Vamos abordar essas interfaces com mais detalhes. 

Uma GUI é uma interface de usuário que usa ícones na tela para gerenciar diferentes tarefas no computador. A maioria dos sistemas operacionais pode ser usada com uma interface gráfica de usuário. Se você já usou um computador pessoal ou um telefone celular, já experimentou operar uma GUI. A maioria das GUIs inclui esses componentes: um menu inicial com grupos de programas, uma barra de tarefas para iniciar programas e uma área de trabalho com ícones e atalhos. Todos esses componentes ajudam a se comunicar com o sistema operacional para executar tarefas. Além de clicar nos ícones, o sistema operacional executa tarefas. Além de clicar nos ícones, ao usar uma GUI, você também pode pesquisar arquivos ou aplicativos no menu Iniciar. Basta lembrar o ícone ou o nome do programa para ativar um aplicativo.

Agora vamos discutir a interface de linha de comando. Em comparação, a interface de linha de comando, ou CLI, é uma interface de usuário baseada em texto que usa comandos para interagir com o computador. Esses comandos se comunicam com o sistema operacional e executam tarefas como abrir programas. A interface de linha de comando é uma estrutura muito diferente da interface gráfica do usuário. Ao usar a CLI, você notará imediatamente a diferença. Não há ícones ou gráficos na tela. A interface da linha de comando é semelhante às linhas de código que usam determinadas linguagens de texto. Uma CLI é mais flexível e mais poderosa do que uma GUI. Pense em usar uma CLI, como criar qualquer poderosa do que uma GUI. Pense em usar CLI, como criar qualquer refeição que você quiser com ingredientes comprados em um supermercado. Isso lhe dá muito controle e personalização sobre como você vai comer. 

Imagine que você tenha uma pasta com centenas de arquivos de tipos diferentes e precise mover somente os arquivos JPEG para uma nova pasta. Pense em como isso seria lento e entediante ao usar uma GUI para encontrar cada arquivo JPEG nessa pasta e movê-lo para a nova. Por outro lado, a CLI permitiria agilizar esse processo e movê-los todos de uma vez. 

Conclusão:

É possível entender quais são as principais funções de uma sistema operacional e como estabelece a interação do usuário com o hardware, agregando diversas funções que têm o objetivo de facilitar a vida do usuário, além disso, ele demonstra uma diversidade de formas de interação sejam elas por meio de linha de comando ou uma interface gráfica.   
