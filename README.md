# BidBot

Webapp to set advanced orders on crypto exchanges.

## Prerequisites

This Webapp is build using the Python based Flask framework. Therfore you have to install and setup some stuff. How is described here.

### Prepare the Operating System

May update your system to the latets state
```
sudo apt-get update
sudo apt-get upgrade
```
Install Python

```
sudo get install build-essential python-dev python2.7-dev
```

### Prepare Python environment

Check if `easy_install` is available
```
easy_install --version
```
If not available, use this script:
```
curl -O http://python-distribute.org/distribute_setup.py
python distribute_setup.py
```

#### Set up virtualenv
```
sudo easy_install pip
sudo pip install virtualenv
```
Then:
```
cd bidbot
virtualenv env
``` 
This will create a self-contained Python installation fro this project.

Now we make things more easy with
```
ln -s bidbot/bin/activate
```
Activate the virtual environment with
```
source activate
```





