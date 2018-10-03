# Install-Anaconda-on-Windows-10
Necessary steps to install anaconda in windows 10. Also instruction is provided to run jupyter notebook on windows with required libraries.


## What is Anaconda ?

[Anaconda](https://www.anaconda.com/) is a free and open source distribution of the Python and R programming languages for data science 
and machine learning related applications (large-scale data processing, predictive analytics, scientific computing), that aims to simplify 
package management and deployment. Package versions are managed by the package management system conda.The Anaconda distribution is used 
by over 6 million users, and it includes more than 250 popular data science packages suitable for Windows, Linux, and MacOS.

## Prerequisites for Anaconda

* Python 2.7 or above
* 4 GB of RAM (May run less than 4GB but will not provide good qualification)

## Installing on Windows

#. Download the installer:

   * [Miniconda installer for
     Windows](https://conda.io/miniconda.html>)

   * [Anaconda installer for
     Windows](https://www.anaconda.com/download)

# Double-click the ``.exe`` file.

# Follow the instructions on the screen.

   If you are unsure about any setting, accept the defaults. You
   can change them later.

   When installation is finished, from the **Start** menu, open the
   Anaconda Prompt.

# [Test your installation](https://conda.io/docs/user-guide/install/test-installation.html)


Installing in silent mode
=========================

NOTE: The following instructions are for Miniconda. For Anaconda,
substitute ``Anaconda`` for ``Miniconda`` in all of the commands.

To run the the Windows installer for Miniconda in
:ref:`silent mode <silent-mode-glossary>`, use the ``/S``
argument. The following optional arguments are supported:

* ``/InstallationType=[JustMe|AllUsers]``---Default is``JustMe``.
* ``/AddToPath=[0|1]``---Default is ``1``'
* ``/RegisterPython=[0|1]``---Make this the system's default
  Python.
  ``0`` indicates ``JustMe``, which is the default. ``1``
  indicates ``AllUsers``.
* ``/S``---Install in silent mode.
* ``/D=<installation path>``---Destination installation path.
  Must be the last argument. Do not wrap in quotation marks.
  Required if you use ``/S``.

All arguments are case-sensitive.

EXAMPLE: The following command installs Miniconda for the
current user without registering Python as the system's default:

.. code-block:: bat

   start /wait "" Miniconda4-latest-Windows-x86_64.exe /InstallationType=JustMe /RegisterPython=0 /S /D=%UserProfile%\Miniconda3


Updating conda
==============

#. Open your Anaconda Prompt from the start menu.

#. Navigate to the ``anaconda`` directory.

#. Run ``conda update conda``.


Uninstalling conda
==================

#. In the Windows Control Panel, click Add or Remove Program.

#. Select Python X.X (Miniconda), where X.X is your version of Python.

#. Click Remove Program.

NOTE: Removing a program is different in Windows 10.

