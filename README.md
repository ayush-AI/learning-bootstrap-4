# learning-bootstrap-4

# Getting started with Bootstrap
Setting up the Project Folder
Go to a convenient folder location on your computer and download the Bootstrap4-starter.zip file using the link provided at the top of this page.
Unzip the file to see a folder named Bootstrap4 and a sub-folder under it named conFusion created. Move to the conFusion folder.
Open a cmd window/terminal and move to the conFusion folder.
At the prompt type
-npm install
This will install the lite-server node module to your project.
Next, initialize a Git repository in the project folder, and then set up a .gitignore file with the contents as shown below:
node_modules 
Now do a commit of your project folder to the Git repository with the message "Initial Setup". You will be doing a commit of your project at the end of each exercise so that you retain the completed files of each exercise.
Set up an online Git repository and synchronize your project folder with the online repository.
Downloading Bootstrap
You will use npm to fetch the Bootstrap files for use within your project. Thereafter you need to install JQuery and Popper.js as shown below since Bootstrap 4 depends on these two. At the prompt, type the following to fetch Bootstrap files to your project folder:
- npm install bootstrap@4.0.0 --save
- npm install jquery@3.3.1 popper.js@1.12.9 --save
This will fetch the Bootstrap files and store is in your node_modules folder in a bootstrap folder. The bootstrap->dist folder contains the precompiled Bootstrap CSS and JS files for use within your project.
Open your project folder in your editor, and then open the index.html file in the conFusion folder. This is your starting web page for the project. We have already created the web page with some content to get you started. We will use Bootstrap to style this web page, and learn Bootstrap features, classes and components along the way.
Start your lite-server by typing npm start at the prompt. The index.html file should now be loaded into your default browser.
Getting your Web page Bootstrap ready
Open the index.html file in your favourite text editor. If you are using Visual Studio Code, Brackets, Sublime Text or similar editors, you can open the project folder in the editor and then view index.html.
Insert the following code in the <head> of index.html file before the title.
      <!-- Required meta tags always come first -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
This will include Bootstrap CSS into your web page. Note the subtle change in the fonts of the content of the web page. This is the Bootstrap typography effect coming into play. The default Bootstrap typography sets the font to Helvetica Neue and selects the appropriate font size based on the choice of the heading style and paragraph style for the content.
At the bottom of the page, just before the end of the body tag, add the following code to include the JQuery library, popper.js library and Bootstrap's Javascript plugins. Bootstrap by default uses the JQuery Javascript library for its Javascript plugins. Hence the need to include JQuery library in the web page.
          <!-- jQuery first, then Popper.js, then Bootstrap JS. -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
 
Now, do a Git commit with the message "Intro. to Bootstrap". You may push the commit to your online repository.
    



