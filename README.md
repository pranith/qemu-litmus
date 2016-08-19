# qemu-litmus
Litmus tests for qemu TCG

To generate litmus tests, first download the latest version of the litmus tool
from: http://diy.inria.fr/sources/index.html. Then run:

	$ litmus -exit true -mach overdrive01.cfg -o run_x86/ x86/*
	$ litmus -exit true -mach overdrive01.cfg -o run_aarch64/ aarch64/*
	
You will then have a Makefile and a run script in the folder to run the
genearated litmus tests.
