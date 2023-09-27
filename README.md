# Voice Factory
 
How to Install and Run "Prof Moore's Digital Voice Factory"
===========================================================

These instructions will help you set up your PC in order to be able to install and run the Voice Factory software.  Note that the software will only work on a PC running Windows (with a suitable soundcard installed).  Note also that it requires the installation of the Pure Data (Pd) programming environment plus Pd's special GUI package - GrIPD.


Installation of Pd and GrIPD
----------------------------

Step 1:  Download and install the latest version of 'pd-extended' (for Windows) from "http://puredata.info/downloads/pd-extended"

Step 2:  Download GrIPd (for Windows) from "http://crca.ucsd.edu/~jsarlo/gripd/"

Step 3:  Unzip the contents of gripd-*.zip to "C:\Program Files\pd\extra\gripd"


Installation of Voice Factory
-----------------------------

Step 1:  Create a folder "VoiceFactory" on Drive "C:"

Step 2:  Unzip the contents of "VoiceFactory.zip" into "C:\VoiceFactory"

Step 3:  Check that you have the "KidTYPEPaint" font installed on your PC (Control Panel => Fonts) - if it's not there, install "KIDTYPEP.TTF" from the "C:\VoiceFactory" folder


Running the Application
-----------------------

Step 1:  Ensure that the audio system on the PC is working OK, that the output volume is set at a reasonable level, and that a microphone is attached

Step 2:  Double-click on "VoiceFactory.pd".  This should start Pd, run the core program and open the GrIPD GUI window

Step 3:  Click anywhere on the GrIPD GUI window to bring the application to the foreground, and move the window to an appropriate place on the screen

Step 3:  The application should now be running - test it by pressing one of the buttons and speaking into the microphone when instructed


Closing the Application
-----------------------

Step 1:  Locate "pd-extended" in the Windows Task Bar.

Step 2:  Close "pd-extended" (note: if it asks whether you want to save any files, answer "no").


(C) Prof. Roger K. Moore 2012
