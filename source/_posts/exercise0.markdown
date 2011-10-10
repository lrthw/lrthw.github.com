---
layout: post
title: "Exercise 0 Help"
---
# Exercise 0 Help
If you are on this page then you are doing Exercise 0 (Zero) and trying to complete it. Great, now you can download your editor. We will use the editor [gedit](http://projects.gnome.org/gedit/) as our editor. It works relatively the same on all computers, has good Ruby support, and is a great simple editor.

You can get it for these platforms:

* [gedit for OSX](http://learnpythonthehardway.org/static/gedit-2.30.2.dmg)
* [gedit for Windows](http://learnpythonthehardway.org/static/gedit-setup-2.30.1-1.exe)

If you are using Linux, then you either probably already have gedit, can install a package for it, or know how to install it. Actually, if you use Linux you'll probably just use whatever editor you think makes you look smarter, so go ahead and use that one.

## Windows 7

When installing Ruby on a windows 7 system, the user may have to add the path to the Ruby executable to the path list.

1. Right click computer > properties > advanced system settings .
2. On the advanced tab click environment variables.
3. In the bottom half of the window highlight the word "path" click edit.
4. At the end of the current line, add a semicolon followed by the full path to the `ruby` executable path, something like this:

    %SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;;c:\ruby\bin

Your path will be different, and you should get help from someone if you can't do this.
