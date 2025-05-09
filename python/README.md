
## About
Steps to set up a Python 3 environment.

## Steps

### Update operation system
```
$ sudo apt update
$ sudo apt upgrade
```

### Install tools
```
$ sudo apt install build-essential
$ sudo apt install libssl-dev
$ sudo apt install libffi-dev
```

### Install Python 3
```
$ sudo apt install python3-pip
$ sudo apt install python3-dev
$ sudo apt install python3-venv
```

### Install common libraries
```
$ pip3 install matplotlib
```

### Create virtual environment
```
$ mkdir <project-name>
$ cd <project-name>
$ python3 -m venv <nome-ambiente-virtual>
$ source <nome-ambiente-virtual>/bin/activate
```

### Deactivate virtual environment
```
$ deactivate
```
