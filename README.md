# Hello World

Apigee Hello World example with maven files for deployment.  

To invoke  
`curl -i 'http://<apigee_org>-test.apigee.net/helloworld/greetings'`  

### To deploy:

`cd HelloWorld`  
`mvn apigee-enterprise:deploy -P test -Dusername=${APIGEE_USER} -Dpassword=${APIGEE_PASS}`  


