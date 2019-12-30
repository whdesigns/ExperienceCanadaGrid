![](img/logo.png)

<br/>

## Introduction
#### 

<br/>

## Configuration 

### Step One
###### Open Command line on either Windows or Mac and type in the following to clone the repo onto your desktop:

```
cd ~/Desktop/

git clone https://github.com/whdesigns/12-point-grid 
```
<br/>

### Step Two
###### Open the cloned repo inside Visual Studio Code on either Windows or Mac.

###### Note: Ensure Node JS is installed. If not [click here](https://nodejs.org/en/) to download it. Once installed npm will be available to use on the terminal. Type....
```
node -v
 ```
###### in the terminal to ensure the latest version has been installed. 

### Step Three 
###### Type the following into the terminal to initialize npm and install gulp-cli globally
 ```
npm init
sudo npm install gulp-cli -g
 ```
###### While attempting to install gulp-cli npm will ask for a "password", which is used for the user's computer.
 
###### Type...

 ```
gulp -v
 ```
###### to check if the latest version of gulp has been installed.

  <br />

### Step Four
###### Install gulp-sass and browser-sync by typing the following into the terminial 

 ```
npm install --save-dev gulp gulp-sass browser-sync
 ```
###### This will automatically update the dependencies in the package.JSON file.
 
   <br />

### Step Five:
###### Type following into the terminal to pull up the website using your localhost with the use of browser-sync

 ```
gulp watch
 ```
