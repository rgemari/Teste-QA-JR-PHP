<h4> Este projeto implementa uma API REST utilizando o framework Laravel PHP para gerenciamento de ordens de serviço. A API permite criar e listar ordens de serviço, com validações e testes automatizados para garantir a integridade dos dados. </h4>

_Requisitos_:
Antes de iniciar o projeto, verifique se os seguintes requisitos estão instalados:

- **PHP**: 8.0 ou superior

- **Composer**: para gerenciar as dependências do PHP

- **Laravel**: versão mais recente

- **MySQL**: banco de dados para armazenamento dos dados

- **Pest PHP**: ferramenta para testes automatizados

<h2> Instalação: </h2>

<h4> 1. Clonar o repositório: </h4>

Primeiro, clone este repositório para o seu ambiente local:

``git clone https://github.com/rgemari/teste-qa-jr-php.git``

``cd teste-qa-jr-php``

<h4> 2. Instalar as dependências: </h4>

Execute o seguinte comando para instalar todas as dependências do Laravel:

``composer install``

<h4> 3. Configurar o banco de dados: </h4>

Crie um banco de dados MySQL e configure as credenciais no arquivo .env:

``DB_CONNECTION=mysql``

``DB_HOST=127.0.0.1``

``DB_PORT=3306``

``DB_DATABASE=laravel``

``DB_USERNAME=root``

``DB_PASSWORD=``

<h4> 4. Rodar as migrações e seeders: </h4>

As migrações e seeders são necessárias para criar as tabelas service_orders e users, além de popular a tabela users com alguns dados iniciais.

Execute o seguinte comando para rodar as migrações:

`php artisan migrate --seed`

<h4> 5. Iniciar o servidor </h4>

Agora, inicie o servidor Laravel:

`php artisan serve`

