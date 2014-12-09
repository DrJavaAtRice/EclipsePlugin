Written by Robert Ko on Dec 9, 2014.

This readme is just a list of jar files I removed/changed in the eclipse/lib directory compared to the commit that has the original v0.9.8 plugin (2df95ba3878ef76250864f343b7eb7cab010d660, Oct 30, 2006).

I basically built the latest drjava (commit 67f28dd86e0f07b126e34e0442649e4033c61546, Nov 19, 2014) into drjava.jar, put it here, and removed all the duplicated jar files that already exists in drjava/lib.
--------------------------------------------------------------------------------

List of jar files I changed:
================================
drjava.jar
	- built by pulling from Github's drjava.git repository
	- I updated my local repository to match that of commit 67f28dd86e0f07b126e34e0442649e4033c61546 (Nov 19, 2014)

	- build attributes:
		- built using Oracle Java 64-Bit version 1.7.0_71
		- built on Dec 3, 2014
		- built on Mac OSX 10.9.5
		- built using Apache Ant version 1.9.3
-------
plt.jar
	- REMOVED on 12/3/14 after putting in drjava.jar
-------
dynamicjava 
	- REMOVED on 12/3/14 after putting in drjava.jar
-------
javalanglevels.jar
	- REMOVED on 12/3/14 after putting in drjava.jar
-------
platform.jar
	- REMOVED on 12/3/14 after putting in drjava.jar
================================