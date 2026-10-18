
The current design uses a non-inverting amplifier configuration with a voltage gain of 21 V/V.

This configuration - non-inverting with DC Biasing

To ensure a clean and stable power supply, the circuit uses the LP5907 low-noise LDO regulator, featuring an output noise level of just 6.5 µV RMS.



### TPH2861Q — Pinout

| Pin | Name | Function | Description / Connection |
|---:|---|---|---|
| 1 | FB | Feedback Output | Feedback connection electrically tied to the output, placed closer to the input pins to minimize feedback path length and improve high-frequency performance. |
| 2 | VCC− | Negative Supply | Connect to GND when using a single-supply configuration. |
| 3 | IN− | Inverting Input | Connect to the feedback network. |
| 4 | IN+ | Non-Inverting Input | Signal input; apply the appropriate DC bias when required. |
| 5 | VCC+ | Positive Supply | Connect to the positive supply voltage. |
| 6 | OUT | Output | Amplified signal output. |
| 7 | NC | Not Connected | Leave unconnected. |

**Note:** FB is an output feedback connection located closer to the input pins than OUT, allowing a shorter feedback path and improved high-frequency PCB layout.
