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

- Download the installer:

   * [Miniconda installer for
     Windows](https://conda.io/miniconda.html>)

   * [Anaconda installer for
     Windows](https://www.anaconda.com/download)

- Double-click the ``.exe`` file.

- Follow the instructions on the screen.

   If you are unsure about any setting, accept the defaults. You
   can change them later.

   When installation is finished, from the **Start** menu, open the
   Anaconda Prompt.

- [Test your installation](https://conda.io/docs/user-guide/install/test-installation.html)

## Updating conda

- Open your Anaconda Prompt from the start menu.

- Navigate to the ``anaconda`` directory.

- Run ``conda update conda``.


## Uninstalling conda

- In the Windows Control Panel, click Add or Remove Program.

- Select Python X.X (Miniconda), where X.X is your version of Python.

- Click Remove Program.

NOTE: Removing a program is different in Windows 10.


## Common Commands

Here is a list of frequently used conda commands, and you can see a longer list at the [Conda cheet sheet..](https://leifengtechblog.files.wordpress.com/2016/01/conda-cheatsheet.pdf)

* ***conda info***: Displays information about current conda install.
* ***conda help***: Displays the list of conda commands and their help strings.
* ***conda list***: Lists all packages installed in the current environment.
* ***conda env list***: Displays the list of environments installed and the currently active one is marked by a star *.
* ***conda serarch somepackage***: search for a package to see if it is available.
* ***conda install somepackage***: Installs a Python package.
* ***conda install somepackage=0.7***: Installs a specific version of a package.
* ***conda update somepackage***: Updates a Python package to the latest available version.
* ***conda update anaconda***: Updates all packages.
* ***conda update conda***: Updates conda itself.
* ***conda update --all***: Updates all packages.
* ***conda remove somepackage***: Uninstalls a Python package.
* ***conda remove -n myenv --all***: Removes the environment named myenv.
* ***conda clean -t***: Removes the old tarballs that are left over after installation and updates.


## A few references about Anaconda:

* Installation Guide: https://conda.io/docs/user-guide/install/windows.html

* Anaconda websit: https://store.continuum.io/cshop/anaconda/

* Conda user cheet sheet http://conda.pydata.org/docs/_downloads/conda-cheatsheet.pdf

* List of Anaconda packages: http://docs.continuum.io/anaconda/pkg-docs

* Conda main page: http://conda.io/

* Anaconda mailing list: https://groups.google.com/a/continuum.io/forum/#!forum/anaconda

* Conda FAQ: http://conda.pydata.org/docs/faq.html
