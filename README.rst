Hermes Module Schroedinger
==========================

This module solves the Schroedinger equation. 

Build the Module
----------------

In the root directory of this module, type::

    cmake .
    make

Run the Module on C++ Level
---------------------------

C++ sources are located in the directory src/. Change dir to the directory 
src/ and run the module using::

    ./schroedinger

The file model.cfg is a text file that emulates input from a GUI. You can 
change the parameters there at your will.


Run the Module on Python Level
------------------------------

Python wrappers are located in the directory python/ and they allow you 
to call the module from Python as follows::

    python schroedinger.py

The file module-basic.py contains a set of parameters analogous to those
which on C++ level are in the file model.cfg. The user can change these
parameters arbitrarily. 

Run the Module in the Online Lab SDK
------------------------------------

To be completed.
