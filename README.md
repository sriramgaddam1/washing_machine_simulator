 Washing Machine Simulator using PIC16F877A

This project simulates a basic washing machine operation using the PIC16F877A microcontroller. The embedded C code is written and compiled using MPLAB X IDE with the XC8 compiler. The logic is tested and simulated using PICSimLab on the PICGenios board.
Setup Guide
Refer to the Installation Guide for detailed steps to install MPLAB X IDE, XC8 Compiler, and PICSimLab.

🔧 Tool Installation Overview
Download and install MPLAB X IDE.
Install the XC8 Compiler.
Download PICSimLab.
🛠️ Tools & Technologies Used
Microcontroller: PIC16F877A
Board: PICGenios
IDE: MPLAB X IDE
Compiler: MPLAB XC8 Compiler
Simulator: PICSimLab
📂 Folder Structure
washing-machine-simulator/ ├── source_files/ # All .c source code files ├── header_files/ # All .h header files ├── README.md # Project overview and instructions

⚙️ How to Run the Project
🧱 Step 1: Open and Build in MPLAB X IDE
Open MPLAB X IDE and create a new project or import the source and header files.
Make sure the XC8 compiler is properly installed and selected.
Use the Clean and Build Project option (hammer icon) to compile the project.
This will automatically generate a .hex file for simulation.
🧪 Step 2: Simulate in PICSimLab
Launch PICSimLab.
Select the PICGenios board.
Choose the PIC16F877A microcontroller.
Load the generated .hex file (from the dist directory of your MPLAB project).
Start the simulation and observe washing machine behavior through simulated LEDs or components.
🎯 Features
Simulates washing machine stages: Washing, Rinsing, and Spinning.
Implements time-based transitions using delay logic.
Visual feedback via LEDs.
Demonstrates embedded systems design and microcontroller programming.
📸 Demo
A Demonstration Video showing Real-Time working of the Washing Machine Simulator.
📑 License
This project is open-source and available under the MIT License.
You may use or modify it for educational or non-commercial use.

🙋‍♂️ Author
Gaddam Sriram
Final Year B.Tech Student, Computer Science and Engineering
Guru Nanak Institutions Technical Campus
