# -Regulated-DC-Power-Supply
 A dual-polarity DC power supply providing ±15V and ±5V from 220V AC input

This project is a dual-polarity regulated DC power supply designed to provide ±15V and ±5V outputs from a 220V AC input. It is suitable for powering analog and digital circuits requiring dual voltage rails.

---

##  Project Specifications

- Input Voltage: 220V AC
- Output Voltages: +15V, -15V, +5V, -5V DC
- Regulation Type: Linear
- Current Capacity: ~1A  (depending on the transformer and regulator ICs used)
- Protection: Filter capacitors and heat sinks for stability and thermal protection

---

##  Components Used

- Transformer (220V to dual 15V and 5V windings)
- Bridge Rectifier (4 diodes or integrated)
- Filter Capacitors (e.g., 1000µF/25V electrolytic)
- Voltage Regulators:
  - LM7815 (for +15V)
  - LM7915 (for -15V)
  - LM7805 (for +5V)
  - LM7905 (for -5V)
- Heat sinks
- Terminal Blocks or Output Pins**

---

##  Working Principle

1. The transformer steps down the 220V AC to lower AC voltages (e.g., 15V and 5V).
2. The bridge rectifier converts AC to pulsating DC.
3. Filter capacitors smooth the DC signal.
4. Voltage regulator ICs provide precise and stable +15V, -15V, +5V, and -5V outputs.
5. Output is taken through terminal blocks for external circuit usage.

---
##  Final Assembled Board

This image shows the final assembled regulated DC power supply circuit with all components in place:

![Final Board with Components](https://github.com/Hesham-19-4/-Regulated-DC-Power-Supply/blob/main/final_board_with_components.jpg?raw=true)

##  -15V Output Measurement

The following image shows the output of the regulated DC power supply (e.g., -15V):

![-15V Output](https://github.com/Hesham-19-4/-Regulated-DC-Power-Supply/blob/main/-15.png?raw=true)

##  +15V Output Measurement

The image below shows the measured +15V DC output from the power supply circuit:

![+15V Output](https://github.com/Hesham-19-4/-Regulated-DC-Power-Supply/blob/main/15.png?raw=true)

### +5V Output Measurement
![+5V Output](https://github.com/Hesham-19-4/-Regulated-DC-Power-Supply/blob/main/5.jpg?raw=true)





## Applications

- Operational amplifier circuits
- Analog audio systems
- Testing and development of analog/digital electronics
- Microcontroller-based circuits requiring dual rails


---

## Notes

- For better performance and safety, always mount voltage regulators on proper heat sinks.


