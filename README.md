# Project Setup

[![devDependency Status](https://david-dm.org/thanhluu/project-setup/dev-status.svg)](https://david-dm.org/thanhluu/project-setup#info=devDependencies)

Whenever I start developing a new project, it really takes me quite a lot of time to set up neccessary tools. In this repo, I would like to share the great tools which I have been using to build the Website. Plus, they were also standardized so that I totally develop the Website with high quality.

## List of tools

* [Bower](http://bower.io/) for front-end package management
* [Grunt](http://gruntjs.com/) for running automation JavaScript tasks
	- [grunt-autoprefixer](https://github.com/nDmitry/grunt-autoprefixer) for parses CSS and adds vendor-prefixed CSS properties using the [Can I Use](http://caniuse.com/) database.
	- [grunt-contrib-compress](https://github.com/gruntjs/grunt-contrib-compress) for compress files and folders
	- [grunt-contrib-copy](https://github.com/gruntjs/grunt-contrib-copy) for copy files and folders
	- [grunt-contrib-concat](https://github.com/gruntjs/grunt-contrib-concat) for concatenate files
	- [grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify) for minify files with UglifyJS
	- [grunt-contrib-jshint](https://github.com/gruntjs/grunt-contrib-jshint) for validate files with JSHint
	- [grunt-contrib-less](https://github.com/gruntjs/grunt-contrib-less) for compile LESS files to CSS
    - [grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch) for run tasks whenever watched files change
    - [grunt-git-deploy](https://github.com/iclanzan/grunt-git-deploy) for deploy files to any branch of any remote git repository
    - [load-grunt-tasks](https://github.com/sindresorhus/load-grunt-tasks) for load multiple grunt tasks using globbing patterns
    - [time-grunt](https://github.com/sindresorhus/time-grunt) for display the elapsed execution time of grunt tasks
* [Gitignore](http://www.gitignore.io/) for determine which files and directories to ignore, before you make a commit
* [Editor Config](http://editorconfig.org/) for configuring the editor according to the same [standard](http://make.wordpress.org/core/handbook/coding-standards/php/#indentation)

## Globally Setup

Your Computer must setup those tools before start develop this theme:

1. [Node.js](http://nodejs.org/download/)
2. [Git CMD](http://git-scm.com/) (For Windows, you must install Git Bash)
3. Grunt-CLI: Open CMD (on Windows) or Termnial (Mac and Linux) type `npm install -g grunt-cli`
4. [Sublime Text](http://www.sublimetext.com/)
5. [Sublime Package Control](https://sublime.wbond.net/)
5. [Editor Config Sublime](https://github.com/sindresorhus/editorconfig-sublime) (You can install via Sublime Package Control)

## Project Setup

From the command line, navigate to the theme directory

1. Run `npm install` to install Node modules
2. Run `bower install` to install front-end packages
3. Run `git submodule init` and then `git submodule update` to clone Git Sub-Modules

## Available Grunt Commands

When completed, you'll be able to run the various Grunt commands provided from the command line:

* `grunt watch` — Compile assets when file changes are made

## Editor Config

Regarding Sublime Text Editor, you can install a plugin named [Editor Config Sublime](https://github.com/sindresorhus/editorconfig-sublime) into Sublime via [Package Control](https://sublime.wbond.net/).
