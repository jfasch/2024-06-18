Development Workflow
====================

.. contents::
   :local:

Checkout and Initialization
---------------------------

.. code-block:: console

   $ cd ~/My-Projects                      # <--- or wherever you like
   $ git clone https://github.com/jfasch/2024-06-18.git
   $ cd ~/My-Projects/2024-06-18
   $ git submodule init
   $ git submodule update

Build
-----

Create build directory for Intel architecture (``x86_64``)

.. code-block:: console

   $ mkdir ~/My-Builds/2024-06-18-x86_64   # <--- or wherever you like
   $ cd ~/My-Builds/2024-06-18-x86_64
   $ cmake ~/My-Builds/2024-06-18
   $ make
