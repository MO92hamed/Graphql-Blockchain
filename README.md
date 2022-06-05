# Blockchain Graphql Application

In this application , we have an authentication syteme with email validation, Blockchain news with Graphql contain  transfers per day for Several digital currencies and store them in the database using nodejs expressjs, mongodb and Blockchain data API. 


## Dependencies

- Nodejs

- Expressjs

- Graphql

- bcrypt

- jsonwebtoken

- mongoose

- dotenv

- nodemon

## Roadmap

- Install Dependencies

- Create Server

- add Auth-Router

- Connect to Database

- Create User model

- Create user with POST /auth/register

     - Check if email is unique

     - Hash pasword

     - Insert into database

- Login user with POST /auth/LOGIN

     - Check if email in database.

     - Compare password with hashed password in database.

     - Create and assign a JWT     

- Connect with a real time Blockchain data api and fetch a data

- Create a graphql Systeme
  
   









## Deployment

To deploy this project run

```bash
  npm install
```

```bash
  npm start
```


## Authors

- [@Mo92hamed](https://github.com/MO92hamed)
