Welcome to the README file for KKM Auto's Hugo website! Our website is built on the Hugo framework, with a focus on simplicity, responsiveness, and lightness. In this file, we'll walk you through how to get started running and editing the website, using the package.json file as a basis for the runtime.

## Getting Started    

To begin, you'll need to have Node.js and npm installed on your machine. If you don't have them already, you can download and install them from the official Node.js website.  

### Dependencies  
Once you have Node.js and npm installed, you can open up your terminal or command prompt and navigate to the root directory of the website. From there, you can run the following command to install all the necessary dev dependencies:  
```{sh}  
npm install
```
This will download and install all the necessary dependencies to run and edit the website.  

### Development  
Once the installation is complete, you can run the following command to start the website:  

```{sh}  
npm run start
```  

This will start a local server at http://localhost:1313 where you can preview the website in your web browser.

#### Modes   
To make changes to the website, you can edit the source files located in the `layouts`, `content`, `data` and `assets` directory. You can also use the following commands to watch and rebuild the CSS and HTML files in real-time:


```{sh}  
npm run watch:tw
```  
This command will watch the `./assets/css/main.css` file for changes and compile it into `./assets/css/style.css` using Tailwind CSS.  
```{sh}  
npm run watch:hugo  
``` 
This command will start the Hugo server with live-reload to rebuild the HTML files in real-time as you make changes to the source files.
### Production 

```{sh}  
npm run build
```  
This command will build the website for production by compiling the CSS and HTML files and minimizing them.

We hope you find our KKM Auto Hugo website useful and informative. If you have any questions or run into any issues, feel free to reach out to us for support.  