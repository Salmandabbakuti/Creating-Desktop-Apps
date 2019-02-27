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
 


