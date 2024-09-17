 I designed a basic FIR filter with 4 coefficients using the following steps.

1. Generated a sine wave with noise in MATLAB and converted the same to binary form.
2. Exported the binary form of noise signal to signal.data file. 
3. Using the direct form of FIR filter, we designed a Verilog code using basic operations like multiplication with delay elements, addition of all terms. D flip flop is used to create delay. 
4. Imported the signal.data file into the testbench and verified the result.

To implement this directly, download the fir_filter.xpr file. 
Open the project file in Xilinx Vivado and run behavioural synthesis. 
Choose waveform style as analog and radix as unsigned decimal. This helps you to view the input and output in sine wave format clearly. Adjust the filter coefficients accordingly. 
