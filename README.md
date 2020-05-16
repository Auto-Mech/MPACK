# MPACK

Multiprecision linear algebra PACKage.

### Installation using Conda

The most direct way to install the code is through the conda package manager.
If you have conda installed, simply run the following command in whichever
environment you choose:
```
conda install -c auto-mech mpack
```
If you do not have conda, it can be installed using the shell script
`debug/install-conda.sh`.

### Building from source without Conda

This is not the advised way to install, since the user will have to deal with their specific system setup

Run build.sh, which uses cmake to compile MPACK:
```
bash build.sh
```

Note that the results of the `make install` command in build.sh will depend on your system setup.


## Notice 

Authors:
Nakata Maho <maho@riken.jp>

Distributed under GNU LESSER GENERAL PUBLIC LICENSE, Version 3, 29 June 2007
See 'COPYING' file for more details
