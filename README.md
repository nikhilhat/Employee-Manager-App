
# Employee-Manager-App

It is a project made using Angular Framework.

The major things used is JavaScript, HTML, CSS.

This project is mainly a mock database management system for employee of any firm.


## to Run this project Locally

Clone the project

```bash
git clone https://github.com/nikhilhat/Employee-Manager-App.git
```

Go to the project directory

```
After cloning the project, make sure you download all the 
npm modules required in the project.
```
First redirect yourself to the project containg folder

```
cd Employee-Manager-App 
```
After redirecting to the folder use code (--save is used to save all your 
installed core packages into the depedency section in the package )
```
$ npm i  --save
```

Start the live server

```bash
  before starting everything make sure you have created the database in Mongodb.
  make sure you creat a collection with admin.
  Then make another collection with name "emp"
  add data into it 
  ```
  ```
  db.emp.insert({"empid":1,"empname":"Arnold","dept":"IT","email":"arnold@gmail.com","level":"junior"})

```
Open your terminal  >

use node to run the App.js file
```
$ node app.js
```
This will allow the backend to start which will help our front end to work after putting a proper input.


