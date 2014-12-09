alljoyn_example
===============

A Cordova Application to provide an example for the cordova alljoyn plugin in development.


Development Setup
=================

Node
Cordova 3.5

To Build (for android)
----------------------

cordova platform add android (and it's requisite bits)
cordova plugin add https://github.com/irjudson/cordova-plugin-alljoyn.git
cordova plugin add org.apache.cordova.dialogs
cordova build 
cordova run
