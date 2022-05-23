<html>
<body>
  
 <h1 align="center"> Portólio de APIs Fatec São José dos Campos</h1>
  
  <p align="center">
     <a href=""> 1º Semestre</a> 
     <a href="">2º Semestre</a> 
     <a href="">3º Semestre</a> 
     <a href="">4º Semestre</a>
     <a href="">5º Semestre</a>
     <a href="">6º Semestre</a>
</p>
  
  ---
  
  <h2> Autor :necktie: </h2>
  <table align="center">
   <tr>
    <td align="center"><a href="https://www.linkedin.com/in/gabrielferraz01">" <img style="border-radius: 50%;"   src="https://github.com/ferrazghs/Vempracasa/blob/main/images/ferraz.jpeg" width="200px;" alt=""/><br/><b>Gabriel Ferraz</b></a>
      <br/>
       Desenvolvedor banco de dados e back-end
     </td>
   </tr>
  </table>
   <h2 style="font-family:roboto;"> Projeto Assistente virtual para idosos - 1º Semestre</h2>
   <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p> Aplicação mobile que tem por objetivo facilitar o uso do smartphone Android para o público da 3º idade.</p>
  <p>São diversas funcionalidades que o sistema proporciona para seu usuário final, entre elas podemos citar a funcionalidade "adicionar alarme" que permite ao usuário adicionar um alarme definindo o horário, dias da semana e titulo. Além disso é possivel realizar uma ligação de emergência redirecionando ao número de emergência 192 (SAMU), através do aplicativo padrão de ligações do Android.</p> 
  <p>O aplicativo ainda proporciona ao usuário funcionalidades como adicionar um contato, realizar ligaçoes informando o numero desejado, pesquisa na WEB, configuração de conectividade que permite ligar/desligar o wifi e bluetooth, acessar a camêra através de um comando de voz e adicionar contatos informando o número e nome desejados.</p>
      
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
  
  <h3>Método OnCreate</h3>
  <p align="justify" style="font-family:roboto;">O método "onCreate" foi desenvolvido com o objetivo de aguardar uma instância do usuário, assim que o usuário
  clicar no botão de microfone na interface, o método é ativado e é chamado um segundo método chamado "catchSpeed"</p>
  
    <details>
  <summary>Demonstração método onCreate</summary>
  <br>
   <img style="border-radius: 50%;" src="" alt=""/>
  </details>
  
    <h3>Método catchSpeed</h3>
  <p align="justify" style="font-family:roboto;">O método "catchSpeed" tem por objetivo chamar uma ação atraves das funcionalidades nativas do sistema Android, essa
  "ação" é chamada de Itent, e através do método catchSpeed iniciamos as requisições padrões do Android para a chamada do método de voz.</p>
  
    <details>
  <summary>Demonstração método catchSpeed</summary>
  <br>
   <img style="border-radius: 50%;" src="" alt=""/>
  </details>
	
  <h3>Método createAlarm</h3>
  <p align="justify" style="font-family:roboto;">O método "createAlarm" tem por objetivo chamar uma itent nativa do Android para a criação de um alarme, para efetivar a criação do alarme é necessário instanciar algumas variaveis, entre elas temos: mensagem que o alarme vai mostrar ao usuário, o horário e os dias da semana que será ativado, através da Itent AlarmClock conseguimos iniciar essas variavéis, todas as informações necessário são armazenadas em variáveis instanciadas, através de comandos de voz passados pelo usuário, seguindo as instruções que estão contidas no front-end do projeto.</p>
	
  <p align="justify" style="font-family:roboto;">Além disso para definir os dias da semana foi criado um HashMap, onde cada inteiro de 1 á 7 corresponde aos dias da semana, o desenvolvimento desse hash se deu pelo motivo da Itent necessitar de um inteiro como parâmetro para definir os dias da semana.</p>
  
    <details>
  <summary>Demonstração método createAlarm</summary>
  <br>
   <img style="border-radius: 50%;" src="" alt=""/>
  </details>
  
 <h3>Método addContact</h3>
