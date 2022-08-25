# intelhex-2-c
Python utility to convert Intel Hex file to C source code
* Requires IntelHex library installed. Install with pip install intelhex

usage: intelhex2c.py [-h] [-s START] [-e END] [-p PADDING] [-w WIDTH] hex_file

Utility program to convert an Intel Hex file to C source code

positional arguments:
  hex_file              Intel Hex file to read in

options:
  -h, --help            show this help message and exit
  -s START, --start START
                        Start Address for output. Default=Lowest address in hex File
  -e END, --end END     End Address for output. Default=Top address in hex file
  -p PADDING, --padding PADDING
                        Byte value for uninitialized data. Default=0xff
  -w WIDTH, --width WIDTH
                        Values per line, default=8
