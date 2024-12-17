# Washing_Machine

# Project Overview

This project implements a Washing Machine Controller using Finite State Machine (FSM) in Verilog HDL. The system transitions through various states to automate the washing machine's functions: door check, water filling, detergent addition, wash cycle, water draining, and spinning for drying. The design ensures correct state flow based on conditions like water levels, detergent presence, and timeouts.

# Features

State Management: Implements a 6-state FSM to control the washing machine:

* CHECK DOOR: Ensures the door is closed and machine is ready.
* FILL WATER: Water fills up for washing purposes.
* ADD DETERGENT: Waits until detergent is added.
* CYCLE: Wash cycle operates until timeout.
* DRAIN WATER: Drains water after the wash cycle.
* SPIN: Spins clothes for drying.

Conditions Handled:

* Door check failure or success.
* Water fill success or failure.
* Detergent added or missing.
* Cycle timeout and motor control.
* Draining water condition.

Looping/Completion: Clothes can be removed after drying or the cycle can be repeated.





