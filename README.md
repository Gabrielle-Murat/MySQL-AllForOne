<h1 align="center">Projeto MySQL - All For One</h1>

<p align="center"> 
  <img src="gif/mysql.jpg" alt="MySQL Logo" width="40%">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Tabela de Conteúdos</h2>

<details open="open">
  <summary>Tabela de conteúdos</summary>
  <ol>
    <li><a href="#sobre"> ➤ Sobre o projeto</a></li>
    <li><a href="#tecnologias"> ➤ Tecnologias utilizadas</a></li>
    <li><a href="#descrição-do-projeto"> ➤ Descrição do projeto</a></li>
    <li><a href="#instruções"> ➤ Instruções</a></li>
    <li><a href="#requisitos"> ➤ Requisitos realizados </a></li>
    <li><a href="#requisito1"> ➤ Requisito 1: Buscando dados específicos em uma tabela </a></li>
    <li><a href="#requisito2"> ➤ Requisito 2: Buscando todos os dados contidos em uma tabela </a></li>
    <li><a href="#requisito3"> ➤ Requisito 3: Buscando primary keys em uma tabela </a></li>
    <li><a href="#requisito4"> ➤ Requisito 4: Contando elementos de uma busca </a></li>
    <li><a href="#requisito5"> ➤ Requisito 5: Buscando uma quantia de dados específica </a></li>
    <li><a href="#requisito6"> ➤ Requisito 6: Buscando dados e ordenando </a></li>
    <li><a href="#requisito7"> ➤ Requisito 7: Buscando dados, ordenando e limitando a quantia </a></li>
    <li><a href="#requisito8"> ➤ Requisito 8: Buscando dados, utilizando Alias e exibindo operações aritméticas </a></li>
    <li><a href="#requisito9"> ➤ Requisito 9: Filtrando por valores não nulos </a></li>
    <li><a href="#requisito10"> ➤ Requisito 10: Filtrando por condicional "OR" e ordenando os dados </a></li>
    <li><a href="#requisito11"> ➤ Requisito 11: Filtrando por string </a></li>
    <li><a href="#requisito12"> ➤ Requisito 12: Filtrando por data </a></li>
    <li><a href="#requisito13"> ➤ Requisito 13: Filtrando por condicional "OR" </a></li>
    <li><a href="#requisito14"> ➤ Requisito 14: Filtrando por condicional "AND" </a></li>
    <li><a href="#requisito15"> ➤ Requisito 15: Filtrando por hora, usando Alias </a></li>
    <li><a href="#requisito16"> ➤ Requisito 16: Filtrando datetime por condicionais </a></li>
    <li><a href="#requisito17"> ➤ Requisito 17: Filtrando por uma lista de possibilidades </a></li>
    <li><a href="#requisito18"> ➤ Requisito 18: Filtrando por condicional "AND" </a></li>
    <li><a href="#requisito19"> ➤ Requisito 19: Filtrando por condicionais, contando elementos e usando Alias </a></li>
    <li><a href="#requisito20"> ➤ Requisito 20: Inserindo 1 linha de dados em uma tabela </a></li>
    <li><a href="#requisito21"> ➤ Requisito 21: Inserindo várias linhas de dados em uma tabela </a></li>
    <li><a href="#requisito22"> ➤ Requisito 22: Atualizando dados em uma tabela </a></li>
    <li><a href="#requisito23"> ➤ Requisito 23: Atualizando dados por uma condicional </a></li>
    <li><a href="#requisito24"> ➤ Requisito 24: Atualizando dados por combinação de condicionais </a></li>
    <li><a href="#requisito25"> ➤ Requisito 25: Deletando dados por condicional </a></li>
    <li><a href="#requisito26"> ➤ Requisito 26: Deletando dados por condicional </a></li>
    <li><a href="#requisito27"> ➤ Requisito 27: Deletando todos os dados de uma tabela </a></li>
    
    <li><a href="#créditos"> ➤ Créditos </a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="sobre"> :pencil: Sobre o projeto </h2>

  <p align="center">Projeto desenvolvido durante a formação de BackEnd na Trybe com o intuito de consolidar o aprendizado de MySQL.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="tecnologias"> :computer: Tecnologias utilizadas</h2>

