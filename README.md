# TERA Reverse Engineering

I use this repository to share my reverse engineering artifacts for
[TERA](https://en.wikipedia.org/wiki/TERA_(video_game)).

## Binaries

Under [releases](https://github.com/alexrp/tera-re/releases) you will find both
original and unpacked TERA binaries for the following revisions:

* [r367239 (95.00)](https://github.com/alexrp/tera-re/releases/tag/r367239)
  (unprotected)
* [r377345 (100.02)](https://github.com/alexrp/tera-re/releases/tag/r377345)
  (packed and unpacked)
* [r387486 (115.02)](https://github.com/alexrp/tera-re/releases/tag/r387486)
  (packed and unpacked)

Additionally, for revisions that I am actively reverse engineering, the release
will also include a BNDB file usable by [Binary Ninja](https://binary.ninja).
This file contains most of the 'juicy' bits - types, functions, variables, etc.

## Articles

I have written a series of articles on the process of unpacking and repairing
the TERA executable:

* [Unpacking and Repairing the TERA Executable](https://www.alexrp.com/p/unpacking-and-repairing-the-tera-executable)
* [Spring Cleaning in the Unpacked TERA Executable](https://www.alexrp.com/p/spring-cleaning-in-the-unpacked-tera-executable)
* [Neutralizing Protection in the TERA Executable](https://www.alexrp.com/p/neutralizing-protection-in-the-tera-executable)

## Tools

The following tools were used to unpack and repair TERA binaries:

* [Binary Ninja](https://binary.ninja)
* [CFF Explorer](https://ntcore.com/?page_id=388)
* [IDA Free](https://hex-rays.com/ida-free)
* [PE Tools](https://petoolse.github.io/petools)
* [Unlicense](https://github.com/ergrelet/unlicense)
* [WinDbg Preview](https://apps.microsoft.com/store/detail/windbg-preview/9PGJGD53TN86)
