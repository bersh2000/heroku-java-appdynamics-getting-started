# Java with AppDynamics: Getting Started (Maven)

This is a fork of a barebones Java app, which can easily be deployed to Heroku. 
It should pop up on the controller screen in five minutes or less. 

[Get Your Java Agent at AppDynamics.com](https://appdynamics.com)

# Drop your AppDynamics Agent zip in place of heroku-java-appdynamics-getting-started/src/appd/AppAgent.zip and you should be ready to deploy on Heroku. 

Changes include 
Procfile, pom.xml and a placeholder file for the agent zip 
Everything else is identical to the origianal heroku 

You might want to put some memory restrictions to your Procfile, I am using eco dyno with

 -Xms156m -Xmx412m

