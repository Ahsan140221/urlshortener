# urlshortener
The following github repository contains code files for the frontend and backend of a web application named 'urlshortener'. The basic purpose of this url shortener is that a user types in a url with the proper url standards for instance (wwww.google.com) and gets a short url i.e a random number. The original url along with short url are stored in as a collection in mongodb. When the user requests again with the shorturl, database is queried which checks the corresponding original url with that short url and the user is redirected to the original url with the help of short url.

Tools and Technologies used:
Frontend :
Angular, Angular Material are used for designing frontend of the application.
For the front end to work download the frontend.rar(https://github.com/Ahsan140221/urlshortener/blob/master/frontend.rar). Unzip the rar file. Open command prompt in the directory in which the files are extracted. Run the command ng serve.

Backend :
Node.js, Express and MobgoDB are used for developing backend logic. For the back end to work download the frontend.rar(https://github.com/Ahsan140221/urlshortener/blob/master/backend.rar). Unzip the rar file. Open command prompt in the directory in which the files are extracted. Run the command node app.js and in the browser type (https://localhost:3021).



