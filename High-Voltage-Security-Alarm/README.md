⚡ Voltage-Level Detection Alarm PCB

📌 Project Overview

The Voltage-Level Detection Alarm is an electronics-based circuit designed to detect an input voltage level and activate an audible alarm when the voltage reaches the configured detection condition.

The circuit was designed using a 555 timer, Zener diode, resistors, capacitors, and a piezoelectric buzzer. The circuit was initially simulated in Tinkercad to verify its functionality under different input voltage conditions.

Following simulation, the circuit schematic and PCB were designed using Autodesk Fusion. The PCB development process included schematic design, component placement, PCB routing, copper pouring, layer configuration, design-rule checking, error correction, silkscreen customization, and 2D and 3D PCB visualization.

After validating the PCB design and correcting the identified errors, the Bill of Materials (BOM) and fabrication files were generated and submitted to a PCB fabrication vendor.

After PCB fabrication, the assembled circuit was tested using different battery supplies to observe its alarm response under different input voltage conditions.

This project demonstrates the complete PCB development workflow, from circuit simulation and schematic design to PCB layout, design verification, fabrication, and physical hardware testing.

---

🎯 Project Objectives

- Design a voltage-level detection circuit with an audible alarm.
- Implement voltage-level detection using electronic components.
- Simulate the circuit and verify its behavior under different input voltage conditions.
- Develop a complete circuit schematic using Autodesk Fusion.
- Design and route a PCB layout.
- Perform copper pouring and configure PCB layers.
- Generate 2D and 3D PCB representations.
- Perform Electrical Rule Check (ERC) and PCB design-rule verification.
- Identify and correct design errors before fabrication.
- Customize the PCB silkscreen with project identification and my name.
- Generate a Bill of Materials (BOM) and fabrication files.
- Submit the validated PCB design for fabrication.
- Assemble and test the fabricated PCB using different battery supplies.

---

🧰 Hardware Components

Component| Purpose
555 Timer IC| Used as part of the circuit's alarm-control functionality
Zener Diode| Used in the voltage-level detection circuitry
Resistors| Used to establish circuit operating conditions
Capacitors| Used in the circuit's timing and electrical configuration
Piezoelectric Buzzer| Provides audible alarm indication
PCB| Supports the circuit components and electrical connections
Battery Supply| Provides the input voltage for circuit testing
PCB Connector| Provides the connection point for the input power supply

---

⚙️ Working Principle

The circuit is designed to respond to a configured input voltage condition.

The Zener diode forms part of the voltage-detection circuitry, while the 555 timer is used in the alarm-control section. Resistors and capacitors support the circuit's operating conditions, and the piezoelectric buzzer provides audible indication.

The circuit was evaluated under different input voltage conditions during simulation and physical testing.

- At the configured alarm-triggering condition: The circuit activates the buzzer.
- Below the configured detection condition: The buzzer remains inactive.

The circuit's behavior was first verified through simulation before proceeding to PCB design and physical implementation.

---

🧪 Circuit Simulation — Tinkercad

The circuit was first developed and simulated using Tinkercad before beginning the PCB design process.

Simulation was used to examine the circuit's behavior under different input voltage conditions and verify its intended alarm response.

Simulation Verification

- Simulated the voltage-level detection alarm circuit.
- Evaluated circuit behavior at different input voltage levels.
- Observed buzzer activation under the configured triggering condition.
- Verified the intended circuit response before proceeding to PCB development.

Simulation helped validate the circuit concept before transferring the design into the PCB design environment.

---

🖥️ PCB Design — Autodesk Fusion

After completing circuit simulation, the schematic and PCB design were developed using Autodesk Fusion.

1. Schematic Design

The circuit schematic was developed in Autodesk Fusion, incorporating the 555 timer, Zener diode, resistors, capacitors, buzzer, and required electrical connections.

The schematic served as the foundation for the PCB design and component connectivity.

2. Component Placement

The components were arranged on the PCB while considering their placement, connectivity, and board layout.

3. PCB Routing

PCB routing was performed to establish the electrical connections between the components according to the circuit schematic.

4. Copper Pouring

Copper pouring was incorporated into the PCB layout as part of the board design process.

5. Layer Configuration

The PCB layers were configured as part of the board development process to prepare the layout for fabrication.

6. Silkscreen Customization

The PCB silkscreen was customized to include my name and project identification, adding personalization and identification to the board layout.

7. 2D PCB Layout

The 2D PCB layout was developed to visualize the component arrangement, routed connections, layer configuration, and board design.

8. 3D PCB Visualization

The PCB was visualized in 3D using Autodesk Fusion to inspect the board layout and component arrangement before fabrication.

---

✅ Design Verification and Error Correction

Before submitting the PCB for fabrication, the design was checked for errors to verify its readiness for manufacturing.

Electrical Rule Check (ERC)

Electrical Rule Check (ERC) was performed to identify potential electrical connectivity and schematic-related issues.

The identified errors were reviewed and corrected as part of the design validation process.

