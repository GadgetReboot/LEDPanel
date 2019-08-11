These modified source files are used with a Teensy 3.6 and a 64x64 1/32 scan LED panel.  
Make backups of the original files so the changes can be undone if necessary.

Locate the folder where the SmartMatrix library was installed in Arduino.
Copy these files into the src folder within the SmartMatrix library installation.  
Overwrite the existing files.  
These changes add support for an extra address pin (Teensy 3.6 pin 37) to control a 64x64 1/32 scan rate panel.
This assumes use of the SmartMatrix V3 shield hardware architecture.  There is a newer shield that doesn't use any address pins, 
but requires the addition of a latch IC.  

This hack allows getting the display running on Teensy 3.6 without needing the extra hardware.
