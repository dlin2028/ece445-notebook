## Entry Title: Initial Design Review - PANCAKE FLIPPER
### Date: Feb 4, 2024
### Team Members: David Lin, Jason Kim, James Lu
### Supervisor: Professor Arne Fliflet
### Teaching Assistant: Abhisheka Mathur Sekar

### Objectives
- To finalize the initial design specifications for the Pancake Flipper project.
- Address subsystem requirements and integration.

### Activities Conducted
1. **Design Review**:
    - Discussed and finalized the block diagrams for power supply, camera module, flipper module, control unit, and display module.
    - Addressed the functional overview and requirements for each subsystem, including power specifications and mechanical operations.

2. **Subsystem Analysis**:
    - Performed initial tolerance analysis for the flipper module to ensure servo motor capabilities meet the project requirements.
    - Discussed the software approach for video acquisition, image processing, and real-time control using the Raspberry Pi and microcontroller.

3. **Component Selection**:
    - Selected commercial components for servos, power supplies, and camera modules, ensuring they meet our design criteria and budget.

4. **Safety and Ethics Review**:
    - Evaluated potential safety issues and planned for UL and CE compliance.
    - Discussed ethical considerations, especially concerning data privacy and user safety.

### Equations and Formulas
1. **Torque Calculation for Flipper Servo**:
   \\[
   \\tau = (m_p + m_s + m_f) \\cdot g \\cdot (l_s + r_p)
   \\]
   Where:
   - \\( \\tau \\) = Torque needed
   - \\( m_p \\) = Mass of pancake
   - \\( m_s \\) = Mass of spatula
   - \\( m_f \\) = Mass of flipping servo
   - \\( g \\) = Acceleration due to gravity
   - \\( l_s \\) = Length of spatula
   - \\( r_p \\) = Radius of pancake

### Documentation of Testing and Debugging
- **Initial Power Supply Testing**:
    - Conducted voltage stability tests to ensure that both 12V and 5V rails deliver consistent power under load conditions.
    - Checked the thermal performance of voltage regulators under maximum expected load.

### Decisions Made
- Approved the use of the TIP120 transistor for motor control due to its high current capacity and availability.
- Decided on the LED display specifications and interfacing method with the microcontroller.

### Bibliographic References
- [Power Supply Handling](https://www.electronics-tutorials.ws/blog/power-supply.html)
- [Safety and Regulatory Compliance Guidelines](https://www.ul.com/resources/ul-safety-index)

---

### Future Actions
- Begin procurement of selected components.
- Start development on the initial software modules for camera image processing.
- Plan initial prototype assembly for subsystem testing.