# devops
Devops using all the agile knowledge to improve yourself.

# install maven is really easy
 - first of all you need to have java installed and properlly configured.
 - then go to https://maven.apache.org/download.cgi and download the lastes version .zip
 - once the download is done extract the apache-maven-{version}-bin.zip to a folder of your choice.
 - go to the system variables and create M2_HOME variable point to the apache-maven-{version}-bin folder
 - go again to the system variables and add to the path variable the apache-maven-{version}-bin/bin folder
 - start a command line of your choice, it can be cmd or powershell, and type mvn -version and hit enter.
 - that's all, we are done with maven instalation.
 
 # a very easy way to create your own archetype and save it on your local repository
- How to create maven archetypes base on your own projects.
- Create the project as usually then run the maven command 
- mvn archetype:create-from-project
- The first parte is done
- Now is time to save this archetype on the local repository, so we can use it to create new projects base on our new archetype.
- If you are using an IDE refresh the projects so you will be able to see in the target -> generated-sources the archetype folder 
- go inside of the archetype folder and run the maven command mvn clean install
- And now your new archetype is saved on the local repository ready to use.

#what is swagger?
- swagger is a tool built by ... to automate RESTful documentation
- test integration with icescrum

#what are the swagger dependencies?
- io.springfox:springfox-swagger2:2.6.1
- io.springfox:springfox-swagger-ui:2.6.1