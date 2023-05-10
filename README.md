# criandoPrimeiroProjeto
Com este projeto você conseguira criar seu primeiro projeto com Cypress.

Para realizar a execução completa siga as instruções abaixo.

## Requisitos:

Para rodar o Cypress no Windows, você precisará ter os seguintes requisitos:

## Node.js: 
O Cypress requer o Node.js instalado no seu sistema. Você pode baixar o instalador do Node.js no site oficial (https://nodejs.org) e seguir as instruções para instalação.

## npm: 
O npm (Node Package Manager) é instalado automaticamente junto com o Node.js. Certifique-se de ter uma versão atualizada do npm, que geralmente é incluída na instalação do Node.js.

## Editor de código: 
Você pode usar qualquer editor de código de sua preferência para escrever seus testes no Cypress. 
Usaremos o Visual Studio Code, porém existem muitos editores disponíveis, segue alguns editores populares como o; Atom, Sublime Text, entre outros.

Após instalar o Node.js, você pode seguir os seguintes passos para começar a usar o Cypress:

Abra o terminal ou prompt de comando no Windows.
Navegue até o diretório do seu projeto ou crie um novo diretório para o projeto.
Execute o seguinte comando para iniciar um novo projeto Cypress e instalar as dependências necessárias:

## 1°  "npm init"
Inicializa um projeto Node -  para ser o nosso gerenciador de pacotes.
Criação do arquivo "package.json".

## 2°  "npm install -D cypress" 
ou alguma versão específica  exemplo => "npm install cypress@0.0.0" 
Instala como dependência de desenvolvimento. 
Criação da  pasta "node_modeules" e o arquivo: "package-lock.json".

## 3° "npx cypress open" 
Irá executar a tarefa no caso abrir o Cypress criando as pastas estruturadas necessárias para o projeto.
* Obs: 
 - O comando "npm cypress open" => cria a estrutura que é a pasta padrão e abre o cypress.
 - A primeira vez que roda o cypress, ira aparecer uma mensagem onde o Cypress identifica e irá realizar uma configuração de compatibilidade.
 - Então caso ocorra algum erro de time out, basta rodar novamento o comando "npx cypress open". 
        
 ### Estrutura Básica:       
Ao final será aberto o Cypress Test Runner, com alguns arquivos de exemplo para vc estudar sobre o nosso querido cypress.
Também cria a estrutura de pastas na raiz do projeto.
Esta pasta leva o nome de "cypress", sendo ela composta por outras 4 pastinhas:
## 1° - pasta "cypress"
  ### 1° pasta "fixtures": 
  utilizada para armazenar dados e mocks
  ### 2° pasta "integration": 
  pasta onde são criados todos os testes
  ### 3° pasta "plugins": 
  configuração de plugins e  configurações fora do browzer, por exemplo comandos SQL.
  ### 4° pasta "support": 
  configuração de extensão ou plugins são adicionados aqui, além da criação dos "commands".
Posterior existe outro arquivo chamado:
### cypress.json 
Onde ficam as configurações do Cypress, como uma url padrão(url base) para usar em todos os testes, dados para login entre outras configurações.



