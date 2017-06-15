## Week 1 > Module 1 > Python Tools for Machine Learning

### Install the environment

Course advice to install all needed libraries via https://www.continuum.io/downloads

#### Download the OSX command line installer

From https://www.continuum.io/downloads

```sh
$ # For Python 2.7
$ curl https://repo.continuum.io/archive/Anaconda2-4.4.0-MacOSX-x86_64.sh -O
$ bash Anaconda2-4.4.0-MacOSX-x86_64.sh 
```

```sh
$ # For Python 3.6
$ curl https://repo.continuum.io/archive/Anaconda3-4.4.0-MacOSX-x86_64.sh -O
$ bash Anaconda3-4.4.0-MacOSX-x86_64.sh
```

Let's Anaconda install itself in the default folder... (the goal is to do machine learning not managing Python environment)

```sh
$ bash Anaconda3-4.4.0-MacOSX-x86_64.sh

...

Anaconda3 will now be installed into this location:
/Users/gsempe/anaconda3

  - Press ENTER to confirm the location
  - Press CTRL-C to abort the installation
  - Or specify a different location below

[/Users/gsempe/anaconda3] >>>
```
...and let it add itself to the PATH

```sh
Do you wish the installer to prepend the Anaconda3 install location
to PATH in your /Users/gsempe/.bash_profile ? [yes|no]
[yes] >>> yes

Prepending PATH=/Users/gsempe/anaconda3/bin to PATH in /Users/gsempe/.bash_profile
A backup will be made to: /Users/gsempe/.bash_profile-anaconda3.bak


For this change to become active, you have to open a new terminal.

Thank you for installing Anaconda3!

Share your notebooks and packages on Anaconda Cloud!
Sign up for free: https://anaconda.org
```

#### To update (when needed)

cf. https://conda.io/docs/install/full.html#os-x-anaconda-install

```sh
$ conda update conda
```

#### To uninstall (it's good to be prepared)

cf. https://conda.io/docs/install/full.html#os-x-anaconda-install

> To uninstall Anaconda open a terminal window and remove the entire anaconda install directory: `rm -rf ~/anaconda`. You may also edit `~/.bash_profile` and remove the anaconda directory from your `PATH` environment variable, and remove the hidden .condarc file and .conda and .continuum directories which may have been created in the home directory with `rm -rf ~/.condarc ~/.conda ~/.continuum`


### Launch offline Jupyter notebooks

```sh
$ anaconda-navigator
```