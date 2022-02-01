# SecureCRT-Cisco-Keywords
A little .ini file for SecureCRT v7.3 or later, to highlight the Keywords based on Cisco IOS.

###### *Links*
- https://lihaifeng.net/?p=1084
- https://forums.vandyke.com/showthread.php?p=49910#post49910


## Example: Import Keyword Highlighting INI File 
This example demonstrates an easy way to import a Keyword Highlighting INI file into SecureCRT. 

*Note: This script will only work with SecureCRT version 7.3 and later. That's the version where Keyword Highlighting with regular expressions was first made available.*
1. Download the "Cisco.ini" if you haven't already done so.
2. Copy the downloaded .ini file to the "Keywords" subfolder found in SecureCRT's Configuration folder.
	- If you don't know where SecureCRT's Configuration folder is, open Options / Global Options and navigate to the Configuration paths category.
	- If a "Keywords" subfolder doesn't exist in SecureCRT's Config folder, create one there and set permissions on it (if necessary) so that you can write/copy files into that location.
	- Now you can edit the session options for any of your saved sessions (or the Default session, if you want it configured for all of your existing and future sessions/connections) and in the Keyword Highlighting category of the Session Options window you'll now see "Cisco Words" as an entry in the "List name" drop-down.

The configuration file directory is in %appdata%\VanDyke\Config\keywords, the suffix is .ini


![image](https://user-images.githubusercontent.com/22855177/143246542-41e43eb4-9b34-4087-9c0f-5225dae3045e.png)
