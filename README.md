# First step kit

## Require
* node.js
* local httpd (also, MAMP) with 80 port listen.

## How to start
1. Please starting httpd for localhost, here listen 80 port
2. Get this repo
3. $ npm install -g
4. $ gulp watch

## Directory structure
* /src			=> source files area
** /js			=> *.js *.coffee (output dist: /public_html/js/ and compress)
** /jade		=> *.jade meta.json (output dist: /public_html/ but compile for jade files only)
** /scss		=> *.scss *.css (output dist: /public_html/css/ and compress)
* /public_html	=> public files area, and jade output distination
** /js			=> js and coffee-script output distination, and js libraries
** /css			=> scss outpu distination
** /img

