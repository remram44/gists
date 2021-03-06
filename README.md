# General

General programming stuff that can probably be translated to another language if need be.

* [color.py](https://gist.github.com/remram44/6284607): rgb/hsv conversion, and generator of visually different colors
* [file_is_binary.py](https://gist.github.com/remram44/5241399): identifies whether a file is binary or plaintext
* [pbs-vagrant](https://gist.github.com/remram44/01a05dd023cfe5097be7): Vagrant setup for a test PBS cluster

# C

* [matrix_to_quaternion.c](https://gist.github.com/remram44/5260578): builds a quaternion from a matrix (from Id Software)
* [stringify.c](https://gist.github.com/remram44/5109330): preprocessor trick to get `#variable` to quote the value

# Java

* [TextLoader.java](https://gist.github.com/remram44/1974886): UTF-8 decoder that fallbacks on Latin-1 on error

# Python

* [debugmt.py](https://gist.github.com/remram44/5699241): metaclass that logs all the instances' method calls
* [http_directory.py](https://gist.github.com/remram44/6540454): recursively download a directory via HTTP
* [https.py](https://gist.github.com/remram44/10935541): secure usage of urllib2; default doesn't check SSL certificates at all
* [ipython_callbacks.py](https://gist.github.com/remram44/5902529): wrapper for IPython.parallel.Client with thread-safe future callbacks
* [ipython-errors.py](https://gist.github.com/remram44/6395281): routines for formatting RemoteErrors
* [pickleable_staticmethods](https://gist.github.com/remram44/5769651): metaclass making instance methods pickleable
* [QtWrapper.py](https://gist.github.com/remram44/5985681): compatibility layer allowing transparent use of PyQt4 or PySide
* [twistedconsole.py](https://gist.github.com/7659c61ce771989c9ff9): version of StandardIO that works on Windows
* [ipc_2to3.py](https://gist.github.com/remram44/ec2fbead9bad035395de): example of multiprocessing between Python 2 & 3 using a POSIX pipe
* [text_pager.py](https://gist.github.com/remram44/7d9dc3d4844151a1cf9b214a7484363a): breaks a string into chunks of a specified size on whitespace characters

# Utils

Useful utilities not intended to be put in other software.

* [rename.sh](https://gist.github.com/remram44/6394470): mass file renaming with a regex
* [timeprefix.py](https://gist.github.com/remram44/6054764): prefixes each line of input with the time elapsed (for use in pipes)

# Other

* [cygwin_wrapper](https://gist.github.com/remram44/4642964): allows to place an `sh` binary on the Windows PATH that runs through Cygwin
