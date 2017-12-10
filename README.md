# mod_helloworld
This is a Node.js module to print Hello World in the console

# Installation and Testing
* Create a new project folder
* cd into the directory from the command line
* Install the mod_helloworld package using the following command 
  ```sh
    npm install mod_helloworld --save
  ```
* Create a test.js file in the directory and copy this code below 
  ```javascript
  var helloworld = require('mod_helloworld');
  helloworld.HelloWorld();
  ```
* Run the following command in the command line
  ```sh
    node test.js
  ```
  ### Output
  ```sh
    Hello World!!!
  ```

