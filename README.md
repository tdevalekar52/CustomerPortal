#steps for downloading project using GIT
1. First you have to install git in your PC from below link and install it 
	https://git-scm.com/downloads

2. Configure your git with git bash terminal with your username and email
	You can set up Git with your name
	git config --global user.name "<Your-Full-Name>"

	You can set up Git with your email
	git config --global user.email "<your-email-address>"

#(If already Done Above steps then you can Skip to 3rd step)	
	
3. Clone (download project) file in empty folder using below commands
	1. git init
	2. git clone https://github.com/tdevalekar52/CustomerPortal.git
	
4. Download dependencies node_modules with command and run the project
	npm install
	ng serve

5. when start working on project daily
	1. git status
	2. git pull origin master
		
6. After changes done do
	1. git push -u origin master
		(this will push your changes on git in modified section)
	
	2. git commit
		(this will save your changes and merge changes )



# Metronic Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
