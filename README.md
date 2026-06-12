# Task_04
# RTL Design of Finite State Machines (FSM) and Control Units

## Objective

This project demonstrates the RTL implementation and simulation of Finite State Machines (FSMs) using Verilog HDL. The task covers Moore FSM, Mealy FSM, Traffic Light Controller, and Sequence Detector designs along with testbench verification and waveform analysis.

---

## Tools Used

* Verilog HDL
* EDA Playground
* Icarus Verilog
* GTKWave

---

## Repository Structure

```text
Task Files/
Screenshots/
Report/
README.md
```

---

# 1. Moore FSM

## Description

A Moore FSM where the output depends only on the present state. The FSM cycles through three states:

S0 → S1 → S2 → S0

### Verilog Design

![Moore FSM](Screenshots/moore_fsm.png)

### Testbench

![Moore FSM TB](Screenshots/moore_fsm_tb.png)

### Output Waveform

![Moore FSM Output](Screenshots/moore_fsm_output.png)

### Observation

The FSM transitions correctly between all states on every positive clock edge and resets to the initial state when reset is asserted.

---

# 2. Mealy FSM

## Description

A Mealy FSM where the output depends on both the current state and the input signal.

### Verilog Design
 
![Mealy FSM](Screenshots/mealy_fsm.png)

### Testbench

![Mealy FSM TB](Screenshots/mealy_fsm_tb.png)

### Output Waveform

![Mealy FSM Output](Screenshots/mealy_fsm_output.png)

### Observation

The output changes immediately based on the state-input combination, demonstrating Mealy machine behavior.

---

# 3. Traffic Light Controller

## Description

A traffic signal controller implemented using FSM states to control Red, Yellow, and Green lights.

### Verilog Design

![Traffic Light](Screenshots/traffic_light.png)

### Testbench

![Traffic Light TB](Screenshots/traffic_light_tb.png)

### Output Waveform

![Traffic Light Output](Screenshots/traffic_light_output.png)

### Observation

The controller cycles correctly through Green, Yellow, and Red states, simulating real-world traffic light operation.

---

# 4. Sequence Detector (1011)

## Description

A sequence detector designed to identify the binary pattern 1011 from a serial input stream.

### Verilog Design

![Sequence Detector](Screenshots/sequence_detector.png)

### Testbench

![Sequence Detector TB](Screenshots/sequence_detector_tb.png)

### Output Waveform

![Sequence Detector Output](Screenshots/seq_det_output.png)

### Observation

The detector successfully recognizes the 1011 sequence and generates the detection signal at the appropriate clock cycle.

---

## Key Concepts Learned

* Finite State Machines (FSM)
* Moore Machine
* Mealy Machine
* State Encoding
* State Transition Logic
* Traffic Light Controller Design
* Sequence Detection
* Testbench Development
* Waveform Analysis

---

## Conclusion

This project provided practical exposure to FSM-based RTL design using Verilog HDL. Through simulation and waveform verification, the behavior of Moore FSM, Mealy FSM, Traffic Light Controller, and Sequence Detector circuits was successfully analyzed and validated.
---
##Author
T Gayathri
VLSI Intern
