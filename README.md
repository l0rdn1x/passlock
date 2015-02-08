#################################################################################
#					       			       VER1.0.5                                           #
# 	   (¯`·._.·(¯`·._.· l0rdn1x's Password Locker ·._.·´¯)·._.·´¯)         	    #
#			                  	Developers Edition				                            #
#		        						                                                       	#
#      									                                                      	#
#  o()xxxx[{:::::::::::::>						                                        	#
#  Please Donate Bitcoin: 16uh36eJbFrETYp1qkwgaS9SrnK3YSRwkJ		              	#
#  Email: lucif3r1776@gmail.com						                                     	#
#################################################################################

*************** NEW IMPORTANT UPDATES **********************************************
1. gnuGPG support has been added for extra security this is not enabled by default,
during the firstrun script you will be asked if you would like to utilize GPG for
enhanced security.  This is HIGHLY recommended but is not enabled by default incase
you dont have access to gnuGPG.

2. Several logic errors have been found and fixed which makes all previous versions
and database's of this script obsolete and any passwords which remain in the old
database shall be recovered before switching to the new version.
***********************************************************************************

DISCLAIMER: This script is free and open source without any charge, with that
statement, USE AT YOUR OWN RISK.

NOTE: This bash script should work for most distributions of Linux, but for the
record it was made from within Ubuntu 14.04 LTS and tested on distros listed below.
	I. Slacko Puppy Linux 5x

EXTRA SECURITY INSTRUCTIONS: Unzip the contents of .tar file to your thumbdrive,
cd your way to the path on the thumbdrive which you extracted the files. you will
notice a file that is named runfirst it has been named that for a reason. The only
intention of this file is to alter the script file ONE time only to make your
copy of the script different than anyone else's copy of the script. Run this file
one time and then delete it from your USB because you won't need it again.

Afer you have completed the extra security instructions you may need to run
chmod +x passlock so the file can be executed.

After the file is ready to be executed, type [ ./passlock ].

This will start the FIRST RUN process of the script and creates the directory
named lock and inside that directory according to the script version a special
file inside of that directory.  Once this process is complete the script will
tell you to run [ ./passlock -help ].

Everything should be self explanitory from here but let me explain a few things.
When you type your service and passphrase they are both CASE sensitive, now you
might be thinking why you need a passphrase, this is to attempt to keep the
real random password safe on your thumbdrive.

When you run [ ./passlock -gen] you will be prompted to first enter a Service,
after you enter a service you will be prompted to enter a passphrase. After you
finish the interactive process the script will add data to the file located in
the folder lock that stores your password.  Do not use any special characters
~`!@#$%^&*()_-+={[}]|\:;"'<,>.?/ some of these are reserved for regular expressions
in programming and I haven't filtered them all out and things might break!

When you are ready to retrieve your password you will type [ ./passlock -call ]
this will start the interactive process to recall your password from the database.
you must input the information EXACTLY how you did when you generated the password.


