# CRUDNODEJSCOMPLETO

<p>1.Preparação:
Certifique-se de ter o Node.js e o MySQL instalados em seu sistema. Para instalar as dependências Node.js, crie um diretório para o projeto, navegue até ele pelo terminal e execute:

bash
Copy code
npm init -y
npm install express mysql ejs

</p>
<p>
2.Configuração do MySQL:
  
Certifique-se de ter o MySQL em execução e crie um banco de dados chamado crud_example. Seu usuário será "root" e a senha estará vazia.

Estrutura de Arquivos:
Crie os seguintes arquivos na pasta do projeto:

index.js: Arquivo principal do servidor Node.js.
views/index.ejs: Arquivo de modelo para a página HTML.
public/style.css: Arquivo CSS para estilização.

</p>

<p>



  Execução:
No terminal, navegue até o diretório do projeto e execute:

bash
Copy code
node index.js
Acesse http://localhost:3000 em um navegador para ver e interagir com o aplicativo CRUD básico. Este exemplo é apenas um ponto de partida, e você pode expandi-lo com mais funcionalidades, tratamento de erros e segurança adequada conforme necessário.
</p>


<p>

  dentro da tabela CRUD_EXAMPLE rode a seguinte query:

  CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  email VARCHAR(255) NOT NULL
);

</p>
