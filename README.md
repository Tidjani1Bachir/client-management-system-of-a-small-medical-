# client-management-system-of-a-small-medical-
a client management system of a small medical using typescipt and react and elecron
#### 1/ to run this application u have to put all folders and file expect electron folder in a folder called app or any thing else 
#### 2/ put the content of electron folder in the root of the progerct
#### 3/ go to thge app directory and run npm i 
#### 4/ in the same directory run npm run build
#### 5/ go to package.json and add this {
  "name": "app",
  "version": "0.1.0",
  "private": true,
  "homepage": ".",
  "dependencies": {
  ...
  }
  ...
#### 6/ go to the main directory and run git init
#### 7/ in the same directory run npm i 
#### 8/ go to the package.json in the same directory and add
  ...
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "electron .",
    "dev:watch":"npx electronmon --trace-warnings ."
  },
  ...
#### 9/ run npm start ro run the disktop app
#### 10/ to package this app for windows in the terminal of the root directory run npm i electron-packager after that in the terminal run electron-packager ./ name-of-the-disktop-app --platformwin32 --overwrite 
