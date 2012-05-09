=================

This is a simple lab setup for playing around with Twitter Bootstrap


Quick start
-----------

Clone this repo, `git@github.com:henrikreinhold/bootstrap-lab.git`

and then clone the Bootstrap repo `git clone git@github.com:twitter/bootstrap.git`

Open ../boostrap-lab/new/profile.html or ../boostrap-lab/new/index.html and start to play.
Example of current KPerson files could be found in the ../bootstrap/old/ folder.

Build Bootstrap
----------

If you intend to tweak the look and feel of boostrap the easiest way is to modify the ../less/variables.less file in Boostrap
and re-build.

Here are the original instructions on how to build
(copy from [Twitter Boostrap GitHub ReadMe](https://github.com/twitter/bootstrap/)).

----------
We have included a makefile with convenience methods for working with the Bootstrap library.

+ **dependencies**
Our makefile depends on you having recess, uglify.js, and jshint installed. To install, just run the following command in npm:

```
$ npm install recess uglify-js jshint -g
```

+ **build** - `make`
Runs the recess compiler to rebuild the `/less` files and compiles the docs pages. Requires recess and uglify-js. <a href="http://twitter.github.com/bootstrap/less.html#compiling">Read more in our docs &raquo;</a>

+ **test** - `make test`
Runs jshint and qunit tests headlessly in phantom js (used for ci). Depends on having phatomjs installed.

+ **watch** - `make watch`
This is a convenience method for watching just Less files and automatically building them whenever you save. Requires the Watchr gem.

