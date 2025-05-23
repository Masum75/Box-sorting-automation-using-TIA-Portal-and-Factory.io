Box-sorting-automation-using-TIA-Portal-and-Factory.io

I have made a box sorting system that categorizes boxes based on their height using Siemens S7-1200 PLC, programmed in TIA Portal V18, and simulated using Factory I/O.

Project Overview:

-Height Detection Logic: 3 capacitive sensors were used to detect the height of the boxes.
-If 2 sensors are triggered → Box is small → Moves to the left side.
-If 3 sensors are triggered → Box is large → Moves to the right side.
-Counting System: A counter tracks the number of small and large boxes and displays the counts in real time.

Tools Used:

-TIA Portal V18 for PLC programming
-Factory I/O for 3D simulation and logic testing

Simulation vs Real-Life Implementation – Key Differences:

-Sensor Calibration: Simulated sensors respond ideally, while real sensors may require tuning.
-Timing Delays: Physical systems introduce mechanical delays and unexpected behaviors.
-Hardware Constraints: Real setups require careful wiring, mounting, and safety measures.

Limitations of Factory I/O Simulation:

-No electrical faults or noise are simulated – making it hard to test robustness of real-world systems.
-Limited component variety compared to actual industrial environments.
-No real-world material properties, like friction or weight variation, which can affect mechanical response.

This project strengthened my skills in PLC programming, sensor integration, and industrial automation design, and gave me practical insights into translating logic from simulation to real-world implementation.
