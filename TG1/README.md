<html>
<body>
  
 <h1 align="center"> Portólio de APIs Fatec São José dos Campos</h1>
 <h3 align="center"> Meus projetos :books: </h3>
  
  <p align="center">
     <a href="#-projeto-assistente-virtual-para-idosos---1º-semestre">1º Semestre</a> •
     <a href="#-projeto-trinity---2º-semestre">2º Semestre</a> • 
     <a href="#-projeto-airplan---3º-semestre">3º Semestre</a> •
     <a href="#-projeto-vempracasa---4º-semestre">4º Semestre</a> •
     <a href="">5º Semestre</a> •
     <a href="">6º Semestre</a> 
  </p>
  
  ---
  
  <h2> Autor :necktie: </h2>
	
  <p>Meu nome é Gabriel, tenho 21 anos e atualmente estou cursando o 5º semestre de Banco de dados. Sou formado técnico em informática pela escola técnica <a          href="https://www.institutoideia.online/">IDEIA - Instituto de Desenvolvimento Educacional</a> onde tive meu primeiro contato com o mundo da tecnologia e desenvolvimento de software. Após a conclusão do técnico ingressei na  <a href="https://fatecsjc-prd.azurewebsites.net/index.php">FATEC - São José dos Campos</a> no 1º Semestre/2020.</p>
  <p>Durante o desenvolvimento do curso aprendi muito sobre tecnologias, boas práticas e metodologias, o aprendizado por projetos (APIs) foi muito importante para minha formação como profissional de TI, durante os projetos englobamos todas as matérias do semestre vigente e desenvolvemos projetos com empresas reais, parceiras da faculdade, esse método de ensino está próximo do que acontece no mercado de trabalho, além de desenvolver aplicações em metodologias ágeis como o Scrum, versionamento de código através do GIT, as boas práticas e tecnologias são usadas durante esses projetos.</p>
<p> Atualmente sou estágiario na empresa <a href="https://codex.tec.br/">Codex Utilities</a> trabalhando como Analista de desenvolvimento, minhas experiências durante os projetos são de extrema importancia durante meu trabalho.</p>

  <table align="center">
   <tr>
    <td align="center"><a href="https://www.linkedin.com/in/gabrielferraz01"> <img style="border-radius: 50%;"   src="https://github.com/ferrazghs/Vempracasa/blob/main/images/ferraz.jpeg" width="200px;" alt=""/><br/><b>Gabriel Ferraz</b></a>
      <br/>
       Analista de desenvolvimento
     </td>
   </tr>
  </table>
   <h2 style="font-family:roboto;"> Projeto Assistente virtual para idosos - 1º Semestre</h2>
   <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p> Aplicação mobile que tem por objetivo facilitar o uso do smartphone Android para o público da 3º idade.</p>
	
  <p>São diversas funcionalidades que o sistema proporciona para seu usuário final, entre elas podemos citar a funcionalidade adicionar alarme que permite aos usuários adicionar um alarme definindo o horário, dias da semana e título. Além disso é possivel realizar uma ligação de emergência redirecionando ao número de emergência 192 (SAMU), através do aplicativo padrão de ligações do Android.</p> 
	
  <p>O aplicativo ainda proporciona aos usuários funcionalidades como adicionar um contato, realizar ligações informando o numero desejado, pesquisa na WEB, configuração de conectividade que permite ligar/desligar o wifi e bluetooth, acessar a camêra através de um comando de voz e adicionar contatos informando o número e nome desejados.</p>
      
   <h2 style="font-family:roboto;"> Tecnologias utilizadas :computer:</h2>

  <li><a href="https://www.java.com/pt-BR">Java</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">  O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto, por um conhecimento prévio no desenvolvimento baseado nessa linguagem por parte do time, além de ser uma linguagem muita utilizada no mercado de trabalho e possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
