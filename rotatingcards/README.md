## Rotating Cards

### npm init

### SASS Package

#### Install SASS package using CLI
	
	`npm install node-sass --save-dev`

	`--save-dev` - to add devDependency in package.json
	
	
#### SASS compilation command
	
	add the following line in scripts variable of package.json
	
	`"scripts": {
		"compile:sass": "node-sass sass/main.scss css/main.css -w"
    }`
	
	and run the command  

	`npm run <script-name given in package.json>`
	
### Live-Server

#### Live-server Install

	`npm install live-server -g`
	
	Note : -g means install globally.
	
#### live-server running command
	
	Go to project root folder and run `live-server` command from console.
	After successful execution of the command, the page will be open in browser.