<p align="justify" style="font-family:roboto;">O método "addContact" tem por objetivo chamar uma itent nativa do Android "ContactsContract" para a criação de um novo contato, para efetivar a criação do contato é necessário instanciar duas variaveis, que são o nome do contato e também seu numero. essas variaveis são iniciadas assim que o usuário passar as informações necessárias via comando de voz, após essa ação as variaveis são iniciadas através do métodos "ContactsContract.Intents.Insert.NAME" e ContactsContract.Intents.Insert.PHONE, finalizado a ação o usuário é redirecionado para a tela de contatos do Android para salvar a ação.</p>
	
  <details>
  <summary>Demonstração método addContact</summary>
  <br>
   <img style="border-radius: 50%;" src="" alt=""/>
  </details>	
	
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   

  <h2 style="font-family:roboto;"> Projeto Trinity - 2º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p> O projeto Trinity tem por objetivo auxiliar a empresa parceira  <a href="https://tecsus.com.br/"> TecSUS </a> através de um software promover uma melhora na digitação de contas de água e luz por parte de seus colaboradores. </p>
  <p>Antes do software desenvolvido a empresa fazia toda digitação e construção dos relátorios de forma manual. A solução automatiza processos de digitação, por exemplo armazenando empresas que já são clientes em uma base de dados, diminuindo os usuários ao buscar informações de empresas já clientes, o sistema promove também um controle de erros na hora da digitação, contralando a entrada de dados errados, fazendo com que os relátorios gerados sejam mais efetivos.</p> 
  <p>Além disso do cadastro de contas e empresas parceiras, o sistema também gera relátorios para seus usuários, permitindo então a analise de consumo e gastos nas contas digitadas.</p>
      
  <h2 style="font-family:roboto;"> Tecnologias utilizadas :computer:</h2>

  <li><a href="https://www.java.com/pt-BR">Java</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">  O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto, por um conhecimento prévio no desenvolvimento baseado nessa linguagem por parte do time, além de ser uma linguagem muita utilizada no mercado de trabalho e possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
</ul></li>
  
  <li><a href="https://www.mysql.com/">MySQL</a>:
  <ul>
    <p align="justify" style="font-family:roboto;"> O MySQL é um SGBD (Sistema Gerenciador de Banco de Dados) para banco de dados relacionais, que utiliza a linguagem SQL, esse SGBD é suportado pela empresa Oracle e utiliza o modelo cliente-servidor, onde o servidor é onde fica armazenados os dados e o cliente é oque faz a solicitaçãp desses dados.</p>
  </ul></li>
  
  <li><a href="https://www.gitpod.io/">GitPod</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">GitPod é um ambiente de desenvolvimento de aplicações em nuvem, onde você possui um ambiente de trabalho integrado e de fácil manipulação, podendo adicionar as instalações e extensões utilizadas dentro de um projeto de software.</p>
  </ul></li>	
		
  <li><a href="https://openjfx.io/">JavaFX</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">O JavaFx e uma biblioteca gráfica da linguagem Java que permite a criação de interfaces gráficas de forma automática para aplicações desktop e mobile.</p>
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

  <h2 style="font-family:roboto;"> Projeto AirPlan - 3º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
  <p>O AirPlan é um solução de software solicitado pela empresa parceira  <a href="https://embraer.com/br/pt"> Embraer </a>  </p>
  <p>O sistema tem por objetivo o controle e armazenamento de documentações de aeronaves, antes da solução desemvolvida a empresa parceira possuía grandes problemas em gerar e manipular arquivos que integram um documento de uma aeronave, fazendo de forma manual e com isso gerando grandes erros.</p> 
  <p>A aplicação automatiza a integração dos diversos arquivos em apenas um de forma eficaz e intuitiva, levando em consideração toda regra de negócio que os colaborades usam, é constituido de 3 APIs distintas e independentes que permite a ligar diversos documentos, verificar a integridade dos arquivos, upload das partes de um documento, download completo dos arquivos integrados e controle de usuários.</p>
     
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
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   

  <h2 style="font-family:roboto;"> Projeto Vempracasa - 4º Semestre</h2>
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
	
 <p align="justify" style="font-family:roboto;"> :calendar: <b>#VEMPRACASA</b> é uma parceria entre a <a href="https://www.oracle.com/br/index.html">Oracle</a> e a FATEC São José dos Campos, a proposta apresentada pela a empresa parceira tem a finalidade do desenvolvimento de um sistema que realiza agendamentos de eventos nos espaços da Casa Oracle, o sistema tem o intuito de solucionar um problema recorrente que a empresa possuía no agendamento manual dos eventos..</p>
  
  <p align="justify" style="font-family:roboto;"> O sistema tem diversas funcionalidades que tornam o agendamento de eventos algo intuitivo e prático para o usuário final, foi inteiramente desenvolvido utilizando a metodologia ágil Scrum. No aplicativo temos três tipos de usuários que consistem em: Organizador, Administrador, Convidado.</p>

  <p align="justify" style="font-family:roboto;"> Cada usuário tem o seu papel definido dentro do programa, o organizador tem como principal funcionalidade a solicitação de um evento, onde é possível cadastrar um titulo, data/hora de inicio e fim do encontro, uma breve descrição, caso o evento necessite de fornecedores terceirizados é possível verifica a lista dos fornecedores já cadastrado no sistema aquele que melhor se encaixa, definir também se o evento é aberto para todos os usuários (publico) ou apenas para funcionários Oracle (privado), e por fim adicionar os convidados através do e-mail correspondente.</p>
  
  <p align="justify" style="font-family:roboto;"> Após a solicitação do evento por parte do organizador, o encontro deve passar pela a aprovação do administrador geral do programa, onde o usuário “admin” tem a possibilidade de visualizar informações dos eventos que foram solicitados e definir se será aprovado ou não, para deixar a ação de aprovar mais intuitiva foi desenvolvida uma priorização na solicitação de eventos, assim usuários que possuem uma função maior na hierarquia da empresa tem uma prioridade na aprovação. O “admin” também tem a possibilidade de cadastrar novos fornecedores dentro do sistema, que serão utilizados durante os eventos. Depois de aprovado o evento, os convidados cadastrados recebem um e-mail com informações sobre o evento, e o organizador a confirmação que sua solicitação foi aprovada.</p>
  
  <p align="justify" style="font-family:roboto;"> Os convidados são divididos em externos e internos. Para se cadastrar no programa esses usuários devem acessar a aba especifica e definir se são funcionários Oracle ou não. Funcionários Oracle além de participar e receber via e-mail os eventos, tem o poder de solicitar para o “admin” para que se tornem organizadores. Convidados externos apenas participam dos eventos e recebem a confirmação.</p>
  
  
   <p align="justify" style="font-family:roboto;"> O projeto por fim trás uma facilidade muito grande para seus usuários, além da solicitação rápida e intuitiva de um evento, é possível ter uma segurança através da sua aprovação por meio do administrador, além disso, a confirmação do evento via e-mail para os convidados trás uma grande facilidade na comunicação.</p>
	  
