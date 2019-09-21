# SmartBrain-api - v2
Nodejs backend 
Knexjs used
bcrypto for password/dbencryption
CORS disabled

- brew install postgresql
- start service -> brew services start postgresql
- create smartbrain db -> createdb 'smartbrain'

//Psquel db for mac(GUI)

Clarifai - AI powered face recognition rest api

dotenv for process.env files


You must add your own API key in the `controllers/image.js` file to connect to Clarifai API.

You can grab Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.
