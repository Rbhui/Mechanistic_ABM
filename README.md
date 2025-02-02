# Mechanistic_ABM
# Introduction
NetLogo  is an open source with lots of documentation and tutorials. Users can visit the http://ccl.northwestern.edu/netlogo/ at Northwestern and the http://groups.yahoo.com/group/netlogo-users/ on Yahoo.

# Application requirement
Windows
NetLogo runs on Windows 7 and older and Vista. NetLogo 5.2.1 was the last version to support Windows XP and Windows 2000. For Windows, the NetLogo installer includes Java 8 for NetLogo (private use only).

Mac OS X
Mac OS X 10.8.3 or newer is required (the last version that supports 10.5 and 10.4 was NetLogo 5.1 and NetLogo 5.2.1 for 10.6 and 10.7). 

Linux
NetLogo works on standard Debian-based and Red Hat-based Linux distributions. The NetLogo tarball includes a copy of the Java 8 runtime.

# 3D Requirements
An older, less powerful system may not be able to use the 3D view or NetLogo 3D.

# 32-bit / 64-bit
Both versions work. 64-bit version can add additional heap space by changing the "-Xmx" JVM option. To run 64-bit NetLogo, 64-bit Windows is needed.

# Model requirement
It needs NetLogo 3D 6.0.4 installed in the computer. 

# User guide
These are the following steps to run the program.

Install NetLogo 3D 6.0.4 
Download model and open it with the installed NetLogo. 
A folder named "ABMData" should be created on the same folder as the netlogo model beforehand to save the data.
In the interface tab, there is setup button. The setup parameters can be changed by changing sliders as well as changing the parameters in the code. Once the parameters are setup, the artery can be created by clicking the setup button. Note, depending on the capabilities of the computer, the initial setup takes a lot of time (~ 30-45 min) to load all the agents in the model. However, if the "view updates" box on the view panel is unchecked, it takes ~15 minutes. To make sure the program is still working as it is loading up the agents, you can check your computer's task manager (% of CPU, memory etc.).
Once the artery is setup, the plaque-growth button has to be clicked to run the model.
