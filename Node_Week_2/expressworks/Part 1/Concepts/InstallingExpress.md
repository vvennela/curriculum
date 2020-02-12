## Installing Express

After downloading Node.js, you will need to create a directory that will contain your application.

Create a directory and move into that directory, for example:

```
$ mkdir myapp
$ cd myapp
```

Use the npm init command to create a package.json file for your application.

```
$ npm init
```

This command prompts you for a number of things, such as the name and version of your application. 
For now, you can simply hit ENTER to accept the defaults for most of them, with the following exception:

```
entry point: (index.js)
```
```index.js``` is the default file name which can be changed to what you want it to be. For example, you can change it to 
``app.js`` instead. After you create your desired file name, hit ENTER.

Now install Express in the myapp directory and save it in the dependencies list. For example:
```
$ npm install express --save
```

To install Express temporarily and not add it to the dependencies list:
```
$ npm install express --no-save
```

https://expressjs.com/en/starter/installing.html
