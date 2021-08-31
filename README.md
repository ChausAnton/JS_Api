## How to run this api on mac
- Clone this project
- run mysql server
- go to config/config.json and specify database data
- create file .env
- add field "SECRET", to .env, which will equal to some secret key
- add field "MAIL_USERNAME", "MAIL_PASSWORD", "MAIL_HOST", "FROM_EMAIL", "URL", "CLIENTURL"
- run command "npm install cat package-lock.json"
- run command "npm run server"
