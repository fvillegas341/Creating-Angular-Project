# Creating-Angular-Project
This list the steps to take when creating a new Angular App CLI

prereq: 
-Install node.js current version
-Install VSC

Step 1: 
-Open default system terminal (Depending on the OS, on window open command line terminal). Leave this window open and we will get back to it.

-Visit angular.io/cli on a web browser

-execute: npm install -g @angular/cli on the default system terminal and hit enter. For Mac you will need to add sudo command to give it permission.

Step 2: 
-Create a folder where you want to store the project. For example create a folder called "My_Angular_App". Use mkdir command.

-In the default system terminal, once the angular is installed, cd to the folder previously created and type "ng new (title of the app)". It can be anything
for example: "ng new my-first-app".

-For first timers: include" --no-strict --standalone false --routing false"

-Hit enter. For the stylesheet use CSS, choose N for server-side. Hit enter.

-cd to the application. For example: cd my-first-app then type ng serve to make sure it works. It works if it is compiled successfully.

Step 3: Adding bootstrap

-add npm install --save bootstrap@3

-once installed, inform the CLI by going into the .angular-cli.json file and under styles array target the path of the file "node_modules/bootstrap/dist/css/bootstrap.min.css"

-verify it works by inputting a bootstrap class in the html. For example
<div class="container">
  <div class="row">
    <div class="col-md-12">
      <h2>I'm working</h2>
    </div>
  </div>
</div>



  
