# Lab 4

## Exercise 1 - BPSK Transmitter

### Aim
	In this exercise, we constructed a BPSK Transmitter 
	
	Diagram:
	![BPSK Transmitter Diagram](screenshots/lab4_ex1_BPSK_Tx.PNG)
	
### Observation
	Values: ![Ex 1 values](screenshots/lab4_ex1_values.PNG)
	
	For a IQ Rate of 200k and a symbol rate of 10k the number of samples per symbol is 20.
	
	Graphs for values above: ![Ex 1 graph 1](screenshots/lab4_ex1_graphs.PNG)
	
	Main lobe: ![Main Lobe](screenshots/lab4_ex_mainlobe.PNG)
	
	Main lobe bandwidth: *_INSERT SOMETHING_*
	
	No pulse shaping filter graphs: ![#nofilter](screenshots/lab4_ex1_graphs_none.PNG)
	
	No pulse shaping filter main lobe: ![Main Lobe no filter](screenshots/lab4_ex_mainlobe_none.PNG)
	
	Main lobe bandwidth: *_INSERT SOMETHING_*
	
	* We observed that without a pulse shaping filter, the sideband lobes continued for a larger frequency range. This is because without a pulse shaping filter, higher frequency elements are required due to the rapid change in the message signal.
	* Spectral rolloff is much faster using the pulse shaping filter.

## Exercise 2 - BPSK Receiver

### Aim

![BPSK Theory](screenshots/lab4_ex2_instr.PNG)	

### Observation



| Tx Gain (dB)  | Rx Gain (dB)  | BER1 | BER2 | BER3 | BER4 | BER5 | Average BER |
|:-------------:|:-------------:|:----:|:----:|:----:|:----:|:----:|:-----------:|
| 0             | 0             |0.499 |0.508 | 0.002| 0.002|0.003 |0.203        | 
| -35           | -15           |0.505 |0.470 |0.002 |0.496 |0.536 |0.389        | 
| -37           | -15           |0.190 |0.506 |0.463 |1     |0.480 |0.528        | 
| -40           | -15           |0.487 |0.466 |1     |0.470 |0.469 |0.587        |

## Exercise 3 - Error Correction Coding

### Aim

### Observation
* BER Module does not allow the program to compile.
* FEC Decoder seems to 	

## Exercise 4 - Differential Phase Shift Keying (DPSK)

### Aim

### Observation