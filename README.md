## How to run this api on mac
- Clone this project
- run mysql server
- go to config/config.json and specify database data
- create file .env
- add field "SECRET", to .env, which will equal to some secret key
- add field "MAIL_USERNAME", "MAIL_PASSWORD", "MAIL_HOST", "FROM_EMAIL", "URL", "CLIENTURL"
- run npm run server:install
- run npm run client:install
- run npm run client:build
- then go to client/build/index.html and replace all "./" to "/"
- then go back to react_express dir
- node_modules/.bin/sequelize db:migrate
- node_modules/.bin/sequelize db:seed:all
- run npm run start
- app will run on http://localhost:8080
