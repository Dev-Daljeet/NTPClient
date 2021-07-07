![Alt text](screenshot.jpg)

# NTP Client

This project is a NTP client which is similar in nature to `ntpdate` but does not accept any command line arguments
nor does it update the system clock. Note that this NTP client does not use any NTP libraries
but rather works directly at the [NTP protocol level](http://tools.ietf.org/html/rfc958).  

This project is based on  [Let's make a NTP Client in C](https://lettier.github.io/posts/2016-04-26-lets-make-a-ntp-client-in-c.html).

## Installation and Setup Instructions

### Prerequisites (Requirements):

C program can be written and executed on any machine that has a suitable environment to run the program.
Clanfg, MinGW compiler (Minimalist GNU for Windows), Portable 'C' compiler, and Turbo C are popular compilers available. 
I am using [GCC Compiler](https://gcc.gnu.org).
It is recommended using an IDE to run C programs. An IDE includes a compiler, editor and debugger. 

Firstly, use the following command to check if your system has gcc installed or not:

`gcc -v`

If your system doesn't have gcc installed, here is the [link](https://www.guru99.com/c-gcc-install.html) to download GCC complier for Windows, Linux and Mac. Moreover, you can download Code::Blocks (IDE) which bundles a compiler (gcc offered by Free Software Foundation GNU), editor and debugger in a neat package.

### How to Run:

**Compile:**

`gcc main.c -o ntpClient.out` 

**Run:** 

`./ntpClient.out` 

## License
MIT License
Copyright (c) 2021 Daljeet Singh

Refer to [LICENSE](LICENSE) file for full information.
