# inc

## ZipRISC1

Explore how this code might be used to emit ZipRISC1 instructions instead of x86.
It's Scheme (i know, I know) but pretty simple.

### Orginal Readme

Step-by-step development of a Scheme-to-x86 compiler, based on
Abdulaziz Ghuloum's [paper][1], _An Incremental Approach to Compiler
Construction_, and extended draft [tutorial][2], _Compilers: Backend to
Frontend and Back to Front Again_.

The CPS conversion is based on Matt Might's [web article][3], _How to
compile with continuations_.

[1]: https://github.com/namin/inc/blob/master/docs/paper.pdf?raw=true
[2]: https://github.com/namin/inc/blob/master/docs/tutorial.pdf?raw=true
[3]: http://matt.might.net/articles/cps-conversion/

## More on `inc`

See the [src](src) directory.

## Docker cheatsheet

- `docker build -t=namin/inc .`
- `docker run -i -t  namin/inc /bin/bash`
- `docker run -it -v $(pwd):/inc-live namin/inc /bin/bash`
