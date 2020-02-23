# git Workshop Universe Istic

## to initialize a git project we will use this command:

```Bash

$ git init

```

## Config your git

```Bash

$ git config --global user.name "Your Name Comes Here"
$ git config --global user.email you@yourdomain.example.com
$ git config

```

## Clonning a Project

We will clone this repository

```Bash

$ git clone https://github.com/bahachammakhi/gitworkshop.git

```

## Add changes

We will add our changes to git !

```bash
$ git status

$ git add .

```

By . we mean all files !
if you wanna select only one file write the file name

## Commit changes

we will make a version of our project !

```bash
$ git commit -m "Your message about the changes you made ! "

```

## Push changes to a host !

we will push our code to github

```bash

$ git push origin master

```

\*origin means the git origin because you can link the same project to many hosting platforms !

\*master means the branch you will push your code into !

## Pull changes from hosting platform !

In case your working with someone that will push his code ofc you need to merge his code with yours !

```bash

$ git pull origin master

```

\*As we said origin is for the git origin and master is the branch you can pull from !