<p align="center">
  <a href="https://www.docker.com/" target="_blank"><img src="gif/docker-logo.jpg" alt="Docker Logo" width="15%"></a>
  <a href="https://code.visualstudio.com/" target="_blank"><img src="gif/visual-studio-code-logo.jpeg" alt="VS Code Logo" width="20%"></a>
  <a href="https://github.com/" target="_blank"><img src="gif/github-logo.jpg" alt="gitHub Logo" width="15%"></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="gif/mysql-logo.png" alt="MySQL Logo" width="15%"></a>
</p>

 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="descrição-do-projeto"> :page_facing_up: Descrição</h2>

<details>
  <summary>Descrição</summary><br />
  
  Neste projeto eu realizei:
  
  <ol>
    <li>Consolidação de conceitos e comandos de SQL;</li>
  </ol><br />

  Tem-se um banco de dados (`Northwind`) e uma série de requisitos com diferentes níveis de complexidade neste repositório.<br />
  Durante o desenvolvimento foi utilizado Docker para evitar a restauração manual do banco de dados no MySQL Workbench.<br />
  Foram desenvolvidos os arquivos contendo apenas o comando necessário para resolver o requisito pedido.<br />
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="instruções"> :scroll: Instruções</h2>

1. Clone o repositório
  * `git clone git@github.com:Gabrielle-Murat/MySQL-AllForOne.git`
  * Entre na pasta do repositório que você acabou de clonar;


2. Instale as dependências:
  * `npm install`

3. Como restaurar o banco de dados, se necessário:
  * Abra o MySQL Workbench,
  * Abra uma nova aba de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`,
  * Execute a query e aguarde alguns segundos,
  * Atualize a lista de dbs;

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="requisitos"> :woman_technologist: Requisitos Realizados:</h2>

<details open="open">
  <summary>Queries iniciais:</summary>

  <h4 id="requisito1">Requisito 1: Criando um container</h4>
  
    1. Criar um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12`

  <h4 id="requisito2">Requisito 2: Iniciando um containter</h4>
  
    2. Iniciar o container `01container`

  <h4 id="requisito3">Requisito 3: Listando containters</h4>
  
    3. Listar os containers filtrando pelo nome `01container`

  <h4 id="requisito4">Requisito 4: Executando comando sem acoplar</h4>
  
    4. Executar o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

  <h4 id="requisito5">Requisito 5: Removendo um containter</h4>
  
    5. Remover o container `01container`

  <h4 id="requisito6">Requisito 6: Fazendo o download de uma imagem</h4>
  
    6. Fazer o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container

  <h4 id="requisito7">Requisito 7: Manipulando um containter</h4>
  
    7. Rodar um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro

  <h4 id="requisito8">Requisito 8: Parando um containter</h4>
  
    8. Parar o container `02images` que está em andamento

</details>
<br />

<details open="open">
  <summary>Filtragem de dados:</summary>

  <h4 id="requisito9">Requisito 9: Gerando uma build para backend</h4>
  
    9. Gerar uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`

  <h4 id="requisito10">Requisito 10: Gerando uma build para frontend</h4>
  
    10. Gerar uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`

  <h4 id="requisito11">Requisito 11: Gerando uma build para testes</h4>
  
    11. Gerar uma build a partir do Dockerfile dos `tests` do `todo-app` nomeando a imagem para `todotests`

</details>
<br />

<details open="open">
  <summary>Manipulação de tabelas:</summary>

  <h4 id="requisito12">Requisito 12: Orquestrando containeres</h4>
  
    12. Subir uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar

</details>
<br />

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="créditos"> 💳 Créditos</h2>

Aplicativo ToDoList (todo-app) fornecido pela Trybe.


