                              Asciiquarium v1.1
                    by Kirk Baucom <kbaucom@schizoid.com>
                          http://www.robobunny.com

Asciiquarium is an aquarium/sea animation in ASCII art.


This program displays an aquarium/sea animation using ASCII art.

The current version of this program is available at:
http://robobunny.com/projects/asciiquarium



Requeriments

You must have the Term::Animation module, which you can get from
http://www.cpan.org. The Term::Animation module also requires the Curses
module, which you can also get from CPAN. This program will only run on
platforms that have a Curses library (so it won't work on Windows, but
you might get it to run under cygwin).


Instalation

Term-animation

First, you need to install Perl module called term-animation:
sudo apt install libcurses-perl
This will install the program that will run perl scripts on your system.

Acess the directory Term-Animation-2.6 and execute:

perl Makefile.PL &&  make &&   make test

Install 

sudo make install


Asciiquarium

Next, we need to copy the perl script to /usr/local/bin where all of the executable commands are

Acess the directory asciiquarium_1.1 and execute:

sudo cp asciiquarium /usr/local/bin/


To be allowed to run asciiquarium, you need to give yourself permission to execute the perl script:

sudo chmod 0755 /usr/local/bin/asciiquarium

Finally, we have an aquarium:

asciiquarium


