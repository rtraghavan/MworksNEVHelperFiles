**Overview**
---
This repository contains a core set of matlab functions used to align **.mwk** files to simultaneously acquired .**nev** files in Movshon Lab.

**.mwk** files are generated by [MWorks](https://mworks.github.io/), a stimulus control and display program.   
**.nev** files are neural recording files generated by [Blackrock Microsystems](http://blackrockmicro.com/) hardware.

**Contents**
---
getmworksinfo.m : a function that uses mworks matlab tools (installed with software) to extract information from mworks **.mwk** files  

mworks2nevconversion.m: a function that uses mowrks matlab tools, the blackrock microsystems [NPMK](https://github.com/BlackrockMicrosystems/NPMK/tree/master/NPMK) package and getmworksinfo.m to derive a scaling factor that can align times extracted from **.mwk** files to times recorded in **.nev** files.

**License**
---
The code is provided for free via the GNU General Public License. See license file in this repository for further details.
