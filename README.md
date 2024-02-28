# Axiom
##Prerequisites:
1.Node Js installed.
2.Visual studio code installed.
3.Cypress installed.

###Download & Install visual studio by following below steps:

1.Download the VS Code file from the Official Website.
2.Execute the download file.
3.Accept the Terms & Conditions.
4.Click on the Install button.
5.Wait for the installation to complete.
6.Click on the Launch button to start it.

####Install cypress by following below steps:

1.Create a folder
2.Open the folder in the visual studio code
3.Set up a Node project using npm -i init command using the terminal. You will get the package.json file created with default values.
4.Open new terminal run the following command to install cypress
  npm install cypress --save -dev
5.Now run the command to launch the cypress
  npx cypress open
A.Select E2E testing
B.Select chrome browser
C.Create empty space
Once configured those configuration will get added in the folder section.
6.Open up the terminal of your project and type the following command
  npm install -D cypress-xpath
7.This will install cypress xpath plugin will be automatically installed.
8.Add xpath reference to your support/command.js
  /// <reference types="cypress-xpath" />
   We are adding this line in support/command.js because, it will automatically load xpath commands to all the test spec files 
   instead of adding this line individually to each spec.
9.Add the following code under support/e2e.js file
  require('cypress-xpath');

#####To Run the project below steps:

1.Open up the terminal of your project and type the following command
  npx cypress open
2.Select E2E testing
3.Select chrome browser
4.Select file
  
 





