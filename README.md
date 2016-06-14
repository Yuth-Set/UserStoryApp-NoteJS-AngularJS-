# UserStoryApp-NoteJS-AngularJS-

All the stap and process for building this app
------------------------------------------------
*AngularJs with NodeJs and MongoDB
__________________________________________________
1.First Step
---------
PS D:\Project> mkdir angularappd
PS D:\Project> cd .\angularapp\
PS D:\Project\angularapp> npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg> --save` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
name: (angularapp)

version: (1.0.0)
description: This is angular app with nodjs and mongodb
entry point: (index.js) server.js
test command:
git repository:
keywords:
author: GiantPlay
license: (ISC)
About to write to D:\Project\angularapp\package.json:

{
  "name": "angularapp",
  "version": "1.0.0",
  "description": "This is angular app with nodjs and mongodb",
  "main": "server.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "GiantPlay",
  "license": "ISC"
}


Is this ok? (yes) yes
-----------------
2. Install node_modules package
------------
PS D:\Project\angularapp>npm install express body-parser morgan --save
------------------------------
3. Run the server
-----------
PS D:\Project\angularapp> node server.js
Listening on port 3000
---------------------------------
4. Install mongoose for db
----
PS D:\Project\angularapp> npm install mongoose --save
---------------
*Install nodemon to start app services
npm install -g nodemon
-> nodemon server.js (to run our app service)
5. Connect to DB
-----------
PS D:\Project\angularapp> nodemon server
----------
6. Install bcrypt-nodejs library
-------------
PS D:\Project\angularapp> npm install bcrypt-nodejs --save
-------------
7. To create Token we need to install
-------
PS D:\Project\angularapp> npm install jsonwebtoken --save
------------
8. Install the reall time for web application socket.io
------
PS D:\Project\angularapp> npm install socket.io --save 
https://www.youtube.com/watch?v=VzpCVLYQAik&list=PLutYP2Nolsfj5yVYWXDQiyyMN0f6j8HlG&index=21#t=2.680788
