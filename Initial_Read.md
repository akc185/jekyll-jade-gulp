Workflow which supports Jekyll-SASS-JADE-AUTO_PREFIXER-BROWSER_SYNC using GULP
=============================

## SYSTEM PREPARATION
To start with this workflow, you need to install (or upgrade) the following things on your machine.

1. [Jekyll](http://jekyllrb.com) - `$ gem install jekyll`
2. [NodeJs](http://nodejs.org) - go to the [link](http://nodejs.org) to download and install the installer
3. [GULP](http://gulpjs.com) - `$ npm install -g gulp` (sudo may need to use on MAC machines)

## LOCAL INSTALLATION
1. Make a duplicate copy of this folder (or clone repo)
2. Open terminal and direct the cursor (cd) to project directory
3. Inside the project directory, run `$ npm install`

## CHECK UPDATES FOR DEPENDENCIES2:
1. Install npm-check-updates to check the current version and installed version of dependencies `$ gem install -g npm-check-updates`
(If mac user encounters any errors then they might need to 'sudo')
2. Run `$ ncu in project directory `
3. To upgrade the dependencies, use `$ ncu -u`
    Reference : [link](https://www.npmjs.com/package/npm-check-updates)

## RUN PROJECT
You can run all tools using gulp with command in your project directory
```shell
$ gulp
```

## CREDITS
1. [Travis Neilson](http://www.travisneilson.com) for his [YouTube Channel](https://www.youtube.com/user/DevTipsForDesigners) from where I learn all of this.
2. [Shane Osbourne](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync) for his work `jekyll-gulp-sass-browser-synce`
