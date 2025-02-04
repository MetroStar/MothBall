[![license](https://img.shields.io/github/license/MetroStar/mothball.svg)](./LICENSE)
[![Build Status](https://travis-ci.org/MetroStar/mothball.svg)](https://travis-ci.org/MetroStar/mothball)

# Mothball
Mothball is a Python package and application for Backing up all ec2 instance configurations for an AWS Account. The
package also snapshot's EBS volumes and terminates instances. Mothball requires that the User executing the script has 
sufficent privledges to collect information about and execute snapshots and termination requests against instances in
their AWS account and region.

## Installation

For installation with Git from source.

```
git clone https://github.com/MetroStar/mothball.git
cd mothball
python setup.py build
sudo python setup.py install
```

or for installation with pip

```
sudo pip install mothball
```

Validate that installation was successful and that the cli tool is available

```
MbBackup --help
```

