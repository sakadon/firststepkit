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
```
/src			=> source files area
/src/js			=> *.js *.coffee (output dist: /public_html/js/ and compress)
/src/jade		=> *.jade meta.json (output dist: /public_html/ but compile for jade files only)
/src/scss		=> *.scss *.css (output dist: /public_html/css/ and compress)
/public_html		=> public files area, and jade output distination
/public_html/js		=> js and coffee-script output distination, and js libraries
/public_html/css	=> scss outpu distination
/public_html/img
```
