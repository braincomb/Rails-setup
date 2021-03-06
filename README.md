#Rails-setup

##What is Rails-setup?
Rails-setup is a tiny script to automatically do the boring tasks usually done when creating a new Rails project

Right now, it does the following:

* Creates your new Rails project
* Updates the Gemfile to include:
  * Haml
  * Sass
  * RSpec
  * Debugger
  * FactoryGirl
  * FFaker
  * Shoulda-matchers
  * Database-cleaner

These are all gems I use in pretty much every rails project, and so I created this script for my use. You're more than welcome to use it, or fork and and create something more personalized to what you use.

##Installation
* Clone this repository somewhere ```https://github.com/chintanparikh/Rails-setup.git```
* Move the rails-setup file somewhere into your path (/usr/bin should usually work) ```sudo cp rails-setup/rails-setup /usr/bin/```
* Chmod rails-setup in your PATH to 755 ```chmod 755 /usr/bin/rails-setup```

##Usage
To create and setup a new rails app with name project_name:
```rails-setup project_name```