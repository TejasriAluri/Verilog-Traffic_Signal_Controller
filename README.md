# Verilog-Traffic_Signal_Controller
A Verilog implementation of a traffic signal control system which controls the sequencing of the lights at the intersection of busy main street and a lightly used side street using a datapath and control path (FSM) architecture.
Controls a six-light traffic signal (Main/Side Red, Yellow, Green).
Implements a four-state FSM using Gray-code state encoding (00, 01, 11, 10).
Uses a vehicle sensor input (vehicle_sensor) to detect waiting cars on the side street.
Having two timers: a 25-second long timer for green light and a 4-second short timer for yellow light .
