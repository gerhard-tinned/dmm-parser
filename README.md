## RS232 parser for Mastech Multimeters ##

This script implements a parser for Mastech Digital Multimeters. To use the script, simply connect the RS232 optical cable to your PC and run:

```
./mastech.py
```

Currently supported for Linux and Mac OS X. To use in Windows, simply change the serial port name to whatever COM you are using.

**Supported models**

The following models are reported to work with this script:

 - MS8250B
 - MS8226
 - MS8226T

### Dependencies ###

To run, please install the python libraries `serial` and `bitarray` (try with `pip install serial bitarray`).

Note: Using in Mac OS X? Check [here](http://stackoverflow.com/questions/22313407/clang-error-unknown-argument-mno-fused-madd-python-package-installation-fa) if you're having trouble building bitarray.

### Documentation ###

I based this work on the documents available in the `doc` folder.
