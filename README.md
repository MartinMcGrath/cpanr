# NAME

cpanr - View cpan ratings from the command line.

# SYNOPSIS

  This script displays content from cpan ratings
  http://cpanratings.perl.org on the command line. Simply call it with the
  module name:

    $ cpanr Path::Tiny
    $ cpanr Path::Tiny

    Reviewer: Michiel Beijen
    Review date: 2014-12-17 @ 03:13:06
    Module version: 0.061
    Rating: 5/5
    Comment: I really, REALLY like this module. It makes managing files so much
    easier. Just opening them, reading them into a scalar or array, printing
    them out. Of course it STARTED out as a true ::Tiny module but as seems to
    happen with those it is now not so Tiny anymore, it even has support for 
    stuff on platforms as AIX and such. I wrote a platform for managing Video 
    on Demand files and had to load and process a whole lot of XML metadata 
    files, images, and videos. I used this module extensively to crawl 
    directories, read files and so on. It has helped me a lot writing code 
    faster while also making my code much easier to read and maintain. Thanks
    a LOT for this module!  

    ....

  This short script was written in a few minutes based upon
  <http://perlmonks.org/index.pl?node_id=1169281> and subsequent discussions
  just for fun. A better solution will be created in due course.

# AUTHOR
  Martin McGrath "mcgrath.martin@gmail.com"

# COPYRIGHT (c)
  Copyright 2016-2017 by Martin McGrath "mcgrath.martin@gmail.com".

# LICENSE
  This module is released under the same terms as Perl itself.

