# Docker++

Using this you can setup your C and CPP compiler environment on the Go in Windows 7 onwards.
gcc,g++ flavor compiler image for Windows Operating

### An ubuntu 20.14.1 LTS image 
which has
1. GCC compiler
2. G++ compiler
3. VIM editor

### Steps to install:-
1. [Download](https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe) and install Docker on windows

2.Start Docker Quickstart Terminal. If not found Search it in Start menu by pressing Win Key.

3.run below commands in **Docker Quickstart Terminal**
```
docker pull rphrishi4/ubuntu_20.04.1_gcc_cpp:gcc_cpp_vim
docker run --name ubuntuContainer -v "$(pwd)":/myCodes --rm -it  rphrishi4/ubuntu_20.04.1_gcc_cpp:gcc_cpp_vim /bin/bash
```
4. Now you are inside your Ubuntu Machine. Which has a myCodes folder where you can store and run all your codes. Type below command to get into it
```
cd myCodes/
```
5. You can type ```ls``` to get list of all the files in current directory.
6. type ```exit``` command to exit out of it.
