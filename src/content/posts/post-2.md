---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'My Second Blog Post'
pubDate: "Sep 30, 2023"
description: "This is a copy of some of my notes"
author: "Farhan K"
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'The full astro logo'
tags: ["astro","blogging","notes"]
---
# Zsh and Bash cheatsheet 

(zsh only) **man**; manual for the command that follows man. equivalent to **help** is Bash. use **q** to exit the manual page in terminal when finished
**pwd**; print working directory. prints the current path or working directory (aka folder) in the terminal
**ls**; list the contents of the files and folders in the current directory
**ls -l**; list the contents of the working directory in a long list format, easier for reading many-file folders
**ls --all or ls -a**; list all contents of the working directory, including hidden files
**cd**; change directory- change the directory to the path or directory specified
**cd .**; change to the current working directory (no change)
**cd ..**; change the working directory to one level higher
**cd ../..**; change the working directory to two levels higher
**clear**; clean or clear the terminal screen, both inputs and outputs
**more**; describe the contents of a file, particularly a file that may contain text
**touch**; create a new file in the current working directory
**mkdir**; create a new directory (folder) in the current working directory
**mkdir -p**; create intermediate directories as required 
**rm**; delete a file
**rmdir <directory_name\>**; delete a directory
**rm -r**; delete folder and all of its contents (recursively)
**cp <files\> <destination\>**; copy file to directory
**cp -r <folder_to_copy\> <name_of_copy\>**; copy entire folder
**mv <filename\> <new_filename\>**; rename a file 
**mv <file\> <destination\>**; move file to directory
**find**; view file tree, including contents of current folder and subfolders
**find -name <filename\>**; search for a particular file or folder
**echo**; print to terminal
**echo text >> filename**; print to file
**exit**; quit the terminal