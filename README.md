# qemu-litmus
Litmus tests for qemu TCG

To generate litmus tests, run

	$ litmus -exit true -mach overdrive01.cfg -o run_x86/ x86/*
	$ litmus -exit true -mach overdrive01.cfg -o run_aarch64/ aarch64/*
