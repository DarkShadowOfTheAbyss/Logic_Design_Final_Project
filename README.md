# Logic Design Final Project
The project develops a digital magic box system using basic principles of digital design. Rather than a traditional lock-based system, the digital magic box accepts binary inputs and generates fascinating outputs that provide a sense of digital magic. Using combinational logic components and sequential logic components, including logic gates and flip-flops, the design demonstrates that digital circuits are capable of delivering creative and interactive functionality. During the process, the project reinforces essential Boolean algebra and circuit analysis principles and demonstrates digital system creativity.
## Content


### Quartus
Contains the files of the circuit simulation and digital analysis
### Datasheet
The datasheet for each IC chip used in designing the system
### Scratch
The results of the brainstorming that led to this results
### Report
The report that holds the complete analysis of the system and the final results
###  Truth Table
The core of the analysis and the first step to create this system

## Design Choice


Outstanding Design Features Which Offer Advantages Over Alternative Designs

The design of the logic-controlled board incorporates some thoughtful choices that yield functional or practical advantages over simpler or less modular implementations. They include:

1. Modular System Architecture

	- Advantage: Dividing parts (sequence generator, register banks, control circuits) into modular blocks eases debugging, simulation, and hardware construction.

	- Alternative: A monolithic architecture would be more difficult to test and respond to changes.

2. Application of Finite State Machine (FSM) to Control Logic

	- Benefit: Using FSM allows structured control of complex sequences and behaviors (like the capless trick).

	 - Alternative: Hardwired logic would be inflexible and far harder to extend or change.

3. Timer-Based Dynamic Behavior

	- Benefit: Utilization of 4-second and 1-second timers adds interactive and timed behavior, making such things as automatic sequence detection and capless trick possible.

	- Alternative: Static control or manual reset would decrease interactivity and user engagement.

4. Practice vs Performance Mode

	- Advantage: The removable 7-segment display allows the user to switch between a learning/debugging mode and a performance mode to contribute to the illusion.

	- Alternative: Having the sequence displayed constantly would dispel the illusion for the audience.

5. Cap Detection Feature

	- Benefit: Provides an interactive "trick" that involves users and illustrates conditional logic handling.

	- Alternative: Straight switch-to-LED mapping doesn't carry this level of complexity and innovation.
 
## Setup Instructions
Build the circuit using the formulas provided in the report using the needed ICs and based on the circuit diagram provided.

📺 [Watch the demo](https://youtube.com/example_video)
