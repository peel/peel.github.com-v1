---
layout: post
title: Successfuly migrating modular Maven project to SBT
category: Java Scala
---

Switching over from Scala's CLI, simple one-task-at-a-time development tools to fully featured swiss army knife w/ XML backend Maven is a painful experience. Even though JBoss forge eases the pain from time to time you certainly need to jump into one or two dredged pom.xml files. 
And the files grow. Massively.  

Having a bit of experience with SBT in Scala projects I wanted to take try to migrate the Maven multimodule project to SBT. Without any further ado...  


#### Project structure

The original Maven project follows a classic maven project structure for 3/n-layer app. Thus I have 
    
    /project
    + /project-db
    | + /src
    | | + /main
    | | |   + /java
    | | |   + /scala
    | | |   + /resources
    | | + /test
    | | |   + /java
    | | |   + /scala
    | | |   + /resources
    | | - pom.xml
    + /project-services
    + /project-api
    + /project-web
    + /project-it
    + /project-docs
    - pom.xml

<div class="textBox">
  <h5>One of the assumption was not to change Maven's dir structure.</h5>
  <a class="button headed light arrow" href="http://maven.apache.org" target="_self"><span>Learn More</span></a>
</div>

