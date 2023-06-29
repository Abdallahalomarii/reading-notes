# Pratice in the Terminal

## introduction

- #### Where are we ?
    - `pwd` : print working directiry.
        - this command telling you what is your current working directory is.
        - example : /home/user
--- 
- #### What's in our current Location ?
    - `ls` : which is stand for List to telling you what you have inside your directory. 
    - where the `pwd` run without any arguments the `ls` can take arguments and you run with out argument. 
        ```bash 
        ls [options] [location]
        ```
    - options: `-a`, `--all`: show all files, including hidden ones;
    - `-l`, `--long`: list information about each file (permissions etc.); `-h`, `--human
--- 
- #### Change Directory
    - `cd` : stands for change directory.
    - it will move us from one location to another.
    - ### NOTE:  **with out any arguments it will move us to the home directory**
    - examples of usages :
    ```bash
    cd .. # go back a level
    cd ../.. #go two levels up
    cd ~ #move into user folder
    cd ~/Desktop #move into desktop folder
    cd ~/test #move into test folder 
    ```
    ---
- #### Everything is a file
    - in linux everything is a file. A text file is a file, a directory is a file, my keyboard is a file also.
    - Linux system ignores the extension of file and looks inside the file to determine what type of file is it. so it doesn't matter if you have a picture and you change the extension for .txt while it is .png linux will understand it is a image.

    - `file` : return a file details, like what is this file and the extension and a another details for this specfic file

    - ### one thing should be in mind that linux is case sensative. 

    ```bash 
    ls test 
    test1.txt test2.txt test3.md

    ## if i want to look inside test1.txt by file command
    file test/test1.txT 
    ## this should return: ERROR: connot open 'test1.txT' (no such file or directory)
    ```
    - so the name of the file should be exactly what you have in your directory.

    - the space in names will not work for example : 
    ```bash 
    cd test 
    file test1 .txt
    ## this should give me an error.
    ```
    ---

- ### Quotes `'` `"`
    - thing inside  the quotes is considerd as a single item.

- ### escape quotes `\`
    - backslash escape the special meaning of the character.

- ### `man`
    - `man <command to lookup>`
    -The manual pages are a set of pages that explain every command available on your system including what they do,the specifics of how you run them and what command line arguments they accept.

    - a simple example :
    ```bash 
    man pwd
    NAME
       pwd - print name of current/working directory SYNOPSIS
       pwd [OPTION]...DESCRIPTION
       Print the full filename of the current working directory.
    ```
    - `man -k <search item>`
     Do a keyword search for all manual pages containing the given search term

- ## File Manipulation!
    - ### making a Directory `mkdir` :
    from it is name this command making for me a directory.

    - example : 
    ```bash
    mkdir test2
    cd test2 
    pwd 
    # /home/user/test2
    ```

    - mkdir takes options 
    `mkdir [options] directory`
    and example of `-p`
    ```bash 
    mkdir -p test/test1/test2

    cd test/test1/test2
    pwd 
    /home/user/test/test1/test2
    ```
    so the benefit of -p is allow you to make a parent directory.

    - `mkdir -v directory`
    verbose mode will show us if we have success or not in creating our directories.
    and telling us what it is doing.

    ```bash 
    mkdir -pv test1/test2
    ## mkdir : created directory test1
    ## mkdir : created directory test2
    cd test1/test2
    pwd 
    /home/user/test1/test2```

- ### Removing Directories  `rmdir`: following by directory path to delete the directory while this directory not empty

- ### create a blank file 
`touch`: 
```bash 
touch test1.txt 
ls 
test1.txt
```
- ### Copying a File or Directory `cp`

    - you can know the meaning from it names it copies files inot another files. 

    - syntax `cp [options] <source> <destination>`

    ```bash 
    ls 
    test1 test2 
    cp test1 test3 
    ls 
    test1 test2 test3 
    ```
    - Using the -r option, which stands for recursive, we may copy directories. Recursive means that we want to look at a directory and all files and directories within it, and for subdirectories, go into them and do the same thing and keep doing this.

     ```bash ls 
    test1 test2 
    cp -r test1 test4 
    ls 
    test1 test2 test4 
    ```
--- 
- ### Moving a File or Directory
    - `mv [options] <source> <destination>`: which means move the source into another destination

    - here an example :
     ```bash 
        ls 
        test1 test2 test3 
        mv test1 test3/
        ls 
        test2 test3 
        ls test3 
        test1
    ```
- ### removing file 

    - `rm [options] <file>`
    to remove a file 

    - here an example :
    ```bash 
    ls 
    test1.txt test2.txt
    rm test1.txt
    ls 
    test2.txt
    ## we use -r to remove a directory 
    
    ```