</ul></li>
	 
  <li><a href="https://developer.android.com/studio">Android Studio</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> Android Studio é uma plataforma para desenvolvimento de apps mobile para o sistema operacional Android, é uma IDE (Integrated Development Environment) que tem por funcionalidade disponibilizar todos os recursos necessários para o desenvolvimento mobile Android. </p>
  </ul></li>
	 
  <li><a href="https://trello.com/pt-BR">Trello</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> Trello é uma ferramenta colaborativa que organiza projetos em quadros, onde são inseridas listas de tarefas a serem seguidas individualmente ou em equipe. Cada lista recebe cartões com descrições, prazos determinados e objetivos a serem concluídos, utilizado para auxiliar no desenvolvimento de projetos utilizando metodologias agéis, como exemplo o Scrum.</p>
  </ul></li>	
	 
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  
  <h3>Método onCreate</h3>
  <p align="justify" style="font-family:roboto;">O método "onCreate" foi desenvolvido com o objetivo de aguardar uma instância do usuário, assim que o usuário
  clicar no botão de microfone na interface, o método é ativado e é chamado um segundo método chamado "catchSpeed"</p>
  
  <details>
  <summary>Demonstração método onCreate</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/MetodoonCreate.jpg" alt=""/>
  </details>
  
  <h3>Método catchSpeed</h3>
  <p align="justify" style="font-family:roboto;">O método "catchSpeed" tem por objetivo chamar uma ação atraves das funcionalidades nativas do sistema Android, essa
  "ação" é chamada de Intent, e através do método catchSpeed iniciamos as requisições padrões do Android para a chamada do método de voz, a intent utilizada para o       método de voz é a "RecognizerIntent"</p>
  
  <details>
  <summary>Demonstração método catchSpeed</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Metodocatchspeed.jpg" alt=""/>
  </details>
	
  <h3>Método createAlarm</h3>
  <p align="justify" style="font-family:roboto;">O método "createAlarm" tem por objetivo chamar uma intent nativa do Android para a criação de um alarme, para efetivar a ação é necessário instanciar algumas variaveis, entre elas temos: mensagem que o alarme vai mostrar ao usuário, o horário e os dias da semana que será ativado, através da Intent AlarmClock conseguimos iniciar essas variavéis, todas as informações necessárias são armazenadas em variáveis instanciadas através de comandos de voz passados pelo usuário, seguindo as instruções que estão contidas no front-end do projeto.</p>
	
  <p align="justify" style="font-family:roboto;">Além disso para definir os dias da semana foi criado um HashMap, onde cada inteiro de 1 á 7 corresponde aos dias da semana, o desenvolvimento desse hash se deu pelo motivo da Intent necessitar de um inteiro como parâmetro para definir os dias da semana.</p>
  
  <details>
  <summary>Demonstração método createAlarm</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Metodo%20createAlarm.jpg" alt=""/>
  </details>
  
 <h3>Método addContact</h3>
<p align="justify" style="font-family:roboto;">O método "addContact" tem por objetivo chamar uma intent nativa do Android chamada "ContactsContract" para a criação de um novo contato, para efetivar a ação é necessário instanciar duas variaveis, são elas: nome do contato e também seu numero. essas variaveis são iniciadas assim que o usuário passar as informações via comando de voz, após essa ação as variaveis são instanciadas através do métodos "ContactsContract.Intents.Insert.NAME" e ContactsContract.Intents.Insert.PHONE, finalizando o método o usuário é redirecionado para a tela de contatos do Android para salvar a ação.</p>
	
  <details>
  <summary>Demonstração método addContact</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Metodo%20addContact.jpg" alt=""/>
  </details>
	
 <h3>Método processMachineLearning</h3>
<p align="justify" style="font-family:roboto;">O método "processMachineLearning" foi desenvolvido dentro da classe "MainActivity", esse método possui uma cadeia de ifs que tem por paramêtro uma String que recebe o comando de voz do usuário, dependendo do que for passado é chamado uma função especifica.</p>
	
  <details>
  <summary>Demonstração método processMachineLearning</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/ProcessMachineLearning.jpg" alt=""/>
  </details>
	
 <h3>Método Enable/Disable Wi-fi e Bluetooth</h3>
