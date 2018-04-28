oed
===
Portable OpenBSD `ed(1)`.

Why?
----
Because all operating systems deserve a good editor.

Supported systems
-----------------
`oed` should run on any minimally `POSIX` operating system.
Pull requests are much appreciated to support more operating systems.

Supported compilers
-------------------
`oed` is known to build with the following C compilers:
* clang (https://llvm.org/)
* gcc (https://gcc.gnu.org/)
* pcc (http://pcc.ludd.ltu.se/)
* cparser (https://pp.ipd.kit.edu/firm/)

Building with a compiler not listed here? Add it and send a pull request!

Dependencies
------------
Any C89 compiler should be able to compile `oed`. Please see the
list of C compilers above for a list of known working compilers.

A `configure` script that produces a `POSIX` `Makefile` is provided to
ease building and installation and can be run by:
```
$ ./configure
$ make && sudo make install
```

License
-------
Files originating with `oed` are BSD licensed.
Portability files are ISC licensed; see individual file headers
for details.

Get a tarball
-------------
http://devio.us/~bcallah/oed/oed-20180428.tar.gz
