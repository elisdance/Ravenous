# Ravenous

Ravenous is a food app. Made with help of Codecademy.


## Technologies & Tools Used:
- Java Script
- HTML
- CSS
- React
- [Yelp](https://www.yelp.com/developers)
- [CORS Anywhere](https://cors-anywhere.herokuapp.com)

## Description 

This application can help you with a search of appropriate cuisine in american public catering

## Installation

Clone my project to your desktop:
   - Click “Code” and copy the given URL.
   - Open "Terminal" and change the current working directory to the location for a cloned project.
   - Type 
   ```bash 
   git clone {repository URL}
   ```
## Requirements 
For development, you will need Node.js and  Gulp installed on your environement.

### Node
[Node](https://nodejs.org/en/) is really easy to install & now include [NPM](https://www.npmjs.com). You should be able to run the following command after the installation procedure below.

```bash 
$ node --version
v0.10.24

$ npm --version
1.3.21

```

#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in /Applications/Utilities/Terminal.app.

Please install [Homebrew](https://brew.sh) if it's not already done with the following command.

```bash 
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
```
If everything when fine, you should run
```bash
brew install node
```
#### Node installation on Linux
``` bash
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```
#### Node installation on Windows
Go on official [Node.js website](https://nodejs.org/en/) & grab the installer. Also, be sure to have git available in your PATH, npm might need it.

### Gulp 
- Check for node, npm, and npx
``` bash
node --version
npm --version
npx --version
```
If they are not installed, follow the instructions [here](https://nodejs.org/en/).

- Install the gulp command line utility
``` bash
npm install gulp -g
```

### Project Dependencies
Install project dependencies
```bash
npm install 
```
  OR use this command to speed up installation
```bash
npm ci 
```
(about the differences between npm install and npm ci you can read [here](https://docs.npmjs.com/cli/v8/commands/npm-ci))

### Start the development environment 
```bash 
npm start
```
### Simple build for production
```bash
npm run build
```

### Before opening project in browser, [click here](https://cors-anywhere.herokuapp.com) to activate a trial version of CORS Anywhere 

### [Here](https://www.yelp.com/developers/v3/manage_app) you can generate your API key 