<h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
    	
  <li><a href="https://www.java.com/pt-BR/">Java</a>:
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
 
  <li><a href="https://jira.atlassian.com/">Jira</a>:
  <ul>
    <p align="justify" style="font-family:roboto;">Jira é uma ferramenta que permite o monitoramento de tarefas e acompanhamento de projetos em um único lugar. Utilizamos esse software para desenvolver e monitorar nosso Sprint backlog, onde podemos repartir as funções a serem desenvolvidas em “cartões” para um melhor acompanhamento de evolução e organização e atribuir quem é o responsável por aquela tarefa a ser desenvolvida, além de separar por área (back-end, front-end ou banco de dados) e delegar ao responsável uma data de inicio e fim daquela tarefa. O software foi escolhido pela equipe pois é utilizado em grande escala no mercado de trabalho, além de ser uma ferramenta fácil e intuitiva.</p>
  </ul></li>	  
	
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  
  <h3>Modelo Conceitual do banco de dados</h3>
  <p align="justify" style="font-family:roboto;">A modelagem de dados conceitual é uma descrição do projeto de banco de dados de forma independente de implementação em um SGBD, é um modelo que possui um alto nível de abstração, é o primeiro passo feito antes da implementação final dentro do SGBD Oracle. O MER (Modelo Entidade Relacionamento) é composto por : Entidade (representação de um conceito físico), Atributo (propriedades especificas de uma entidade) e Relacionamento (associações entre uma ou mais entidades</p>
  
  <p align="justify" style="font-family:roboto;">O modelo foi desenvolvido utilizando o software “brModelo” especifico para a criação do MER. Após a definição do “Product Backlog” e o desenvolvimento das perguntas que foram enviadas a empresa parceira, para obter uma visão mais aprofundada sobre o projeto, foi feito uma análise sobre a proposta e com isso foi possível o desenvolvimento das entidades, atributos e relacionamentos presentes no modelo. Essa parte foi crucial no inicio do projeto para elaborar um modelo de dados consistente e funcional, com o MER conseguimos resolver questões importantes que refletiram durante as sprints, por exemplo, o relacionamento que os usuários do sistema têm com os eventos criados pelos mesmos.</p>
 
  <details>
  <summary>Demonstração do modelo conceitual</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/conceitual.jpg" width="1000px;" alt=""/>
  </details>
  
  <h3> Modelo relacional banco de dados</h3>
  <p align="justify" style="font-family:roboto;">O modelo relacional é um tipo de modelo lógico, é também uma parte importante durante o desenvolvimento de um banco de dados completo e funcional, esse modelo apresenta uma estrutura diferente do modelo conceitual, é baseado em : Linhas, Colunas e Chave primária(PK) e se relacionam através de chaves estrangeiras(FK), é um modelo intermediário, está localizado entre o modelo conceitual que é o primeiro passo, e o a estruturação no SGBD. Para o desenvolvimento desse modelo foi utilizado à ferramenta “Vertabelo” que é possível estruturar seu modelo relacional utilizando todas as informações necessárias.</p>
  
  <p align="justify" style="font-family:roboto;">O desenvolvimento foi feito levando em consideração as entidades, atributos e relacionamento do conceitual, nesse novo modelo as entidades se tornam tabelas, os atributos se tornam colunas e os relacionamentos são feitos através de chaves estrangeiras, nele também ocorre a “trigramação” que é uma técnica utilizada para nomear tabelas e colunas.</p>
  
  <details>
  <summary>Demonstração modelo relacional</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/relacional.jpg" width="'1000px;" alt=""/>
  </details>
  
  <h3> Documentação de dados</h3>
  <p align="justify" style="font-family:roboto;">Após o desenvolvimento do modelo relacional pela ferramenta foi gerada uma documentação de dados através de um arquivo pdf, essa documentação foi entregue ao cliente, e descreve todas tabelas, colunas e relacionamentos que o banco possui, caso seja necessário algumas atualização na estrutura do código SQL o cliente consegue de forma fácil e rápida ter acesso a estrutura atual.</p>
  
   <h3>Estruturação do banco de dados </h3>
  <p align="justify" style="font-family:roboto;">Após a finalização dos modelos, foi feito a estruturação do banco de dados através do modelo relacional para linguagem SQL no banco de dados Oracle utilizando comandos DML.</p>
  <p align="justify" style="font-family:roboto;">Os códigos abaixo são alguns exemplos  de códigos SQL que foram desenvolvidos durante a estruturação do banco de dados.</p>
 
   <p align="justify" style="font-family:roboto;"><b>Comando DML para criar algumas tabelas no banco de dados, atribuindo suas colunas e especificando as restrições de integridade conforme o modelo relacional</b></p>
   
  <p align="justify" style="font-family:roboto;">
     <b>Linha 1 (comando DML para criação de tabela)</b>
       <br>
    CREATE TABLE Evento
       <br>
  <b>Linha 2 (atribuindo a coluna uma chave primaria e denominando um nome a sua constraint)</b>
       <br>
    evt_id Integer CONSTRAINT pk_evento PRIMARY KEY,
       <br>
  <b>Linha 3 (atribuindo a coluna uma restrição que não aceita valores nulos)</b>
       <br>
    evt_titulo Varchar2(30)  NOT NULL,
       <br>
    evt_descricao Varchar2(80),
       <br>
    evt_data_inicio Varchar2(100)NOT NULL,
       <br>
    evt_data_fim Varchar2(100) NOT NULL, 
       <br>
    evt_tipo Varchar2(10) NOT NULL,
       <br>
  <b>Linha 9 (imputando uma valor default NULL, caso não seja inserido nenhum valor na coluna)</b>
       <br>
    evt_status Integer DEFAULT NULL,
       <br>
    evt_imagem Varchar2(200),
       <br>
    usu_email Varchar2(80)
       <br>
) ;
</p>
                                                   
  <p align="justify" style="font-family:roboto;">
     <b>Linha 1 (comando DML para criação de tabela)</b>    
	<br>
