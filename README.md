SConsDebPackage
===============

Debian packaging facility. This package allows you to define and generate
debian packages for your SCons-based project.

DOWNLOAD AND INSTALL
--------------------

You may download and unpack source tarball
    
    user@host:$ cd /tmp
    user@host:$ wget https://github.com/ptomulik/scons-deb-package/tarball/master -O scons-deb-package.tar.gz
    user@host:$ tar -xzf scons-deb-package.tar.gz

or clone the repository

    user@host:$ cd /tmp
    user@host:$ git clone git://github.com/ptomulik/scons-deb-package.git

To install ``SConsDebPackage`` locally in your project, copy the directory
``SCOnsDebPackage`` to your project's ``site_scons/``

    user@host:$ cp -r /tmp/scons-deb-package/SConsDebPackage myproj/site_scons/

DOCUMENTATION
-------------

There are two kind of documentation provided: ``api-doc`` (for developers) and
``user-doc`` (actually, for developers too :)). Each one may be generated from
the top-level directory. 

For ``api-doc`` you'll need at least

    * epydoc (python-epydoc) <http://epydoc.sourceforge.net/>

To generate API documentation, go to the top-level of downloaded source tree
and type

    user@host:$ scons api-doc

For ``user-doc`` you'll need at least

    * xsltproc
    * docbook5-xml

To generate user's documentation (including manual), type

    user@host:$ scons user-doc

The generated documentation is placed under ``build/doc/`` directory.

LICENSE
-------

Copyright &copy; 2012 by Paweł Tomulik

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE
