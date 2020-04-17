# BurgersWithORM

## Description
Using a homemade ORM and MYSQL database, it allows you to create burgers and either eat them moving them into an eated coloumn or delete from either list entirely.

## Installation
To install this program you will need to download some NPM packages. First if you don't have a package-json file type into the terminal `npm init`. Once that is done type into the terminal again `npm install express mysql express-handlebars`. This will download the three npm packages that we need for the program to run. When you have this all done you can type `node server.js` to run this application on localhost:8080, but this program will also work on a hosted server.

![init-example](/images/init.PNG)
![install-example](/images/install.PNG)

## Usage
This program is very simple and used only as an example of a homemade ORM with a database. If you need a program that has lists and want to move items between them and add/delete them, then this program can also work.

Eat item in the list has two buttons. The first button text changes depending on which side of the list you are on and will move them between lists. The second button is the delete button what will remove the whole item. Down below it lets you add a new item and select which list it will be added to.

![example](/images/home.PNG)

## Credits
Creator:
* [Paul Lee](https://github.com/vb27)

## NPM Packages Used
* [MySQL](https://www.npmjs.com/package/mysql)
* [Express](https://www.npmjs.com/package/express)
* [Express-Handlebars](https://www.npmjs.com/package/express-handlebars)
