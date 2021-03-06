# generator-blueman

## Getting Started

### Overview

> [Yeoman](http://yeoman.io) generator for a basic [Node.js](https://nodejs.org/) app with [Express.js](http://expressjs.com/) created for a [Bluemix](https://console.ng.bluemix.net/) environment. It uses the [Gulp.js](http://gulpjs.com/) task runner to serve the app with a few optimizations based on [this starter environment](http://github.com/una/gulp-starter-env). 

To use Bluemix, you'll need to first sign up for an account [here](https://console.ng.bluemix.net/).

Make sure you have Node installed as well at the [Cloud Foundry CLI](https://github.com/cloudfoundry/cli).

### Installation

Then install Yeoman (our scaffolding tool):
```bash
npm install -g yo
```

To install generator-blueman from npm, run:

```bash
npm install -g generator-blueman
```

Finally, make the directory you want to create your app in, `cd` into it, and initiate the generator:

```bash
yo blueman
```

You now have a Bluemix-ready app!

### Usage

Once the initial files are set up through Yeoman, run `gulp` to start the server and make edits. See [the starter environment](http://github.com/una/gulp-starter-env) repo for more documentation on editing files. 

### Deployment

To deploy the app, use `gulp deploy`

## License

MIT
