# Git e GitHub # 

### Prefácio ###

Essas anotações foram feitas durante as aulas do curso básico de Git e GitHub na plataforma Dio. Quero começar mencionando que inicialmente foi difícil entender todos esses conceitos. Tendo em vista essa minha dificuldade, tentei deixar a linguagem o mais tangível possível. Ou seja, essas anotações foram escritas para serem lidas por iniciantes assim como eu. Com elas, além de fixar ainda mais esses conceitos, posso ajudar outras pessoas praticando algo que gosto bastante que é escrever. Estou aberta a sugestões e possíveis correções que sejam necessárias fazer. Espero que gostem da leitura. 

### Introdução ###

Git é um sistema de controle de versões distribuído. Ou seja, é um sistema que permite ao desenvolvedor “guardar” seu primeiro código de um projeto e ir alterando sempre que for necessário sem ter que criar o código novamente.  Então, uma vez que o trabalho foi criado, ele cria um código base e isso faz com que o desenvolvedor acompanhe as mudanças que estão sendo feitas ali. 
Já o GitHub é um sistema de controle de versões distribuído, porém remoto. Além disso, é um tipo de “rede social” voltada para profissionais de TI, sendo esse sustentado pelo Git. Em outras palavras, o GitHub é uma plataforma online onde você pode criar repositórios e guardar neles seus projetos, colaborar com outros projetos, interagir com outros profissionais da área e com códigos de terceiros. 

### **Comando Básicos no Git no Windows**

* Para entrar numa pasta: para entrar em uma pasta o comando vai ser **cd *.**
  Ex.: cd workspace - para entrar numa pasta chamada workspace;

* Para sair de uma pasta e voltar para uma anterior o comando é **c . .**

* Para listar as pastas existentes o comando será: **dir**
* Para limpar a tela de comando é só clicar **ctrl l** simultaneamente
* Para criar uma nova pasta o comando vai ser **mkdir** 
  Ex.: mkdir workspace para criar uma pasta chamada workspace. 
* Para deletar os arquivos dentro de uma pasta, você escreve o comando **del (nome da pasta**).
* Já para deletar a pasta com todo o seu conteúdo você vai escrever **rmdir (nome da pasta) /S/Q**. 

### **Ciclo de Vida dos Artigos no Git** 

**Git Init**: É o comando que vai criar um repositório dentro de uma pasta (diretório) 
Tracked ou Untracked

* Tracked são os arquivos que o Git tem conhecimento, ou seja, que podem ser rastreados por ele. Eles são subdivididos em três grupos: **unmodified**: arquivo que ainda não foi modificado. **Modified**: sofreu alguma modificação **Staged**: são arquivos que ainda estão sendo preparados para fazer parte de um outro agrupamento. 

* Untracked são os arquivos que o Git ainda não tem conhecimento .

  **Os artigos que estão em staged estão se preparando para fazer parte de um commit, e, nesse caso, a partir disso, eles retornam para Unmodified**.

### Objetos Internos do Git ###

No Git existem 3 objetos básicos responsáveis pelo versionamento do código. Por ser um assunto um tanto complexo, esse material traz consigo somente o funcionamento básico desses objetos. 

**Blobs **: é o objeto responsável por guardar os arquivos colocados no Git.  

**Tree**: as trees são responsáveis por armazenar os blobs. 

**Commit**: é o objeto que irá agrupar tudo que tem ali. 

Para melhorar o entendimento. Imagine como se fosse um armário, sendo o blobs o bloco básico, onde ficam os arquivos, as trees sendo as gavetas desse armário e o commit sendo o armário em si. Lembrando que essa comparação serve apenas para ser entendida de forma palpável, numa tentativa de deixar o assunto menos complexo. 

Para entender melhor recomendo a leitura: https://git-scm.com/book/pt-br/v2/Funcionamento-Interno-do-Git-Objetos-do-Git





 





