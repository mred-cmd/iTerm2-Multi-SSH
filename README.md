iTerm2-Multi-SSH
================

iTerm has sophisticated Applescript support allowing one to write stand-alone scripts to launch the application and open multiple sessions. This script connects to multiple SSH hosts in different sessions, splits the window and initiates keyboard input to all sessions.


## How to use it?

- Download the script.
- Edit it - chaging the host names to the hosts you want to connect to. 
	- These hosts must be configured in your .ssh/config


The script itself needs to be stored under the ~/Library/Application Support/iTerm/Scripts directory. You can create this directory if it does not already exist. iTerm checks this directory on startup for scripts and these can be run from the scripts menu in iTerm. You will need to restart iTerm if it to put up the Scripts directory or new scripts added.


![image](http://markreddy.ie/wp-content/uploads/2014/01/iTerm-Multi-SSH.png =640x385)