# PrintFile
Content output utility

## Description

PrintFile is a utility that outputs the contents (partial contents) for a specified file to the standard output stream.

The program supports the following options:

**-l, --lines=n** output only n (positive only) first (last) lines of the file (optional argument, default is all)

**-t, --tail** output n last lines of the file (optional argument)

**-d, --delimiter=c** end-of-line character (optional, default is ‘\n’)

The file name and options are passed through command line arguments in the following format:

_**PrintFile.exe [OPTION] filename**_