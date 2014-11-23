AWS Archive
===========

`awsarchive` is a Python toolkit for archiving files using AWS_ services.

The goal of this project is to provide best practice methods for archiving files
using the products provided by AWS_. This project will provide both command
line utilities and Python API's.

* `Used AWS Services`_
* `Command line utilities`_
* `Contribute`_


Used AWS Services
-----------------

`awsarchive` makes use of the following AWS services:

* Glacier_
* SimpleDB_


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

Contribute
----------

`awsarchive` is an open-source software originally written by BillyShambrook_ 
and released under the MIT licence. The project is hosted on Github_ , where
everyone is welcome to contribute, ask for help or simply give feedback. Please
fork project, add your changes and open a pull request.

.. _AWS: http://aws.amazon.com/
.. _Glacier: http://aws.amazon.com/glacier/
.. _SimpleDB: http://aws.amazon.com/simpledb/
.. _BillyShambrook: https://github.com/billyshambrook
.. _Github: https://github.com/billyshambrook/awsarchive