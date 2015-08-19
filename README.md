# Emil's Nuke-Proof, Intergalactic, Front End Boilerplate #

## A basic front end web boilerplate aimed at rapid set up for web projects. ##

This boilerplate includes [jQuery](https://jquery.com/), [FontAwesome](https://fortawesome.github.io/Font-Awesome/) and [JustGridIt](https://github.com/dyson/just-grid-it) in its bower dependencies by default. All the heavy lifting is handled by the Gulpfile. You don't need to touch './dist' - just create all your scss, js, css etc in the correct dir in './src' and when you run gulp it will automatically compile, concatenate, minify and move all your code to './dist'. 

You can run 'gulp sass:watch' to watch and compile all your scss, or you can use 'gulp all:watch' to watch, compile and concatenate all your resources in './src'.

A [separate version](https://github.com/ChewyJetpack/Emils-Exemplary-October-CMS-Boilerplate) of this project exists for use with [October CMS](https://octobercms.com)

Installation:

1. clone this repo

2. cd into project dir

3. initialise the project by running 'npm install'

4. run 'gulp'

4. make websites