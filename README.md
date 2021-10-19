# ADC-DAC

The goal of this project is first to connect the Spartan 7 FPGA platform's integrated ADC and DAC so that real-world signals may be handled by the FPGA board.

First, the ADC was connected, and the results were seen using ChipScope Pro.

The DAC was then connected and tested to see whether it was working.

Finally, both were operated together, where registers were used to store the digital data values obtained from the ADC and then sent to the DAC to reconstruct the original signal, which could be observed via a DSO.
