==================================================
Emak - erl -make, only more so.
==================================================

Emak is a make tool for erlang projects written in erlang (well,
escript).

Requirements
============

Erlang R13B+, Escript

Building
========

It's an escript! Joy! No compilation necessary.


Installation
============

Just symlink it into one of the directories on your $PATH.

Use
===

Common Targets
______________

emak clean:
    Cleans compiled modules, app files and run 'make clean' anywhere
    it can find c_src.

emak [all]:
    Compiles all modules, app files and runs 'make all' anywhere it
    can find c_src.

Unusual Targets
_______________

emak what:
    Lists all targets

emak erl_src <src/[path/]file.erl>
    Compiles a single erlang source file.
