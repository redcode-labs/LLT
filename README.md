<h1 align="center"> LLT </h1> <br>

<p align="center">
  <a>
    <img alt="LLT" src="LLT.png">
  </a>
</p>

<p align="center">
  Low-level toolkit
</p>

![License](https://img.shields.io/badge/License-MIT-purple.svg?longCache=true&style=flat-square)   

## Introduction
A gathering of tiny scripts (mostly one-liners) that can help in low-level
developmet and shellcoding. 

Useful for hex/bytestream conversions, NASM compilation and instructions analysis.

The output of every script can be piped, except for `nasm32/64` that simply drops a compiled binary in current dir.

## Scripts

* `bin2hex` - converts raw binary file to a hexpair stream

* `bin2op` - converts raw binary file to a hexpair stream in "0xFF, ..." form

* `bin2x` - converts raw binary file to a hexpair stream in "\xFF\xEE" form

* `cmd2hex` - constructs a base64 command executor and converts it to hex

* `nulls` - shows all instructions from object file that contain nullbytes 

* `rdlf` - `readelf` pretty-printer

* `binsrv` - serves single or multiple binaries on random port and returns the port number

* `v4hex` - converts an IPv4 address to hex (prefixed with '0x')

* `v6hex` - converts an IPv6 address to hex (prefixed with '0x')

 * `nasm64` - compiles NASM source to 64 bit ELF

 * `nasm32` - compiles NASM source to 32 bit ELF

 * `txt` - extracts raw .text section from executable

 * `datxt` - same as above, but extracts also .data section and saves both in separate files

 * `push` - creates an assembly push sequence that places a desired string on stack
* _More coming soon..._


## License
This software is under [MIT License](https://en.wikipedia.org/wiki/MIT_License)


