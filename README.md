# Random-Survivor
Python script that chooses a random survivor for Risk of Rain 2.

This has been tested on Windows systems and Debian-based Linux systems with Python3 installed.  I have not tested this with Python2 or on other operating systems,
but it should work as long as Python3 is installed.

On Windows, simply double click the file and you'll be given a command prompt with the survivor choice that closes after 5 seconds.
On Linux, run "python3 randomsurvivor.py".  It will print your choice and your terminal will hang for 5 seconds as a result of the time.sleep call at EOF.
