# Quick intro

## Video intro and tutorial

 - Git for designers? [why bother](https://www.youtube.com/watch?v=4S3h5L21KlA)?
 - Github for poets :) from [Coding Train](https://www.youtube.com/watch?v=BCQHnlnPusY)

## Setup
1. Install and setup [git](https://git-scm.com/) on your computer. For beginners a graphical user-interface is quite handy. We will work with the [Github Desktop client](https://desktop.github.com/)

In case you want to work with the commandline use this for configuration:
    ~~~bash
    $ git config --global user.name "Firstname Lastname"
    $ git config --global user.email "example@mail.com"
    ~~~

2. Create an account (or login) to GitHub at [git](https://github.com)
3. (optional) Generate a ssh-key and add it to your GitHub account (for more 
   information [click here](https://help.github.com/articles/connecting-to-github-with-ssh/)

    Open your terminal app and generate your keys:
    ~~~bash
    $ ssh-keygen -t rsa -C "example@mail.com"
    $ cat ~/.ssh/id_rsa.pub
    ~~~

4. Fork this [repository](https://github.com/fleshgordo/passerelle21)

## Exercises

Making Commits

1. Clone the forked repository to your computer

    ~~~bash
    $ git clone <url>
    ~~~

2. Create and add a new file

    ~~~bash
    $ git add <file>
    ~~~

3. Commit the new file

    ~~~bash
    $ git commit -m "message"
    ~~~

4. Examine the state of your repo with `git status`. 

    ~~~bash
    $ git status
    ~~~

5. Edit and save your new file, then add it to the staging area. Finally make a 
   new commit with the edited file. At all stages use `git status` to see how 
   your repository changes

    ~~~bash
    $ git add <file>
    $ git commit -m "message"
    ~~~

6. Make some more commits and view the log

    ~~~bash
    $ git log 
    ~~~

7. Commit everything you have done so far

    ~~~bash
    $ git commit -a -m "message"
    ~~~

8. Push the commits to the server

    ~~~bash
    $ git push
    ~~~

