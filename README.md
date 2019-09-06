Anti-Tampering Cordova Plugin - with directory exclusion
========================================================

## Installation

Install latest commit from branch develop:

    cordova plugin add https://github.com/henrytranter/cordova-plugin-antitampering#develop

## Usage

### Exclude directories by name

This fork allows you to define directories which you wish to exclude from the assets which are checked by the plugin.

    cordova plugin add cordova-plugin-antitampering --variable EXCLUDE_DIRECTORIES="www\lib" --save
