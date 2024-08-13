# Verfication-of-APB-Slave-using-SV
This repository contains the verification environment for an APB (Advanced Peripheral Bus) Slave module, developed using SystemVerilog and the Universal Verification Methodology (UVM). The primary goal of this project was to ensure that the APB Slave adhered to the protocol specifications and functioned correctly under various conditions.

Key Features:
UVM-Based Testbench: Designed a comprehensive UVM environment to drive and monitor transactions on the APB interface. This includes components such as the driver, monitor, scoreboard, and sequencer to facilitate structured and reusable verification.

Protocol Compliance: Implemented detailed checks and assertions to ensure that the APB Slave meets the required protocol standards, handling various transaction types and scenarios effectively.

Functional Coverage: Developed functional coverage models to track and measure the extent of verification, ensuring that all critical paths and edge cases were tested thoroughly.

Constrained Random Verification: Used constrained random stimulus generation to explore a wide range of input scenarios, uncovering edge cases and potential issues in the APB Slave design.

Bug Identification and Resolution: During the verification process, multiple design bugs were identified and resolved, enhancing the overall robustness and reliability of the APB Slave module.

This project serves as a solid example of applying UVM for complex SoC (System-on-Chip) verification tasks, particularly for bus protocol verification. The repository includes all relevant testbenches, UVM components, and scripts necessary to reproduce the verification results.