PCB Design-Rule Checking

The PCB design was checked against the applicable design rules to identify potential layout and manufacturing-related issues.

The detected errors were reviewed and corrected before finalizing the PCB design.

Design Validation

- Performed electrical rule checking.
- Checked the PCB design against the applicable design rules.
- Identified design errors.
- Corrected the detected errors.
- Rechecked the design after making corrections.
- Finalized the design after resolving the identified errors.

Design verification helped ensure that the PCB design was prepared for the fabrication stage.

---

📋 Bill of Materials (BOM)

A Bill of Materials (BOM) was generated before submitting the PCB design for fabrication.

The BOM provides a structured list of the electronic components required for circuit assembly and serves as a reference for component procurement and PCB assembly.

Generating the BOM was part of the PCB preparation process before vendor submission.

---

🏭 PCB Fabrication Preparation

After completing the PCB design, layer configuration, design verification, and error correction, the fabrication files were prepared.

The PCB design was finalized after checking the design rules and correcting the identified errors.

Fabrication Preparation Process

- Finalized the PCB layout.
- Configured the PCB layers.
- Completed routing and copper pouring.
- Customized the silkscreen.
- Checked electrical and PCB design rules.
- Corrected identified design errors.
- Generated the Bill of Materials (BOM).
- Prepared fabrication files.
- Submitted the finalized design to a PCB fabrication vendor.

The design was submitted for fabrication after the verification process was completed.

---

🔬 Hardware Testing and Validation

After receiving the fabricated PCB, the circuit was tested using two different battery supplies through the connector provided on the PCB.

The testing was performed to observe the alarm response at different input voltage levels.

Battery Testing

Test Supply| Observed Response
9V Battery| The buzzer activated, producing an audible alarm.
3V Lithium-Ion Battery| The buzzer did not activate because the input voltage was below the configured detection threshold.

Testing Observations

- Connected the battery supply through the PCB connector.
- Tested the circuit using a 9V battery supply and observed buzzer activation.
- Tested the circuit using a 3V lithium-ion battery supply and observed that the buzzer remained inactive.
- Verified the circuit's response to the different input voltage conditions.

These tests demonstrated the circuit's threshold-dependent alarm response under the tested conditions.

The physical testing helped validate the circuit's intended functionality after PCB fabrication.

---

💻 Software and Design Tools

Tool| Purpose
Tinkercad| Circuit simulation and functional verification
Autodesk Fusion| Schematic design, PCB layout, routing, copper pouring, layer configuration, design verification, 2D layout, and 3D visualization

---

🔄 Project Workflow

Circuit Concept
      ↓
Circuit Design
      ↓
Simulation in Tinkercad
      ↓
Circuit Verification
      ↓
Schematic Design in Autodesk Fusion
      ↓
Component Placement
      ↓
PCB Routing
      ↓
Copper Pouring
      ↓
Layer Configuration
      ↓
Silkscreen Customization
      ↓
2D PCB Layout
      ↓
3D PCB Visualization
      ↓
ERC and Design-Rule Checking
      ↓
Error Identification and Correction
      ↓
Design Reverification
      ↓
BOM Generation
      ↓
Fabrication File Preparation
      ↓
PCB Fabrication
      ↓
PCB Assembly and Hardware Testing
      ↓
Battery-Based Validation

---

🧠 Concepts and Skills Learned

Through this project, the following concepts and practical skills were explored:

- Voltage-level detection
- Zener diode application
- 555 timer circuit design
- Electronic alarm circuits
- Circuit simulation
- Schematic development
- PCB design
- Component placement
- PCB routing
- Copper pouring
- PCB layer configuration
- Silkscreen customization
- 2D PCB layout
- 3D PCB visualization
- Electrical Rule Check (ERC)
- PCB design-rule checking
- Design error identification and correction
- Bill of Materials (BOM) generation
- PCB fabrication preparation
- Hardware testing
- Battery-based circuit validation
- Electronic design workflow

---

🔮 Future Improvements

Possible future improvements include:

- Adding visual alarm indication using LEDs.
- Exploring adjustable voltage detection thresholds.
- Enhancing the PCB layout for improved design efficiency.
- Incorporating additional protection features where appropriate.
- Developing a more compact PCB design.
- Improving circuit functionality and testing documentation.

---

🎯 Project Outcome

This project provided practical experience in designing an electronic circuit, validating its functionality through simulation, developing and routing a PCB, configuring board layers, performing design-rule verification, correcting errors, generating a BOM, preparing the design for fabrication, and testing the fabricated PCB using different battery supplies.

It strengthened my understanding of electronic circuit design, PCB development, fabrication preparation, design validation, and hardware implementation.

---

👩‍💻 Project Information

Project Title: Voltage-Level Detection Alarm PCB

Tools Used: Tinkercad, Autodesk Fusion

Project Domain: Electronics, Circuit Design, PCB Design

This project was developed as part of my practical learning in electronics and PCB design.
