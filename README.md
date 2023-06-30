# camunda-with-spring-boot-example
Now lets build an spring boot camunda project: 

First of all we need to add camunda archetype-spring-boot to our intellij maven project

groupId: org.camunda.bpm.archetype

ArtifactId: camunda-archetype-spring-boot

version : 7.16

Repository: https://artifacts.camunda.com/artifactory/camunda-bpm/

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/8dfdf1ae-744a-4013-9ccf-7f0427b79a77)

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/28906e4b-ef2a-466b-8521-b0094ccd1b58)

CamundaApplication class => is the entry point of the application
@EnableProcessApplication => is responsible of bootstrap the camunda


The default bpmn file existing : 

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/8119c0b5-682f-4abf-bdba-6152a64397af)


=============application.yaml=================

contains different properties about the application :

the used database is h2 in memory database

the user name

the password 

the port

use can also add more user in the config

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/1ab9fb86-e6de-485e-9725-b95452cf83b8)

=================The project structure====================

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/6ab87680-bfe7-4740-b64e-0d3750dc5d30)



==========Run the application and server==============

mvn install to generate the jar : 

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/7b71085f-5b6e-43a1-8827-cdf9940288c7)


the run the server by going the main class and click run java application:

the server is up on port 8080:

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/d8c3acaa-31ba-43b4-886f-6b07d9deb9fa)


open localhost:8080 to enter to the camunda webapp:

Now we can run our process : 

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/7cd9cad9-f496-4c58-ae6c-d85c567c80d5)

we can see the service task of log will print the log into our spring boot application console:

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/c02586f0-b2e5-438a-a0f8-af45baa1fc02)

in the application console:

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/fe49c0f3-b553-4dfe-aed9-f7d902f4a61e)



