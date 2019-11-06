# Adonis API application

### `sudo docker run --name database -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11`
Cria o container do postgres passando como parametro o usuario, senha e a porta do banco de dados.

### `sudo npm i --global @adonisjs/cli`
Instala a **CLI** do AdonisJs.

### `git clone https://github.com/victorreinor/adonisjs`
Clona o repositório do projeto.

### `cd adonisjs`
Entra dentro da pasta do repositório.

Em seguida crie um arquivo **.env** com base no **.env.example** para setar as variáveis de configuração do sistema.

Caso a máquina virtual for criada igual a do exemplo acima, não irá precisar alterar nada, somente crie a **.env** copiando o conteúdo completo.

### `yarn install`
Instala as dependências que estão sendo usadas no projeto.

### `adonis serve --dev`
Inicia o servidor de desenvolvimento.

### Comandos adicionais

#### `adonis make:controller NomeDoController`
Cria o controller com o nome desejado.

#### `adonis migration:run`
Roda as migrations (cria a tabela e o banco de dados).


#### `docker ps`
Exibe todos os containers que estão onlines.

#### `docker ps -a`
Exibte todos os containers que foram criados.