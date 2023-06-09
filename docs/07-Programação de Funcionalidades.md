# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Implementação do sistema descritas por meio dos requisitos funcionais e/ou não funcionais. Deve relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de  .

Para cada requisito funcional, pode ser entregue um artefato desse tipo

- ## Tela home 

A tela principal mostra a apresentação do site. A tela tambem mostra a opção de login, depoimentos e favoritos.

![Exemplo de UserFlow](img/pagina_home.png)


 - **requisitos atendidos**

    **RF_001**

- ## Artefatos da funcionabilidade
 **index.html**
 **home.html**
 **style.css**

 
- ## instruções de acesso
 1. Clique no botão no canto superior direito da tela indicado como login
 2. Preencha as informações de acordo com o solicitado pelo site (Nome, Email, Senha e Confirme Senha), se não for cadastrado, vá na apção de cadastro



 
- ## Estrutura de dados


![Exemplo de UserFlow](img/codigo_home.png)

- ## Tela de login e cadastro
A tela de login permite ao usuário já cadastrado ter acesso a suas informações pessoais e a funcionalidades do site disponíveis apenas para os que já possuam login. Se nao for cadastrado, oferece a opção de cadastrar

![Exemplo de UserFlow](img/tela_login.png)

 - **requisitos atendidos**
 
 - **Rf-02**

 - ## Artefatos da funcionabilidade

 **login.html**
 **style.css**
 **login.js**

- ## Estruturas de dados 


![Exemplo de UserFlow](img/codigologin.png)

- ## instruções de acesso
 1. Clique no botão no canto superior direito da tela indicado como Login;
 2. Preencha as informações de acordo com o solicitado pelo site (Email e Senha);
3. Clique em Fazer login.
(se o usuario não tiver cadastro redirecionar para a tela de cadastro )


- ## Tela de cadastro 
A tela de efetuar cadastro permite ao usuário se cadastrar no site para que possa ter acesso a outras funcionalidades como gerenciar tarefas, suas receitas favoritas, participar de forum e etc.

![Exemplo de UserFlow](img/tela_cadastro.png)


 - **requisitos atendidos**
 
 - **Rf-02**

 - ## Artefatos da funcionabilidade
**cadastro.html**
**style.css**
**cadstro.js**

- ## Estruturas de dados 

![Exemplo de UserFlow](img/codigocadastro.png)

 ## instruções de acesso
1. Preencha as informações de acordo com o solicitado pelo site (Nome, CPF,Email, Senha)
2. Clique em Cadastrar



- ## link do site 
https://ephemeral-lamington-4e9f9d.netlify.app/






























    




  






> **Links Úteis**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)