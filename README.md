# Title 
E-commerce Back end 

  # Description
  This is the back end code for an e-commerce app. In it you will find the api routes set up using CRUD functionality for Prodcuts, Categories and Tags which you can test in Insomnia.  

  # Table of contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribute](#contribute)
  * [Questions](#questions)
  
  ## Installation <a name="installation"></a>
  
  In order to install first you must clone the repo from Github. To do so enter this into your command line/terminal:
  `git clone git@github.com:Mcrouse42/e-commerce-back-end.git`
  
  After cloning the repo you will need to install npm, which is a package manager. This will also install the dependencies you need. First, in your command line/terminal, make sure you are in the correct directory. In this case it should be something like "e-commerce-back-end". Then you want to enter this into command line/terminal:
  `npm install` 
  
  Then you will need to initialize 
  
  `npm init`
  
  
  ## Usage <a name="usage"></a>
  Since you are using MySQL you will need to create a .env file in the main directory. In it you will store your MySQL login info safely so others can not get access. 
  
  In terminal navigate to the main directory for the project. Next you will need to create and seed the data using MySQL. To do so open MySQL and enter this:
  `source db/schema.sql`
  
  After that seed the information:
  `npm run seed`
  
  Once the database is created and the infomation is seeded you will want to run the program. To do so enter this into the command line/terminal:
  `npm start`
  
  From there you can test out the api routes by using Insomnia as shown in the Walkthrough video.

  [Walkthrough Video Link](https://drive.google.com/file/d/1Tm55ecX-2fIOK_hJpQAx-KpBNcqzZFku/view?usp=sharing)
  
  ## Technology used 
  Javascript
  MySQL/MySQL2
  Node.js
  Express.js
  .dotenv
  
  
  ## Contribute <a name="contribute"></a>
  If you would like to contribute you can fork this repo and clone it to your own computer. 


  ## Questions <a name="questions"></a>
  If you have any questions feel free to reach out through email or GitHub.
  GitHub: [Mcrouse42](https://github.com/Mcrouse42)
  Email: [matthew.crouse@temple.edu](mailto:matthew.crouse@temple.edu)
