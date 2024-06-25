# VSDsquadron---CLOCK--CYCLE--DIVIDER

A clock cycle divider is a circuit that takes an input clock signal and produces an output clock signal with a frequency that is a fraction of the input frequency. This is often used in digital circuits to reduce the frequency of a clock signal for various components.

Here’s a simple example of a C program that simulates a clock cycle divider. This program assumes that the input clock signal is a simple periodic signal, and it divides the clock frequency by a specified factor.

To compile and run the provided C program using RISC-V GCC, follow these steps:

# Save the Program:

Create a file named " clock_divider.c " 

![file 1](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/46d22c2d-abf3-47ca-8c4a-f7857b5d5fac)

![file 2](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/90cfa9e2-3262-405f-b4fa-5d9577081f3e)


# Compile the Program:

When you run the program, it will prompt you to enter a divider value. For example, if you enter 20, the output will look like this:

https://drive.google.com/file/d/1QM4P8uk_5PAlZocckJSuMuQNnpV4NU5L/view?usp=drivesdk

(Another Example)

Enter the divider value: 10
Input clock cycle 0, Output clock state: 0

Input clock cycle 1, Output clock state: 0

...

Input clock cycle 9, Output clock state: 0

Input clock cycle 10, Output clock state: 1

...

Input clock cycle 19, Output clock state: 1

Input clock cycle 20, Output clock state: 0

...

This output shows the state of the output clock for each input clock cycle, simulating a clock divider.

# Use the RISC-V GCC compiler to compile the program. Here’s the command:

" riscv64-unknown-elf-gcc -o clock_divider clock_divider.c "

![file 3](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/5cc5857b-3714-4c32-bd19-bfbe67e49ae1)

![file 4](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/ea5aa3f7-ef7c-43fd-8ee2-cc3fd929ac83)

# Evaluating RISC-V Assembly

![file 5](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/448b0a39-a076-43d4-a6aa-3c1694413ccb)

![file 6](https://github.com/Varsha212003/VSDsquadron---CLOCK--CYCLE--DIVIDER/assets/173601368/2db60ba6-b2ec-42ed-9f60-80441b0efb68)

One common simulator is Spike, the RISC-V ISA Simulator. If you have Spike installed, you can run the program like this:

" spike pk clock_divider "
