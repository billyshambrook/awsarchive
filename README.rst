AWS Archive
===========

`awsarchive` is a Python toolkit for archiving files using AWS_ services.

The goal of this project is to provide best practice methods for archiving files
using the products provided by AWS_. This project will provide both command
line utilities and Python API's.

* `Used AWS Services`_
* `Installation`_
* `Contribute`_
* `Command line utilities`_
* API_

Further Documentation: http://awsarchive.readthedocs.org/


Used AWS Services
-----------------

`awsarchive` makes use of the following AWS services:

* Glacier_
* SimpleDB_

The project assumes that you have a single AWS access and secret key that can be
used across the AWS services used.


Installation
------------

Install via `pip`_:

::

    $ pip install awsarchive

Install from source:

::

    $ git clone git://github.com/billyshambrook/awsarchive.git
    $ cd awsarchive
    $ python setup.py install


Contribute
----------

`awsarchive` is an open-source software originally written by BillyShambrook_ 
and released under the MIT licence. The project is hosted on Github_, where
everyone is welcome to contribute, ask for help or simply give feedback. Please
fork project, add your changes and open a pull request.


Command line utilities
----------------------

`awsarchive` can be accessed via the command line using `awsarchive` followed
by the command you wish to perform.

To list all the commands available do:

.. code-block:: bash

  $ awsarchive --help

or to get help for a specific command do:

.. code-block:: bash

  $ awsarchive <command> --help

======== ==========================
Commands Description
======== ==========================
glacier  Move files to Glacier_.
======== ==========================


.. _AWS: http://aws.amazon.com/
.. _Glacier: http://aws.amazon.com/glacier/
.. _SimpleDB: http://aws.amazon.com/simpledb/
.. _pip: http://www.pip-installer.org/
.. _BillyShambrook: https://github.com/billyshambrook
.. _Github: https://github.com/billyshambrook/awsarchive
.. _API: http://awsarchive.readthedocs.org/#api
