# SmallestSpringSample

The smallest (few code and config) possible spring application. With both backend and frontend.

##What is it for

A clean example of a spring boot app.
It is as short and simple as posiable so it will not confuse new developers.
It can be use as a seed and a starting point for any other spring boot project.

###What it contain

Contain 2 server java file: Application and WelcomeController. Each with a single function of one line.
Contain 1 client html file: index.html with only a few html code.
Contain 2 config file: A small pom.xml with one dependency only on spring-boot-starter-web. And a application.properties with one line: port number.
And that it. This is a working spring program that create both a server and a client.

##How to run it

You can run it from eclipse IDE or from the command line. You can search google for menual on each step. They are generic as posiable. 
1. Download dependencies using maven. Run maven clean install. 
2. Compile the java code.
3. Run the java application. 
4. Open a browser and go to url: http://localhost:8011/.
5. If the server is working you should get an empty page with the text "Hello World".

That it. The server is runnig and it as send a message to the client you opend in the browser.

##More examples

For more advance application please visit the official examples site: https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples
Or look for them in orbartal github.

Hope this was helpfull.
For any questions please contect me at: orbartal at gmail.com