CREATE TABLE Usuario (
        <br>                                        
    usu_email Varchar2(80) CONSTRAINT pk_usuario PRIMARY KEY,
         <br>                                                                               
    usu_nome Varchar2(80) NOT NULL,
         <br>                                        
<b>Linha 3 (adicionando uma restrição de chave única á coluna, impossibilitando valores iguais)</b> 
	  <br>
    usu_cpf Varchar2(15) CONSTRAINT uk_usuario_cpf UNIQUE NOT NULL,
         <br>                                        
    usu_telefone Varchar(50) NOT NULL,
         <br>                                                                      
    usu_departamento Varchar2(30),
         <br>                                        
    usu_nome_empresa Varchar2(50),
          <br>                                        
    usu_id_oracle Integer,
          <br>                                        
    usu_comprovante_vacinacao Varchar(200),
         <br>                                        
    usu_tipo Varchar2(20)NOT NULL,
        <br>                                        
    usu_cargo Varchar2(50),
         <br>                                        
    usu_senha Varchar2(100) CONSTRAINT uk_usuario_senha UNIQUE NOT NULL
          <br>                                        
) ;
</p>
     <p align="justify" style="font-family:roboto;"><b>Tabela de relacionamento (Usuário – Evento)</b></p>
    <p align="justify" style="font-family:roboto;">
                                             
