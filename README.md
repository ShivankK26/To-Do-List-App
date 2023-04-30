<!-- ABOUT THE PROJECT -->
# About The Project
![Screenshot 2023-04-22 at 5 01 08 PM](https://user-images.githubusercontent.com/115289871/235348566-82515112-2ac4-48dd-8176-e16e45a5484a.png)




In this Project, I've built a WebApp called as To Do List App using which you can create a To Do List for all your daily tasks. This WebApp is extremely beneficial for College Students who want to keep a Track of their entire Daily Activity. So, use it and just have fun!!!



Use the `README.md` to get started.




# Built With

The Tech Stacks use are:

<div align="center">
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mongodb,expressjs,nodejs,js,bootstrap,ejs,css" />
</a>
</div>




<!-- GETTING STARTED -->
# Getting Started

To get started, create a file called app.js and import all the required modules in it. After that create a folder called views and place the about.ejs, footer.ejs, header.ejs, list.ejs files in it. Also, create another folder called public in which add another folder called css in which you'll need to add a file called styles.css.


* modules

  ```sh
  const express = require('express')
  const mongoose = require('mongoose')
  const ShortUrl = require('./models/shortUrl')
  const app = express()
  ```

* ejs connectivity

  ```sh
  app.set("view engine","ejs")
  ```
  
* Using Body Parser

  ```sh
  app.use(bodyParser.urlencoded({extended: true}));
  ```

## Prerequisites

To begin with our Project, we'll need to install some npm packages like express, mongoose, body-parser, ejs, and lodash using the command given below. 


* npm

  ```sh
  npm install express mongoose ejs lodash body-parser
  ```
  
  
* To ease the process of development, we'll install nodemon (Make sure you already have nodemon installed in your system, if not then [visit here](https://nodemon.io/)).

  ```sh
  npm i nodemon
  ```


<!-- CONTACT -->
# Contact

Your Name - Shivank Kapur - shivankkapur2004@gmail.com

Project Link: 
