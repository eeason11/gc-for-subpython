# gc-for-subpython
Memory garbage collection for a simplified version of python. Programmed in C. 
Implemented reference counting (recursive solution used for decreasing references) and stop and copy algorithms.

Only the refs.c file is included as this repository is for showcasing purposes only.

All the code I wrote in this file lies between //// REFERENCE COUNTING //// and //// END REFERENCE COUNTING //// for
reference counting and between //// GARBAGE COLLECTOR //// and //// END GARBAGE COLLECTOR //// for stop and copy, as well
as the brief method close_refs(void).

All other code in the file is categorized as "Adapted from Andre DeHon's CS24 2004, 2006 material. Copyright (C) California 
Institute of Technology, 2004-2010. All rights reserved."
