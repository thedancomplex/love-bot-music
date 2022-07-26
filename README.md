# Auto Audio based on ToneMatrix Redux

This program takes various types of data from online and automatically converts it into a format that the ToneMatrix can understand.  The resulting song/pattern is then automatically played.  This is a part of the "Love-Bot" series by Daniel M. Lofaro and Elena Knox. - 2022

# ToneMatrix Redux

Click on the boxes and make music! This project is an HTML5 revival of [ToneMatrix by Audiotool](https://tonematrix.audiotool.com/), which was originally written in Flash.

<a href="https://www.maxlaumeister.com/tonematrix/"><img alt="ToneMatrix Redux Screenshot" src="/etc/screenshot.png?raw=true" height="300" title="Click To Play!"></a>

## How to Play

Visit [https://www.maxlaumeister.com/tonematrix/](https://www.maxlaumeister.com/tonematrix/)

## How To Build

### Setting Up

1. Install nodejs and npm: `sudo apt update; sudo apt install nodejs npm`
2. Install [Gulp CLI](https://gulpjs.com/): `sudo npm install -g gulp-cli`
3. `cd` into the project folder and install dependencies: `npm install`

### Compilation

* To compile for development and generate docs, run `gulp dev`.

* To compile for development and generate docs, start a localhost server, and auto-recompile changes in source files, run `gulp serve`.

* To compile for production (minified, without source maps), run `gulp prod`.

In any case, the compiled application will be in the `dist` folder.

# Class Diagram (UML)

<img alt="ToneMatrix Class Diagram" src="/etc/uml.png?raw=true" title="ToneMatrix Class Diagram">

## Useful tools

* Install the `eslint` extension in VS Code by using the built-in extension browser. VS Code should automatically find the `.eslintrc.js` config file and start highlighting lines of js that fail the linter.
* Likewise, you can install and use the `sass-lint` extension.

## TODO

See [Issues](https://github.com/MaxLaumeister/ToneMatrixRedux/issues).

## Special Thanks

Thanks to [Camilo Mejia](https://github.com/camilosw/) for his [Procedural ToneMatrix](https://github.com/camilosw/procedural-tone-matrix) fork of this project.

Thanks to [SimplyLinn](https://github.com/SimplyLinn) for [this performance fix](https://github.com/MaxLaumeister/ToneMatrixRedux/pull/26).
