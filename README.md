# E-Commerce

## Description
This is a back-end application for an e-commerce site. You can get, add, update and delete different products.
## Demo
Showing all categories using Insomnia:
<img width="1262" alt="Screen Shot 2021-10-24 at 1 22 25 PM" src="https://user-images.githubusercontent.com/86693696/138609523-2f4ebf9a-f12d-4c02-be29-38125a5c4f93.png">

Showing a category by id:
<img width="1263" alt="Screen Shot 2021-10-24 at 1 22 58 PM" src="https://user-images.githubusercontent.com/86693696/138609563-3bb90085-52ff-4bc8-b773-e3637d80de4e.png">

Showing how to create a new category:
<img width="1261" alt="Screen Shot 2021-10-24 at 1 22 47 PM" src="https://user-images.githubusercontent.com/86693696/138609566-d154a91f-9b31-40dd-bbc4-f0409a3296ff.png">

Showing how to update a category:
<img width="1259" alt="Screen Shot 2021-10-24 at 1 23 32 PM" src="https://user-images.githubusercontent.com/86693696/138609589-5c57434d-8b80-4023-88f6-d3a4deff4a2f.png">

Showing how to delete a category:
<img width="1263" alt="Screen Shot 2021-10-24 at 1 23 45 PM" src="https://user-images.githubusercontent.com/86693696/138609595-f0ebff71-35e7-4921-9a19-df7673a04107.png">

Watch a full video demo here:
https://watch.screencastify.com/v/1kVtmAn7Df2F2cKKIGAf

## Installation
* Have MYSQ2, Sequelize and dotenv installed in the terminal w/ the following commands:'npm i mysql2', 'npm i sequelize', 'npm i dotenv'
* Add a .env file to the root of the app with the following information: (replacing USER AND PW infor with your own)
     DB_NAME='ecommerce_db'
     DB_USER='root'
     DB_PW='yourpassword'

* In your terminal run 'mysql -u root -p' and enter in your password
* Run 'SOURCE db/schema.sql;'
* Then 'SHOW DATABASES;' and 'USE ecommerce_db;'
* In a new terminal window, run 'npm run seed' and 'npm start'

## Built With
* MYSQL2
* Sequelize
* Node.js


