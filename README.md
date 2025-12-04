# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  27.9.2025
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

## 6 A :- LOW PASS FILTER



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-02 at 19 09 22_55f61fea](https://github.com/user-attachments/assets/9707e642-03ab-4233-a717-5268644b358d)

## SIMULATION CIRCUIT DIAGRAM

<img width="1280" height="1005" alt="image" src="https://github.com/user-attachments/assets/7ee4ff8a-902b-4e3a-a585-c2ce425cd55b" />

## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ

![WhatsApp Image 2025-12-04 at 12 36 55_cf282226](https://github.com/user-attachments/assets/fff84698-eaab-4153-8dca-b90414e84aba)


![WhatsApp Image 2025-12-03 at 19 55 59_d0462e7d](https://github.com/user-attachments/assets/cb600b7a-ec53-4444-acbc-ee073c012809)



## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-12-02 at 19 11 09_223c5289](https://github.com/user-attachments/assets/22e518dc-ae9b-4c18-adf1-3174a9b2237f)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-02 at 19 13 21_1ffc7f18](https://github.com/user-attachments/assets/ca7f89e8-04f8-40ad-a06f-57958bb0f54f)

## SIMULATION OUTPUT

<img width="1903" height="446" alt="image" src="https://github.com/user-attachments/assets/88b095be-7603-493e-9c15-89e2914c680e" />

---

 ## 6 B HIGH PASS FILTER

## DATE: 4.10.2025
---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-02 at 19 15 26_9f7e1aa5](https://github.com/user-attachments/assets/b24f628d-248b-4e81-98a7-a1c3e11f2666)

## SIMULATION CIRCUIT DIAGRAM

<img width="735" height="461" alt="image" src="https://github.com/user-attachments/assets/0dce1823-f1e6-4aa1-ac87-0186d4e3d5d6" />

## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ

![WhatsApp Image 2025-12-04 at 12 36 55_cf282226](https://github.com/user-attachments/assets/9dd2d590-05a8-4dcc-a794-d6aaa832e630)


![WhatsApp Image 2025-12-03 at 19 58 18_f8421c85](https://github.com/user-attachments/assets/fca109da-803d-4906-95f5-f302434e7bca)



## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-12-02 at 19 18 38_70cf02ef](https://github.com/user-attachments/assets/8d9dd1e3-f5ce-419e-8edf-ea903b1fd625)


---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-02 at 19 20 46_48dbb56d](https://github.com/user-attachments/assets/19de9e2d-c40f-4c95-8bf8-0001724b2cf0)

## SIMULATION OUTPUT

<img width="1280" height="339" alt="image" src="https://github.com/user-attachments/assets/7503d57c-f950-4578-b148-1bf15f9afa67" />

---

 ## 6C Band Pass Filter

## DATE: 11.10.2025
---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-02 at 19 24 44_565deea1](https://github.com/user-attachments/assets/25030434-2aa4-4908-a60b-c495cfb1bb7a)

## SIMULATION CIRCUIT DIAGRAM

<img width="1175" height="618" alt="image" src="https://github.com/user-attachments/assets/584b2f5e-73cc-4eb6-8b12-6fa1b0d32b63" />

## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ

![WhatsApp Image 2025-12-04 at 12 39 28_0be6d5bf](https://github.com/user-attachments/assets/cb51327f-e811-45ea-83bc-9eb21342a68f)

![WhatsApp Image 2025-12-03 at 20 00 47_c20b5229](https://github.com/user-attachments/assets/6782275a-8423-4013-a538-cd0005847dc3)



## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-12-02 at 19 26 39_7fb16a1d](https://github.com/user-attachments/assets/4155eba5-b57e-4c5c-abcc-dcd2f68d0675)


---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-02 at 19 30 19_61b1b8be](https://github.com/user-attachments/assets/21f76786-c3d4-48c3-8bbf-d76b299f678c)


## SIMULATION OUTPUT

<img width="1901" height="441" alt="image" src="https://github.com/user-attachments/assets/a2f1424a-179f-4231-903c-3fe58aa89d0c" />

---
## RESULT:
Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
