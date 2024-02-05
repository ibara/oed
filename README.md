# OpenED
Portable OpenBSD `ed(1)`.
## Why?
Because all operating systems deserve a good editor.
## Supported systems
OpenED should run on any minimally `POSIX` operating system.
Pull requests are much appreciated to support more operating systems.
## Supported compilers
OpenED is known to build with the following C compilers:
* clang (https://llvm.org/)
* gcc (https://gcc.gnu.org/)
* pcc (http://pcc.ludd.ltu.se/)
* cparser (https://pp.ipd.kit.edu/firm/)
* lacc (https://github.com/larmel/lacc)
* Tiny C Compiler (https://bellard.org/tcc/)
* CompCert (https://compcert.org/)

Building with a compiler not listed here? Add it and send a pull request!
## Dependencies
Any C89 compiler should be able to compile OpenED. Please see the
list of C compilers above for a list of known working compilers.

A `configure` script that produces a `POSIX` `Makefile` is provided to
ease building and installation and can be run by:
```
$ ./configure
$ make && sudo make install
```
## License
Files originating with OpenED are BSD licensed.
Portability files are ISC licensed; see individual file headers
for details.
## Get a tarball
Tarballs can be found in the Releases tab.

The latest release is oed-7.4.
