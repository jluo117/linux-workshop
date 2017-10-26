# linux-workshop

This introduction will be a brief intro on how to use Linux. Linux is an operating system that powers many devices that range from webservers to cell phones.

## File Structure
In Linux the file system is structred as shown

![Linux File System](https://github.com/ucrcyber/linux-workshop/blob/master/img/linux-filesystem.png)

```/```
That is the root of the file system

```/etc```
Contains system wide configurations

```/usr```
Contains system installed files such as programs like vim

```/var```
Contains variable data such as logs

```/home```
Contains user directories


## Navigating the file system
Knowing how to navigate around the Linux filesystem is a basic but critical skill.

The following are a couple of critical commands for navigating around.

* ``` ls ```
* ``` cd ```
* ``` pwd ```

### ls
This command will allow you to list all files and directories in your current working directory

### cd
This command will allow  you to change your directory

### pwd
This command will return what your current working directory is

## Processes
* ``` ps ```
* ``` top ```
* ```kill```


## Getting system info
* ```uname -r```
* ``` w ```
* ``` cat /etc/*releases```

## Viewing files
* ```vim```
* ```less```
* ```cat```
* ```tail```

## SSH
* ```ssh user@hostname ```

## Useful tools
* ```grep```
* ```awk```
* ```sed```
* ```ping```


## Man pages
If you don't know the arguments or how to use a command just read the man pages

```man ls```
