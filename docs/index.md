# Welcome to bloxy

Welcome to the unofficial bloxy docs! This will be used for my personal reference, but I'm opening it up for others until
there is an official alternative which is updated for the v4 specification.

If you'd like to check out bloxy, make sure to visit [the repository](https://github.com/Visualizememe/bloxy).

## Initial Installation

* Make sure your versions for **npm** (``npm -v``) and **node** (``node --version``) are up to date. Bloxy generally runs on the most updated version of node.

* *(Optional)* Create a new project in a folder, with `npm init` - this will enable you to save modules (through creating a package.json) and install your distribute your project.

* Run the command `npm install bloxy --save` - this will install bloxy into your project.

* Include this into your codebase. 
  This can be done like this:
  
```js
const bloxy = require('bloxy');
const roblox = new bloxy.Client();
```
