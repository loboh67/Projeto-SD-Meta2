# Projeto-SD-Meta2
Para executar o projeto necessita dois computadores diferentes, um que vai ser o server e outro que vai ser o cliente
Primeiro precisa de obter o IP do PC do server e deve inseri-lo no ficheiro Configuration.java no campo RMI_ADDRESS_SEARCH_MODULE
Após isso:
- No PC servidor correr os ficheiros:
  - SearchModule.java
  - UrlQueue.java
- No PC cliente ir para a diretoria do mvnw e correr o comando: *./mvnw spring-boot:run*

Após isto pode ir ao browser do cliente e aceder ao *localhost:8080* e testar todas as funcionalidades
