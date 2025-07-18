# ⚡ Classic Control Circuits – EKTS Projects

This folder contains a collection of **classic control circuit simulations** created using **EKTS (Electrical Control Techniques Simulator)**. These circuits demonstrate various industrial automation tasks such as motor control, star-delta starters, sequential operations, and timing-based logic.

Each project includes:
- ✅ `.esc` simulation file (editable in EKTS)
- 🖼️ Circuit diagram screenshot (`.png`)
- 🎞️ Animated simulation as a `.gif` (when available)
- 📄 Task description and functionality

---

## 🗂️ Circuit List

| # | Task Name | Description |
|--:|-----------|-------------|
| 1 | Start motor using 2 different push button | Motor runs by pressing either Start 1 or Start 2; stops by Stop button |
| 2 | AND Start / OR Stop Motor Control | Requires both Start buttons to run; either Stop button halts the motor |
| 3 | Sequential Start of Three Motors with Single Stop | Motors start one after another via 3 buttons; all stop together |
| 4 | Sequential Start/Stop Control for Three Motors | Each motor has its own start/stop logic |
| 5 | Parallel Motor Start with Delayed Motor 2 Stop | Both motors run together; motor 2 stops after 5s delay using On-Delay timer |
| 6 | Parallel Motor Start with Delayed Motor 2 Stop | Same as Task 5 using only off-delay timer |
| 7 | Sequential Motor Control with Auto Timed starts / Stops | Timed motor sequencing with global stop at any moment |
| 8 | Sequential Motor Control with Auto Timed starts / Stops | Modified version of Task 7 using maximum one off-delay timers |
| 9 | Motor Sequence with Conditional Switch and Delay | Timed switching of motors with conditional logic |
| 10 | Forward and Reverse Motor Control | Two start buttons for forward/reverse direction |
| 11 | Forward-Reverse with 5s Safety Lockout (Timer) | Prevents immediate switching between directions |
| 12 | Forward-Reverse with 5s Safety Lockout (Timer) | Same logic using only off-delay timers |
| 13 | Star-Delta Motor Starter with Stop at Any Time | Classic motor starter with timed transition |
| 14 | Bidirectional Star-Delta Starter with Two Start Buttons | Forward and reverse star-delta switching |
| 15 | Bidirectional Star-Delta Starter with Two Start Buttons and 5s Lockout Between Direction Change | Prevents sudden reverse after stop |
| 16 | Basic single phas induction Motor Start-Stop Control | Simple one-button start and stop logic |
| 17 | Forward and Reverse single phase induction Motor Control with Separate Stops | Forward and reverse with independent stops and interlock to prevent sudden reverse direction|
| 18 | Three-LED Traffic Cycle with Repeat Until Stop | Repeating LED sequence simulation |
| 19 | Timed Motor Pulse ON/OFF Cycle Until Stop | Auto-cycling motor control |
| 20 | Single Button Toggle Start/Stop Control | Start and stop with the same button |
| 21 | Staggered 3-Motor Start & Reverse Timed Stop | Three motors start and stop in timed reverse sequence |

---
