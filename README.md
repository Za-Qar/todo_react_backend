# Todos-counters-notes backend

This api acts as the backend for [this project](https://github.com/Za-Qar/react_todo). This is a RESTful api that is conected to the Heroku database. 

When a user created a todo, counter or note, a post request is sent here then using Crypto js AES, it is encrypted and stored on the database. When the user requests data, I have get functions written to retireve data in ascending order using SQL. The user can of course also patch and delete items and this api gives them the capability in doing so.

## Built with

* Nodejs
* Express
* PostgreSQL
* Crypto Js AES encryption

## View the app

* clone down the repository
### `git clone https://github.com/Za-Qar/todo_react_backend.git`

* install all the dependencies needed
### `npm i`

* run the server
### `npm run start`

## Contact method

Please don't hesitate in contacting me if you have any queions or need ay assistance as I want to hear from you
[Contact email](mailto:za.qa@outlook.com?subject=[GitHub]%20Todos%20Counters%20Notes%20Backend)