CREATE TABLE Usuario_Evento (
      <br>
    evt_id Integer,
      <br>
    usu_email Varchar2(80),
      <br>
<b>Linha 3 (atribuição das chaves primárias da tabela, informando duas colunas, tornando assim uma chave primária composta)</b>
      <br>
    CONSTRAINT pk_usuario_evento PRIMARY KEY (evt_id,usu_email)
      <br>
) ;
  </p>
  <p align="justify" style="font-family:roboto;"><b>Especificação das chaves estrangeiras da tabela Usuario_Evento, referenciando as tabelas de origem.</b></p>
    <p align="justify" style="font-family:roboto;">
ALTER TABLE Usuario_Evento ADD CONSTRAINT fk_usuario_evento_evt_id
      <br>
    FOREIGN KEY (evt_id)
      <br>
    REFERENCES Evento (evt_id);
      <br>
      <br>
ALTER TABLE Usuario_Evento ADD CONSTRAINT fk_usuario_evento_usu_email
      <br>
    FOREIGN KEY (usu_email)
      <br>
    REFERENCES Usuario (usu_email);
      <br>
  </p>
   <h3>Implementação LiquiBase. </h3>
  <p align="justify" style="font-family:roboto;">O liquibase é uma ferramenta de migração de banco de dados de código fonte aberto que permite rastrear, gerenciar e aplicar alteração na base de dados. Essa biblioteca acabou sendo útil para fazer toda migração no banco de dados, e padronizar o banco na maquina de cada desenvolvedor do sistema. Porém com o deploy do banco no Oracle Cloud junto, essa ferramenta parou de ser utilizado.</p>
  <p align="justify" style="font-family:roboto;">O primeiro passo foi adicionar a dependência da biblioteca liquibase no POM.xml do projeto</p>
  <details>
  <summary>Dependencia Liquibase no POM.xml</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/liquibase.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Após a configuração do POM, é criado um arquivo em resources -> db -> changelog onde é feito a configuração do diretório onde será armazenado as migrações no banco de dados.</p>
  <details>
  <summary>Criação do changelog</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changelog.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;"> Após o changelog, é criado um arquivo “.sql” para adicionar as migrações, cada alteração no banco de dados é chamada de changeset, onde é possível atribuir um id, que deve ser diferente em cada alteração, e o autor daquela migração.</p>
  <details>
  <summary>Arquivo changeset</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changeset1.jpg" width="1000px;" alt=""/>
      <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changeset2.jpg" width="1000px;" alt=""/>
  </details>
   <h3>Implementação ORM utilizando o framework Hibernate </h3>
   <p align="justify" style="font-family:roboto;">O Hibernate é a solução ORM Java que consiste em uma ferramenta utilizada para realizar o mapeamento objeto-relacional de forma completa e eficiente, essa tecnologia segue a especificação JPA que define um meio para realizar esse mapeamento. O Hibernate é o intermediário das interações entre as classes Java com o banco de dados relacional, fazendo assim a conversão da programação orientada a objetos para o banco de dados relacional. Durante o desenvolvimento do projeto foi utilizado a arquitetura Modelo-Visão-Controle (MVC) onde separamos através de uma lógica arquitetural o sistema em componentes interligados, onde é possivel definir a conexão com a camada de dados, interação com o usuário e as regras de negócio.</p>
	
  <p align="justify" style="font-family:roboto;">A lógica arquitetura implementada consistem em :</p>
        <li>Model - Representação das tabelas do banco de dados, onde foi definido as relações entre objetos e seus atributos, foi utilizado o método ORM para mapear essas classes.</li>
	<li>Repository - São interfaces Java que tem como principal função serem a camada de acesso a dados, durante seu desenvolvimento foi utilizado o padrão de projeto Facade pois é uma interface que simplifica as funcionalidades do JPA.  </li>
	<li>Services - São classes que possuem os métodos do Repository, é onde são mantidos as lógicas conforme as regras de negócio conforme a requisição do cliente.</li>
	<li>Controller - É a classe onde encontramos os endpoints utilizado para a interação com o front-end do projeto, a comunicação ocorre entre requisições HTTP presentes nas rotas do Controller, para essas requições utilizamos o padrão de projeto Proxy onde controlamos o acesso aos objetos nas com as anotações do Spring.</li>
  <details>
  <summary>Adicionando a dependência do hibernate</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/hibernate.jpg" width="1000px;" alt=""/>
  </details>
	<p align="justify" style="font-family:roboto;">O mapeamento das classes é construído através de algumas tags especificas do Hibernate, através desses dois exemplos acima conseguimos identificar tags chaves para o mapeamento, são elas: </p>
	<p align="justify" style="font-family:roboto;">@Table – Notação para especificar qual o nome da tabela no banco de dados; </p>
	<p align="justify" style="font-family:roboto;">@Column – Identifica o nome da coluna; </p>
	<p align="justify" style="font-family:roboto;">@Id – Identifica a “primary key”, ou seja, a coluna identificadora da tabela;</p>
	<p align="justify" style="font-family:roboto;">@SequenceGenerator – Cria uma sequencia de números no banco de dados.</p>

  <details>
  <summary>Exemplo mapeamento de classes</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/orm1.jpg" width="1000px;" alt=""/>
    <br>
    <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/orm2.jpg" width="1000px;" alt=""/>
  </details>
	    <p align="justify" style="font-family:roboto;" >Além das anotações citadas, é possível adicionar características especificas a determinada coluna. Ex:</p>
	    <p align="justify" style="font-family:roboto;" ><b>@Column(name = "evt_titulo", nullable = false, length = 30)</b></p>
	    <p align="justify" style="font-family:roboto;" >No trecho de código foi possível determinar o tamanho de caracteres que a coluna aceita estabelecer a restrição NOT NULL a coluna</p>
	    <p align="justify" style="font-family:roboto;" ><b>@Column(name = "usu_cpf", unique = true, nullable = false, length = 15)</b></p>		 	
  <p align="justify" style="font-family:roboto;">Nesse outro trecho foi possível estabelecer uma restrição de chave única (UK).</p>
	
  <p align="justify" style="font-family:roboto;"Durante o desenvolvimento do modelo utilizado no banco de dados, verificamos diversos relacionamento com cardinalidade n:n ( muitos pra muitos) ou seja vários elementos de uma entidade A podem se relacionar com vários elementos da entidade B e vice-versa, esses relacionamentos geram no banco de dados uma tabela de ligação, que possui o atributo identificador da primeira tabela com o identificador da segunda tabela.</p>
  <p align="justify" style="font-family:roboto;"No exemplo a seguir temos um dos vários relacionamento n:n no nosso banco de dados. As tabelas são Evento e Usuário. Ou seja, um evento pode estar ligado com diversos usuários, do outro lado um usuário pode estar ligado com diversos eventos no sistema.</p>
  <details>
  <summary>Implementação relacionamento n:n </summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/manytomany1.jpg" width="1000px;" alt=""/>
    <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/manytomany2.jpg" width="1000px;" alt=""/>
  </details>
    <p align="justify" style="font-family:roboto;" >No mapeamento utilizamos a anotação @ManytoMany par a identificar um relacionamento muito pra muitos, após isso foi escolhido a classe que identificar a classe dominante no relacionamento, que nesse caso é a classe Evento, com isso através da anotação @JoinTable identificamos o nome da tabela de relacionamento, em “joinColumns “ informamos o nome da coluna identificadora da classe dominante (Evento) e em ”inverseJoinColumns” informamos o identificador da outra classe (Usuário).</p>
    <p align="justify" style="font-family:roboto;" >
      Na classe Usuário identificamos através do “mappedBy” que a classe é o lado dominado do relacionamento, ou seja tem função apenas de mostrar os eventos ligados aquele usuário, através da “List” chamada “eventos”.</p>
   <h3>Controle de exceção</h3>
  <p align="justify" style="font-family:roboto;" >Durante o desenvolvimento de um API ocorre diversos erros durante o processo, o padrão do framework Spring é retornar uma resposta genérica para esses erros, acarretando em diversos problemas durante o teste e desenvolvimento da aplicação, levando a uma perda de tempo enorme, que na maioria das vezes é solucionado com algo simples. Com isso foi desenvolvido um controle de algumas exceções no projeto ajudando durante o seu desenvolvimento e para sua manutenção posteriormente. A primeira validação foi utilizando a implementação Bean Validator que vem junto com hibernate, essa função nós trás algumas anotações que são utilizadas para validar os atributos das classes.</p>
  
   <details>
  <summary>Controle de exceção de atributos </summary>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao1.jpg" width="1000px;" alt=""/>
  </details>
	  <p align="justify" style="font-family:roboto;">Levando como exemplo a classe Usuário verificamos a utilização da anotação @NotBlank que informa ao Spring que aquele atributo não pode estar vazio, outra anotação é @Email que verifica se o atributo “email” está em seu formato correto.</p>
	
  <details>
  <summary>Personalização de mensagens</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao2.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Para personalizar as mensagens que serão mostradas, foi criado um arquivo em “resources” chamado ValidationMessages.properties, esse nome é utilizado pelo spring para verificar se existe uma mensagem caso a validação falhar, caso a validação não possua mensagem personalizada será mostrado a padrão, no arquivo criado identificamos as mensagens personalizadas, após isso identificamos na anotação @NotBlank ou @Email o id dessa mensagem, como no exemplo a seguir:</p>
	
	
 <ul>
    <li>@NotBlank(message = "{email.not.blank}")</li>
    <li>@Email(message = "{email.not.valid}")</li>   
 </ul>
	
 <p align="justify" style="font-family:roboto;">Na classe controller da aplicação utilizamos a anotação @Valid nas requisições para verificar esses atributos.</p>
