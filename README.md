# README #

Use the application generator tool, express-generator, to quickly create an application skeleton (kerangka applikasi).
1. Install express generator in global. 
$ npm install express-generator -g
2. Run this if you want use view engine jade for default.
$ express express-app
OR, If you wanna change the view engine, for example pug. So run this :
$ express --view=pug express-app
3. Navigate to the location of your project folder
$ cd express-app
4. Install dependencies
$ npm init
5. Install git
$ git init
6. Create readme file and add to git
$ git add README.md
7. Commit ke git 
git commit -m "first commit"
8. Add .gitignore and write file path for ignore
$ touch .gitignore

Install socket io for websocket
$ npm install socket.io --save

Run application on MAC or Linux
$ DEBUG=express-app:* npm start
Run application on Windows
$ set DEBUG=express-app:* & npm start
