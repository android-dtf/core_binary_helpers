Binary Helpers
==============
`dtf` content for performing light analysis on Shared Object ("SO") and binary ("ELF") files on your device.

Content
-------

### getbins
Will pull all binaries from typical binary directories.

### getsyslibs
Will pull all SO files from typical library directories.

### libinfo
Quick analysis on SO file. Useful for looking for:

*  `ioctl`, `socket`/`connect`/`listen`, functions
* Extracting potential JNI functions
* Evidence of device driver (`/dev/*`) usage
