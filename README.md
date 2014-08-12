git1perl2
=========

Very Brief Presentation of git1perl2 for Madison Perl Mongers, Aug 12, 2014

Even when you are not able to install Modern Perl on your environment, 
  if you have git, you still have perl (albeit older) from git bash:

skaftanski@TDDEV ~
$ pwd
/c/Users/skaftanski

skaftanski@TALENDDEV ~
$ perl -v

This is perl, v5.8.8 built for msys
...

skaftanski@TALENDDEV ~/git1perl2
$ git init
Initialized empty Git repository in c:/Users/skaftanski/git1perl2/.git/

...

Grab some useful files (such as from http://search.cpan.org/~cwest/ppt-0.14/ )
 Eg., "cal" and "strings" (which otherwise are not available from git bash)
  and both of which work in perl 5.8.8

$ git clone https://github.com/skaftanski/git1perl2
Cloning into 'git1perl2'...
...
Unpacking objects: 100% (7/7), done.
Checking connectivity... done.

...

skaftanski@TALENDDEV ~
$ cd git1perl2


skaftanski@TALENDDEV ~/git1perl2 (master)
$ perl cal
         August 2014
  Su   M  Tu   W  Th   F  Sa
                       1   2
   3   4   5   6   7   8   9
  10  11  12  13  14  15  16
  17  18  19  20  21  22  23
  24  25  26  27  28  29  30
  31

...
Perl Power Tools has not been worked on for a decade or so, but was an
 attempt at a (pre-modern) Perl implementation of standard Unix shell tools.
 Latest checkins appear to be circa 2004, so works pretty good in v5.8.8
