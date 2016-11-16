---
layout: post
title: 1. Project Setup and basic flow
---
Guide for getting started using Git and Github.

## Project Setup

1. Create folder in terminal ie ```mkdir project```
2. Enter folder in terminal ie ```cd project```
3. Initialize git ie ```git init```
4. Create a repository in github (look for `New`  or `New repository` button) and follow the instructions to setup link to github and push

Alternatively, you can setup the repo in your user github page (Where the list of your repos exist).
  1. Open it and Find the clone or download button.
  2. Copy the address.
  3. In terminal, search for where you want to store the repository(project folder)
  4. Type ```git clone <`https://github.com/<username>/<repo name>.git```
  5. where the last part is the address copied from github. This will now copy the folder and `init git` on local disk, so from here can just use ```git push`` to push to repo on github.

## Work flow

This is most common actions I have performed when using git. It would be best to create alias to speed up entering the commands using a shorthand notation.

  1. Create or add to files, for example:
    1. Create readme as first commit ie ```touch README.md```
    2. Open file (use own text editor ie vim, atom etc)
    3. Add or make changes to file
    4. Save file
  2. To see what files were changed and/or created do ```git status```
    - To show the difference that have been made from last commit do ```git diff HEAD```
  3. Add unstaged changes ie ```git add README.md ```
    - To add several files do ``` git add file1.md file2.md``` and continue adding other files
    - To add all the files do ```git add . ```
    - To go through each file see the changes before adding do ```git add --patch```
  4. To commit staged files with short commit message do ```git commit -m 'description of changes'```
    - To add more details to the commit message do ```git commit```.
    - This will take you to vim editor in the terminal
      - To start typing press ```a```
      - To save, press esc then type ```:wq```
      - To abort commit type press esc then type ```:q!```
  5. To push commits do ```git push origin master``` (only push the master branch)
    - To push all branches do ```git push origin --all```
    - Can also do ```git push``` to push to master branch if followed setup when creating repository on Github.
  6. Repeat

Key tips:

`Alway commit after each passing test and after a refactor`

`Always write commit messages which mean something and refer to user stories`

`If commit contains a lot of changes, write a longer commit message detailing what was done during this commit`
