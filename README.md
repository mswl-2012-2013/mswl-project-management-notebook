mswl-project-management-notebook
================================

Project Management Notebook - Master on Libre Software (URJC - GSyC/Libresoft) http://master.libresoft.es

Introduction
=============

**TBC**

Requirements
=============

* Use markdown syntax: http://github.github.com/github-flavored-markdown/ and this extended guide for markdown http://daringfireball.net/projects/markdown/syntax.

Wiki Notebook
==============

* Lesson 0: `Presentation of the course`.
* Lesson 1: `Introduction to the infrastructure used by Libre Software Communities`.
* Lesson 2: `Communicaton, outreach and netiquette`.
* Lesson 3: `Management of FLOSS projects`.
* Lesson 4: **TBC**.
* Lesson 5: **TBC**.

Development
============

# Pick an issue for the lesson you are going to update.
# Start collaborating.

You have two basic options to collaborate:

Online
-------

Go to [Project Management Wiki](https://github.com/mswl-2012-2013/mswl-project-management-notebook/wiki) and edit online.

Offline
--------

You can use Github wiki like a git repository.

Clone to your local machine:

```
git clone git@github.com:mswl-2012-2013/mswl-project-management-notebook.git
```

Edit or add every page you need and push it to master.

You can use [gollum](https://github.com/github/gollum) to launch a wiki editor offline in your local copy of the repository.

Install gollum gem:

```
$ [sudo] gem install gollum
```

Go to your clone repository and launch gollum:

```
$ cd mswl-project-management-notebook.git
$ gollum
[2013-02-02 10:37:51] INFO  WEBrick 1.3.1
[2013-02-02 10:37:51] INFO  ruby 1.8.7 (2011-06-30) [x86_64-linux]
== Sinatra/1.3.4 has taken the stage on 4567 for development with backup from WEBrick
[2013-02-02 10:37:56] INFO  WEBrick::HTTPServer#start: pid=3853 port=4567
```

Go to `localhost:4567` and start editing.

Every change you save becomes a commit, so to push your changes you only have to launch **git push**:

```
$ git push origin master
```

**Note:** Don't forget to pull from master every time before you start to edit.

Other editors
--------------

Fell free to use the editor you are more comfortable, you can use other editor you want to develop this wiki.

License
========

<a href="http://creativecommons.org/licenses/by/3.0/" rel="Creative Commons Attribution 3.0">![Foo](http://i.creativecommons.org/l/by/3.0/88x31.png)</a>

This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).
