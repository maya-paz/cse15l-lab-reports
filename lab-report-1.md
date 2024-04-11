
Name: Maya Dautoff

PID: A15512320

***

Hello, welcome to my first lab report! 

In this lab report, I will be showing what happens when I use the `cd`, `ls`, and `cat` commands with different arguments.

***


#### Using `cd` with no argument:

![Image](cd-noarg.png)

The absolute path to the working directory is right before the command was run: `/home`.

I got this output because without a direction of a place to go to, `cd` doesn't change anything. It needs a place to change the directory to. 

It is not an error, it simply doesn't do anything. 


#### Using `cd` with a path to a directory:

![Image](cd-directory.png)

The absolute path to the working directory is right before the command was run: `/home`.

I got this out because `cd` was working correctly. It changed the directory from `/home` to `/home/desktop`. 

It is not an error and working properly. 


#### Using `cd` with a path to a file:

![Image](cd-file.png)

The absolute path to the working directory is right before the command was run: `/home/desktop/`.

I got this output because `cd` takes a directory as an argument and a file is not a directory. 

It resulted in an error because a file was used as an argument as opposed to a directory.

***


#### Using `ls` with no argument:

![Image](ls-noarg.png)

The absolute path to the working directory is right before the command was run: `/home`.

I got this output because terminal received the directions to list files, and it listed all the folders in home. 

This was not an error.

#### Using `ls` with a path to a directory:

![Image](ls-directory1.png)

The absolute path to the working directory is right before the command was run: `/home/desktop/`.

I got this output because terminal received the directions to list files and it listed everything in desktop.

This was not an error.

#### Using `ls` with a path to a file:

![Image](ls-file1.png)

The absolute path to the working directory is right before the command was run: `/home/desktop/`.

I got this output because terminal received the directions to list files and it listed everything within one file, which was simply that file.

This was not an error. 


***


#### Using `cat` with no argument:

![Image](cat-noarg.png)

The absolute path to the working directory is right before the command was run: `/home`.

`cat` displays files onto the screen in terminal, with no argument to read, nothing shows up. 

This is an error because there was the incorrect argument type. 

#### Using `cat` with a path to a directory:

![Image](cat-directory.png)

The absolute path to the working directory is right before the command was run: `/home`.

`cat` displays files onto the screen in terminal. Since the argument was not a file, it was unable to run.

This is an error because there was the incorrect argument type. 

#### Using `cat` with a path to a file:

![Image](cat-file.png)

The absolute path to the working directory is right before the command was run: `/home/desktop`.

I got this output because `cat` displayed the contents of the file onto the screen.

This is not an error

***

