# Lena's Bookshop
This is a note of building a web application using Vue, based on the course CS5244 Web Application Development at Virginia Tech. 

## Set Up Environment
To setup the environment for your web application, do the followings:

1. Create a working directory, this is where all your projects will be located. Your Tomcat directory will all be located here.
2. Make sure you have installed the latest version of the [Java 11 SDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) that your system supports. It should be fine to use OpenJDK and it should also be fine to use a Java 13.
3. Download and install [IntelliJ IDEA Ultimate](https://www.jetbrains.com/community/education/#students)
4. Download and install the latest version of [Tomcat 9](https://tomcat.apache.org/download-90.cgi). Put the archive file in your working directory and unzip it.
5. Download and install [Node.js](https://nodejs.org/en/download/).
6. Install [Vue-CLI](https://cli.vuejs.org/guide/installation.html). Once Node is installed, you should be able install the Vue Command Line Interface by running the following command in your terminal: 
  ```npm install -g @vue/cli```
7. This step is only for those who already have Node.js and/or Vue-CLI on their machines. Update them to the latest version using the following commands in your terminal: 
    ```bash
    npm cache clean -f
    npm install -g n
    sudo n stable
    npm update -g @vue/cli
    ```
8. Install the vue.js plugin for IntelliJ IDEA. Open IntelliJ and go to "preferences" in the menu. It will open a window and one of the categories should be "plugins". When you click on it, you should see tabs for "Marketplace" and "Installed". Search for "vue" in the Marketplace tab and click the install button. You may have to restart IntelliJ for the plugin to take effect.
9. Install the Vue.js devtools extension for Chrome. Go the the extensions manager for Chrome and search for the Vue.js devtools extension. Install it. If you use Firefox, you can install it there also.

## Create the Client-Server application in IntelliJ IDEA
Create an IntelliJ IDEA Project. The project will have two separate modules in it. One of them will be a module named "server", and the other module will be named "client".  The server module will be a Gradle project with Java and Web plugins; and the client module will be a static Vue project that will invoke the vue-cli took when it is created.

The following slides are the walk through of project.

[Client-Server-App](https://drive.google.com/file/d/1_3oVNJDX4N2Qv81J9B6a7qWt-tXEtzOP/view)
