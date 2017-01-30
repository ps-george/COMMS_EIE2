# Lab 2 - AM Simulation and USRP

## Exercise 1 - AM Modulation


Effect of Modulation Index 
0.5 - 
1 - 
1.5 - 

Effect of increasing frequency of the message

* When the message frequency is lower, the waveform is symmetrical around the x-axis.
* At 5k, the waveform becomes malformed because there is an operlap between -fc+fm and fc-fm.
* "Nyquist Rate" - message bandwidth must be at most half the carrier bandwidth.


## Exercise 2a) - Coherent Demodulation
* Scaled the output by a factor of 2
**MATTTTHS**
m(t)cos(2pifct)^2= m(t)(1/2(1+cos(4pifct)))

Explain briefly the mathematical theory behind this demodulation technique. Moreover, why
are we using a low pass filter and why do we have to get rid of the DC component? Why do you
need to scale the message amplitude?

## Exercise 2b)



## Exercise 3
* Envelope detection is better at high frequencies.
* Envolope detection works until the modulation index goes above 1; at that point only coherent detection works correctly because during modulation the envelope signal has parts that are left negative.
* Coherent detection is fine at >1 modulation indexes, but requires the transmitter and receiever to be in phase and at the same frequency.

## Exercise 4
URSP = Universal Software Radio Peripheral
1. niUSRP Open Tx Session: 
2. niUSRP Configure Signal: - S
3. niUSRP Write Tx Data
4. niUSRP Close Session
5. niUSRP Open Rx Session
6. niUSRP Initiate
7. niUSRP Fetch Rx data
8. niUSRP Abort

* Need USRP