<p align="justify" style="font-family:roboto;">O método enable/disable foi desenvolvido com o objetivo de ativar e desativar o wi-fi e bluetooth do dispositivo Android.Para a implementação do método foi utilizado duas classes "WifiManager" e "BluetoothAdapter" ambas as classes possuem dois métodos que tem por objetivo acionar a ação de ligar e desligar.</p>
	
  <details>
  <summary>Demonstração método Enable/Disable Wifi e Bluetooth</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/EnableDisableWifiBluetooth.jpg" alt=""/>
  </details>
	
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
  <ul>
  <li>GIT
  <ul>
    <li>Versionamento de código com comandos GIT;</li>
    </ul></li>
  <li>Desenvolvimento Android:
  <ul>
    <li>Desenvolvimento de classes e metódos utilizando Java para Android;</li> 
    <li>Utilização de Intents nativas do Android.</li>
    </ul></li>
  <li>XML:
  <ul>
    <li>Desenvolvimento de telas utilizando XML.</li>
    </ul></li>
    </ul>
  
   <h2 style="font-family:roboto;"> <a href = "https://github.com/Gil-cos/Projeto_Integrador_1-Sem2020">  GitHub :house: </a></h2>   
   
   <h2 style="font-family:roboto;"> A aplicação :trophy:</h2>
    <details>
  <summary>Demonstração funcionamento da aplicação</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Untitled-video-%E2%80%90-Feito-com-o-Clipchamp.gif" />
  </details>
	
  		
  ---
	
  <h2 style="font-family:roboto;"> Projeto Trinity - 2º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p> O projeto Trinity tem por objetivo auxiliar a empresa parceira  <a href="https://tecsus.com.br/"> TecSUS </a> através de um software promover uma melhora na digitação de contas de água e luz por parte de seus colaboradores. </p>
	
  <p>Antes do software desenvolvido a empresa fazia toda digitação e construção dos relátorios de forma manual. A solução automatiza os processos de digitação por exemplo armazenando empresas que já são clientes em uma base de dados, diminuindo assim o tempo dos colaboradores ao buscarem informações de empresas já clientes, o sistema promove também um controle de erros na hora da digitação, não permitindo a entrada de dados errados, fazendo com que os relátorios gerados sejam mais efetivos.</p> 
	
  <p>Além do cadastro de contas e empresas parceiras, o sistema também gera relátorios para seus usuários, permitindo então a analise de consumo e gastos nas contas    digitadas.</p>
      
  <h2 style="font-family:roboto;"> Tecnologias utilizadas :computer:</h2>

  <li><a href="https://www.java.com/pt-BR">Java</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">  O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto, por um conhecimento prévio no desenvolvimento baseado nessa linguagem por parte do time, além de ser uma linguagem muita utilizada no mercado de trabalho e possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
