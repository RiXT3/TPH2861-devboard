# TPH2861 

The current design uses a non-inverting amplifier configuration with a voltage gain of 21 V/V.

This configuration - non-inverting with DC Biasing

To ensure a clean and stable power supply, the circuit uses the LP5907 low-noise LDO regulator, featuring an output noise level of just 6.5 µV RMS.

<img width="740" height="626" alt="obraz" src="https://github.com/user-attachments/assets/a3824e7e-b370-4dcc-b48a-8e635149e3da" />



### TPH2861Q — Pinout

| Pin | Name | Function | Description / Connection |
|---:|---|---|---|
| 1 | FB | Feedback Output | Feedback connection electrically tied to the output, placed closer to the input pins to minimize feedback path length and improve high-frequency performance. |
| 2 | VCC− | Negative Supply | Connectef to GND for signle rail operation. |
| 3 | IN− | Inverting Input | Feedback. |
| 4 | IN+ | Non-Inverting Input | Signal input;  DC bias installed. |
| 5 | VCC+ | Positive Supply | VCC (3.3V) |
| 6 | OUT | Output | Amplified signal output. |
| 7 | NC | Not Connected | GND. |

**Note:** FB is an output feedback connection located closer to the input pins than OUT, allowing a shorter feedback path and improved high-frequency PCB layout.
