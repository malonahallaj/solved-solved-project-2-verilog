Download Link: https://assignmentchef.com/product/solved-solved-project-2-verilog
<br>
Design and simulate an 8-bit adder/subtractor using a hierarchical Verilog structural description. Your design should accept 2 twos complement 8-bit inputs (x and y) and generate an output (result) which is either their sum or difference, based on another input (sub). If sub is 1, perform a subtract; if sub is 0 perform an addition. You must also set four condition bits (ccn, ccz, ccv, ccc) to indicate whether the result is negative, zero, resulted in an overflow, resulted in a carry out, respectively.

Create the design in a hierarchical fashion as follows. Build a 1-bit full adder using a behavioral dataflow description. Create a testbench to thoroughly test the full adder. Then, create an 8-bit ripple carry adder by instantiating and connecting multiple instances of your debugged full adder. Write a testbench to verify your 8-bit ripple carry adder.

Do not use any delay in your design modules.

You must declare your 8-bit adder/subtractor exactly as follows:

module AddSub8Bit (x, y, sub, result, ccn, ccz, ccv, ccc);

input [7:0] x, y;

input sub;

output [7:0] result;

output ccn, ccz, ccv, ccc;

Your Verilog programs must be compiled and simulated. Save and print the simulator timing diagrams so that you can include them in your final report. This final report must include:

1. A brief problem description

a.       The problem your circuit solves

b.       b. Specific requirements

2. The project deliverables (exactly what you are generating)

3. Approach/methodology (the steps you will take to solve the problem)

4. Block diagrams

5. K-maps where appropriate

6. Your design work

7. Verilog source code listings (for all designs and their testbenches)

8. Timing diagrams showing how your full adder and 8-bit design performed