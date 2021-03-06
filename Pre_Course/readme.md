# Basics of Coding

## This module on Variables and Data Types. In this module, you will learn about various aspects of computational thinking. You will learn how to compile and run your program on the command line. Also, you will be introduced to the concept of variables in programming and the various data types that exist in JavaScript.

### In this session, you will learn about the following aspects of computer programming:

**1. Introduction to Computational Thinking**

**2. NodeJS - Installation and Description**

**3. Using Terminal and CLI in Mac**

**4. The ‘Hello World’ Program in JS in Browser and NodeJs**

**5. Code editor - VScode**

**6. Git and Version Control**


## Introduction to Computational Thinking

### Computational thinking involves expressing solutions to the problems in ways that a computer can understand.There are four major steps involved with computational thinking:

**1. Decomposition:**
This involves breaking a problem into several smaller ones. For example, consider that you want to reverse the name of a file. (i.e. Images should change to segami)
Let us now list down the things that the computer should be able to do in order to accomplish this task:

- Navigating to the desired folder.

- Should be able to reverse the characters of a word or a sentence(which will be the filename)

**2. Pattern Recognition:**
Pattern recognition is the ability to recognise patterns or similarities in the smaller chunks that you broke your problem down to. It is a boon if you are looking to save time and the resources invested in problem-solving. It is frequently the basis for solving problems and designing problem-solving strategies.
Let’s think of a very basic question. If you are told to find the 400th term of the sequence 1, 3, 6, 10….
How will you go about it? Will you go till the 400th term or are you already starting to see something in it? Do you find a pattern that is repeating itself in this sequence?

**3. Abstraction:**

Abstraction involves working on relevant information and ignoring information that is not useful to the problem at hand.

Consider the following examples:

While browsing a particular website, you just type the URL of the site and click Enter. You never think of how typing this takes you to your required website. If every time you try to open a website, you want to know how the URL opens it and how the contents appear on the page, you are not doing justice to your original problem, which is, let’s say, retrieving the contact information of the company from the website. Retrieving this information doesn’t require you to know how websites work.

Abstraction means reducing and figuring out the relevant details of a problem so that it can be modelled computationally, thus reducing the complexity of the problem. In other words, it is an approach where you don’t think about a problem in very specific terms. Rather, you focus your attention on the more general and key information about the problem.

**4. Algorithm Design:**

Representation of your plan in step-by-step sequential instructions. This is what we call algorithms or algorithm designs.

Remember, the steps should be well defined, exhaustive, sequential, and should have a finite endpoint, i.e. the one who is reading the instructions should clearly know when to stop.

## NodeJS - Installation and Description

