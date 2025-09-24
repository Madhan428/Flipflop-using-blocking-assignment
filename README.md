# EXPERIMENT 3: Simulation of All Flip-Flops using Blocking Statement

## AIM
To design and simulate basic flip-flops (SR, D, JK, and T) using **blocking statements** in Verilog HDL, and verify their functionality through simulation in Vivado 2023.1.

## APPARATUS REQUIRED
- Vivado 2023.1
- Computer with HDL Simulator

## DESCRIPTION
Flip-flops are the basic memory elements in sequential circuits.  
In this experiment, different types of flip-flops (SR, D, JK, T) are modeled using **behavioral modeling** with **blocking assignment (`=`)** inside the `always` block.  
Blocking assignments execute sequentially in the given order, which makes it easier to describe simple synchronous circuits.

## PROCEDURE
1. Open **Vivado 2023.1**.  
2. Create a **New RTL Project** (e.g., `FlipFlop_Simulation`).  
3. Add Verilog source files for each flip-flop (SR, D, JK, T).  
4. Add a testbench file to verify all flip-flops.  
5. Run **Behavioral Simulation**.  
6. Observe waveforms of inputs and outputs for each flip-flop.  
7. Verify that outputs match the truth table.  
8. Save results and capture simulation screenshots.

---

## VERILOG CODE

### SR Flip-Flop
<img width="1920" height="1080" alt="sr_flipflop_code" src="https://github.com/user-attachments/assets/a7ecce66-86ce-45b3-8a1f-55bfb61e3660" />

### SR Flip-Flop Test bench 
<img width="1920" height="1080" alt="sr_tb_code" src="https://github.com/user-attachments/assets/1295bb0c-54a8-4dd1-ad69-e40604044450" />

#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="sr_flipflop_outform" src="https://github.com/user-attachments/assets/62873b16-53e1-4539-8286-bbb9d762aa45" />


### JK Flip-Flop 
<img width="1920" height="1080" alt="jk_code" src="https://github.com/user-attachments/assets/234594ce-4bc4-4737-9943-8f684a1362d3" />


### JK Flip-Flop Test bench 
<img width="1920" height="1080" alt="tb_jk_code" src="https://github.com/user-attachments/assets/dc7ca92e-2098-497d-bb21-2c37a68d9b88" />

#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="tb_jk_output" src="https://github.com/user-attachments/assets/ae9a9fb3-25b6-48e1-b81b-187f7dfd4e56" />


### D Flip-Flop 
<img width="1920" height="1080" alt="d_flip_flop_code" src="https://github.com/user-attachments/assets/0879be0e-35f3-4bb5-b47d-a89f358fe92d" />

### D Flip-Flop Test bench 
<img width="1920" height="1080" alt="D_FLIPFLOP_CODE_TB" src="https://github.com/user-attachments/assets/ad0370d0-bb82-4ec9-9e02-45407a0d12ce" />

#### SIMULATION OUTPUT
<img width="1920" height="1080" alt="D_FLIPFLOP_OUTPUTWAVEFORM_TB" src="https://github.com/user-attachments/assets/7be422a4-fe58-4472-b56f-0f0c54944ef0" />

### T Flip-Flop
<img width="1920" height="1080" alt="t_flipflop_code" src="https://github.com/user-attachments/assets/c054a4c2-41ed-45fd-a7a6-24054d5eb562" />

### T Flip-Flop Test bench 
<img width="1920" height="1080" alt="tb_t_ff_code" src="https://github.com/user-attachments/assets/f5558f4f-5a29-4f51-b8ad-d5856a6cbec2" />

#### SIMULATION OUTPUT

<img width="1920" height="1080" alt="t_flipflop_output" src="https://github.com/user-attachments/assets/890192c8-e99c-4ab0-9409-041992be1189" />

### RESULT

All flip-flops (SR, D, JK, T) were successfully simulated using blocking statements in Verilog HDL.
The outputs matched the expected truth table values, demonstrating correct sequential behavior.
