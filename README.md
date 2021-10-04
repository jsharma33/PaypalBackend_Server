

### components
- CSS: Styling web pages, html files
- Javascript: Primary programing language
- ReactJS: Javascript library for building User Interfaces
- nodejs: Used in the backend
- express: To create the calling API


#### External Service Dependencies
- MongoDB Atlas: A cloud database used to store transaction details	

## Requirements
</br>

- node --version >= 6
- npm --version >= 3


## Local Installation for frontend
</br>

### Steps
- `git clone <repository-url>` where `<repository-url>`is the link to the forked repository
- `cd Repository_Path`


## Local Installation for backend
</br>

### Steps
- `git clone <repository-url>` where `<repository-url>`is the link to the forked repository
- `cd Repository_Path`



#### Config Variables
Define config variables in config.env.

- Create a free mongoDB atlas account at [https://www.mongodb.com](https://www.mongodb.com) and set a new cluster connection url equal to `db_connection_URL`
- Set `JWT_SECRET = <your_jwt_secret_string>` where `<your_jwt_secret_string>` is long alphanumerical string 


#### Starting server

```
cd Repository_Path
```
- Install all the dependencies with `npm install`
- Start the server with `npm start`
- Visit your API at [http://localhost:5000](http://localhost:5000.) :tada:

#### Starting frontend

```
cd Repository_Path
```
- Install all the dependencies with `npm install`
- Start the server with `npm start`
- Visit your app at [http://localhost:3000](http://localhost:3000.) :tada:
# PaypalBackend_Server
