runasweb
========

Author: [Donald L. Merand](http://donaldmerand.com)

This is a shell script to run any parameters as the web user by storing them in
a .txt file, temporarily creating a PHP file that executes the contents of that
.txt file, and then removing all traces of either file. It is intended to be
run from the command line of the web server itself.

It solves the problem of not being able to execute scripts as the web user when
logged in to the web host. This is pretty common in shared web hosting
environments.

[MIT-Licensed](http://www.opensource.org/licenses/MIT)
