# Python-Flask - Login and logout of a webpage

This is an example to show how we can use Flask framework for creating a webpage.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Python 2.7 or later
* Flask 0.11.1 or later
* functools any versions
* base64 any versions
* MySQLdb 1.2.5 or later
```

import base64
from flask import *
from functools import wraps

import MySQLdb

```


### Installing

Need to Install Python and to install the others pacakges we need to install pip

For unix

```
apt-get python
apt-get pip

yum install python
yum install python
```
Once pip in stalled , you can use pip to install flask and others packages

```
pip install flask
pip install base64
pip install functools
pip install MySQLdb

```

You can also put all the packages in requirement.txt and install all at once.

```
pip install -r requirements.txt

```

for window users

From https://www.python.org/download/releases/2.7.6 download appropriate Python 2.7.10 Windows Installer. (If that link doesn't work, check https://www.python.org/downloads/)
Run the file
Select install for all users or install just for me, click Next
You'll see it installs under the C:\Python27 folder, click Next
Click Next again for the 'Customize Python' step
Click Finish
Open Control Panel, then System
Click 'Advanced system settings' on the left
Click the 'Environment Variables' button
Under 'System variables' click the variable called 'Path' then the 'Edit...' button. (This will set it for all users, you could instead choose to edit the User variables to just set python as a command prompt command for the current user)
Without deleting any other text, add C:\Python27; (include the semi-colon) to the beginning of the 'Variable value' and click OK.
Click OK on the 'Environment Variables' window.
Open a new command prompt window type python, you will have python running in the command prompt. Note: command prompt windows open prior to setting the Environment Variable will not have the python command available.

open Command prompt as **Administrator**

C:\Python27\Scripts>

```
C:\Python27\Scripts>pip -r requirements.txt

```