</ul></li>
  
  <li><a href="https://www.mysql.com/">MySQL</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> O MySQL é um SGBD (Sistema Gerenciador de Banco de Dados) para banco de dados relacionais, que utiliza a linguagem SQL, esse SGBD é suportado pela empresa Oracle e utiliza o modelo cliente-servidor, onde o servidor armazena os dados e o cliente é oque faz as solicitações desses dados.</p>
  </ul></li>
  
  <li><a href="https://www.gitpod.io/">GitPod</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">GitPod é um ambiente de desenvolvimento de aplicações em nuvem, onde se tem um ambiente de trabalho integrado e de fácil manipulação, podendo adicionar as instalações e extensões utilizadas dentro de um projeto de software.</p>
  </ul></li>	
		
  <li><a href="https://openjfx.io/">JavaFX</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">O JavaFx e uma biblioteca da linguagem Java que permite a criação de interfaces gráficas de forma automática para aplicações desktop e mobile.</p>
  </ul></li>	
	
 <li><a href="https://www.mockflow.com/">Mockflow</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">O Mockflow é um utilitário utilizado para a prototipação de wireframes, possui diversos mecanismos para estruturar suas telas que posteriormente serão desenvolvidas em uma aplicação</p>
  </ul></li>	
	 
  <li><a href="https://trello.com/pt-BR">Trello</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> Trello é uma ferramenta colaborativa que organiza projetos em quadros, onde são inseridas listas de tarefas a serem seguidas individualmente ou em equipe. Cada lista recebe cartões com descrições, prazos determinados e objetivos a serem concluídos, utilizado para auxiliar no desenvolvimento de projetos utilizando metodologias agéis, como exemplo o Scrum.</p>
  </ul></li>
 
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
  <h2 style="font-family:roboto;"> <a href = "https://github.com/GabrielSG20/Projeto_Integrador_2-Sem2020">  GitHub :house: </a></h2>   

  <h2 style="font-family:roboto;"> A aplicação :trophy:</h2>
  <details>
  <summary>Demonstração funcionamento da aplicação</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Apresenta%C3%A7%C3%A3o_TecSUS.gif" />
  </details>
	
  ---
	
  <h2 style="font-family:roboto;"> Projeto AirPlan - 3º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p>O AirPlan é um solução de software solicitada pela empresa parceira  <a href="https://embraer.com/br/pt"> Embraer </a>  </p>
  <p>O sistema tem por objetivo o controle e armazenamento de documentações de aeronaves, antes da solução desenvolvida a empresa possuía grandes erros ao gerar e manipular arquivos que integram um documento de uma aeronave, fazendo de forma manual.</p> 
  <p>A aplicação automatiza a integração dos diversos arquivos em apenas um de forma eficaz e intuitiva, levando em consideração toda regra de negócio que os colaborades usam, é constituido de 3 APIs distintas e independentes que permitem: ligar diversos documentos, verificar a integridade dos arquivos, upload das partes de um documento, download completo dos arquivos integrados e controle de usuários.</p>
     
  <h2 style="font-family:roboto;"> Tecnologias utilizadas :computer:</h2>

  <li><a href="https://www.java.com/pt-BR">Java</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">  O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto, por um conhecimento prévio no desenvolvimento baseado nessa linguagem por parte do time, além de ser uma linguagem muita utilizada no mercado de trabalho e possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
</ul></li>
	 
 <li><a href="https://www.mysql.com/">MySQL</a>:
 <ul>
    <p align="justify" style="font-family:roboto;"> O MySQL é um SGBD (Sistema Gerenciador de Banco de Dados) para banco de dados relacionais, que utiliza a linguagem SQL, esse SGBD é suportado pela empresa Oracle e utiliza o modelo cliente-servidor, onde o servidor é onde fica armazenados os dados e o cliente é oque faz a solicitaçãp desses dados.</p>
  </ul></li>

<li><a href="https://spring.io/">Springboot</a>:
 <ul>
    <p align="justify" style="font-family:roboto;">O Spring Boot é um framework Java open-source que facilita o desenvolvimento de aplicações baseadas em Java, tornando o trabalho mais rápido e dinâmico. Além de possuir diversas funcionalidades, o recurso foi utilizado durante o projeto para fazer a configuração de todas as bibliotecas que foram utilizado, O framework foi escolhido, pois facilita durante o desenvolvimento de projetos, fazendo com que os programadores se preocupem apenas com a implementação das regras de negocio.</p>
  </ul></li>
	
  <li><a href="https://trello.com/pt-BR">Trello</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> Trello é uma ferramenta colaborativa que organiza projetos em quadros, onde são inseridas listas de tarefas a serem seguidas individualmente ou em equipe. Cada lista recebe cartões com descrições, prazos determinados e objetivos a serem concluídos, utilizado para auxiliar no desenvolvimento de projetos utilizando metodologias agéis, como exemplo o Scrum.</p>
  </ul></li>
 
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
	
<h3>Modelo Conceitual</h3>
<p align="justify" style="font-family:roboto;">O modelo conceitual do banco de dados foi desenvolvido de acordo com as regras de negócio passadas pela empresa parceira, com ele foi possivel estruturar o banco de dados e consequentemente utilizar no armazenamento dos dados do projeto.</p>
	
  <details>
  <summary>Modelo conceitual</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/ModeloConceitual3SEM.jpg" alt=""/>
  </details>
	
<h3>Estruturação do banco de dados</h3>
<p align="justify" style="font-family:roboto;">A partir do modelo de dados foi possivel fazer a estruturação da base a ser utilizada criando então as tabelas, colunas, restrições, relacionamento e tipos de dados.</p>
	
