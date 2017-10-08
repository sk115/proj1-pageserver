# README #

## Author: Carter Fritsch , cfritsch@uoregon.edu ##

A "getting started" project for CIS 322, introduction to software
engineering,  at University of Oregon.

### What is this repository for? ###

The objectives of this mini-project are:

  * Experience with GIT workflow with separate configuration:  Fork the project, make and test changes locally, commit;  turn in configuration file with reference to repo. (Project 0 is practice for this part.) 
  * Extend a tiny web server in Python, to check understanding of basic web architecture
  * Use automated tests to check progress (plus manual tests for good measure)

### What do I need?  Where will it work?

* Designed for Unix, mostly interoperable on Linux (Ubuntu) or MacOS.
  Target environment is Raspberry Pi. It *may* also work on Windows, but no promises.  A Linux virtual machine
   may work, but our experience has not been good.

* Requires Python 3.4 or higher. 
* Designed to work in "user mode" (unprivileged), therefore using a port 
  number above 1000 (rather than port 80 that a privileged web server would use)
* Windows 10 note:  The new Windows bash on ubuntu looks promising.
  If you are running Windows 10, please give this a try and let me
  know if the Ubuntu/bash environment is suitable for CIS 322
  develpment. 

### Starting the Server
  ~~~~
  git clone <yourGitRepository> <targetDirectory>
  cd <targetDirectory>
  make install
  make run
  ~~~~

  *test it with a browser now, while your server is running in a background process*

### Stopping the Server
  ~~~~
  make kill 
  ~~~~
