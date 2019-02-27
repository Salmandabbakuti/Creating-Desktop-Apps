# Creating-Desktop-Apps

#  Pre-requisites
1. Node.js 
2. Install "Electron Forge" using the following command:
```
npm install -g electron-forge
```

# Steps For Creating Temparature Converter App

1.Creating your application Project:

```
electron-forge init converter-app
```
The above command will take some time to run. here, "converter-app" is the name of your project folder

2. Once it finishes running, Go to your project directory ```./src/``` and replace the files with this repository files(index.html, index.js,renderer.js).

here , ```index.js``` is for displaying GUI and ```renderer.js``` is for converting Temparature and display it in respective boxes..

3. start the application using the following commands:
 ```
 cd converter-app
 npm start
 ```
 above commands will display your converter app window, Check it out with different values..
 
 <img align="center" src="https://github.com/Salmandabbakuti/Creating-Desktop-Apps/blob/master/Screenshot%20(61).png">
 

4. Packaging Application:

```
npm run package
```
This command will take some time to run. Once it finishes check the ```/out``` folder within the project folder.

5. Creating a make File or installer:

In order to create a make file or an installer for the application, use the following command:

```
npm run make 
```
This command will take some time to run. Once it finishes check the ```./out/make``` folder within the project folder.it  will have a Windows installer for the desktop application.

Boom....
