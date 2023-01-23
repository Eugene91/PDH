# Simple circuit for Pound-Drever-Hall stabilization
The circuit performs heterodyne detection of subcarrier phase from a photodetector 
by mixing it with local oscillator radio-frequency (RF) mixer. 
The circuit has two SMA inputs J1 and J2 for the phased-locked and signal  local oscillator, respectively. 
The operation of the circuit follows simple procedure:

- Signal from J1 and J2 are mixed in RF mixer Minicircuit ADE-1+. 
Prior to coming to mixer the signal from J2 is amplified by Minicircuit MAN1LN.
- The output from the RF mixer is low passed through an active filter
with 4.5 KHz bandwidth and DC gain of 4.
- The low passed signal is inverted and amplified by inverting amplifier with variable DC gain up to 10.
The signal is summed with variable offset and is routed on 50 Ohm load through 

