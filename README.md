# Naveed-UMAI-SQA-Assesment
Its an UMAI SQA Assessment test implementation using Cypress tool

Cypress Implementation: 

 

INTRODUCTION: 

 

-It is a test Automation tool 
-It can test anything that runs on web browser 
-It uses JavaScript 
-It also has cypress dashboard 

 

How to use Cypress 

 
1: Setup: 
-We install cypress and select IDE or an editor where we want to write the test. 

2: Write test: 
-Write the actual tests 

3: Run the tests: 
Run our test and see the result. 

4: Debug 
-Based on the result we can also do debugging if required. 

Cypress Features: 

1)Time Travel: 

 
-Take snapshots as your tests run of your application 
on every command and after you have executed your test, 
you can see a command log and if you have however any 
of the command you can see a corresponding screenshot 
from your application 

2)Debuggability 

Readable errors and stack traces 

3)Automatic waits 

Automatically waits for commands and assertions before moving on 
or custom waits cypress will take care of all the waits 
whenever you have any assertions 

In case u want to add some customs waits that option is always there we have 
consistent 

4)Consistent Results 

-Doesn't use selenium or we driver, Fast, consistent and reliable 

-cypress interacts with browser directly and application directly 

5)Screenshots and videos 

 
-When u run cypress, u will get screenshots and videos 

6)Cross Browser Testing 

All the browser setup you can do cross browser testing from your local system and if required u can also use remote system or cloud services for doing cross browser testing and can easily interact with CI and CD 

Cypress enables u write all types of tests: 

-End to end test 
-Integration test 
-Unit test 

 

Setup: 

 

Prerequisite: 

 
Node.js (we can install cypress NodeJS) 
10 or 12 

open cmd--> node --version 
Also have npm(node package manager) 

 

- Download node js 

Download | Node.js  

 
As per your OS, it will go to windows installer 

 

Why we are installing node? 

We are installing because cypress is a node program and we will get it using npm 
and after installation, 

Check the version in cmd through below command: 

node –v 

 

-Install Visual Studio Code: 

 
We need some IDE or editor where we can write and create our test 

you can also use another editor. 

 

-Create a new folder for the cypress project 
In this folder we have set up the cypress project and we will have all the sub folders in it. 

Cypress--> inside this folder--> Project1 -> Folder created 

 
-Open the folder in VS: 

 

-Open VS CODE terminal and run command npm init -y 

There is terminal option so we will click and select the new terminal. It will open the terminal 
windows on the same folder that u have in the VS. 

Now run npm init -y command in terminal. 
we can run this command without –y. In this case u will get some question and will have to answer or just uses the defaults and can skip 

-y --> want to use all the defaults you can use the -y flag here 
now what is? 

this will create a file call package. Json in our project 
it is like a dependency management file 
go back to the folder u will see a file 

u can edit as per your requirement managing all the dependencies, also initializing the npm project. 

Now we can use npm commands directly on this project in case we had any dependencies and any libraries. 

 
It will manage all these if I want to send this project to any new system using the package. JSON, all my dependencies will be downloaded and I don't have to do it manually. 
In case u are familiar with java and maven, it is something like a pom file where it manages and takes care of all the dependencies. 

 

Now, Install Cypress npm install cypress (will install the latest version) and npx cypress -v 
If u want then give some particular version number e.g.  6.0 npm, install cypress @6.0, it will install a particular version. You can check cypress version also. 

In JavaScript End to End Testing Framework --> go to latest version 
if u get any warning u will ok and if you get any error u will to 
troubleshoot 

for clear--> clear project 
version to run 
npx is used to run npm commands in the local folder 
npx cypress -v -- to check the version of cypress 

 

-Open Cypress: 

 
command: npx cypress open 

Here u can see the cypress guide. You can see project structure in VS 

now u can project structure in vs 
here we have a folder, we have sub folder most important integration. 

here we have also an example folder 
cyp create the folder with some sample just for our learning if u want u can delete and create your own. 

we will create our test in the integration folder: 

fixtures folder 

Upload and download any file. You can keep it in this and also if u want to refer any data from file like: 
example. Json 

Plugin 
Any file u can put here 

Supports 
command.js -- custom command 
index.js-- this file is loaded before all the tests so 
you can use it for global configuration and again we will look at it 
later. 

Node modules 
this will have all the libraries and all the node module by this project 

cypress. Json 
we can do or we can set some configuration the port and base URL the default wait time 
all the project setup and configuration we can set in cypress. Json. 

 

 
