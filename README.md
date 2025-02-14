# ChinguTalk

## 📝 Description
Ths application is a social media web application model where users can enter a database based on similar interest. The user's interests and image (through Cloundinary) can be updated on the profile page with a in app chat feature utilizing Socket.io.

## Table of Contents

- [Description](#📝-description)
    - [User Story](#👤-user-story)
- [Technologies Used](#🛠️-technologies-used)
- [Usage](#💻-usage) 
    - [Screenshot](#📸-screenshot)
- [License](#📃-license)
- [Links](#🔗-links-to-docs)

---------------
## 🛠️ Technologies Used

<ul>
<li>JavaScript
<li>Node
<li>dotenv
<li>express
<li>MySQL2
<li>sequelize
<li>cloudinary
<li>socket io
<li>heroku
</ul>

---------------

## 💻 Usage
<em>MySQL has to be installed on computer for this application to run.</em>

***Steps for Usage***  
**1:** once repo is cloned to local machine cd into it in the terminal

**2:** use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data 

**3:** run `npm i` to install dependencies   

**4:** run `mysql -u root -p` to start mysql     

**5:** once logged into mysql shell run `source schema.sql;` to create the database then `exit` to quit mysql shell   

**6:** run `node server.js` to start app  

**7:** open Insomnia or another  API development app to GET, POST, PUT, and delete the routes for users and interest    


### 📸 Screenshot

![screenshot placeholder](/public/Assets/homepageplaceholder.png)

---------------
## 🔗 Links to Docs

**dotenv:** https://www.npmjs.com/package/dotenv  
**express:** https://www.npmjs.com/package/express  
**mysql2:** https://www.npmjs.com/package/mysql2  
**sequelize:** https://www.npmjs.com/package/sequelize  
**cloudinary** https://cloudinary.com/documentation  
**socket.io** https://socket.io/docs/v4/ 

