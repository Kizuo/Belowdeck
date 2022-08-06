
# Belowdeck

Don't stop at the settings menu, go Belowdeck and change what you want. After all, it's your system.

Belowdeck is what it sounds like; an utility that allows you to go Belowdeck and change things about your Mac computer that you cannot access from any of the preinstalled settings menus. 

## Installation

<ol>
	<li>Python 3 is required for Belowdeck, so make sure it is installed. <br>
	<li>Go up to the top right corner of your Mac's screen, and click the magnifying glass icon in the menu bar. <br>
	<li>Type in the word "Terminal" in the Spotlight Search box, and press enter. A command prompt should open. <br>
	<li>Enter the command ``python3 --version`` in the terminal. If it returns a string and no errors, press the orangish-yellow button in Terminal's title bar and continue to step 8. If it returns an error, go to the next step. <br>
	<li>Download Python 3.10 Stable for Mac: https://www.python.org/ftp/python/3.10.6/python-3.10.6-macos11.pkg
	<li>When it finishes downloading, run the .pkg file and follow all instructions exactly as told for optimum results. <br>
	<li>If it asks you if you want to delete the installer, select move to trash. <br>
	<li>Download Command Line Tools for Mac: https://drive.google.com/uc?export=download&id=1AVw6QG-ygLWYhTtu3IWU8G-EOatU2O1J (Click "download anyway", this is from Apple) <br>
	<li>When it finishes downloading, run the .pkg file and follow all instructions exactly as told for optimum results. <br>
	<li>If it asks you if you want to delete the installer, select move to trash. <br>
	<li>Open Terminal by clicking its icon in the dock. It should be black with a white arrow in the corner. <br>
	<li>To be sure that Git has installed properly, enter the command ``git --version`` in the terminal. If it returns a string and no errors, continue. If it returns an error, go back to step 2 and follow the instructions again. <br>
	<li>Enter the command `cd Documents` into your terminal the same way you did with the first command. Allow the terminal to access the documents folder if it asks. This will <strong>c</strong>hange <strong>d</strong>irectory to your Documents folder for the software to install there. <br> 
	<li>Enter this command: ``sudo git clone --depth 1 https://www.github.com/Kizuo/Belowdeck && cd Belowdeck`` into your terminal to install the software. <br>
	<li>Run the program with the following command: ``python3 belowdeck.py``
	<li>Enjoy your awesome Belowdeck experience!
