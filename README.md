# Digital-Filter-Design

*COMPANY*: CODTECH IT SOLUTIONS  

*NAME*: KRISHNA SINGH 

*INTERN ID*: CT04DR278  

*DOMAIN*: VLSI 

*DURATION*: 4 WEEKS  

*MENTOR*: NEELA SANTOSH

##Description 

Objective

The objective of this task is to design, implement, and simulate a Digital Filter using Verilog HDL, analyze its behavior in terms of signal attenuation and waveform response, and verify the functional correctness through simulation on EDA Playground. The experiment demonstrates the basic operation of a Finite Impulse Response (FIR) Low Pass Filter, which is widely used in digital signal processing for noise removal and smoothing applications.

Tools and Resources Used

For this experiment, the following tools and online resources were used:

EDA Playground (www.edaplayground.com
) – An online simulation platform for Verilog and VHDL. It provides instant compilation, waveform viewing, and debugging using simulators such as Icarus Verilog and Aldec Riviera-PRO.

Verilog HDL – Hardware Description Language used to define the digital logic behavior and structure of the filter.

GTKWave – The waveform viewer integrated within EDA Playground for analyzing simulation outputs.

Online References: Tutorials from ChipVerify and ASIC World were referred to for understanding the Verilog coding and filter structure.

Theory and Design Working

Digital filters are used to process discrete-time signals by selectively allowing or blocking certain frequency components. In this task, a Low Pass FIR Filter is designed, which allows low-frequency components to pass while attenuating higher frequencies.(are stored as constants representing the filter characteristics).
The design involves:

A register block for sampling the input values.

A multiplier block for coefficient multiplication.

An adder tree to sum up the products and generate the output sample.

Simulation and Waveform Explanation

The simulation was performed on EDA Playground using Icarus Verilog. The testbench was created to apply a sequence of digital input signals representing varying frequencies.

After compilation and running the simulation, the waveform viewer displayed the following results:

The input waveform showed rapid fluctuations corresponding to higher frequency components.

The output waveform (after filtering) appeared smoother, representing the attenuation of high-frequency noise — confirming correct low-pass behavior.

The time delay between input and output indicated the filter latency due to the number of taps used.

The red line observed in the waveform viewer represents transition markers or active signal transitions, helping identify the exact timing when signals change states.

Observation and Result

The simulated output verified that the designed digital filter:

Successfully suppressed high-frequency components.

Maintained a stable and smooth output signal.

Operated correctly within the timing constraints.
The simulation results validate that the filter design functions as intended. The waveform results confirmed that the filter allows only desired low-frequency signals to pass through, effectively filtering noise.

Conclusion

The task of designing and simulating a Digital Filter using Verilog HDL was successfully achieved. Through this experiment, we demonstrated how digital filtering can be implemented in hardware description language and analyzed using waveform simulations. The EDA Playground tool proved highly efficient for quick design verification and waveform visualization without needing local tool installation.

This experiment strengthened the understanding of FIR filter implementation, coefficient-based processing, and hardware-based signal manipulation. The successful simulation output verified that the Verilog code correctly represents the digital filter’s working and timing behavior. Overall, the experiment effectively bridges theoretical signal processing concepts with practical digital design and simulation skills

