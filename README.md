# Smart-Curtain-System
##🔍 Overview
The Smart Curtain System is a fully hardware-based automation project that uses digital logic gates, switches, and an LDR sensor to control curtain movement based on ambient light levels and manual inputs — all without any microcontroller.

##⚙️ System Description
This system leverages fundamental digital logic principles to manage curtain operation. It intelligently opens or closes curtains by evaluating the surrounding light and control inputs using TTL logic gates.

##🔌 Key Inputs
LDR (Light Dependent Resistor): Senses ambient light to enable automatic curtain control.
LC (Local Control): Allows manual control using a physical switch.
SO (System Override): Overrides both automatic and manual functions to force the curtain open or closed.
SC (Set Control): Additional configurable input signal.

##🧠 Logic Design
Built using AND, OR, NOR, and NOT gates (from the 7400 TTL IC series).
Logical conditions processed entirely via combinational logic.
An LED output indicates system errors or specific status conditions.

##💻 Simulation & PCB Development
✅ Simulated using Proteus to verify logic and input/output behavior.
✅ PCB layout designed with proper labeling and optimized routing.
✅ Fully constructed with TTL logic chips – no microcontroller or programming involved.

##🔧 Schematic Preview
<img width="1290" height="821" alt="Schematic" src="https://github.com/user-attachments/assets/3ffba00a-7196-4414-8bf7-f4ae6f5ce1ec" />

##🧾 PCB Layout
<img width="839" height="783" alt="2D PCB" src="https://github.com/user-attachments/assets/a2db37d2-61f2-47ba-81d5-530c7935fb58" />

##🔧 Visual Components
🖥️ Schematic Diagram: Designed to clearly illustrate logic flow and component connections.
🧾 2D PCB Layout: Professionally drawn to match real-world implementation.

##📌 System Features
🔘 100% hardware-based logic design (no software dependencies)
🌞 Intelligent light-responsive automation via LDR
🎛️ Manual and override control via switches
🎓 Ideal for educational use to demonstrate practical digital logic applications

##🧰 Tools & Software
Proteus: For simulating digital logic circuits
Altium Designer: For schematic creation and PCB design
