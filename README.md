# Projeto de Loteria - Java Web

Este projeto é um sistema de loteria desenvolvido em **Java**, utilizando **PostgreSQL** como banco de dados e rodando no servidor **Apache Tomcat**. Ele permite o cadastro de jogadores, registro de apostas, geração de resultados aleatórios e consulta ao histórico de jogos.  

## Tecnologias Utilizadas  
O sistema foi desenvolvido utilizando tecnologias robustas e confiáveis:  
- **Java** – Linguagem principal para a lógica do sistema.  
- **PostgreSQL** – Banco de dados relacional para armazenar apostas e jogadores.  
- **Apache Tomcat** – Servidor de aplicação responsável por hospedar o sistema web.  
- **JPA/Hibernate** – Para o mapeamento objeto-relacional (ORM), facilitando a manipulação dos dados.  
- **Spring Boot** (Opcional) – Para simplificar a configuração e inicialização do projeto.  

## Como Rodar o Projeto  
Para executar o sistema localmente, siga os passos abaixo:  
1. **Clone o repositório:**  
   ```bash
   git clone https://github.com/seuusuario/loteria-java-web.git
   ```
2. **Configure o banco de dados:**  
   - Crie um banco de dados chamado `loteria` no PostgreSQL.  
   - Execute os scripts SQL disponíveis em `src/main/resources/db/migration`.  

3. **Configure o servidor Apache Tomcat:**  
   - Baixe e instale o [Tomcat](https://tomcat.apache.org/).  
   - Adicione o projeto à pasta `webapps` do Tomcat.  

4. **Compile e execute o projeto:**  
   ```bash
   mvn clean install
   mvn tomcat7:run
   ```
