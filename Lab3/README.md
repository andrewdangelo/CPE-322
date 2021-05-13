# Lab 3A Modified: Python 
Changes made:
* Added steps in the run scripts to have people create a virtual environment (venv) to run their python code in.
* I added a *system_info_alternative.py* file to provided system information for mac, windows, and linux operating systems so that the *system_info.py* is no longer exclusive to the raspberry pi.

### NOTE: Raspberry Pi OS (or macOS/Linux) has both Python 2 and Python 3 already preinstalled
### WARNING: Don't upgrade the preinstalled Python or PIP on Raspberry Pi OS
* Run pip3 to install/upgrade packages, update the IoT repository, and run Python 3 programs
```sh
$ sudo pip3 install 
$ cd iot
$ git pull
$ cd lesson3
$ python3 -m venv lesson3
$ python -m pip install psutil
```
### On Raspberry Pi only
```sh
$ python3 system_info.py
```

### On Windows, Mac, or Linux
```sh
$ python3 system_info_alternative.py
```
