# catalyst-trading
Trading strategies based on the Catalyst platform

# Installation

1. Install/update setup/dev tools

`sudo apt-get install libatlas-base-dev python-dev gfortran pkg-config libfreetype6-dev`

2. Create a conda environemnt (i named it `catalyst`)

`conda create -n catalyst_py27`

3. Install [requirements.txt](https://github.com/enigmampc/catalyst/blob/master/etc/requirements.txt) into conda environment

`pip install -r requirements.txt`

4. Finally install catalyst and matplotlib

`sudo pip install enigma-catalyst matplotlib`

Detailed installation guides and troubleshooting for platfrom other than Debian linux can be found [here](https://enigmampc.github.io/catalyst/install.html)
