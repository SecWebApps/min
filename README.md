# SecWebSurf

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

SecWebSurf is a smarter, faster web browser. It includes features such as:

* Information from [DuckDuckGo](https://duckduckgo.com) in the searchbar.
* Built-in ad and tracker blocking
* Fuzzy search
* Full-text search for bookmarks
* Reading list
* Tabs improvements (tabs open to the right, and fade out when inactive).

More information, and prebuilt binaries, are available [here](https://secwebapps.github.io/secwebsurf/).

## Screenshots

![The searchbar, showing information from DuckDuckGo](https://secwebapps.github.io/secwebsurf/tour/img/searchbar_duckduckgo_answers.png)

![The Tasks Overlay](https://secwebapps.github.io/secwebsurf/tour/img/tasks.png)

![Reader View](https://secwebapps.github.io/secwebsurf/tour/img/reading_list.png)

## Installing

If you just want to run SecWebSurf, you can download binaries [here](https://github.com/SecWebApps/secwebsurf/releases).

If you want to develop SecWebSurf:

* Install [Node](https://nodejs.org) and [Grunt](http://gruntjs.com).
* Run `npm install` to install dependencies.
* Build a copy of the JS by running ```grunt```.
  * You can also have Grunt watch for changes and automatically rebuild by running ```grunt watch:scripts```.
* Download a copy of Electron from [here](https://github.com/electron/electron/releases).
* Start SecWebSurf by running `/Path/To/Electron /Path/To/SecWebSurf`.

## Building Binaries

If you are using OS X, install [Homebrew](http://brew.sh), then run `brew install fakeroot dpkg`.
Then run `grunt build`.
