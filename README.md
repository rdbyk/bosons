# Bosons
- is an **experimental ATOMS repository** for [Balisc](https://github.com/rdbyk/balisc) / [Scilab 6.x](http://www.scilab.org/en/community/news/scilab6)
- provides some **precompiled Toolboxes** for **Linux 64bit only**

## How to use it?
#### Setup
- `atomsRepositoryList()` will return a list of available repositories
- `atomsRepositoryAdd('https://raw.githubusercontent.com/rdbyk/bosons/master')` will add the _**Bosons**_ to the list of available repositories

(Hint: In case of ATOMS related problems, make sure that your that your _Edit | Preferences | Web | Proxy settings_ are correct.)

#### List / Install / Remove Toolboxes
- use the commands `atomsList` / `atomsInstall` / `atomsRemove`,
- or the _Applications | Modules Manager - ATOMS_ with GUI

## Contents (_in alphabetical order_)
- [_**SYMSCI**_ - Symbolic Math Toolbox for Scilab (Version 0.5)](http://www.kybdr.de/software#symbolic_math_toolbox_for_scilab)

  The _**SYMSCI Toolbox**_ provides (currently) very basic capabilities for _**symbolic arithmetic**_ and _**differentiation**_,
and _**arbitrary precision floating point**_ calculations.

  Under the hood works the MIT/BSD licensed C++ libary [SymEngine](https://github.com/symengine/symengine).
SymEngine itself needs the following LGPL licensed GNU libraries: [GMP](https://gmplib.org/), [MPFR](http://www.mpfr.org/), and [MPC](http://www.multiprecision.org/).

  1. You have to install these shared libraries  _**a priori**_ to the _**installation**_ of the _**SYMSCI Toolbox**_ itself, e.g. via
  
     `sudo apt-get install libgmp10 libmpfr4 libmpc3`
  
     under Ubuntu.
  
  2. Followed by `atomsInstall("symsci")` under _**Balisc**_/Scilab 6.x, which _**downloads**_ and _**installs**_ _**SYMSCI Toolbox**_ from the _**Bosons**_ repository.
  
