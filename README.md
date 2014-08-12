git1perl2
=========

Presentation of git1perl2 for MadMongers (Madison Perl Mongers) Aug 12, 2014

Even when you are not able to install Modern Perl on your environment, 
  if you have git, you still have perl (albeit older) from git bash:

skaftanski@TDDEV ~
$ pwd
/c/Users/skaftanski

skaftanski@TALENDDEV ~
$ perl -v

This is perl, v5.8.8 built for msys
...

skaftanski@TALENDDEV ~
$ mkdir git1perl2

skaftanski@TALENDDEV ~
$ cd git1perl2

skaftanski@TALENDDEV ~/git1perl2
$ git init
Initialized empty Git repository in c:/Users/skaftanski/git1perl2/.git/

...

Grab some useful files (such as from http://search.cpan.org/~cwest/ppt-0.14/ )

...


# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# Committer: Steve Kaftanski <skaftanski@talenddev.x-es.com>
#
# On branch master
#
# Initial commit
#
# Changes to be committed:
#       new file:   git1perl2
#
# Changes not staged for commit:
#       modified:   git1perl2 (modified content, untracked content)
#
# Untracked files:
#       inlinePerlPackages/
#
Adding subdir git1perl2 several files from PPT-0.14 (2004):
  cal
  strings
 ...not otherwise available from git bash

...

curl -O http://search.cpan.org/CPAN/authors/id/C/CW/CWEST/ppt-0.14.tar.gz

http://search.cpan.org/~cwest/ppt-0.14/


skaftanski@TALENDDEV ~/git1perl2 (master)
$ git clone https://github.com/daviddelikat/inlinePerlPackages/
Cloning into 'inlinePerlPackages'...
remote: Counting objects: 82, done.
remote: Total 82 (delta 0), reused 0 (delta 0)
Unpacking objects: 100% (82/82), done.
Checking connectivity... done.

