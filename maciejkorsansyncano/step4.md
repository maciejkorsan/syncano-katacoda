Congratulations! You've made your first socket working! Let's try to do something more. Syncano CLI has hot deployment feature which allows you to debug and instantly deploy your new code to the cloud. 

⌨️ `npx s hot`{{execute}}

Now the process watches for files changes inside `syncano` directory. Let's change our socket's response. To do so go to the file `syncano/hello/src/hello.js` in the editor above. In line no. 8, replace `Hello` word with `My name is` (file autosaves when you make a change). You can see in the terminal that socket has been deployed. Now go back to your sample website and fill the form again. Your response should be changed right now.

That's it for now! You have a real, working Syncano account, and you can now try to build a real thing on your computer. 

To read more about Syncano - go to our website: https://syncano.io