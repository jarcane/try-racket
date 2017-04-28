try-racket
==========

**NOTE: This repo is no longer maintained**

A web-based Racket REPL and tutorial.

Try Racket is written in Racket and JavaScript with Chris Done's [jquery-console](https://github.com/chrisdone/jquery-console).
   
   It borrows a lot of code and content from [Try Clojure](http://www.tryclj.com/) and [paste.rkt](https://github.com/samth/paste.rkt).

Slight additional modifications have since been made to remove dependencies on X11 by John Berry, with help from many others in the Racket community. Please note that the REPL and its server are still to some extent a work in progress, and community contribution is vigorously encouraged. Pull requests will likely be met with cheer, though we ask that you try to give it a little bit of testing before submitting (and we will do same as well before pushing to the live server).

## How to run it locally
    
    $ racket main.rkt
    
	Open http://localhost:8080 in your browser
	
*NOTE:* Currently try-racket does not work properly on Windows/Mac platforms. It should run, but hosting is not recommended as surprising behaviors continue to be discovered. 

## Online host

try-racket is no longer hosted online due to server maintenance issues.

## License

Copyright (c) 2013-2014 Emmanuel Delaborde <th3rac25@gmail.com>

try-racket is distributed under the [GNU Lesser General Public License
(LGPL)](http://www.gnu.org/licenses/lgpl-3.0.html).

You can modify it; if you distribute a modified version, you must
distribute it under the terms of the LGPL, which in particular means
that you must release the source code for the modified software.
