# Teste de microsserviço usando Gatling

Desculpe, este repositório não está sendo mantido, a versão mais recente do Gatling tem suporte para alimentadores (para alimentar o input json), verifique o site do Gatling.
Criando o arquivo jar de microsserviço de usuário
----------------------------------------
Etapa 1 : Mude para o diretório to  micro-services/ecommerce-microservices/user-microservice

Etapa 2 : Execute $ mvn package

Etapa 3 : The above will create a JAR in the target directory

Jar de construção: target/user-microservice-0.0.1-SNAPSHOT.jar

--------------------------------------
 $ java -jar target/user-microservice-0.0.1-SNAPSHOT.jar
 
 Como alternativa - Você pode compilar e executar em execução usando  $ mvn -q clean spring-boot:run
 ----------------------------------------------------------------------------------------
 
 Teste o microsserviço
 ----------------------
 Etapa 1 : Abrir a URL em um navegador - http://localhost:9001/users
 
 
Running the Gatling test using Maven
-------------------------------------
Etapa 1 : Abrir o prompt de comando

Etapa 2 : Altere para o diretório micro-services/tests/user-microservice-gatling-tests

Etapa 3 : mvn clean gatling:execute

cleitonferreiraa@hotmail.com
