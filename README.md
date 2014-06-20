threejs-boilerplate
===================

Three.js minimal starter project with useful Three.js plugins.

Since many Three.js plugins and shaders do not have individual bower packages,
bower is not included locally. These files are instead found in `scripts/lib/`.


###Getting Started
Follow these instructions to start a Three.js project with this boilerplate:

#####Installation
* Clone this repository
* Run: `npm install`


#####Runing locally
If you haven't already, install: `npm install http-server -g`

Then, run either command:
* Nodejs (faster): `http-server -p 9000`
* Python (alternative): `python -m SimpleHTTPServer 9000`

Visit in your browser: `localhost:9000`


#####Alternative method
You can use Yeoman with [generator-webapp-gulp](https://github.com/yeoman/generator-webapp)
automate your build and deployment process. This method is recommended for larger Three.js projects.

* Create a new folder and build your project with `yo`
* Move files to where they are needed in `app/`
* Update `index.html` to include any additional `bower_components` scripts
* Run: `gulp watch` to run your project locally with livereload

Before deploying your project, run: `gulp`. This will generate a `dist/` folder
that contains a minified and concatenated version of your project files.

###Future Tasks
* Create a Yeoman generator to replace the alternative method mention above.
