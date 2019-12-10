## Debug Hard

Ruby String Library Methods and Underlying C Implementations

## Languages and/or Technologies

Ruby 2.5.1

VirtualBox 5.2.16

GNU gdb 8.1.0 (Ubuntu)

## Talk Proposal

What if the Ruby String library 'reverse' method or its underlying C implementation had a bug? What if it produced unexpected results with certain types of inputs? e.g. strings with unicode characters. How would you catch and fix such a bug? How would you explain the unexpected results?

In this talk, we'll take a close look at how Ruby's String library 'reverse' method works. In order to catch a potential underlying bug in this method, we need to understand its implementation. Where exactly is the source code? Does it have adequate unit tests? Put on your debugger hats and join me explore some powerful techniques to isolate and fix such bugs. This talk will add value to your debugging tool belt and improve your confidence in finding/fixing problems that lay underneath the current (Ruby) application programming language.

## NYC Ruby Meetup 2019

[Presentation](./nyc-rb/2019-04-debug-hard.pdf)

## Nokia Bell Labs 2019

[Presentation](./nokia-bell-labs/2019-05-debug-hard.pdf)

## Ruby Conf Kenya 2019

[Presentation](./ruby-conf-kenya/2019-07-debug-hard.pdf)

## Ruby Conf Thailand 2019

[Presentation](./ruby-conf-thailand/2019-09-debug-hard.pdf)

## Building Ruby from Source

### Ruby Source

https://www.ruby-lang.org/en/documentation/installation/

### Ruby Compilation

```
$ sudo apt-get update
$ sudo apt-get install build-essential
$ sudo apt-get install libffi-dev
$ sudo apt-get install zlibc zlib1g zlib1g-dev
$ sudo apt-get install libssl-dev
$ sudo apt-get install libreadline-dev
$ sudo apt-get install libyaml-dev
$ sudo apt-get install libgdbm-dev
$ sudo apt-get install libncurses5-dev
$ sudo apt-get install bison
$ sudo apt-get install apt-file
$ sudo apt-file update
$ sudo apt-get install libgdbm-compat-dev
$ sudo apt-get install autoconf automake

$ ./configure
$ make

$ sudo make install
-OR-
$ sudo make do-install-nodoc
```
