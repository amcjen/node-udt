Copyright (c) 2001 - 2010, The Board of Trustees of the University of Illinois.
All Rights Reserved.

UDP-based Data Transfer (UDT) Library - version 4
Author: Yunhong Gu [yunhong.gu @ gmail.com]

UDT version 4 is free software under BSD License. See ./LICENSE.txt.

============================================================================

UDT Website:
http://udt.sf.net
http://sf.net/projects/udt/ 


CONTENT: 
./src:     UDT source code 
./app:     Example programs 
./doc:     UDT documentation (HTML)
./win:     VS.Net project files for the Windows version of UDT 


To make: 
     make -e os=XXX arch=YYY 

XXX: [LINUX(default), BSD, OSX] 
YYY: [IA32(default), POWERPC, IA64, AMD64] 

For example, on OS X, you may need to do "make -e os=OSX arch=POWERPC"; 
on 32-bit i386 Linux system, simply use "make".

On Windows systems, use the Visual Studio .NET project files in ./win directory.


To use UDT in your application:
Read index.htm in ./doc. The documentation is in HTML format and requires your
browser to support JavaScript.


Questions? please post to the UDT project forum:
https://sourceforge.net/forum/?group_id=115059
