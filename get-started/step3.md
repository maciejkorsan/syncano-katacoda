Now it would be nice to check if our code is working. To do so we've prepared a simple website for checking the hello socket. Let's get the files!

⌨️ `git clone https://github.com/maciejkorsan/syncano-example`{{execute}}

Next you need to set the instance name in the project. To get the instance name type:

⌨️ `npx s info`{{execute}}

Copy the `current instance` value, and put it into `syncano-example/web/app.js` in the second line by replacing `INSTANCE_NAME` with your new value. (File autosaves on change so don't worry 😎)

Syncano has a hosting feature. Now we're going to get our sample website online. To add hosting execute:

⌨️ `npx s hosting add syncano-example/web`{{execute}}

Use default options, and for question `Do you want to sync files now?` answer *yes*. After files are uploaded click on given URL and fill the first and last name fields. 


