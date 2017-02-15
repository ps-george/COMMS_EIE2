# Lab 3: FM Simulation and USRP

## Exercise 1: FM Modulator

Generalised function for FM is:

![general form](screenshots/FM_signal.PNG)

Instantaneous frequency is:

![instantaneous frequency](screenshots/omega.PNG)

Equivalent form we will be using:

![equivalent form](screenshots/equivalent_form.PNG)

## Diagram

![FM modulator](screenshots/FM_modulator_diagram.PNG)

## Varying _delta f_
### _delta f_=500
![500](screenshots/lab3_ex1_500.PNG)

### _delta f_=2000
![2000](screenshots/lab3_ex1_2000.PNG)

### _delta f_=5000
![5000](screenshots/lab3_ex1_5000.PNG)

* As delta f increases, you can more easily see the variations in frequency of the FM signal.
* In the frequency domain, you can see the message signal spread across a larger bandwidth.

## Exercise 2: FM Demodulator

* Theory is that the derivative provides a sinusoidal signal which has amplitude proportional to the message signal.
* This is just like AM modulation, so the envelope detection method works to retrieve the signal from the differentiated signal.
* Coherent detection would not work because we do not know the phase of the resultant signal

![demod](!screenshots/envelope_demodulation.PNG)

### Envelope Detection
![FM demodulator](screenshots/FM_demodulator_diagram.PNG)

## Exercise 3: FM Simulation

### Top level Diagram
![Top level](screenshots/lab_ex3_toplevel_diagram.PNG)

![FM Simulation](screenshots/lab3_ex3_FM_simulation.PNG)

![Zoomed signal without transient](screenshots/lab3_ex3_zoomed_signal.PNG)

## Exercise 4: FM USRP

### Delta f = 1kHz
![Delta f = 1kHz](screenshots/lab3_ex4_1000.PNG)

### Delta f = 5kHz
![Delta f = 5kHz](screenshots/lab3_ex4_5000.PNG)

### Delta f = 30kHz
![Delta f = 30kHz](screenshots/lab3_ex4_30000.PNG)

* Note that the bandwidth of this signal is 62kHz, which agrees with Carsons rule for delta f = 30kHz and B = 1kHz:
![Carson's Rule](screenshots/carsons_rule.PNG) = 62kHz.


