# SecureCRT-Cisco-Keywords
A little .ini file for SecureCRT v7.3 or later, to highlight the Keywords based on Cisco IOS.

	https://lihaifeng.net/?p=1084
	
	https://forums.vandyke.com/showthread.php?p=49910#post49910
	
	Example: Import Keyword Highlighting INI File 
	
	This example demonstrates an easy way to import a Keyword Highlighting INI file into SecureCRT. 
	
	Watch the keyword highlighting video. 
	
	Watch the import keyword INI file video. 
	
	Note: This script will only work with SecureCRT version 7.3 and later. That's the version where Keyword Highlighting with regular expressions was first made available.
	
	Example keyword highlighting INI files:
		○ Cisco Keyword INI file
		○ Cisco Keyword INI file - Dark (for dark backgrounds)
	Please see this forum post by user Casey to pay homage to where this all began.
	
	Want to manually import a keyword INI file instead of using the script?
	If for any reason you don't want to bother with the script -- or it fails to work for you because you're on an unsupported platform/version -- you can "import" your keywords file manually. Here's how...
			Overview:
			Copy the "Cisco.ini" file into the "Keywords" folder found in SecureCRT's Configuration folder location.
			
			Details:
				1) Download the "Cisco.ini" file or "Cisco Words for BlackBckgrd.ini" if you haven't already done so.
				2) Copy the downloaded .ini file to the "Keywords" subfolder found in SecureCRT's Configuration folder.
					® If you don't know where SecureCRT's Configuration folder is, open Options / Global Options and navigate to the Configuration paths category.
					® If a "Keywords" subfolder doesn't exist in SecureCRT's Config folder, create one there and set permissions on it (if necessary) so that you can write/copy files into that location.
				3) Now you can edit the session options for any of your saved sessions (or the Default session, if you want it configured for all of your existing and future sessions/connections) and in the Keyword Highlighting category of the Session Options window you'll now see "Cisco Words" as an entry in the "List name" drop-down.
	
	The configuration file directory is in %appdata%\VanDyke\Config\keywords, the suffix is .ini
	
	Desde <https://lihaifeng.net/?p=1084> 
	
	
	
	Download the example script file here: 
	Attached Files 
		ImportKeywordHighlightINI.py.txt (8.8 KB, 14696 views)
	__________________
	Thanks,
	--Eric
	
	VanDyke Software
	Technical Support
	support@vandyke.com
	(505) 332-5730 
	
	Desde <https://forums.vandyke.com/showthread.php?p=49910#post49910> 
