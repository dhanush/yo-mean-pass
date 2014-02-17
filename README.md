yo-mean-pass
============

Yo-MEAN-Pass is an attempt to bring the [MEAN stack](http://blog.mongodb.org/post/49262866911/the-mean-stack-mongodb-expressjs-angularjs-and) into [Yeoman](http://yeoman.io/) along with security layer, [PassportJS](http://passportjs.org/). This project provides a basic template for all these tehcnologies built into one project.

This is not based on the yo generator `angular-fullstack`, but using the yo generator `angular` with [mean](https://github.com/linnovate/mean). I went about creating this template since I liked the directory structure in [mean](https://github.com/linnovate/mean), and wanted to use it along with the yo generator.

## [Yeoman](http://yeoman.io/) ##

[Yeoman](http://yeoman.io/) is an open source client-side development stack, consisting of tools and frameworks intended to help developers quickly build high quality web applications. Yeoman runs as a command-line interface written in Node.js which combines several functions into one place, such as generating a starter template, managing dependencies, running unit tests, providing a local development server, and optimizing production code for deployment.

## [MEAN](http://www.mean.io/#!/) ##

MEAN stack is the acronym which stands for: (M)ongoDB – a noSQL document datastore which uses JSON-style documents to represent data, (E)xpress – a HTTP server framework on top of Node, (A)ngular – as you know, the JS framework offering declarative, two-way databinding for webapps and (N)ode – the platform built on V8’s runtime for easily building fast, scalable network applications.

## Pre-requisites ##

1. Install NodeJS
2. Install MongoDB and start it on the default port 27017
3. Install Yeoman, with GruntJS and Bower

## Getting Started ##


1. Clone/Fork the project
2. Run the following commands to install dependencies

    	bower install
		npm install

3. Then run the command to start the server


		grunt server

3. Then open a browser and go to: `http://localhost:3000/`
4. For create a new AngularJS controller go ahead ad run the command

 		 yo angular:controller info
This will create an `info.js` file under `app/controllers directory` with the controller named as `InfoCtrl`.

5. See the [Github Project](https://github.com/yeoman/generator-angular) for more options.


### Note ###

Have a look at the yo `generator-angular-fullstack` [here](https://github.com/DaftMonk/generator-angular-fullstack) . This could be an cleaner alternate solution for this project. 