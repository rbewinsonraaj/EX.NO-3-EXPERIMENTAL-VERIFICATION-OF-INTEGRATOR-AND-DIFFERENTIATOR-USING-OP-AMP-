3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            

             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 13 10 43_e61c1270](https://github.com/user-attachments/assets/2401745b-4e27-4ab0-80e8-5e6ac4a3ab90)



## MODEL GRAPH
![WhatsApp Image 2025-11-29 at 13 21 00_9ce86db6](https://github.com/user-attachments/assets/78cce8c9-37db-4e50-bee6-278cd77a2182)

![WhatsApp Image 2025-11-29 at 13 20 49_b9f74ff0](https://github.com/user-attachments/assets/fb712fce-b8a2-48ff-8773-892e7a265be7)


---
## DESIGN
![WhatsApp Image 2025-12-03 at 14 37 30_8f084893](https://github.com/user-attachments/assets/ccda319b-badb-4ba1-a760-03a9cd4a7505)


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![WhatsApp Image 2025-11-29 at 13 20 32_b6d2c84b](https://github.com/user-attachments/assets/d45dd03c-381a-4b06-a8a2-b6eefbfdf9ee)


## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-29 at 13 10 03_ed0f3fa8](https://github.com/user-attachments/assets/29be3ce9-4920-43bf-b4de-3168cfad6165)

---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-29 at 13 23 14_a31cc187](https://github.com/user-attachments/assets/57a135d2-5020-4703-8947-939a8fc7c980)


## MODEL GRAPH

(i)	 SINE WAVE INPUT

![WhatsApp Image 2025-11-29 at 13 23 35_0450dc36](https://github.com/user-attachments/assets/e34aa15d-8fb1-4062-8897-c4ca979aaa10)



(ii) SQUARE WAVE INPUT

![WhatsApp Image 2025-11-29 at 13 23 47_2838d316](https://github.com/user-attachments/assets/f6a8853d-5d2d-45ac-8fa9-54ae3d4cca53)

---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION

 ![WhatsApp Image 2025-11-29 at 13 24 18_9b284f69](https://github.com/user-attachments/assets/c1c58fba-c862-443e-98a1-ea7d5b2af35f)

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 13 11 13_ecdadc56](https://github.com/user-attachments/assets/544670fc-eb6c-43c2-a25c-5ec8990926e6)

---

RESULT:

---

![WhatsApp Image 2025-11-29 at 13 25 52_137b7aa0](https://github.com/user-attachments/assets/6cb8e902-44e2-42eb-9ae1-78ef708d59f9)




