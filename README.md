## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
(Draw neatly in record OR paste Proteus circuit screenshot)
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/4be46d40-2dc3-4712-9ecc-3232d38e23b1" />

Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1377" height="881" alt="image" src="https://github.com/user-attachments/assets/1718033b-f966-440b-9ad0-312ddf26c858" />

## Tabulation
| S.No | Vin (V) | Theoretical Gain (Av) | Theoretical Vout (V) | Practical Vout (V) |
| ---- | ------- | --------------------- | -------------------- | ------------------ |
| 1    | 1.0     | -10                   | -10.0                | -10.88             |
| 2    | 0.5     | -10                   | -5.0                 | -5.4               |
| 3    | 1.2     | -10                   | -12.0                | -12.9              |
| 4    | 1.5     | -10                   | -15.0                | -13 (Saturation)   |

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).

•	Output is amplified without phase reversal.

•	Practical values are close to theoretical values.

## Viva Questions
1.What is a Non-Inverting Amplifier?
    
A non-inverting amplifier is an op-amp configuration in which the input signal is applied to the non-inverting (+) terminal, and the output is fed back to the inverting (−) terminal through a feedback network.
The output voltage is in phase with the input voltage.
2.What is the gain formula?
   
  Av = 1 + (Rf / R1)

  Where:
  Rf = Feedback resistor  
  R1 = Resistor connected to ground  

3.Why is output in phase?
   
  Because the input is applied to the non-inverting (+) terminal, so there is no phase reversal.

4.What happens if Rf increases?

  If Rf increases, gain increases and output voltage increases.

5.What is the input impedance of non-inverting amplifier?

  Input impedance is very high (ideally infinite).
  Practical value is around 1MΩ to 10MΩ.

