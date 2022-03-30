# E-commerce Back End Starter Code
  
  ![language](https://img.shields.io/badge/dotenv-^8.2.0-red)
  ![language](https://img.shields.io/badge/Express.js-^4.17.1-yellow)
  ![language](https://img.shields.io/badge/MySQL2-^2.1.0-blue)
  ![language](https://img.shields.io/badge/Sequelize-^5.21.7-green)
  
  

  ## Description

  ----------------------

  This project uses MySQL2, dotenv, Express and Sequelize to create and maintain a RESTful API for an e-commerce website. 

  [Click Here](https://drive.google.com/file/d/1EAP3DJEIXQcO-9iLOKfBNvwOF1ZMcjrj/view) for a video walkthrough on the functionality of the backend.


  ## Installation

  ----------------------------------------------------

  To install the E-commerce Back End or view the code, open `terminal` or `gitbash` and navigate to desktop.

    cd desktop


Clone this repo

     git clone https://github.com/lrodenyoder/e-commerce-back-end
  
Open folder in Visual Studio Code

Before the generator can be used, a `.env` file must be created in the root directory of the project and populated with the information needed to log into MySQL...

    cd e-commerce-back-end
    touch .env

...and npm modules for the project need to be installed

    npm install

To initialize the server, run the following commands...

    mysql -u <username> -p

...enter password when prompted...
    
    source db/schema.sql
    quit
    npm run seed
    npm start


 ## License

  -----------------------

  MIT License 

  Copyright (c) [2022] by [Lauren Yoder]

  [Click Here](https://choosealicense.com/licenses/mit/) to go to license details