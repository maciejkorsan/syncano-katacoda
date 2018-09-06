Now when you have an account we can deploy our first function in the cloud. In the previous step you've created a sample `hello world` socket. You might be wondering what the heck is `the socket`? Syncano sockets are pieces of code that are executed inside of your instance - they can be used for various things like creating complete backend with database and users support, realtime messaging, and more. You can see the structure of your first `hello world` socket in `syncano/hello` directory. Sockets are described using YAML files (`syncano/hello/socket.yml`), source code is stored inside `syncano/hello/src/hello.js`. Now we're going to send this code to the cloud!

⌨️ `npx s deploy`{{execute}}

This command sends the code of all of your sockets to your instance in the cloud so you can access it from your app!

To get list of your socket's url just type:

⌨️ `npx s list`{{execute}}

You should find there there url: https://<your-instance>.syncano.space/hello/hello/ this is your working socket address!


