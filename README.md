🌟 Docker Playground: Multi-Container Setup!

Bem-vindo ao seu ambiente de desenvolvimento completo com Docker! 🚀 Este projeto usa Docker Compose para levantar múltiplos serviços, incluindo bancos de dados, aplicações web e ferramentas de administração. Tudo configurado para você aprender e experimentar como um verdadeiro Dev! 🙌

🎯 O que esse projeto inclui?

1. PostgreSQL - Banco de Dados SQL 🗄️
Container Name: postgres_container
Imagem: postgres
Porta: 5432
Descrição: O PostgreSQL é um banco de dados relacional poderoso, perfeito para suas aplicações que precisam de persistência de dados. Configure-o com o usuário e senha root.


2. pgAdmin - Interface de Administração para PostgreSQL 🖥️
Container Name: pgadmin4_container
Imagem: dpage/pgadmin4
Porta: 5050
Descrição: O pgAdmin facilita o gerenciamento do banco de dados PostgreSQL com uma interface web amigável. Acesse via localhost:5050 com as credenciais admin@admin.com / root.

4. Flask App - API REST em Python 🐍
Container Name: flask_container
Imagem: python:3.9-slim
Porta: 5000
Descrição: Um contêiner leve que roda um servidor Flask para sua API REST. Pronto para conectar com o PostgreSQL. Mapeado no diretório ./app.

5. PHP com Servidor Embutido - Aplicação PHP 🧙‍♂️
Container Name: php_container
Imagem: php:8.0-cli
Porta: 8000
Descrição: Um servidor PHP embutido para testar suas aplicações diretamente no seu navegador. Acesse em localhost:8000.

6. Apache Tomcat - Servidor de Aplicações Java 🌱
Container Name: tomcat_container
Imagem: tomcat:9.0
Porta: 8080
Descrição: Para aqueles que amam o Java, o Tomcat está aqui para rodar suas aplicações Spring Boot. Apenas jogue seu .war no diretório ./spring_boot_project.

7. MySQL - Banco de Dados SQL 🗄️
Container Name: mysql_container
Imagem: mysql:8.0
Porta: 3306
Descrição: Banco de dados MySQL para quem prefere SQL na versão mais popular da web. As credenciais padrão são root / root para acesso total.

8. phpMyAdmin - Interface de Administração para MySQL 🖥️
Container Name: phpmyadmin_container
Imagem: phpmyadmin/phpmyadmin
Porta: 8081
Descrição: Uma interface web para gerenciar seu banco de dados MySQL. Acesse via localhost:8081.


🚀 Como usar?

Clone o Repositório:

git clone https://github.com/seuusuario/seurepositorio.git
cd seurepositorio
Suba os Contêineres:
 
docker-compose up -d


Acesse os Serviços:


PostgreSQL: localhost:5432


pgAdmin: localhost:5050


Flask: localhost:5000


PHP: localhost:8000


Tomcat: localhost:8080


MySQL: localhost:3306


phpMyAdmin: localhost:8081


📚 Quer se aprofundar em Docker e DevOps?

Se você quer se tornar um mestre no uso de Docker, conte com o Professor Marco Maddo! Com mais de 20 anos de experiência, ele oferece treinamentos que vão do básico ao avançado. Confira em: marcomaddo.com.br 🌐.

💬 Contribua e Compartilhe!

Gostou do projeto? Então, contribua, faça um fork, e compartilhe com seus amigos! Vamos construir juntos! 🤝
