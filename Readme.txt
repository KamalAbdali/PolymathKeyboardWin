US-POLYMATH KEYBOARD LAYOUT FOR WINDOWS

This is a fairly general-purpose keyboard meant to facilitate 
typing technical as well as literary texts. It provides several 
math symbols, especially those commonly used in logic, set theory, 
and number theory, and the most frequently used Greek letters. 
It also includes a variety of "combining diacritical marks" to 
type "extended characters" of Latin script.

The currently available keyboard layouts provide one of two 
alternative methods (sometimes a bit of each) to compose an
extended character. In one method, "dead keys" are assigned to 
the modifying marks or accents. To compose an extended character, 
you first press the dead key and then press the character to be 
modified.  After the first keypress, no output appears on the 
screen, but after the second keypress the modified character is 
output. In the alternative method, you first press the letter to 
be modifed, and then press the special key assigned to the 
combining diacritical mark. The US-Polymath Keyboard uses the 
second method exclusively.

How the extended characters are rendered and processed depends on 
the application receiving the text and the font used. In my own 
limited experimentation, the combination LibreOffice + STIX fonts 
has worked out the best.

The file "US-PolymathKeyboardWin.pdf" (in the "distrib" directory
below) is a printable one-page keyboard map for reference.


*** DIRECTORIES ***

1. src

This directory contains:

- Windows keyboard layout source file us-polymath.klc. 
With this file as input, Microsoft's program "Keyboard Layout 
Creator" produces an application to install the keyboard layout. 
This installer is a set of directories and files, including a 
setup.exe file.  

- TeX source file US-PolymathKeyboardWin.tex. It should be 
processed by the XeLaTeX engine to produce the keymap picture 
US-PolymathKeyboardWin.pdf.


2. distrib

- This directory contains the files needed for installing the 
US-Polymath Keyboard Layout on a Windows computer. It also includes 
a file "readme-win.txt" with some installation instructions and a 
file "US-PolymathWin.pdf" as a convenient one-page keyboard map. 

- A zip of the files in this directory is a convenient way to 
distribute the layout. Such a zip file is downloadable from 
http://geomete.com/ftp/US-PolymathWin.zip



