#Refreshing your files with browser-sync  
  
 
## Requirements  
* Node.js (npm)  
* browser-sync  
* simple command line knowledge  
  
**First Step**  
Install [Node.js](https://nodejs.org/). 
Run through the wizard, and install Node.    
You'll be needing Node.js to have acess to the ```npm``` command through the console.  
  
**Second Step**  
Install [browser-sync](http://www.browsersync.io/).
To install browser-sync, open your command line and type:  
```npm install -g browser-sync```  
This will install browser-sync globally.  
  
**Final Step**

```Cd``` in to the desired directory and run:  
```browser-sync start --files "css/*.css, *.html, scripts/*.js" --server```  
This command should launch a new browser window, launching a server and set itself to watch all the files for any changes. If it detects any changes, it will reload itself automatically.  
  
The ```*``` is there so it watches all files with the .html, .css, and .js extension. 