## Program by Luis Castellano-Martin (Lab D) and Eric Anderson (Lab A)

# Project description
A program to accept any string `word` as an input and a positive integer `n` such that
`0 < n < len(word)`. The program will find the nth character in `word` and return its ASCII value.
Alternatively, if the user enters `ALL` as the input for `n`, the program will return the ASCII values of every
character in the string.

# Installation and use
Clone the repository (or simply download the project zip file) to wherever you want to the project on your computer. You will need to open the unicode_funct.ipynb file in an environment that supports Python notebooks. We recommend using JupyterLab or Binder to do so. Once the notebook is open, execute the code cell (shift + enter on JupyterLab). You will be prompted for a string and an integer. Input whatever string and integer you want, and the program will output the ASCII value for the character at the index in the string that was specified.

# How to contribute
In its current form, this function does not have very many applications. However, with the help of the open source community, this program can evolved and eventually be used for things like cryptography. 
If you would like to contribute:
First, fork this repository. Follow the installation guide. Instead of executing the code, feel free to edit it as you wish. Once you are done, save the .ipynb file. Execute the `git add .` and `git commit` commands in the command line to save your changes. To push your changes back to the copy of this repository you made use the `git push origin master` command. The command line will prompt for your GitHub username and password. Once you do this, go back to GitHub and create a pull request from this repository. We will review/compare the changes you made and decide whether to implement them
Thank you for your contributions!

# License
This project is licensed under the MIT license, which allows anyone to use and distribute this project or forks of it as long as the original license is included. See license.md for further information.

# Miscellany - Why we chose the license/code-of-conduct
We based our code of conduct off of the one from TwitterOSS, which we found [here](https://github.com/twitter/code-of-conduct/blob/master/code-of-conduct.md). We chose it because it provides a very general overview of how to interact with collaborators, and basically just be pleasant and create a development environment that isn't toxic to anybody.

We chose the MIT license because this is a simple project that we don't plan to make any money off of. Also, it could be valuable to other developers and we want them to be able to use our code in their projects.
