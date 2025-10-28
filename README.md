# U Disk Imager
A USB disk image writer/reader with sectors offset and CLI, especially suitable for Embedded Development.

This project is based on znone/Win32DiskImager, which was rewritten from Win32 Disk Imager (http://sourceforge.net/projects/win32diskimager/). Both interface and function are basically the same. The difference is that the project was written using Win32 native technology, while the original project was written in QT. Therefore, the release file of this project is very small. 
This program can run on Windows XP.

## Improve
1. Start sector address can be specified if you needed.
2. Command Line param can be specified for automation.
3. Small size app file, no Qt dependent vs. Original version.
4. Can operate USB storage itself or partition on USB storage
5. Display the size of the file, USB storage or partition

## Build Instructions
### Requirements
1. Visual Studio 2022 or later
2. WTL
2. Windows SDK 7.0
