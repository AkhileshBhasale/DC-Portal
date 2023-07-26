Welcome to the Drupal Design Credits Portal Website repository. This repository contains the code to main website. Follow the following installation instructions to get started.
#Installation : 
We will first start by installing XAMPP. This is a local webserver that helps us to test our drupal website on our desktop. You may also use another service like Lando (paid) or Hostinger (paid). 
##XAMPP Installation:
Visit their [website](https://www.apachefriends.org/index.html) and follow the steps to install XAMPP. 
Once you are done with installation you can use the panel to start and stop the server and database. XAMPP comes with a MySQL database in-built where you can manage this website's database. Installing XAMPP will allow us to test and see how our website looks in real time. In fact most of our development will be done here.
##Drupal 
After installing XAMPP you will have to clone this(the master branch) repository and paste it in the "htdocs" folder insider XAMPP. Then open your browser and go to "localhost/drupal". You will be prompted to do an installation. Then you will have access to the website with administrator priviledges. Keep track of your passwords for XAMPP and Drupal. Having admin access to the website allows you to add content, users and even new features to the website as you please. Keep in mind that you may have to change the name of the "settings.default.php" file to "settings.php".
##Alternative Installation:
If you wish to install a fresh Drupal website then you may follow the steps given [here](https://www.drupal.org/docs/develop/local-server-setup/windows-development-environment/quick-install-drupal-with-xampp-on-windows).
#Some helpful tips:
1. If you wish to see how the website looks to different users create those users and log with their credentials to see how they will see the website.
1. You can add pages by creating new views that show content, or simply create new content types, editing their fields, adding content and finally publishing them.
1. It is also possible to embed basic HTML, CSS and Javascript code into the body of a page to create buttons, links inputs etc. 
1. You can also use modules to implement newer functionalities, but beware that most modules worked on older versions of drupal and are not being maintained anymore. 
1. Keep track of user persmissions and make sure the all users are being grated the minimum number of persmissions required to prevent any security issues.
1. Make use of taxonomy terms properly. Adding taxonomy terms to any content type can help users view and filter content based on taxonomy terms.
