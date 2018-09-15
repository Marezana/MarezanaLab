#Bash Basics#

Bash is a linux based terminal shell, that has a simplier and easier command structure to what is provided on Windows Command Prompt. We had previously set this up on your computer laptop and Visual Studio code. Here are some essential commands that you might want to know.

### Creation ###
- ``mkdir <parameter>`` will make a directory/folder with name provided. **e.g.** `` mkdir example_folder``

- ``touch <parameter>`` will create a file with the name and file type provided **e.g** ``touch index.js``

You can chain create multiple files/folders by adding more paremeters. 
**e.g** `` touch index.js index.html index.css``

### Deletion ###
**ATTENTION PLEASE READ BEFORE USING**

- ``rm <parameter>`` Will permanently delete a file. **i.e.**``rm -rf example_file.txt``

- ``rm -rf <parameter> `` Will permanently delete a directory. **i.e.**`` rm -rf example_folder``.
**NOTE: BE CAREFUL USING THIS ONE. ALWAYS PROVIDE THE PARAMETER BEFORE PRESSING ENTER OTHERWISE ALL THE FOLDERS ON YOUR COMPUTER WILL START BEING IRRETRIEVABLY DELETED.**

### Movement / Rename ###
- ``mv <SOURCE_PATH>/<FILE_NAME> <DESTINATION_PATH>/<FILE_NAME>`` Will move a file or directory to a new provided location. **i.e.** `` mv src/index.js dist/index.js``

-  now I know what you might be thinking: 'why do I have to provide the name of the file and it's type twice?'. The reason why is because you use the same command to rename a file as well. **i.e.** ```mv src/index.js src/firstIndex.js``` The file **index.js** will become **firstIndex.js**.

### Copying ###
- ``cp <SOURCE_PATH>/<FILE_NAME> <DESTINATION_PATH>/<FILE_NAME>`` Will copy a path to the new location **i.e.** ``cp dir1/index.js dir2/index.js``.

- ``cp -r <SOURCE_PATH>/<path> <DESTINATION_PATH>/<path>`` Same as the previous but will copy over a directory.

##Flags 
Ok so you've seen some flags like ``-rf`` and ``-r`` being used (especially when dealng with directories). But what do they actually do?

- ``-r`` tells bash to recursively look through and apply the presceeding command to all folders on the directory provided.

-  ``-rf`` the force version of ``-rf``. It does the same thing however it will ignore something that would cause a warning and do anyways. It is always needed for **delete** commands.

#Git Basics#

We've gone over the git process in person but I have provided a little cheatsheet that goes over all the commands for git and best practices [here](https://www.git-tower.com/blog/git-cheat-sheet).

All right! Once you've given this a read over. Let's start with **exercise_1**!
