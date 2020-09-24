#Docker++

Using this you can setup your temporary C and CPP compiler environment on the Go in Windows 7 onwards.
gcc,g++ flavor compiler image for Windows Operating

###An ubuntu 20.14.1 LTS temporary image 
which has
1.  GCC compiler
2. G++ compiler
3.  VIM editor

###Steps to install:-
1. [Download](https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe) and install Docker on windows

2.Start Docker Quickstart Terminal

3.run below commands 
```
docker pull rphrishi4/ubuntu_20.04.1_gcc_cpp:gcc_cpp_vim
docker run --rm -it  rphrishi4/ubuntu_20.04.1_gcc_cpp:gcc_cpp_vim /bin/bash
```
4. type ```exit``` command to exit out of it.
