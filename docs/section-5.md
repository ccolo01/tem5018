# Section 5: Programmable Microcontrollers — Real-World Problem Solving

!!! abstract "Learning Objectives"
    By the end of this section, you will be able to:
    
    - Explain what microcontrollers are and why they matter for primary computing education
    - Describe the input-process-output model and apply it to physical computing projects
    - Use block-based programming environments to program microcontrollers
    - Design age-appropriate activities using sensors and outputs
    - Connect physical computing to cross-curricular learning objectives

---

## 5.1 Introduction: Making the Invisible Visible

In the previous sections, we explored floor robots and tangible programming interfaces—tools that execute pre-defined movements based on children's instructions. Now we take a significant step forward: **programmable microcontrollers** that can sense the real world, process information, and respond with meaningful outputs.

What makes this leap so important? Consider the world around us. Traffic lights respond to pedestrian button presses. Automatic doors sense approaching people. Smartphones adjust screen brightness based on ambient light. Fitness trackers count steps by detecting motion. All of these everyday technologies rely on embedded computers—microcontrollers—that bridge the gap between the physical and digital worlds.

When children program a microcontroller, they gain insight into how these ubiquitous systems work. They move from being passive consumers of technology to active creators who understand the principles behind the devices they use daily. This is the essence of **physical computing**: combining software and hardware to build interactive systems that sense and respond to the real world.

!!! quote "From the Research"
    "Physical computing—combining software and hardware to build interactive physical systems that sense and respond to the real world—has been shown to result in broad engagement across a spectrum of users."
    
    — Hodges et al. (2020)

For primary teachers, microcontrollers offer remarkable pedagogical opportunities. Research has consistently found that physical computing increases student engagement, creativity, and motivation compared to purely screen-based programming (Sentance et al., 2017). When children can see their code controlling a physical LED, hear a buzzer respond to their touch, or watch a motor spin based on sensor input, abstract programming concepts become concrete and meaningful.

---

## 5.2 Understanding Microcontrollers

### What Is a Microcontroller?

A **microcontroller** is a small, self-contained computer on a single integrated circuit. Unlike a full computer (like a laptop or tablet), a microcontroller is designed for specific tasks: reading inputs from sensors, processing that information according to programmed instructions, and controlling outputs like lights, sounds, or motors.

Think of a microcontroller as the "brain" of a simple electronic system. It doesn't have a screen, keyboard, or operating system of its own—instead, it's programmed from another computer and then runs independently, often powered by batteries.

### The Input-Process-Output Model

The fundamental concept underlying all microcontroller projects is the **input-process-output (IPO) model**:

```
INPUT → PROCESS → OUTPUT
(Sensors)   (Program)   (Actuators)
```

**Inputs** are ways the microcontroller gathers information from the world:

- Buttons (pressed or not pressed)
- Light sensors (bright or dark)
- Temperature sensors (hot or cold)
- Accelerometers (movement and orientation)
- Sound sensors (loud or quiet)

**Processing** is what the program does with that information:

- Makes decisions (if the button is pressed, then...)
- Performs calculations (count how many times...)
- Compares values (if brightness is less than 50, then...)

**Outputs** are ways the microcontroller affects the world:

- LEDs (turn on, off, or change colour)
- Buzzers and speakers (make sounds)
- Motors (create movement)
- Displays (show numbers, letters, or images)

This IPO model provides a powerful framework for children to understand how interactive systems work—and it applies far beyond computing, connecting naturally to science topics like senses and responses in living things.

---

## 5.3 Microcontrollers for Primary Education

Several microcontroller platforms have been designed specifically for educational use. Here we focus on those most suitable for primary schools.

### 5.3.1 BBC micro:bit