<details>
<summary>Anotação @Valid</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/exececao3.jpg" width="1000px;" alt=""/>
  </details>
	
 <h3>Controle de exceção utilizando ExeceptionHandler </h3>
   <p align="justify" style="font-family:roboto;">Outra controle de execeção foi desenvolvido atráves do ExceptionHandler</p>
 <p align="justify" style="font-family:roboto;">Para isso foi criado uma classe chamada “RestExceptionHandler” que captura as exceções que foram lançadas e faz o tratamento, essa classe herda uma outra classe do spring chamada “ResponseEntityExceptionHandler”  que fornece para nós os métodos para tratar exceções internas no Spring. A anotação @ControlleAdvice é uma anotação que lida com as exceções globalmente e a @ExceptionHandler é utilizada para tratar as exceções especificas.</p>
   
  <details>
  <summary> Classe RestExceptionHandler</summary>
  <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao4.jpg" width="1000px;" alt=""/>
                                                                                                                                         <br>
       <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao5.jpg" width="1000px;" alt=""/>
                                                                  
  </details>

                                                                                                                                         
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
   <ul>
  <li>Metodologia Ágil Scrum
  <ul>
    <li>Criação do Product Backlog do projeto utilizando o método Product Backlog Building;</li>
    <li>Criação das User Stories para o desenvolvimento da aplicação.</li>
    </ul></li>
  <li>Framework Spring Boot:
  <ul>
    <li>Mapeamento das classes e relacionamento de objetos utilizando Hibernate;</li> 
    <li>Arquitetura com Repository, Service, Model e Controller;</li>
    <li>Desenvolvimento do controle de exceções utilizando ExceptionHandler e BeanValidation.</li> 
    </ul></li>
  <li>Banco de dados:
  <ul>
    <li>Desenvolvimento do modelo conceitual do banco de dados atendendo os requisitos do cliente;</li>
    <li>Estruturação e configuração do Oracle SQLdeveloper;</li>   
    <li>Programação via SQL do banco de dados.</li>   
    </ul></li>
    </ul>
