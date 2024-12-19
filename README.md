# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

1. Understand the Shift Register Types
Serial-In Serial-Out (SISO): Bits are input serially and shifted out serially.
Serial-In Parallel-Out (SIPO): Bits are input serially and output parallelly.
Parallel-In Serial-Out (PISO): Bits are input parallelly and shifted out serially.
Parallel-In Parallel-Out (PIPO): Bits are input and output parallelly.

3. General Inputs and Outputs

   
Inputs:
clk: Clock signal.
reset: To initialize or reset the register.
data_in: Input data (serial or parallel).

Outputs:
data_out: Output data (serial or parallel).


**PROGRAM**

Developed by:Rajashri I RegisterNumber: 24900207

![DE ex10 code](https://github.com/user-attachments/assets/dcf336cb-fc0b-4450-92d1-24abec0efef5)

**RTL LOGIC FOR SISO Shift Register**

![DE ex9 diagram](https://github.com/user-attachments/assets/8f79bfe0-469b-4a37-bd0f-21f1a508efc2)


**TIMING DIGRAMS FOR SISO Shift Register**

![DE ex10 wave](https://github.com/user-attachments/assets/762106ee-cfb6-46c5-a801-18f141297ee2)


**RESULTS**
The implementation of  SISO Shift Register using verilog and validating their functionality using their functional tables

