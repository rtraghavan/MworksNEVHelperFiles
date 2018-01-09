**Overview**
---
This repository contains a core set of matlab functions used to align mworks data to simultaneously acquired nev data in Movshon Lab.

[MWorks](https://mworks.github.io/) is a stimulus control and display program.  
NEV files are generated by [blackrock microsystems](http://blackrockmicro.com/) hardware.

**Contents**
---
getmworksinfo.m : a function that uses MWORKs matlab tools (installed with software) to extract information from mworks *.mwk* files
mworks2nevconversion.m: a function that uses MWORKS matlab tools, blackrock microsystems [NPMK](https://github.com/BlackrockMicrosystems/NPMK/tree/master/NPMK) software and getmworksinfo.m to get a scaling factor that can align stimulus display times to times recorded using nev.

**License**
---
The code is provided for free via the GNU General Public License. See license file in this repository for further details.