[Node.js](https://nodejs.org/en/) is a JavaScript runtime built on Chrome's V8 JavaScript engine.

Before installing node we will use [NVM](https://github.com/nvm-sh/nvm); Node Version Manager - Simple bash script to manage multiple active node.js versions

Latest node.js can be downloaded and installed by going on [node download page](https://nodejs.org/en/download/)

Node.js is an open source, cross-platform runtime environment for developing server-side and networking applications built on Google Chrome's JavaScript Engine (V8 Engine). Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, and Linux.
Node.js also provides a rich library of various JavaScript modules which simplifies the development of web applications using Node.js to a great extent. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.


## Using Terminal and CLI in Mac

Terminal Cheatsheet for Mac (Basics)
_Letters are shown capitalized for readability only._  _Capslock should be off._

**SHORTCUTS**

| Key/Command | Description |
| ----------- | ----------- |
| Ctrl + A   | Go to the beginning of the line you are currently typing on.  This also works for most text input fields system wide.  Netbeans being one exception |
| Ctrl + E   | Go to the end of the line you are currently typing on.  This also works for most text input fields system wide.  Netbeans being one exception |
| Ctrl + L   | Clears the Screen |
| Cmd + K    | Clears the Screen |
| Ctrl + U   | Cut everything backwards to beginning of line |
| Ctrl + K   | Cut everything forward to end of line |
| Ctrl + W   | Cut one word backwards using white space as delimiter |
| Ctrl + Y   | Paste whatever was cut by the last cut command |
| Ctrl + H   | Same as backspace |
| Ctrl + C   | Kill whatever you are running.  Also clears everything on current line |
| Ctrl + D   | Exit the current shell when no process is running, or send EOF to a the running process |
| Ctrl + Z   | Puts whatever you are running into a suspended background process. fg restores it |
| Ctrl + _   | Undo the last command. (Underscore.  So it's actually Ctrl + Shift + minus) |
| Ctrl + T   | Swap the last two characters before the cursor |
| Ctrl + F   | Move cursor one character forward |
| Ctrl + B   | Move cursor one character backward |
| Option + →  | Move cursor one word forward |
| Option + ←  | Move cursor one word backward |
| Esc + T  | Swap the last two words before the cursor |
| Esc + Backspace | Cut one word backwards using none alphabetic characters as delimiters |
| Tab  | Auto-complete files and folder names |

**CORE COMMANDS**

| Key/Command | Description |
| ----------- | ----------- |
| cd [folder] | Change directory e.g. `cd Documents` |
| cd |  Home directory |
| cd ~ |  Home directory |
| cd /  | Root of drive |
| cd -  | Previous directory |
| ls | Short listing |
| ls -l | Long listing |
| ls -a | Listing incl. hidden files |
| ls -lh| Long listing with Human readable file sizes |
| ls -R | Entire content of folder recursively |
| sudo [command] | Run command with the security privileges of the superuser (Super User DO) |
| open [file] | Opens a file ( as if you double clicked it ) |
| top | Displays active processes. Press q to quit |
| nano [file] | Opens the file using the nano editor |
| vim [file] | Opens the file using the vim editor |
| clear |  Clears the screen |
| reset |  Resets the terminal display |

**CHAINING COMMANDS**

| Key/Command | Description |
| ----------- | ----------- |
| [command-a]; [command-b] | Run command A and then B, regardless of success of A |
| [command-a] && [command-b] | Run command B if A succeeded |
| [command-a] \|\| [command-b] | Run command B if A failed |
| [command-a] & | Run command A in background |


**PIPING COMMANDS**

| Key/Command | Description |
| ----------- | ----------- |
| [command-a] \| [command-b] | Run command A and then pass the result to command B e.g ps auxwww \| grep google |


**COMMAND HISTORY**

| Key/Command | Description |
| ----------- | ----------- |
| history n |  Shows the stuff typed – add a number to limit the last n items |
| Ctrl + r  | Interactively search through previously typed commands |
| ![value] |  Execute the last command typed that starts with ‘value’ |
| ![value]:p |  Print to the console the last command typed that starts with ‘value’ |
| !! |  Execute the last command typed |
| !!:p |  Print to the console the last command typed |

**FILE MANAGEMENT**

| Key/Command | Description |
| ----------- | ----------- |
| touch [file] |   Create a new file |
| pwd | Full path to working directory |
| . |  Current folder, e.g. `ls .` |
| .. | Parent/enclosing directory, e.g. `ls ..` |
| ls -l .. | Long listing of parent directory |
| cd ../../ | Move 2 levels up |
| cat | Concatenate to screen |
| rm [file] |  Remove a file, e.g. `rm data.tmp` |
| rm -i [file] | Remove with confirmation |
| rm -r [dir] | Remove a directory and contents |
| rm -f [file] | Force removal without confirmation |
| cp [file] [newfile] | Copy file to file |
| cp [file] [dir] | Copy file to directory |
| mv [file] [new filename] |  Move/Rename, e.g. `mv file1.ad /tmp` |
| pbcopy < [file] | Copies file contents to clipboard |
| pbpaste | Paste clipboard contents |
| pbpaste > [file] | Paste clipboard contents into file, `pbpaste > paste-test.txt` |

**DIRECTORY MANAGEMENT**

| Key/Command | Description |
| ----------- | ----------- |
| mkdir [dir] | Create new directory |
| mkdir -p [dir]/[dir] |  Create nested directories |
| rmdir [dir] | Remove directory ( only operates on empty directories ) |
| rm -R [dir] | Remove directory and contents |
| less [file]|  Output file content delivered in screensize chunks |
| [command] > [file] |  Push output to file, keep in mind it will get overwritten |
| [command] >> [file] | Append output to existing file |
| [command] < [file] |  Tell command to read content from a file |

**SEARCH**

| Key/Command | Description |
| ----------- | ----------- |
| find [dir] -name [search_pattern] | Search for files, e.g. `find /Users -name "file.txt"` |
| grep [search_pattern] [file] | Search for all lines that contain the pattern, e.g. `grep "Tom" file.txt` |
| grep -r [search_pattern] [dir] | Recursively search in all files in specified directory for all lines that contain the pattern |
| grep -v [search_pattern] [file] | Search for all lines that do NOT contain the pattern |
| grep -i [search_pattern] [file] | Search for all lines that contain the case-insensitive pattern |
| mdfind [search_pattern] | Spotlight search for files (names, content, other metadata), e.g. `mdfind skateboard` |
| mdfind -onlyin [dir] -name [pattern] | Spotlight search for files named like pattern in the given directory |

**HELP**

| Key/Command | Description |
| ----------- | ----------- |
| [command] -h |  Offers help |
| [command] --help | Offers help |
| info [command] | Offers help |
| man [command] |  Show the help manual for [command] |
| whatis [command] | Gives a one-line description of [command] |
| apropos [search-pattern] | Searches for command with keywords in description |


## The ‘Hello World’ Program in JS in Browser and NodeJs

You can run the HelloWorld.js in the browser and in terminal window using nodeJS

## Code editor - VScode

[Visual Studio Code](https://code.visualstudio.com/) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity). Begin your journey with VS Code with these [introductory videos](https://code.visualstudio.com/docs/getstarted/introvideos).

## Git and Version control

[Git](https://git-scm.com) is a fast, scalable, distributed revision control system with an unusually rich command set that provides both high-level operations and full access to internals.