The **[BBC micro:bit](https://microbit.org/)** is one of the most widely used microcontrollers in primary and secondary education internationally. Originally developed by the BBC and partners (including Microsoft, ARM, and Lancaster University) and first distributed in 2016, the micro:bit is now managed by the Micro:bit Educational Foundation and used in over 60 countries worldwide, including Malta.

**Key features**:

- 25-LED display (5×5 grid) for showing images, animations, and scrolling text
- Two programmable buttons (A and B)
- Accelerometer (detects movement, tilt, and shaking)
- Compass (magnetometer)
- Temperature sensor
- Light sensor (using the LEDs)
- Microphone and speaker (V2 model)
- Radio communication (micro:bits can "talk" to each other)
- Bluetooth connectivity
- Edge connector for attaching external components

**Programming environments**:

- **[Microsoft MakeCode](https://makecode.microbit.org/)**: Block-based editor similar to Scratch, with option to view JavaScript code. Includes simulator for testing without hardware.
- **Python Editor**: Text-based programming for more advanced learners.
- **Scratch**: The micro:bit extension allows Scratch projects to interact with micro:bit hardware.

**Why it works for primary**:

- No additional components needed for basic projects—sensors and outputs are built in
- Free, high-quality lesson resources available
- Extensive teacher support and training
- Robust and designed for young learners
- Low cost (approximately €18-25 per unit)

### 5.3.2 Crumble Controller

The **[Crumble](https://redfernelectronics.co.uk/crumble/)** (from Redfern Electronics) is a UK-designed microcontroller specifically created for primary education, particularly for Design & Technology projects.

**Key features**:

- Four input/output terminals for connecting external components
- Can drive two motors directly (unlike micro:bit, which needs additional hardware)
- Supports "Sparkle" RGB LEDs that can be chained together
- Crocodile clip connections—no soldering or complex wiring
- Compact and robust

**Programming environment**:

- Free Crumble software (Windows, Mac, Linux, Chromebook)
- Block-based interface inspired by Scratch
- Programs transfer almost instantly, enabling rapid experimentation

**Why it works for primary**:

- Ideal for D&T projects involving motors (buggies, fairground rides, moving models)
- Very affordable (approximately €14 for controller only)
- Simple crocodile clip connections are accessible for young children
- Excellent for understanding circuits alongside programming

### 5.3.3 Comparing Options

| Feature | BBC micro:bit | Crumble |
|---------|--------------|---------|
| Built-in display | Yes (25 LEDs) | No |
| Built-in sensors | Multiple (motion, light, temp, sound) | No |
| Motor control | Needs additional hardware | Direct (2 motors) |
| Connection method | Edge connector / crocodile clips | Crocodile clips |
| Wireless | Yes (radio, Bluetooth) | No |
| Programming | MakeCode, Python, Scratch | Crumble software |
| Best for | Sensing, data, wearables, games | D&T, motors, moving models |
| Approximate cost | €18-25 | €14-18 |

**Recommendation**: The micro:bit is more versatile for general computing education due to its built-in sensors and display. The Crumble excels for D&T projects involving motors and moving mechanisms. Many schools find value in having both.

---

## 5.4 Block-Based Programming with MakeCode

Microsoft MakeCode is the recommended starting point for primary-age children programming the micro:bit. Its interface will be immediately familiar to anyone who has used Scratch.

### The MakeCode Interface

The MakeCode editor consists of:

1. **Block categories**: Colour-coded groups of blocks (Basic, Input, Music, LED, Radio, Loops, Logic, Variables, Math)
2. **Workspace**: Where you drag and assemble blocks to create programs
3. **Simulator**: A virtual micro:bit that runs your code instantly
4. **Download button**: Transfers your program to a physical micro:bit

### Key Programming Concepts in MakeCode

**Events** (when something happens):

- `on start` — runs once when the micro:bit powers on
- `on button A pressed` — runs when button A is pressed
- `forever` — runs continuously in a loop

**Outputs**:

- `show leds` — display a pattern on the LED grid
- `show string` — scroll text across the display
- `show number` — display a number
- `play melody` — play sounds (V2)

**Inputs**:

- `button A is pressed` — check if a button is pressed
- `acceleration` — read movement data
- `light level` — read ambient brightness
- `temperature` — read temperature in Celsius

**Logic** (making decisions):

- `if...then` — do something only when a condition is true
- `if...then...else` — choose between two actions

**Variables** (storing information):

- Create a variable to keep track of a score, count, or measurement

### Progression Through MakeCode

| Stage | Focus | Example Projects |
|-------|-------|------------------|
| Beginner | Outputs only | Name badge, simple animation, heart display |
| Developing | Inputs + outputs | Button-activated messages, shake to show random number |
| Intermediate | Selection (if/then) | Rock-paper-scissors, step counter, reaction game |
| Advanced | Variables + logic | Score keeper, temperature alarm, data logger |

---

## 5.5 The Crumble Programming Environment

The Crumble software uses a similar block-based approach but is optimised for controlling external components.

### Key Blocks in Crumble

**Motor control**:

- `motor 1 FORWARD at 75%` — run motor forward at specified speed
- `motor 1 STOP` — stop the motor
- `wait 1 seconds` — pause before the next instruction

**Sparkle LEDs**:

- `set sparkle 0 to red` — set an individual LED colour
- `set sparkle 0 to RGB (255, 0, 128)` — precise colour control

**Inputs**:

- `A is HI` — check if input A is high (e.g., button pressed)
- `read A` — get the analogue value from a sensor (0-255)

**Control structures**:

- `do forever` — repeat continuously
- `if...do` — conditional execution
- `repeat 5 times` — fixed repetition

### Example Crumble Project: Traffic Light Sequence

```
program start
  do forever
    set sparkle 0 to green
    wait 3 seconds
    set sparkle 0 to yellow
    wait 1 seconds
    set sparkle 0 to red
    wait 3 seconds
    set sparkle 0 to yellow
    wait 1 seconds
```

This simple program introduces sequence and timing—foundational concepts that children can then apply to more complex projects.

---

## 5.6 Age-Appropriate Progression

Physical computing can begin earlier than many teachers expect, but the complexity should match children's developmental stage.

### Years 3-4 (Ages 7-9)

**Focus**: Simple inputs and outputs, sequence, cause and effect

**Suitable projects**:

- Displaying images and animations on micro:bit LEDs
- Button-activated messages or sounds
- Simple Crumble LED sequences
- Following step-by-step instructions to create known outcomes

**Key concepts**:

- Programs are sequences of instructions
- Inputs trigger outputs
- The order of instructions matters

**Example activity**: "My Digital Badge"

Children create a micro:bit name badge that displays their name when button A is pressed and a picture when button B is pressed. This introduces events, outputs, and the connection between physical buttons and digital responses.

### Years 5-6 (Ages 9-11)

**Focus**: Selection (if/then), sensors, variables, more complex projects

**Suitable projects**:

- Nightlight that responds to light level
- Step counter using accelerometer
- Rock-paper-scissors game
- Crumble buggy that follows a line or avoids obstacles
- Temperature data logger

**Key concepts**:

- Selection: programs can make decisions
- Variables store and update information
- Sensors provide data about the environment
- Debugging: finding and fixing errors

**Example activity**: "Smart Nightlight"

Children program a micro:bit to turn its LEDs on when the room is dark and off when it's light. This requires:

1. Reading the light sensor
2. Using selection (if light level < 50, then...)
3. Controlling output (show/clear LEDs)
4. Testing and refining the threshold value

This project naturally connects to science (light, day/night) and design (what makes a good nightlight?).

---

## 5.7 Cross-Curricular Connections

Physical computing provides exceptional opportunities for cross-curricular learning because it involves real-world phenomena that children can observe, measure, and control.

### Science

**Living things and habitats**:

- Use micro:bit light/temperature sensors to investigate habitats
- Create a data logger to record environmental conditions over time
- Compare conditions in different locations (sunny/shady, inside/outside)

**Forces and motion**:

- Program a Crumble buggy and investigate how changing motor speed affects movement
- Use accelerometer data to measure the "bumpiness" of different surfaces

**Electricity**:

- Understand that the Crumble/micro:bit is part of a circuit
- Explore how adding components changes what the system can do
- Connect to learning about conductors and insulators (which materials complete a circuit?)

### Mathematics

**Data handling**:

- Collect temperature or light data over time
- Calculate averages, identify patterns
- Create graphs from sensor readings

**Number**:

- Program a times-table tester
- Create a random number generator for games
- Use variables to keep score

**Geometry**:

- Program a Crumble buggy to draw shapes (like Logo turtle graphics)
- Explore angles through motor control

### Design & Technology

**Control systems**:

- Design and make products with programmable components
- Understand how everyday products use similar systems
- Evaluate and improve designs based on testing

**Mechanisms**:

- Combine motors with levers, pulleys, and gears
- Create moving models (fairground rides, vehicles, animated scenes)

### Geography

**Weather and climate**:

- Use micro:bit as a simple weather station
- Compare temperature data from different locations
- Understand how sensors work in real weather monitoring

**Fieldwork**:

- Take micro:bits outside to collect environmental data
- Map light levels or temperatures around the school grounds

---

## 5.8 Example Activities

### Activity 1: Emotion Badge (Years 3-4)

**Learning objective**: Use button inputs to control display outputs.

**Resources**: micro:bit, computer with MakeCode, USB cable.

**Activity**:

1. Discuss: How do we show emotions? Can a micro:bit show emotions?
2. Demonstrate: Press button A → happy face; press button B → sad face
3. Children create their own emotion badge with two different emotions
4. Extension: Add a third emotion using A+B pressed together
5. Children wear their badges and demonstrate to the class

**Assessment focus**: Correct use of event blocks; understanding that buttons are inputs.

### Activity 2: Shake Counter (Years 4-5)

**Learning objective**: Use variables to count events.

**Resources**: micro:bit, MakeCode.

**Activity**:

1. Challenge: Can you create a program that counts how many times the micro:bit is shaken?
2. Introduce variables: a "box" that stores a number
3. Guide children to create a variable called "shakes"
4. On shake: add 1 to shakes, then show the number
5. Add a reset: on button A pressed, set shakes to 0
6. Test: Who can shake to exactly 10? 20?

**Assessment focus**: Correct use of variables; understanding that variables change during program execution.

### Activity 3: Smart Greenhouse (Years 5-6)

**Learning objective**: Use sensor input and selection to create an automated system.

**Resources**: micro:bit, MakeCode, optional: cardboard/plastic greenhouse model.

**Activity**:

1. Discuss: What do plants need? How do greenhouses help?
2. Challenge: Design a system that warns if conditions are wrong for plants
3. Planning: What sensor will you use? What output? What threshold?
4. Programming: If temperature > 25, show warning icon; else show tick
5. Testing: Warm the micro:bit with hands; does it respond correctly?
6. Extension: Add light level monitoring; create different warnings

**Assessment focus**: Appropriate use of selection; ability to set and test threshold values.

### Activity 4: Crumble Buggy Challenge (Years 5-6)

**Learning objective**: Program motors to navigate a course.

**Resources**: Crumble controller, motors, buggy chassis, Crumble software.

**Activity**:

1. Build: Assemble buggy following instructions
2. Explore: Test motor forward, backward, stop commands
3. Challenge 1: Program buggy to travel in a straight line for exactly 1 metre
4. Challenge 2: Program buggy to travel in a square (forward, turn, forward, turn...)
5. Challenge 3: Navigate an obstacle course
6. Evaluate: What worked? What would you change?

**Assessment focus**: Iterative design; relationship between code and physical movement; debugging.

---

## 5.9 Practical Considerations

### Equipment and Setup

**Computers**: MakeCode runs in a web browser (Chrome or Edge recommended). Crumble requires software installation. Both work on Windows, Mac, and Chromebook.

**Cables**: USB cables are needed to transfer programs. Micro USB for micro:bit V1; USB-C for V2. Have spares available.

**Batteries**: micro:bit uses 2×AAA batteries for untethered use. Crumble uses 3×AA. Rechargeable batteries are cost-effective long-term.

**Storage**: Designate clear storage for microcontrollers, cables, and accessories. Consider labelled boxes or bags for each group's equipment.

### Troubleshooting Common Issues

| Problem | Likely Cause | Solution |
|---------|--------------|----------|
| Program won't download | micro:bit not connected | Check USB connection; try different cable/port |
| micro:bit not appearing as drive | Driver issue | Use WebUSB pairing in MakeCode |
| Program doesn't do anything | Code error | Test in simulator first; check event blocks |
| Crumble not detected | Software issue | Reinstall; try different USB port |
| Motors not working | Connection issue | Check crocodile clips; check battery power |
| Erratic behaviour | Low battery | Replace/recharge batteries |

### Assessment Approaches

**Observation**: Watch children as they work—do they test and refine? Do they debug systematically?

**Documentation**: Have children save their programs and write explanations of how they work.

**Peer demonstration**: Children explain their projects to classmates.

**Design journals**: Record the design process, including failed attempts and improvements.

**Success criteria checklists**: Child-friendly lists of what the program should do.

---

## 5.10 Resources

### Official Resources

- **BBC micro:bit**: [https://microbit.org/](https://microbit.org/)
- **Microsoft MakeCode for micro:bit**: [https://makecode.microbit.org/](https://makecode.microbit.org/)
- **Crumble (Redfern Electronics)**: [https://redfernelectronics.co.uk/crumble/](https://redfernelectronics.co.uk/crumble/)
- **Scratch micro:bit extension**: [https://scratch.mit.edu/microbit](https://scratch.mit.edu/microbit)

### Lesson Resources

- **micro:bit Classroom**: [https://microbit.org/teach/](https://microbit.org/teach/) — free lesson plans, units of work, and training
- **Teach Computing Curriculum (UK-based, freely accessible)**: [https://teachcomputing.org/](https://teachcomputing.org/) — includes physical computing units adaptable for Malta
- **Crumble Projects**: [https://redfernelectronics.co.uk/category/crumble-projects/](https://redfernelectronics.co.uk/category/crumble-projects/)

### Research

- Hodges, S., Sentance, S., Finney, J., & Ball, T. (2020). Physical computing: A key element of modern computer science education. *Computer*, 53(4), 20–30.

- Sentance, S., Waite, J., Yeomans, L., & MacLeod, E. (2017). Teaching with physical computing devices: The BBC micro:bit initiative. *Proceedings of the 12th Workshop on Primary and Secondary Computing Education*, 87–96.

- Przybylla, M., & Romeike, R. (2014). Physical computing and its scope—towards a constructionist computer science curriculum with physical computing. *Informatics in Education*, 13(2), 241–254.

---

## 5.11 Summary

Programmable microcontrollers represent a significant step in children's computing education journey. They transform programming from an abstract, screen-based activity into something tangible, visible, and connected to the real world.

**Key takeaways from this section**:

1. **The IPO model is fundamental**: Input-process-output provides a framework for understanding all interactive systems, from simple classroom projects to complex real-world technology.

2. **Built-in features matter**: The micro:bit's integrated sensors and display mean children can create meaningful projects without additional components. The Crumble's motor drivers make it ideal for D&T projects.

3. **Block-based programming bridges the gap**: MakeCode and Crumble software allow children to focus on computational thinking concepts without struggling with syntax.

4. **Progression is key**: Start with outputs only, introduce inputs, then selection, then variables. Each step builds on the last.

5. **Cross-curricular connections are natural**: Physical computing inherently involves science, mathematics, and design—embrace these connections rather than treating computing in isolation.

6. **The real-world connection motivates learners**: When children see their code controlling something physical, abstract concepts become concrete and engagement increases.

As you introduce microcontrollers to your class, remember that the goal is not mastery of a particular device, but the development of computational thinking and an understanding of how the digital and physical worlds connect. These little computers are windows into the technology that shapes our world—and through them, children can begin to see themselves not just as users of technology, but as its creators.

---

!!! tip "Fieldwork Task"
    Choose one microcontroller activity from this section to try with your learners. Use the lesson planning frameworks from Section 2 to design your session, and document your experience in your reflective diary.

---

**Ready to continue?** Head to [Section 6: Mechanical Logic Toys](section-6.md) to explore computational thinking without electricity—Turing Tumble, Gravity Maze, and unplugged approaches.

---

[← Back to Section 4](section-4.md) | [Home](index.md) | [References](references.md) | [Section 6 →](section-6.md)
