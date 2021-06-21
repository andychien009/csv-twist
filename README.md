# csv-twist

## Purpose
A simple tool that reorders the columns of the csv file based on a reference
*definition file*; regardless of the casing of the field header.

This tool reads all fields in as a string, no advance algorithm to determine
data type; that's it, no muss no fuss. 

## Installation
Either use as script in src/ or pyinstall packaged win10 encoded *.exe file in 
bin/win10/. The pyinstall packaed EXE will not work in any other environment
other than the one it was packaged from.

If using the win10 packaged EXE, putting it in the PATH and running it from
GUI at least once after trusting it will allow it to run in any other directory
in the command line interface

## Use
To use the tool first supply the following 4 flags and their respective
arguments to see a preview {--data-file, --data-file-sep, --def-file, 
--def-file-sep}

Once satisified supply the {--out-file} flag and the output parameter

## Arguments Input
  -h, --help            show this help message and exit
  --def-file DEF_FILE   File containing the destination column definition
  --def-file-sep DEF_FILE_SEP
                        Separator for the definition file
  --data-file DATA_FILE
                        The data file to be adjusted in accordance to the
                        column specification outlined by --def-file
  --data-file-sep DATA_FILE_SEP
                        Separator for the data file
  --out-file OUT_FILE   The final output of the process

## Known Issue
This tool outputs header column in capital case. Take the header from
the definition file if you so choose.

This tool does not process fields that are not of printable characters.

## License and Rights
The content of this repo is written and put together by Andy Chien. You can
reach me at andy_chienAThotmail.com.

All content in this repo is under GNU GPL v3. See LICENSE for more information

## Dedication
For my loving family, Jina Julia and Alison.
