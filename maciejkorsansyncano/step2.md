Now when you have an account, we can deploy our first function in the cloud. In the previous step, you've created a sample `hello world` socket. You might be wondering what the heck is `the socket`? Syncano sockets are pieces of code that are executed inside of your instance - they can be used for various things like creating a complete backend with database and users support, real-time messaging, and more. You can see the structure of your first `hello world` socket in `syncano/hello` directory. Sockets are described using YAML files (`syncano/hello/socket.yml`), the source code is stored inside `syncano/hello/src/hello.js`. Now we're going to send this code to the cloud!

⌨️ `npx s deploy`{{execute}}

This command sends the code of all of your sockets to your instance in the cloud so you can access it from your app!

To get a list of your sockets simply type:

⌨️ `npx s list`{{execute}}

You should find there there url: **your-instance**.syncano.space/hello/hello/ this is your working socket address!