<h3>Flyway</h3>
<p align="justify" style="font-family:roboto;">O Flyway é uma ferramente de migração de banco de dados, foi utilizada no projeto para: Sincronizar o banco de dados com as diferentes versões da aplicação, automatizar a execução dos scripts SQL e ter um controle de quais scripts foram executados.</p>
<p align="justify" style="font-family:roboto;">O projeto possui uma pasta resouces - db - migration onde estão todas as migrações e alterações da base de dados usadas, fazendo com que os scripts sejam executados.</p>
	
  <details>
  <summary>Demonstração arquivo de migração Flyway</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/migrationFlyway3Sem.jpg" alt=""/>
  </details>

<h3>Mapeamento de classes</h3>
<p align="justify" style="font-family:roboto;">O Hibernate é a solução ORM(Mapeamento Objeto-Relacional) Java que consiste em uma ferramenta utilizada para realizar o mapeamento das classes Java com o Banco de dados de forma completa e eficiente, essa tecnologia segue a especificação JPA que define um meio para realizar esse mapeamento. O Hibernate é o intermediário das interações entre as classes Java com o banco de dados relacional, fazendo assim a conversão da programação orientada a objetos para o banco de dados relacional. Durante o desenvolvimento do projeto foi utilizado a arquitetura Modelo-Visão-Controle (MVC) onde separamos através de uma lógica arquitetural o sistema em componentes interligados, onde é possivel definir a conexão com a camada de dados, interação com o usuário e as regras de negócio.</p>
	
<p align="justify" style="font-family:roboto;">O mapeamento das classes é feito através de algumas tags especificas do JPA, através desses dois exemplos acima conseguimos identificar tags chaves para o mapeamento, são elas: </p>
	<p align="justify" style="font-family:roboto;">@Table – Notação para especificar qual o nome da tabela no banco de dados; </p>
	<p align="justify" style="font-family:roboto;">@Column – Identifica o nome da coluna; </p>
	<p align="justify" style="font-family:roboto;">@Id – Identifica a “primary key”, ou seja, a coluna identificadora da tabela;</p>
	<p align="justify" style="font-family:roboto;">@SequenceGenerator – Cria uma sequencia de números no banco de dados.</p>

  <details>
  <summary>Demonstração mapeamento da classe "Flag"</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/mapeamentoOrm3Sem.jpg" alt=""/>
  </details>

  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>  
	
  <ul>
  <li>Java Springboot
  <ul>
    <li>Mapeamento de classes utilizando JPA;</li>
    <li>Estruturação de Modelos, Serviços e Controladores no Springboot.</li>
    </ul></li>
	  
  <li>GIT:
  <ul>
    <li>GitFlow.</li>
    </ul></li>
	  
  <li>Banco de dados:
  <ul>
    <li>Desenvolvimento do modelo conceitual e relacional do BD;</li> 
    <li>Configuração do MySQL;</li> 
    <li>Estruturação do BD através de SQL;</li>
    <li>Utilização de comandos DML;</li>
    <li>Flyway para integração do banco de dados.</li>
    </ul></li>
	  
  <li>Metodologia Ágile:
  <ul>
    <li>Desenvolvimento do projeto utilizando metodologia Scrum.</li>
    </ul></li>
    </ul>
  
 <h2 style="font-family:roboto;"> <a href = "https://github.com/GabrielSG20/Projeto_Integrador_3BD-1Sem2021">  GitHub :house: </a></h2>   
 <h2 style="font-family:roboto;"> A aplicação :trophy:</h2>
 <details>
 <summary>Demonstração funcionamento da aplicação</summary>
 <br>
  <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/Apresenta%C3%A7%C3%A3o_AirPlan.gif" />
 </details>
	
  ---	
	
  <h2 style="font-family:roboto;"> Projeto #VEMPRACASA - 4º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>

<p>#VEMPRACASA é um projeto para a empresa <a href="https://www.oracle.com/br/index.html">Oracle</a>, a proposta apresentada pela a empresa parceira tem a finalidade do desenvolvimento de um sistema que realiza agendamentos de eventos nos espaços da “Casa Oracle”, local que é realizado eventos e palestras da empresa, o sistema tem o intuito de solucionar um problema recorrente no agendamento manual dos eventos, gerando diversos conflitos.</p>

