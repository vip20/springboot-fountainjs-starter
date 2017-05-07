# springboot-fountainjs-starter

RUN below commands

* npm install

* gulp build

* mvn spring-boot:run (alternative: run in spring tool suite as Spring Boot App)


# How I made this application

#  # Prerequisite (follow the sequence):

[Node.js]:<https://nodejs.org/en/>
[Yeoman]:<http://yeoman.io>
[FountainJS]:<http://fountainjs.io>
* [Node.js] installed.
* [Yeoman] installed.
* [FountainJS] installed.
  
#  # Procedure:
  [SPRING INITIALIZR]: <https://start.spring.io/>
* Head over to [SPRING INITIALIZR] and generate project with your <b>Project Metadata</b> and <b>Dependencies</b>. Later unzip and move the package to your workspace.
* Run ``` $ yo fountain-webapp``` in the package.
* Run ``` $ npm i -g glup-cli``` 
* Change ```  dist:'dist' ``` in conf/gulp.conf.js to  ```  dist: 'src/main/resources/static/'```
*  Run ```  $ gulp:build``` followed by ``` $ mvn spring-boot:run```(alternative: run in spring tool suite as Spring Boot App)
