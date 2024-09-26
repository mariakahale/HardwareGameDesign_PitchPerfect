# Hardware Game Design (PitchPerfect)

![FPGA](https://img.shields.io/badge/FPGA-d7bde2?style=flat-square)
![C++](https://img.shields.io/badge/C++-aed6f1?style=flat-square)
![Intel Quartus](https://img.shields.io/badge/IntelQuartus-f5b7b1?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-d5dbdb?style=flat-square)
![Modelsim](https://img.shields.io/badge/Modelsim-aed6f1?style=flat-square)
![VGA](https://img.shields.io/badge/VGA-f5b7b1?style=flat-square)

ECE241 Project - Audio recognition game using verilog, FPGA, VGA


I led my team with my final project for a Digital Systems course (ECE241)

-	Designed and implemented a musical training game, requiring players to match pitches with corresponding keys on a keyboard; using a Cyclone V FPGA programmed in Verilog for the finite state machines and the game algorithm.
-	Integrated VGA, audio output, and external memory using Intel Quartus and Modelsim to create an engaging game experience.

Our first successful attempt at displaying a .mif file onto the VGA. Don't mind the basic graphics!

<img width="437" alt="image" src="https://github.com/user-attachments/assets/c11749b1-a055-4841-b5ae-f57cde35e811"><img width="437" alt="image" src="https://github.com/user-attachments/assets/41a4ac26-f449-48ad-b05e-834813f5ebef">

We had two main finite state machines, one to handle the states for the VGA screen, and another to handle the incoming raw data from the GPIO pins from the keyboard. 




