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

The project structure: 

![image](https://github.com/ghailen/camunda-with-spring-boot-example/assets/36199753/6ab87680-bfe7-4740-b64e-0d3750dc5d30)

