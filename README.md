# kmallocVSmalloc
1. kmalloc returns physically contiguous memory, 
 malloc does not guarantee anything about the physical memory mapping.
 The other main difference is that kmalloc'ed memory is reserved and locked, it cannot be swapped. 
 malloc does not actually allocate physical memory. Physical memory gets mapped later, during use.
 
 what is physical memory and virtual memory.
 
Physical memory is the actual real memory used in RAM. Virtual memory as the name suggests is not real.
 
Physical memory is the only memory that is directly accessible to the CPU. CPU reads the instructions stored in the physical memory
and executes them continuously.The data that is operated will also be stored in physical memory in uniform manner.

Virtual memory is one classification of memory which was created by using the hard disk for simulating additional RAM,
the addressable space available for the user. Virtual addresses are mapped into real addresses.

virtual memory is a storage abstraction over RAM and HDD that can allow to execute program whose effective size/usage more than the size of physical memory 
										In other words , vm is technique which does not require entire program to be present in memory before the execution begains.
