# Hello World

This is the most simple place to get started programming AL. 

## .gitignore

If you are new to GitHub, and a lot of Navision people are, then take a quick look at the .gitignore file. 
You will need it especially if your project is public. It basically tells git what should not be send to GitHub. 

In this case
````
.vscode/launch.json
.alpackages/*
*.app
````

- The `launch.json` could contain important login information that you don't want to share.
- The `alpackages` folder contains the app files that are generate automatically. 
- And `*.app` files are also generated. 

