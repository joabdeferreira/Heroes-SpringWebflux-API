# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois
## Stacks utilizadas: 

  * Java8  * spring webflux  * Spring data * dynamodb  * junit  * sl4j * reactor
 
### Slides de palestra: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux
### Palestra garavda: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s

### Executar dynamo: 
 na pasta em que o jar está baixado: java -D java.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000
documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html

//UPDATE: Versão feita em casa ainda apresantando erro nos testes na hora de rodar o DynamoDB
https://github.com/joabdeferreira / 

joabdeferreira@gmail.com

Joab Ferreira