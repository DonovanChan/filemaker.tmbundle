# TextMate bundle for FileMaker Pro

## Introduction

Provides syntax highlighting, code snippets, quick documentation reference and robust code generating commands. You can even interact directly with FileMaker Pro's clipboard from within this bundle.

This project was forked from a simpler version by Matt Petrowsky. His bundle was a simplification of the original bundle by Charles Ross. My version mostly adds to the commands.

For more information, please see the help file. You can access that in the bundle menu or in the support folder.

Sublime Text 2 users, see the [alternative branch](https://github.com/DonovanChan/filemaker.tmbundle/tree/SublimeText2).

## Features

* Tab triggers for FileMaker functions
* Documentation for functions, script steps and error codes
* Commands
	* Manipulating/generating calculations
	* Manipulating/generating FileMaker clipboard XML
	* Extracting data from the DDR
	* Extracting data from import.log files
* Syntax highlighting
	* FileMaker
	* FileMaker Clipboard
	* FileMaker Log
* Code folding
* Help section
* Full documention on most commands (displayed when running command with empty input)

## Installation

### For easy installation

1. Download these files. (You should see a giant "Downloads" button on the top-right.)
1. Extract the .zip contents if necessary.
1. Change the name of the downloaded folder to "FileMaker.tmbundle". (You will have to remove some metadata from the name.)
1. Double-click on the file.

That's it! TextMate will install the bundle  automatically into "~/Library/ApplicationSupport/TextMate/Bundles"

### For easy upgrades

You can set up the bundle as a git repository right where TextMate installs it. Here are the Terminal commands:

	mkdir -p ~/Library/Application\ Support/TextMate/Bundles
	cd ~/Library/Application\ Support/TextMate/Bundles
	git clone git://github.com/DonovanChan/filemaker.tmbundle.git "FileMaker.tmbundle"
	osascript -e 'tell app "TextMate" to reload bundles'

The TextMate 2 pre-release stores bundles in a different place, however:

	mkdir -p ~/Library/Application\ Support/Avian/Bundles
	cd ~/Library/Application\ Support/Avian/Bundles
	git clone git://github.com/DonovanChan/filemaker.tmbundle.git "FileMaker.tmbundle"

## Contact

Donovan Chandler  
Beezwax Datatools, Inc.  
donovan_c@beezwax.net  

## History

Original bundle by Charles Ross, puvinyel@znp.pbz  
Forked 3/12/11 by Donovan Chandler from Matt Petrowsky
