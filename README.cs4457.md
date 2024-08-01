# CS 4457 Notes

This is a modified version of the P4 tutorials branch meant to support the Fall 2024
offering of CS 4457.

What's changed:

*  utils/p4runtime_lib/convert.py is modified to support 'bytes' in addition to 'str' when
   encoding Python values for RPC
*  utils/p4runtime_lib/switch.py's WriteTableEntry is hackily modified to support MODIFY and DELETE 
   operations
*  skeleton code in exercises/cs4457_f24 is added, which is our CS 4457 P4 homework
*  the patch in vm-ubuntu-24.04/patches/tutorials-support-venv.patch has been applied (modifying utils/Makefile)
