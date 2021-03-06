
***************
Getting started
***************

============
Installation
============

Yacas is available for a variety of platforms. See 
`<http://www.yacas.org/getting_started/downloads/>`_ for binary packages
and installation instructions.

=========================
Installation from sources
=========================

Getting sources
---------------

Version 1.5.0 can be downloaded from
`<https://github.com/grzegorzmazur/yacas/archive/v1.5.0.zip>`_ or
`<https://github.com/grzegorzmazur/yacas/archive/v1.5.0.tar.gz>`_,
while the current development version is accessible from
`<https://github.com/grzegorzmazur/yacas/archive/develop.zip>`_.

Compilation
-----------

MacOS X
~~~~~~~

* Open ``Terminal`` window
* Change directory to the yacas source directory
* Execute

  .. code-block:: bash
                
     mkdir build
     cd build
     cmake -G Xcode ..
                  
* Open generated project in ``Xcode``

Microsoft Windows
~~~~~~~~~~~~~~~~~

* Open ``Command Prompt`` window
* Change directory to the yacas source directory
* Execute

  .. code-block:: bat
                
     mkdir build
     cd build
     cmake -G "Visual Studio 14 2015 Win64" ..

* Open generated project in ``Visual Studio``

Linux
~~~~~

* Open ``Terminal`` window
* Change directory to the yacas source directory
* Execute

  .. code-block:: bash
                
     mkdir build
     cd build
     cmake -DCMAKE_BUILD_TYPE=Release -DENABLE_DOCS=On ..
     make

* To install newly built binaries execute ``make install``

Java
~~~~
* Open ``Terminal`` or ``Command Prompt`` window
* Change directory to the yacas source directory
* Execute ``ant jar``
