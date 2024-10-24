# **Simple Crash Reporter**

A simple crash reporter window for Python using PyQt5 that can be used to inform the user and help the developper fix critical bugs.

### How to use

First, you need to install a Python version that will work (this has been tested on Python 3.12.6). Then, you should install the required libraries, which can be found in the *requirements.txt* file.

Then, you can have a look at the syntax at the bottom of the Python file to know how to use it. Basically, you need to create and show the *Reporter* object as a Qt window, by giving the following arguments:

- exception: It's the exception object that was raised by the programm that crashed
- logPath: It's the path to the relevant log file, as a string. It will be used to display the log content and eventually export it
- reportLink: It's the link to the web page where users can report the issue to the developpers, as a string

You can customize the reporter as you want, as long as you mention me as the original author.