<p> O sistema tem diversas funcionalidades que tornam o agendamento de eventos intuitivo e prático para o usuário final. A solução consiste em três tipos de usuários: Organizador, Administrador e Convidado.</p>
	
<p>O organizador tem como principal funcionalidade a solicitação de um evento, onde através de tela é possível inserir todas as informações pertinentes ao evento. Já o administrador é responsável por aprovar ou não o evento, visualizando todas as informações referentes ao evento e sugestionar uma nova data. O convidado é dividido em externos ou internos e podem se cadastrar através do site da “Casa Oracle”, funcionários Oracle recebem a confirmação do evento via e-mail e podem solicitar para se tornar organizadores de um evento, já convidados externos apenas participam dos eventos abertos ao público em geral.</p>
	
<p>O projeto por fim trás uma facilidade para seus usuários, além da solicitação rápida e intuitiva de um evento, é possível ter uma segurança através da sua aprovação por meio do administrador, a confirmação do evento via e-mail para os convidados trás uma grande facilidade na comunicação e o controle de acesso através do cartão vacinal.</p>
	
 <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
   	
 <li><a href="https://spring.io/">Java</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">  O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto, por um conhecimento prévio no desenvolvimento baseado nessa linguagem por parte do time, além de ser uma linguagem muita utilizada no mercado de trabalho e possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
</ul></li>
	 
 <li><a href="https://spring.io/">Spring Boot</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">O Spring Boot é um framework Java open-source que facilita o desenvolvimento de aplicações baseadas em Java, tornando o trabalho mais rápido e dinâmico. Além de possuir diversas funcionalidades, o recurso foi utilizado durante o projeto para fazer a configuração de todas as bibliotecas que foram utilizado, O framework foi escolhido, pois facilita durante o desenvolvimento de projetos, fazendo com que os programadores se preocupem apenas com a implementação das regras de negocio. </p>
 </ul></li>
	 
 <li><a href="https://www.javascript.com/">JavaScript</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">Javascript é uma linguagem de programação de script em alto nível, usado em páginas web. Foi utilizado durante o projeto para implementar a interação que o usuário possui com nossas páginas web, tornando assim sua navegação mais dinâmica.  A linguagem foi escolhida pelo grupo, pois é uma das linguagens mais utilizadas no mercado de trabalho para esse tipo de interação, além da alta compatibilidade com navegadores web.</p>
 </ul></li>	
	
 <li><a href="https://angular.io/">Angular</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">Angular é uma plataforma de aplicações web de código-fonte aberto e front-end baseado em typescript, essa plataforma é utilizada na construção otimizada de interfaces de aplicações, utilizado HTML, CSS e principalmente Javascript. Foi usada durante o desenvolvimento das páginas web presente no projeto, possibilitando uma programação mais ágil e fácil. Além de ser uma plataforma bastante utilizada, é open-source ou seja, existe uma grande variedade de conteúdos e funcionalidades disponibilizadas dentro da plataforma.</p>
 </ul></li>	
	
<li><a href="https://www.oracle.com/tools/downloads/sqldev-downloads.html">Oracle</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">Oracle é um Sistema Gerenciador de Banco de Dados de alto nível que utiliza banco de dados relacional. O SGBD foi utilizado durante a execução dos scipts SQL para a prototipação das tabelas e colunas de acordo com o modelo relacional desenvolvido previamente, além da manutenção e armazenamento dos dados do sistema. Foi escolhido pela equipe, pois é um SGBD robusto e com uma grande variedade de funcionalidades.</p>
</ul></li>	

 <li><a href="https://www.figma.com/">Figma</a>:
  <ul>
  <p align="justify" style="font-family:roboto;">Figma é um editor gráfico de vetor e prototipagem de projetos. Ele foi utilizado no projeto durante a prototipação do “Product Backlog Building” um método apresentado pelo PO da equipe, que foi usado para criação de um backlog colaborativo e de forma organizada, para que cada um dos integrantes do time pudesse expor suas ideias referentes ao projeto e assim organizar nossas funcionalidades, além disso, a ferramenta foi usada para a criação das “Wireframes” do projeto, que posteriormente foram apresentadas ao clientes e validadas, a ferramenta foi escolhida pela equipe, pela a alta utilização no mercado e fácil utilização do software.</p>
