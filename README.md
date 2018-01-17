# burger
Eat-Da-Burger! is a web-based application that simulates order-taking app. It lets users decide on the burger they'd like to eat.  Additionally, a user can add new names of burgers they'd like to eat.  If an existing burger has been eaten, the user can decide to make it again.


## Description
This application follows MVC design pattern and is built using Node.js Express, jQuery, MySQL, Bootstrap v3, Handlebars and a homemade ORM.  It runs in the browser on localhost:3030 or is hosted on Heroku [here](https://fierce-atoll-14039.herokuapp.com/).

## burger Interface
After invoking the node file (server.js), in the broswer address window (localhost:3000), the user is presented with the following screen.

Initial screen shot of Eat-Da-Burger!
![Main Screen 1](/public/assets/img/b1.jpeg)


Screen shot of Sequel Pro with data populated from schema.sql and seed.sql
![Main Screen 1](/public/assets/img/b2.jpeg)




To run burger (a.k.a. Eat-Da-Burger) locally, follow the steps below:
```
git clone git@github.com:dpkillian/burger.git
cd burger
npm install
cd db
mysql -u root -p
mysql> source schema.sql
mysql> source seeds.sql
mysql> exit
cd ..
node server.js
open browswer (http://localhost:3000)
```
