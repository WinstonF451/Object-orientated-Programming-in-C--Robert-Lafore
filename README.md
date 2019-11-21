# Object-orientated-Programming-in-C--Robert-Lafore
msoftcon.cpp and msfotcon.h files working in a Visual Studio 2010 and 2012 project. 
Object-orientated programming in C++ Robert Lafore, 4th Edition ISBN 0-672-323087 ISBN 0672323087

These three source code files msoftcon.h msoftcon.cpp and CIRCSTRC.cpp when added to a Visual Studio 2010 or 2012 Win32Console
Application project have compiled resulting in the Circle console graphics program as outlined on page 174 of the book. 
There is no reason why these files will not compile in newer versions of visual studio. circstrc.cpp contains the
int _tmain(int argc, _TCHAR* argv[]) function, therefore after you create your project cut and past the contents of this source code
file to your _tmain containing source file or delete the file created and add these three files to your project. When you add msoftcon.cpp
to your project ensure that the properties are set to 'Not Using Precompiled Headers' in the property pages for this source file
specifically (or for your entire project). This is under the 'Configuration Properties'->C/C++->'Precompiled Headers'.
Otherwise you will receive the error "Did you forget to add #include "stdafx.h" to your source"?