</ul></li>	
	
<h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
	
<h3>Modelo Conceitual do banco de dados</h3>
<p align="justify" style="font-family:roboto;">O modelo foi desenvolvido utilizando o software “brModelo” especifico para a criação do MER (Modelo-Entidade-Relacionamento).Após a definição do “Product Backlog”, foi feita uma análise sobre a proposta e com isso foi possível o desenvolvimento das entidades, atributos e relacionamentos presentes no modelo.</p>
<p align="justify"> Essa parte foi crucial no inicio do projeto para elaborar um modelo de dados consistente e funcional, com o MER conseguimos resolver questões importantes que refletiram durante as Sprints, por exemplo, o relacionamento que os usuários do sistema têm com os eventos criados pelos mesmos.</p>
	
  <details>
  <summary>Demonstração modelo conceitual</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Bertoti/blob/main/TG1/images/ModeloConceitual3SEM.jpg" alt=""/>
  </details>
	
<h3>Modelo relacional banco de dados</h3>
<p align="justify" style="font-family:roboto;">O desenvolvimento foi feito levando em consideração as entidades, atributos e relacionamento do MER, nesse novo modelo as entidades se tornam tabelas, os atributos se tornam colunas e os relacionamentos são feitos através de chaves estrangeiras.</p>
	
  <details>
  <summary>Demonstração modelo relacional</summary>
  <br>
   <img style="border-radius: 50%;" src="" alt=""/>
  </details>

<h3>Documentação de dados</h3>
<p align="justify" style="font-family:roboto;">Após o desenvolvimento do modelo relacional pela ferramenta foi gerada uma documentação de dados através de um arquivo .pdf, essa documentação foi entregue ao cliente, e descreve todas tabelas, colunas e relacionamentos que o banco possui, caso seja necessário algumas atualização na estrutura do código SQL o cliente consegue de forma fácil e rápida ter acesso a estrutura atual.</p>
	
<h3>Implementação ORM utilizando o framework Hibernate</h3>
<p align="justify" style="font-family:roboto;">O Hibernate é a solução ORM Java que consiste em uma ferramenta utilizada para realizar o mapeamento objeto-relacional de forma completa e eficiente, essa tecnologia segue a especificação JPA que define um meio para realizar esse mapeamento.</p>
	
<p align="justify" style="font-family:roboto;">O Hibernate é o intermediário das interações entre as classes Java com o banco de dados relacional, fazendo assim a conversão da programação orientada a objetos para o banco de dados relacional. Durante o desenvolvimento do projeto foi utilizado à arquitetura MVC (Model-View-Controller) onde separamos através de uma lógica arquitetural o sistema em componentes interligados, onde é possível definir a conexão com a camada de dados, interação com o usuário e as regras de negócio.</p>
	
<p align="justify" style="font-family:roboto;">A lógica arquitetura implementada consistem em :</p>
        <li>Model - Representação das tabelas do banco de dados, onde foi definido as relações entre objetos e seus atributos, foi utilizado o método ORM para mapear essas classes.</li>
	<li>Repository - São interfaces Java que tem como principal função serem a camada de acesso a dados, durante seu desenvolvimento foi utilizado o padrão de projeto Facade pois é uma interface que simplifica as funcionalidades do JPA.  </li>
	<li>Services - São classes que possuem os métodos do Repository, é onde são mantidos as lógicas conforme as regras de negócio conforme a requisição do cliente.</li>
	<li>Controller - É a classe onde encontramos os endpoints utilizado para a interação com o front-end do projeto, a comunicação ocorre entre requisições HTTP presentes nas rotas do Controller, para essas requições utilizamos o padrão de projeto Proxy onde controlamos o acesso aos objetos nas com as anotações do Spring.</li>
	
 <details>
  <summary>Demonstração modelagem de classes</summary>
  <br>
   <img style="border-radius: 50%;" src="" width="1000px;" alt=""/>
  </details>
