Description
═════════════════════════════════════════════════════════════════════
* This laboratory activity demonstrates Arduino digital output 
control for IoT systems, focusing on digital signal manipulation. 
Five LEDs create a running light effect, sequentially lighting up 
from pins 8→12 then turning off 12→8, visualizing HIGH/LOW state 
transitions with
1-second delays.

═════════════════════════════════════════════════════════════════════


🎯 Objectives
Implement Arduino digital outputs for IoT component control

Apply digital signal concepts (HIGH/LOW) in sequential LED patterns

Understand timing control for visual signal flow demonstration

🧠 Concepts Applied
Digital signal states (HIGH = 5V, LOW = 0V)

pinMode(pin, OUTPUT) configuration

digitalWrite(pin, HIGH/LOW) state control

delay(ms) for timing synchronization

Sequential programming logic for chase effects

Breadboard prototyping with current-limiting resistors

💡 System Behavior
Five LEDs on digital pins 8, 9, 10, 11, 12 execute:

Forward sequence: Pin 8 HIGH → 9 HIGH → 10 HIGH → 11 HIGH → 12 HIGH (1s each)

Reverse sequence: Pin 8 LOW → 9 LOW → 10 LOW → 11 LOW → 12 LOW (1s each)

Continuous loop: 10-second full cycle repeats indefinitely

Visual effect: Left-to-right "running light" chase, then right-to-left extinguish.

Wiring: Arduino Uno pins → breadboard LEDs (colored wires: orange=8, yellow=9, green=10, blue=11, red=12) → 220Ω resistors → GND.

👥 Team Members
Team Leader: Serrona, John Mark L.

Members:

Atas, Mikkos Cepie (Score: 100)

Gito, Rhic Emmanuel (Score: 99)
