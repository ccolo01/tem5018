# Section 1: From Unplugged to Plugged — Why Physical Computing Matters

---

## 1.1 Introduction: The Next Step in Your CT Journey

Welcome to TEM5018. If you're reading this, you've already taken an important step in your professional development by completing TEM5016, where you explored computational thinking as a powerful framework for problem-solving and reasoning. You've learned that CT isn't about computers at all—it's about thinking clearly, breaking down problems, spotting patterns, and designing step-by-step solutions. You've experienced unplugged activities, tackled Bebras challenges, and begun to see how CT weaves naturally into the subjects you teach every day.

Now we take the next step.

This course is about bringing CT to life through physical computing—through robots that move across your classroom floor, programmable toys that respond to children's commands, microcontrollers that sense and react to the world, and mechanical devices that compute without electricity. Where TEM5016 gave you the conceptual foundations, TEM5018 gives you the tools to make those concepts tangible, visible, and deeply engaging for young learners.

But why "plugged" after "unplugged"? Isn't the point of unplugged activities that they work without technology? Yes—and that remains valuable. Unplugged activities will always have a place in your teaching. But there's something uniquely powerful about seeing an algorithm come to life, about watching a robot execute the exact sequence a child has planned, about debugging not on paper but in the real world where mistakes roll across the floor for everyone to see. Physical computing doesn't replace what you've learned; it extends it.

Throughout this section, we'll explore what physical computing is, why it matters pedagogically, how it connects to the CT concepts you already know, and how it integrates across the primary curriculum. We'll also address the practical realities: managing resources, organising your classroom, and assessing learning that happens through making and doing.

By the end of this section, you'll have a clear understanding of why physical computing deserves a place in your teaching toolkit—and you'll be ready to dive into the specific tools and approaches we'll explore in the sessions that follow.

---

## 1.2 What Is Physical Computing?

At its simplest, physical computing is computing that interacts with the physical world. While traditional computing happens on screens—clicking, typing, watching—physical computing reaches beyond the screen to sense, move, light up, make sounds, and respond to touch, motion, light, temperature, and more.

### The Key Components

Every physical computing system has three essential elements:

1. **Input**: Sensing the world (buttons, sensors for light, sound, motion, temperature, touch)
2. **Processing**: Making decisions based on that input (the "thinking" part—the program)
3. **Output**: Acting on the world (LEDs, motors, speakers, displays)

Consider a simple example: a micro:bit programmed as a step counter. The **input** is the accelerometer detecting motion. The **processing** is the program that counts each shake and keeps a running total. The **output** is the number displayed on the LED grid. The child wearing it sees their steps accumulate in real time—abstract counting made physical and personal.

### Beyond Screen-Based Coding

You may have encountered block-based coding environments like Scratch, where children drag and drop colourful blocks to create animations and games. This is valuable, but it remains on-screen. Physical computing takes those same programming concepts—sequences, loops, conditionals, variables—and connects them to objects that exist in the child's physical space.

When a child programs a Bee-Bot to navigate a maze, the algorithm isn't just an idea; it's a bee-shaped robot trundling across the carpet. When the sequence is wrong, the robot bumps into the wall. There's no "undo" button—just the need to think again, revise, and try once more. The feedback is immediate, concrete, and often delightfully dramatic.

### The Spectrum of Approaches

It helps to think of a spectrum, from fully unplugged to deeply embedded:

| Approach | Examples | Characteristics |
|----------|----------|-----------------|
| **Unplugged** | Bebras puzzles, human robots, paper algorithms | No technology; focuses on pure CT concepts |
| **Mechanical computing** | Turing Tumble, Gravity Maze | Physical systems that compute without electricity |
| **Tangible interfaces** | Cubetto, Scottie Go!, Osmo | Physical objects control on-screen or robotic actions |
| **Screen-based coding** | Scratch, Code.org | Programming on screen; virtual outputs |
| **Physical computing** | Bee-Bot, micro:bit, Makey Makey | Programming controls physical devices |
| **Embedded systems** | Arduino projects, smart devices | More advanced; real-world applications |

Notice that mechanical computing sits between unplugged and digital approaches. Tools like Turing Tumble use physical components—marbles, levers, gears—to perform computation. There's no electricity, no programming in the traditional sense, yet children can build working binary counters and logic gates. These tools bridge the gap between paper-based CT activities and electronic devices, making them valuable stepping stones (Berland & Wilensky, 2015).

This course explores tangible interfaces, physical computing, and mechanical computing—the middle ground where programming concepts meet the physical world in ways accessible to young children.

### A Brief History

Physical computing isn't new. Industrial robots have existed for decades, and hobbyists have tinkered with electronics since the early days of computing. But what's changed is accessibility. Devices like the BBC micro:bit were designed specifically for education, with friendly programming environments and low costs. Floor robots like Bee-Bot have been classroom staples for over 15 years. Mechanical computing toys like Turing Tumble emerged from the maker movement, bringing concepts once reserved for university computer science into primary classrooms.

Today, you don't need an engineering degree to help children build interactive projects. You need curiosity, a willingness to learn alongside your students, and some understanding of why this matters—which is exactly what we'll explore next.

!!! example "A Physical Computing System in Action"
    **The automatic nightlight**: A micro:bit with a light sensor checks the ambient light level. If it's dark, it turns on an LED. If it's bright, the LED stays off.
    
    - **Input**: Light sensor reading
    - **Processing**: "If light level < 50, then turn LED on; otherwise, turn LED off"
    - **Output**: LED on or off
    
    Even this simple system teaches conditionals, sensors, and the input-process-output model—all visible and tangible.

---

## 1.3 The Pedagogical Case for Physical Computing

Why should busy primary teachers add robots and microcontrollers to their already full plates? The answer lies in how children learn—and how physical computing aligns with what research tells us about effective education.

### Embodied Cognition: Thinking with the Body

Cognitive science increasingly recognises that thinking isn't just something that happens in the head. We think with our bodies, through movement and manipulation. When a child physically walks the path a robot will take, or manipulates tangible coding blocks with their hands, or places gears and levers on a Turing Tumble board, they're engaging more of their brain than when they simply watch or listen (Wilson, 2002).

This is particularly important for young children, whose abstract reasoning is still developing. The Swiss psychologist Jean Piaget described children up to about age 11 as being in "concrete operational" stages—they learn best through direct interaction with concrete materials. Physical computing provides exactly this: abstract programming concepts made concrete through objects they can touch, move, and observe.

### Bruner's Progression: Enactive, Iconic, Symbolic

Jerome Bruner (1966) proposed that learning progresses through three modes:

1. **Enactive**: Learning through action and physical manipulation
2. **Iconic**: Learning through images and visual representations
3. **Symbolic**: Learning through abstract symbols and language

Traditional education often jumps too quickly to the symbolic. We ask children to understand written algorithms before they've had the chance to enact them. Physical computing allows children to begin enactively—physically moving robots, pressing buttons, handling sensors, positioning marbles and levers—before progressing to iconic representations (block-based code with visual elements) and eventually symbolic understanding (text-based code, abstract algorithm notation).

A child who has spent time programming floor robots, or building logic circuits on Turing Tumble, develops an intuitive, bodily sense of what a sequence is, what happens when steps are out of order, and what debugging feels like. This embodied foundation makes later abstract learning more meaningful.

### Constructionism: Learning by Making

Seymour Papert, a mathematician and educator who worked with Piaget, developed the theory of constructionism. He argued that learning is most effective when learners are actively constructing something meaningful—something they can share, discuss, and reflect upon (Papert, 1980).

Papert created Logo, an early programming language with a "turtle" that drew shapes on screen, and he pioneered the idea of using technology not to deliver instruction but to empower children as creators. His intellectual descendants include Mitchel Resnick at MIT, whose Scratch programming language and LEGO robotics work have shaped modern educational technology.

!!! quote "From the Research"
    "The role of the teacher is to create the conditions for invention rather than provide ready-made knowledge."
    
    — Seymour Papert, *Mindstorms* (1980, p. 31)

Physical computing is constructionism in action. Children don't passively receive information about algorithms; they build robots that embody their algorithmic thinking. They construct marble-run computers that physically execute logical operations. The artefact—the programmed robot, the interactive invention, the mechanical computer—becomes a vehicle for learning and a source of pride.

### Immediate Feedback: The Power of Real Consequences

One of the most powerful features of physical computing is the immediacy of feedback. When a child runs a program on screen and it doesn't work, they see an error message or unexpected behaviour. When a child runs a program on a robot and it doesn't work, the robot might crash into a table, spin in circles, or miss its target entirely. When a child releases a marble on Turing Tumble and it doesn't follow the expected path, they see exactly where their logic went wrong.

This isn't just more dramatic—it's pedagogically valuable. The feedback is:

- **Visible**: Everyone can see what happened
- **Unambiguous**: The robot either reached the goal or it didn't; the marble either triggered the switch or it didn't
- **Non-judgmental**: The device isn't criticising; it's just following instructions or physics
- **Immediate**: There's no delay between action and consequence

This creates a natural debugging cycle. The device's behaviour reveals the gap between intention and instruction, and the child is motivated to close that gap—not because the teacher demands it, but because they want their creation to succeed.

### Motivation and Engagement

Let's be honest: robots are exciting. There's something magical about making a physical object move according to your will. Similarly, watching marbles cascade through a mechanical computer you've built, triggering switches and flipping bits, creates genuine delight. This isn't mere novelty; it's genuine engagement that can be channelled into deep learning.

Research consistently shows that physical computing activities increase student motivation, particularly among learners who might otherwise disengage from abstract or screen-based work (Sullivan & Bers, 2016). The tactile, kinetic nature of the activities appeals to diverse learners, including those who struggle with traditional approaches.

!!! tip "Harnessing Motivation"
    The excitement of physical computing is a resource, not a distraction. Channel it by:
    
    - Setting clear learning intentions that go beyond "playing with robots"
    - Building in reflection time: "What did the robot teach us about sequences?"
    - Connecting the activity to broader curriculum goals
    - Celebrating not just success, but thoughtful debugging

### What the Research Says

Studies on physical computing in primary education consistently report positive outcomes:

- **Improved CT skills**: Children using programmable robots show gains in sequencing, debugging, and algorithmic thinking (Bers, 2018; Kazakoff & Bers, 2014)
- **Transfer to other domains**: CT skills developed through robotics can transfer to mathematical problem-solving (Kazakoff, Sullivan & Bers, 2013)
- **Increased confidence**: Children, particularly girls, show increased confidence in technology after hands-on physical computing experiences (Sullivan & Bers, 2016)
- **Collaborative learning**: Physical computing naturally promotes peer collaboration and discussion (Resnick, 2017)
- **Conceptual understanding through mechanical systems**: Mechanical computing tools help children understand binary logic and computer architecture without the abstraction of electronics (Berland & Wilensky, 2015)

This isn't about replacing good teaching with gadgets. It's about adding a powerful set of tools to your repertoire—tools that align with how children learn best.

!!! question "Reflection Prompt"
    Think of a concept you find challenging to teach—perhaps something abstract in maths or science. How might making it physical (visible, tangible, interactive) help your learners grasp it?

---

## 1.4 Physical Computing and the CT Concepts You Already Know

You've spent time in TEM5016 developing a strong understanding of the four pillars of computational thinking: decomposition, pattern recognition, abstraction, and algorithmic thinking. You've applied these through unplugged activities and Bebras challenges. Now let's see how physical computing brings these same concepts to life in new ways.

### Decomposition: Breaking Down Robot Tasks

Decomposition is about breaking a complex problem into smaller, manageable parts. With physical computing, this becomes concrete and visible.

Consider a child tasked with programming a robot to navigate from one corner of a mat to another, picking up an object along the way. They can't simply say "go there"—they must break the journey into discrete steps:

1. Move forward to the first intersection
2. Turn right
3. Move forward to the object
4. Pick up the object
5. Turn left
6. Move forward to the destination

Each step is a small, solvable problem. The physical constraints of the robot—it can only move forward, turn left, turn right, etc.—force this decomposition. There's no way to cheat by giving a vague instruction.

Similarly, when children work with Turing Tumble, they must decompose the computational goal into individual components: "I need a bit to flip, which means I need a gear, which needs to be triggered by a ramp, which needs a marble to roll down it..." Each part of the problem becomes a physical piece they place on the board.

### Pattern Recognition: Spotting Repetition in Movement

Pattern recognition is about identifying similarities and regularities. In physical computing, patterns often emerge in movement and behaviour.

A child programming a robot to trace a square might initially write:

- Forward, Turn Right, Forward, Turn Right, Forward, Turn Right, Forward, Turn Right

With guidance, they recognise the pattern: "Forward, Turn Right" repeats four times. This is the foundation for understanding loops—a fundamental programming concept. The physical activity makes the pattern visible in a way that abstract discussion cannot.

On Turing Tumble, children recognise patterns in how marbles flow through different configurations. They notice that certain arrangements of gears and ramps create predictable, repeatable behaviours—the same kind of pattern recognition that underlies understanding of logic gates and binary operations.

### Abstraction: Hiding Complexity

Abstraction is about focusing on what's essential while ignoring irrelevant details. In physical computing, this happens at multiple levels:

- **The robot itself** abstracts away the electronics, motors, and engineering that make it move. The child doesn't need to understand circuits; they need to understand commands.
- **Block-based programming** abstracts away the text-based code underneath. A "move forward" block hides lines of code that control motor timing.
- **Procedures and functions** allow children to create their own abstractions: defining a "draw square" routine that can be reused without rebuilding each time.
- **Mechanical computing components** abstract complex logic into simple physical parts. A Turing Tumble gear bit abstracts the concept of a binary flip-flop into something you can see and touch.

When a child uses a "forward" block without worrying about how the motor works, they're practising abstraction. When they use a gear bit without needing to understand transistors, they're experiencing abstraction. When they create a reusable procedure for a complex manoeuvre, they're taking abstraction to a higher level.

### Algorithmic Thinking: Sequences That Control Real Objects

Algorithmic thinking is about designing precise, step-by-step instructions. With physical computing, algorithms aren't hypothetical—they control real objects with observable consequences.

This makes the requirements of good algorithms crystal clear:

- **Precision**: "Move forward a bit" doesn't work; you need "move forward 3 steps"
- **Order**: Steps must be in the correct sequence, or the robot does the wrong thing
- **Completeness**: Missing a step means the robot won't complete the task
- **Correctness**: Errors in the algorithm produce visible errors in the device's behaviour

Whether the child is programming a Bee-Bot, arranging commands on Cubetto, or positioning components on Turing Tumble, the device becomes an unforgiving but patient teacher. It does exactly what it's told—no more, no less. This reveals the gaps in children's thinking in a way that's informative rather than punitive.

### The Debugging Advantage

Perhaps nowhere is the benefit of physical computing clearer than in debugging. When an algorithm on paper has an error, finding it requires careful mental simulation. When a robot's algorithm has an error, you can see it: the robot turns left when it should turn right, overshoots its target, or stops in the wrong place. When a Turing Tumble configuration has an error, the marble takes the wrong path—and you can watch exactly where it goes astray.

This visibility transforms debugging from a frustrating search into an investigative process:

1. **Observe**: What did the device actually do?
2. **Compare**: What did I expect it to do?
3. **Locate**: At what step did it go wrong?
4. **Hypothesise**: Why might that step be incorrect?
5. **Revise**: Change the algorithm or configuration
6. **Test**: Run it again and observe

This cycle—which mirrors scientific method and design thinking—becomes natural when the subject of investigation is a physical device rather than lines of code on a screen.

!!! example "CT Concepts in a Bee-Bot Maze Activity"
    **Task**: Program a Bee-Bot to navigate from Start to Finish on a grid mat, avoiding obstacles.
    
    - **Decomposition**: The journey is broken into individual steps (forward, forward, turn left, forward...)
    - **Pattern recognition**: "I turn left, then go forward twice to get around each obstacle—that's a pattern!"
    - **Abstraction**: The child focuses on the path, not on how the Bee-Bot's motors work
    - **Algorithmic thinking**: The sequence must be precise, complete, and correctly ordered
    - **Debugging**: When the Bee-Bot hits an obstacle, the child identifies which step was wrong and revises

!!! example "CT Concepts in a Turing Tumble Challenge"
    **Task**: Build a configuration that counts in binary from 0 to 7.
    
    - **Decomposition**: Break the problem into sub-problems—how does one bit flip? How do carries work?
    - **Pattern recognition**: Notice that the rightmost bit flips every marble, the next bit every two marbles, and so on
    - **Abstraction**: Each gear bit abstracts a binary digit; you don't need to think about electronics
    - **Algorithmic thinking**: The sequence of components must be precisely arranged to produce correct counting
    - **Debugging**: When the count goes wrong, watch where the marble went and adjust the configuration

---

## 1.5 Beyond CT: What Physical Computing Adds

While physical computing is a powerful vehicle for CT, it offers additional benefits that extend beyond the four pillars. These additional dimensions make physical computing valuable not just for computing education, but for broader educational goals.

### Design Thinking and Iterative Prototyping

Physical computing naturally invites design thinking—a human-centred approach to problem-solving that emphasises empathy, ideation, prototyping, and iteration (IDEO, 2012).

When children create physical computing projects, they often begin with a problem: "How can we make a nightlight that turns on automatically?" They brainstorm solutions, build prototypes, test them, gather feedback, and refine their designs. This cycle—build, test, reflect, improve—mirrors the processes used by engineers, designers, and innovators.

Unlike paper-based planning, physical prototypes provide real feedback. The nightlight works or it doesn't. The robot reaches its goal or it doesn't. The marble follows the intended path or it doesn't. This grounds design thinking in concrete reality.

### Systems Thinking: Inputs, Processes, Outputs, and Feedback

Physical computing introduces children to systems thinking—understanding how components interact within a larger whole.

Every physical computing project is a system:

- **Inputs**: Sensors, buttons, user actions, or (in mechanical computing) the release of a marble
- **Processes**: The program's logic and decisions, or the mechanical path through gears and ramps
- **Outputs**: Motors, LEDs, sounds, displays, or the final position of marbles and bits
- **Feedback**: Information that loops back (e.g., a sensor reading that affects subsequent behaviour, or a gear that triggers the next stage)

Understanding systems is crucial in our interconnected world. From ecosystems to traffic flow to the human body, systems thinking helps children make sense of complexity. Physical computing provides a hands-on entry point.

!!! example "Systems Thinking with a Traffic Light Project"
    A simple traffic light project using LEDs and a micro:bit illustrates systems thinking:
    
    - **Inputs**: Timer, or a button press from a "pedestrian"
    - **Process**: A sequence that cycles through red, amber, green (and responds to button presses)
    - **Outputs**: Red, amber, and green LEDs lighting in sequence
    - **Feedback**: The pedestrian button creates a feedback loop that modifies the timing
    
    Children learn that systems have interacting parts, that changing one part affects others, and that feedback loops create dynamic behaviour.

!!! example "Systems Thinking with Turing Tumble"
    A binary counter on Turing Tumble demonstrates mechanical systems thinking:
    
    - **Inputs**: Marbles released from the top
    - **Process**: Marbles flow through ramps and gears, each gear representing a binary bit
    - **Outputs**: The final state of the gear bits (showing the binary count)
    - **Feedback**: Each gear's state affects how it directs the next marble
    
    Children see that simple components, connected in the right way, create complex behaviour—the essence of how computers work.

### Tinkering and Productive Failure

Physical computing invites tinkering—playful, exploratory experimentation without a fixed outcome. This is distinct from following instructions or completing a pre-defined task (Resnick & Rosenbaum, 2013).

When children tinker, they ask "what if?" questions:

- What if I add another sensor?
- What if I change the timing?
- What if I combine two programs?
- What if I rearrange these gears?

Tinkering leads to unexpected discoveries and, inevitably, to failure. But failure in physical computing is productive: the robot that spins wildly reveals something about the code; the sensor that doesn't respond reveals something about connections; the marble that goes the wrong way reveals something about the configuration. These "failures" become learning opportunities.

In a culture that often stigmatises mistakes, physical computing provides a safe space for productive failure. The device isn't judging; it's just revealing the truth about the algorithm or design.

### Creativity and Self-Expression

Physical computing is a creative medium. Children don't just follow instructions; they express their ideas, tell stories, solve problems that matter to them, and make things they're proud of.

A child might program a robot to perform a dance, create a musical instrument from fruit and Makey Makey, build an automatic watering system for classroom plants, or design a Turing Tumble puzzle for classmates to solve. These projects reflect the child's interests and creativity while developing CT skills.

Mitchel Resnick argues that the best learning happens when children work on projects they're passionate about:

!!! quote "From the Research"
    "When students work on projects they're passionate about, they're willing to work longer and harder, and they learn more in the process."
    
    — Mitchel Resnick, *Lifelong Kindergarten* (2017, p. 14)

### Collaboration: Physical Projects Demand Teamwork

Physical computing projects often require collaboration. There are physical resources to share, problems that benefit from multiple perspectives, and tasks that are easier with multiple hands.

Unlike individual screen-based work, physical computing naturally promotes:

- **Division of labour**: One child programs while another tests; one places components while another releases marbles
- **Peer teaching**: Children help each other with tricky concepts
- **Shared problem-solving**: Debugging together, brainstorming solutions
- **Communication**: Explaining ideas, defending decisions, resolving disagreements

These collaborative skills are valuable far beyond computing. They're life skills that physical computing develops organically.

### Real-World Relevance

Finally, physical computing connects classroom learning to the real world. We're surrounded by physical computing: automatic doors, traffic lights, fitness trackers, smart speakers, robotic vacuum cleaners. When children program a robot or build a sensor project, they're glimpsing the technology that shapes their daily lives.

Mechanical computing tools like Turing Tumble connect to an even deeper relevance: they show how computation itself works, not through magic or electricity, but through simple physical principles. A child who has built a binary counter from gears and marbles has a concrete understanding of what computers actually do.

This relevance has motivational power. It also opens conversations about technology's role in society: Who makes these decisions? How do we want technology to work? What are the ethical implications? These are important discussions for future citizens.

!!! question "Reflection Prompt"
    Beyond CT skills, what other educational goals could physical computing support in your classroom? Consider skills like collaboration, resilience, creativity, or communication.

---

## 1.6 Integrating Physical Computing Across the Primary Curriculum

One of the most important messages of this course is that physical computing shouldn't exist in isolation. It's not a separate "computing" lesson disconnected from the rest of the curriculum—it's a tool that can enrich learning across subjects. This integration is especially important in primary education, where you often teach multiple subjects and can create meaningful connections between them.

Let's explore how physical computing integrates with different curriculum areas, with concrete examples for each.

### Mathematics

Physical computing is deeply mathematical. The connections include:

- **Measurement and estimation**: How far does the robot need to travel? How many centimetres is one "step"?
- **Angles and direction**: Turning 90 degrees for a right angle; understanding quarter, half, and full turns
- **Coordinates and position**: Grid mats use coordinate systems; robots move through positions
- **Number and counting**: Counting steps, keeping score, calculating distances, binary counting on Turing Tumble
- **Data handling**: Collecting sensor data, creating graphs, interpreting readings
- **Time and duration**: How long does each movement take? Timing sequences
- **Shape and space**: Programming robots to draw shapes; exploring properties of shapes
- **Logic and reasoning**: Binary logic with mechanical computing; conditional statements

!!! example "Maths Activity: Exploring Perimeter with Pro-Bot"
    Challenge children to program Pro-Bot to draw different rectangles with the same perimeter.
    
    - "Draw a rectangle with perimeter 40cm. Now draw a different rectangle, also with perimeter 40cm."
    - Children must calculate side lengths and translate them into movement commands
    - Connects programming to mathematical reasoning about perimeter
    - Extension: Which rectangle has the largest area? (Introduces optimisation)

!!! example "Maths Activity: Binary Numbers with Turing Tumble"
    Use Turing Tumble to explore place value and binary numbers.
    
    - Build a simple binary counter with gear bits
    - Release marbles one by one and record the binary state after each
    - Convert binary readings to decimal
    - Connects physical manipulation to abstract number representation
    - Extension: Can you predict what state the counter will show after 10 marbles?

### Science

Physical computing aligns beautifully with scientific inquiry:

- **Variables and fair testing**: Changing one input while keeping others constant
- **Observation and recording**: Collecting sensor data, documenting robot behaviour
- **Cause and effect**: If I program this, then the robot does that; if I place this gear here, the marble goes there
- **Prediction and testing**: Hypothesising what will happen, then testing
- **Data collection**: Using sensors to measure light, temperature, sound, motion
- **Forces and motion**: How robots move, friction, speed, direction; gravity-powered marble runs
- **Living things**: Modelling animal behaviour, habitats, life cycles
- **Simple machines**: Levers, ramps, and gears in mechanical computing

!!! example "Science Activity: Plant Moisture Monitor with micro:bit"
    Connect a moisture sensor to a micro:bit to monitor soil moisture for classroom plants.
    
    - **Scientific inquiry**: What moisture level do our plants need? How does it change over time?
    - **Data collection**: Recording moisture readings at different times of day
    - **Variables**: What affects moisture? (Watering, evaporation, sunlight)
    - **CT connection**: Programming the micro:bit to display warnings when moisture is low
    - **Extension**: Automate watering with a pump (more advanced)

!!! example "Science Activity: Forces and Motion with Gravity Maze"
    Use Gravity Maze to explore how gravity, ramps, and angles affect motion.
    
    - **Scientific inquiry**: How does the steepness of a ramp affect how far the marble travels?
    - **Variables**: Angle of ramp, height of drop, path length
    - **Prediction and testing**: "I predict the marble will reach this tower because..."
    - **CT connection**: The puzzle solutions require logical sequencing and spatial reasoning
    - Connects physical science concepts to computational thinking

### Literacy

Physical computing can enhance reading, writing, speaking, and listening:

- **Instructional writing**: Writing clear, precise instructions (like algorithms)
- **Sequencing narratives**: Programming robots to act out stories in order
- **Vocabulary development**: Technical vocabulary in meaningful contexts
- **Speaking and listening**: Explaining programs, collaborative discussion, presenting projects
- **Storytelling**: Creating interactive stories, robot characters, narrative journeys
- **Reading comprehension**: Following written instructions, understanding documentation

!!! example "Literacy Activity: Story Sequencing with Bee-Bot"
    Create a mat showing scenes from a familiar story (e.g., *The Very Hungry Caterpillar*).
    
    - Children program Bee-Bot to visit each scene in the correct story order
    - Reinforces sequencing, a key reading comprehension skill
    - Children write programs, developing instructional writing skills
    - Extension: Children create their own story mats and challenge classmates

### Art and Design

Physical computing opens creative possibilities:

- **Interactive art**: Installations that respond to viewers
- **Kinetic sculpture**: Art that moves
- **Sound art**: Musical instruments, soundscapes, programmed compositions
- **Design process**: Ideation, prototyping, iteration, refinement
- **Digital art**: LED displays, programmed light patterns
- **Craft and making**: Combining physical computing with traditional crafts
- **Puzzle design**: Creating challenges for others to solve (e.g., Turing Tumble puzzles)

!!! example "Art Activity: Musical Instruments with Makey Makey"
    Create musical instruments from everyday objects using Makey Makey.
    
    - Children design and build instruments from fruit, foil, play dough, or drawn graphics
    - Connect to Scratch to create custom sounds and interactions
    - Explores circuits (conductivity), design, music, and programming
    - Children perform compositions for the class

### Geography and History

Physical computing can bring geography and history to life:

- **Mapping and navigation**: Programming robots to follow routes on maps
- **Direction and compass points**: North, south, east, west through robot movement
- **Scale and distance**: Understanding scale when planning robot journeys
- **Historical simulations**: Recreating historical journeys or events
- **Local geography**: Creating mats based on local maps, navigating familiar places

!!! example "Geography Activity: Journey Around Malta with a Floor Robot"
    Create a mat showing a simplified map of Malta.
    
    - Children program robots to travel between locations: "Start in Valletta, visit Mdina, then travel to Marsaxlokk"
    - Reinforces geographical knowledge while developing CT skills
    - Discuss cardinal directions, relative position, distance
    - Extension: Add challenges ("Avoid the road works at Mosta")

### Music

Beyond the Makey Makey instruments mentioned above, physical computing connects to music through:

- **Rhythm and timing**: Programming sequences with specific timing
- **Composition**: Creating musical patterns, loops, and variations
- **Sound and vibration**: Exploring how sounds are made with speakers and buzzers
- **Musical notation**: Parallels between musical scores and algorithms (both are sequences of instructions)

### Physical Education

Even PE can incorporate physical computing:

- **Movement and timing**: Robots that require physical movement to control
- **Measuring physical activity**: Step counters, heart rate monitors
- **Spatial awareness**: Navigating through physical spaces
- **Reaction games**: Physical computing games that require quick responses

### Choosing Your Integration Points

You don't need to integrate physical computing into every subject, every week. Start with natural connections:

- Where do you already teach sequencing, algorithms, or logical thinking?
- Which subjects involve measurement, data, or cause and effect?
- Where could hands-on, creative projects enhance engagement?
- What topics might benefit from making abstract concepts concrete?

!!! tip "Integration Strategies"
    - **Start small**: One cross-curricular project per term is a great beginning
    - **Look for natural fits**: Maths measurement, science fair testing, literacy sequencing
    - **Collaborate**: Work with colleagues to plan cross-curricular projects
    - **Let children lead**: Their interests can suggest integration points
    - **Document and share**: Keep notes on what works for future reference

| Curriculum Area | Physical Computing Tools | Key Connections |
|-----------------|--------------------------|-----------------|
| Mathematics | Floor robots, micro:bit, Turing Tumble | Measurement, angles, coordinates, data, binary |
| Science | Sensors, micro:bit, data logging, Gravity Maze | Variables, observation, cause/effect, forces |
| Literacy | Bee-Bot story mats, any tool | Sequencing, instruction writing, narrative |
| Art & Design | Makey Makey, LEDs, motors, all tools | Interactive art, design process, creativity |
| Geography | Floor robots with map mats | Navigation, direction, scale |
| Music | Makey Makey, micro:bit, speakers | Rhythm, composition, sound |
| PE | Wearables, motion sensors | Movement, spatial awareness |

!!! question "Reflection Prompt"
    Choose one topic you'll be teaching in the coming weeks. How might physical computing enhance that topic? What tool might you use? What would children create or explore?

---

## 1.7 Choosing the Right Tool for the Right Purpose

Throughout this course, you'll encounter a range of physical computing tools. It's tempting to focus on the tools themselves—their features, how they work, what they can do. But effective teaching starts not with tools but with learning outcomes. The question isn't "What can this robot do?" but "What do I want my learners to learn, and which tool best supports that?"

### Overview of Tool Categories

We'll explore each of these categories in depth in later sections, but here's an overview:

**Floor Robots** (Section 2)

- Examples: Bee-Bot, Blue-Bot, Pro-Bot, Thymio, LEGO WeDo
- Characteristics: Move through physical space; programmed via buttons or screen
- Best for: Sequencing, direction, spatial reasoning, early algorithms
- Age range: Works well from Early Years through primary

**Tangible Programming Interfaces** (Section 3)

- Examples: Cubetto, Scottie Go!, Kubo, Osmo Coding, Blue-Bot TacTile, mTiny
- Characteristics: Physical blocks, tiles, or objects control the robot or screen
- Best for: Pre-readers, tactile learners, collaborative programming
- Age range: Especially strong for Early Years and lower primary

**Programmable Microcontrollers** (Section 4)

- Examples: BBC micro:bit, CodeBug, Arduino
- Characteristics: Small computers with sensors, LEDs, and expansion options
- Best for: Input-process-output concepts, data, sensors, upper primary
- Age range: Most suitable from around Year 3/4 upward

**Mechanical Logic Toys** (Section 5)

- Examples: Turing Tumble, Gravity Maze, Code Master
- Characteristics: No electricity; logic through mechanical systems
- Best for: Pure logical thinking, understanding how computation works, puzzle-solving, accessible introduction to binary and logic gates
- Age range: Varies by complexity; Gravity Maze from Year 1, Turing Tumble from Year 3+

### The "Low Floor, High Ceiling, Wide Walls" Principle

Mitchel Resnick's research group at MIT popularised this useful framework for evaluating educational tools (Resnick et al., 2009):

- **Low floor**: Easy to get started; accessible to beginners
- **High ceiling**: Room to grow; supports complex, sophisticated work
- **Wide walls**: Supports many different types of projects; not just one path

The best tools score well on all three dimensions. Bee-Bot has a low floor (even 4-year-olds can press the buttons) but a relatively low ceiling (limited commands, no sensors). The micro:bit has a low floor (MakeCode is beginner-friendly) but also a high ceiling (it can support quite complex projects) and wide walls (music, games, wearables, science, and more).

Turing Tumble offers an interesting profile: a moderate floor (requires some spatial reasoning to get started), a surprisingly high ceiling (you can build functioning binary computers), but narrower walls (it's primarily for logic and computing concepts). This makes it exceptionally good at its specific purpose.

Consider what matters for your context:

- For Early Years, floor is everything—it must be immediately accessible
- For upper primary, ceiling matters more—you want room for challenge and extension
- For cross-curricular work, walls matter—you need flexibility
- For teaching computing concepts specifically, a focused tool like Turing Tumble may be ideal

### Factors to Consider When Choosing Tools

**Age and developmental stage**

- Early Years: Large buttons, tangible input, visual output, immediate feedback
- Lower Primary: Simple sequences, floor robots, beginning block-based coding, simple mechanical puzzles
- Upper Primary: More complex algorithms, sensors, data, longer projects, Turing Tumble logic challenges

**Learning outcomes**

- Teaching sequencing? Floor robots work beautifully
- Exploring data? Microcontrollers with sensors
- Understanding how computers work? Mechanical logic toys
- Developing logical reasoning? Both robots and mechanical computers
- Fostering creativity? Open-ended tools like Makey Makey

**Curriculum connections**

- Match tools to subjects: e.g., floor robots for maths/geography, sensors for science, Turing Tumble for maths/computing

**Resource constraints**

- Cost: What's your budget? (Turing Tumble and Gravity Maze can be more affordable than class sets of robots)
- Quantity: How many devices can you afford? (Affects pedagogy—whole class vs. rotations)
- Maintenance: Who manages batteries, repairs, updates? (Mechanical toys have no batteries!)

**Technical requirements**

- Does it need internet? Tablets? Computers?
- How much setup time is required?
- What happens when things go wrong? (They will!)

**Your own confidence**

- Start with tools you find manageable
- Build confidence before adding complexity
- It's okay to learn alongside your students

### Avoiding Tool-First Thinking

Here's a common trap: "I've got a class set of micro:bits—what can I do with them?"

This reverses the proper order. Better: "I want to teach my children about light and shadows in science. Could micro:bits help?" (Yes—the light sensor could measure light levels in different conditions. Or perhaps simple experiments without technology are sufficient.)

Similarly: "I want children to understand how counting in binary works. What tool would help?" (Turing Tumble makes binary counting physical and visible—an excellent match.)

!!! tip "Learning-First Planning"
    1. Start with your learning intentions: What do you want children to know, understand, or be able to do?
    2. Consider whether physical computing adds value: Will it make the learning more concrete, engaging, or effective?
    3. If yes, choose the simplest tool that supports your intentions
    4. Design the activity around the learning, not the tool
    5. Ensure the tool enhances rather than distracts from the learning

!!! question "Reflection Prompt"
    Think about the learning outcomes you most want to achieve with your class. Which physical computing tools might support those outcomes? What factors would influence your choice?

---

## 1.8 Practical Considerations for the Primary Classroom

Physical computing is exciting, but let's be realistic: it also introduces practical challenges. Devices need charging. Things break. Sessions take longer to set up. Children get distracted by the novelty. Effective physical computing teaching requires attention to classroom management and organisation.

### Managing Physical Resources

**Storage**

- Dedicate a clear space for physical computing resources
- Labelled boxes or trays for each type of device
- Visible, accessible storage encourages use
- Consider: who is responsible for returns?
- Mechanical toys like Turing Tumble: store with pieces sorted and boards flat

**Charging**

- Establish charging routines (overnight? over weekends?)
- Visual indicators: charged devices here, charging devices there
- Spare batteries for emergencies
- Check charge before sessions begin
- Note: Mechanical logic toys need no charging—always ready!

**Maintenance**

- Regular checks: do all devices work?
- Simple repair kits (screwdrivers, spare batteries)
- Reporting system: "This Bee-Bot isn't working" notes
- Know who to contact for serious repairs
- Turing Tumble: check for lost pieces, ensure board is level

**Quantity management**

- Inventory: know what you have
- Booking system if shared across classes
- Clear expectations for borrowing and returns

### Classroom Organisation

**Whole-class instruction**

- Useful for introductions, demonstrations, and shared discussions
- Visualiser or document camera to show small devices to the whole class
- Limited hands-on time; risk of passive watching

**Small-group rotations**

- Multiple activities running simultaneously; physical computing as one station
- Children cycle through; each group gets hands-on time
- Requires clear instructions at each station; often needs adult support

**Pairs or threes**

- One device per 2-3 children
- Encourages collaboration, discussion, peer teaching
- Clear role rotation: programmer, tester, recorder

**Individual work**

- Each child has a device (or each pair)
- Maximum hands-on time
- Requires sufficient resources; potential for isolation

!!! tip "The Sweet Spot: Pairs"
    For most primary classrooms, pairs work best:
    
    - Collaboration is built in
    - Resources stretch further
    - Children learn from each other
    - One can "drive" while the other "navigates"
    - Regular role swaps maintain engagement
    
    This works for robots, tablets, AND mechanical toys like Turing Tumble—one child places pieces while the other plans the next move.

### Time Management

Physical computing sessions take longer than you might expect. Build in time for:

- **Setup**: Getting devices out, checking they work, distributing materials (5-10 minutes)
- **Introduction**: Explaining the task, reviewing relevant concepts, demonstrating (5-10 minutes)
- **Activity**: The core hands-on time (20-40 minutes depending on task)
- **Reflection**: Discussing what happened, what was learned, what was challenging (5-10 minutes)
- **Pack-away**: Returning devices, tidying, checking nothing is missing (5-10 minutes)

A "quick 30-minute activity" often needs 45-50 minutes in reality. Plan accordingly.

### Health and Safety

Physical computing is generally safe, but consider:

- **Small parts**: Some kits have small components (choking hazard for youngest children); Turing Tumble marbles require supervision with younger children
- **Batteries**: Teach safe handling; no licking! Watch for battery compartment access
- **Cables**: Trip hazards; keep organised
- **Supervision**: Floor robots moving around require attention; marbles can roll away
- **Hygiene**: Devices pass through many hands; cleaning routines
- **Screen time**: Balance physical computing with other activities (mechanical toys help here—no screens!)

### Inclusion and Accessibility

Physical computing should be accessible to all learners:

- **Motor difficulties**: Consider button size, alternative input methods, partner support
- **Visual impairment**: Sound-based feedback, high-contrast displays, tactile interfaces
- **Hearing impairment**: Visual feedback, text instructions, buddy systems
- **Cognitive differences**: Simpler tasks, step-by-step support, extended time
- **Diverse learners**: Multiple entry points, choice in projects, varied outcomes

Tangible interfaces and mechanical computing tools can be particularly inclusive—they don't require reading, work well for kinesthetic learners, and provide immediate visual/tactile feedback. Consider which tools work best for which learners.

### Working Within Resource Constraints

What if you only have three Bee-Bots for a class of 25?

- **Rotation stations**: Bee-Bot activity is one of five stations
- **Demonstration with participation**: Show the class, invite children up to participate
- **Unplugged parallels**: Paper-based Bee-Bot planning while waiting for the real thing
- **Loan and share**: Negotiate sharing with other classes
- **Prioritise**: Some topics particularly benefit; use devices for those
- **Mix tools**: Use cheaper mechanical puzzles alongside more expensive robots

Limited resources don't mean no resources. Creative organisation extends what you have. One Turing Tumble can serve a whole class through rotation, with children working on paper-based challenges while waiting for their turn.

!!! tip "Five Routines That Make Sessions Run Smoothly"
    
    1. **"Check and report"**: At session start, each pair checks their device works and reports any problems
    2. **"Freeze and focus"**: A signal (hand up, chime, phrase) for stopping and listening—essential when children are absorbed
    3. **"Park and share"**: At intervals, pause for pairs to share discoveries or problems
    4. **"Clean and count"**: At session end, clean devices and count to ensure nothing is missing (especially important for mechanical toys with many pieces!)
    5. **"What did you learn?"**: Never end without a brief reflection—even 2 minutes makes a difference

---

## 1.9 Assessment in Physical Computing Contexts

How do you know if children are learning through physical computing? Traditional tests don't capture the kind of learning that happens when children are programming robots and building interactive projects. You need assessment approaches that match the hands-on, process-oriented nature of the work.

### Why Traditional Tests Fall Short

Physical computing develops skills that are difficult to assess with pencil-and-paper tests:

- **Process skills**: How children approach problems, not just final answers
- **Debugging**: Responding to failure, revising strategies
- **Collaboration**: Working with others, explaining ideas
- **Creativity**: Novel solutions, personal expression
- **Persistence**: Sticking with challenges, trying multiple approaches

A child might struggle on a written CT test but demonstrate brilliant debugging skills with a real robot. Another might answer test questions correctly but fall apart when facing an open-ended physical challenge. Assessment must capture the richness of the learning.

### Process Over Product

In physical computing, the process often matters more than the product. A child whose robot doesn't reach the goal but who shows systematic debugging, clear reasoning, and persistent effort may have learned more than a child whose robot succeeds by lucky guessing. A child whose Turing Tumble configuration doesn't quite work but who can explain their reasoning and identify where it went wrong is demonstrating deep understanding.

This requires shifting your focus:

- Not just "Did the robot complete the task?" but "How did the child approach the problem?"
- Not just "Is the code correct?" but "Can the child explain their thinking?"
- Not just "Did they succeed?" but "What did they learn from failures?"

### Observation and Documentation

Your most powerful assessment tool is observation. Watch children as they work:

- How do they plan before programming?
- How do they respond when things go wrong?
- Do they test systematically or randomly?
- How do they collaborate with partners?
- Can they explain what they're doing and why?
- Do they spot patterns and apply them to new situations?

Document what you observe:

- **Notes**: Brief observations during or after sessions
- **Photographs**: Children's work, their setups, screen captures, Turing Tumble configurations
- **Videos**: Short clips of children programming, explaining, debugging
- **Audio**: Children explaining their thinking
- **Work samples**: Programs, planning sheets, written reflections

### Formative Assessment Strategies

**Questioning**

Ask open questions that reveal thinking:

- "What are you trying to make the robot do?"
- "What did you expect to happen? What actually happened?"
- "How will you fix it?"
- "What's the tricky part?"
- "What would you do differently next time?"
- "Can you explain why the marble went that way?"

**Think-alouds**

Ask children to verbalise their thinking as they work. This reveals their reasoning and helps them become aware of their own strategies.

**Peer feedback**

Children observe and comment on each other's work:

- "I noticed you tried lots of different things before it worked."
- "I didn't understand why you used a loop there—can you explain?"
- "I really like how you solved that problem—can you show me again?"

**Self-assessment**

Simple prompts for children to reflect:

- "What did I find tricky today?"
- "What would I do differently next time?"
- "What am I proud of?"
- "What do I want to learn more about?"

### Rubrics for CT in Action

A simple rubric can help focus observation. Here's an example framework:

| Skill | Beginning | Developing | Secure |
|-------|-----------|------------|--------|
| **Planning** | Starts without a plan | Has a vague plan | Plans systematically before starting |
| **Sequencing** | Steps often out of order | Mostly correct sequences | Accurate sequences with awareness of order |
| **Debugging** | Gives up or random changes | Makes some logical changes | Systematically identifies and fixes errors |
| **Explaining** | Cannot explain choices | Basic explanations | Clear explanations with reasoning |
| **Collaboration** | Works alone; little sharing | Some collaboration | Effective teamwork and communication |

This isn't for grading every child every session—it's a lens for noticing and noting significant observations.

### Capturing Evidence

For your TEM5018 fieldwork (and for ongoing classroom practice), you'll need to document children's learning. Consider:

- **Learning journals**: Children write or draw about their experiences
- **Exit tickets**: Quick end-of-session reflections ("One thing I learned, one thing I'm wondering")
- **Photo evidence**: Annotated photographs showing process and products
- **Video clips**: Brief recordings of children explaining their work
- **Portfolio samples**: Key pieces of work over time showing progression

!!! tip "Quick Evidence Capture"
    Keep your phone or tablet handy for quick snaps and clips:
    
    - Photograph a child's planning sheet next to their completed program
    - Take a 30-second video of a child explaining their debugging process
    - Capture a screenshot of a completed program
    - Record audio of pair discussions during problem-solving
    - Photograph a Turing Tumble configuration with the child explaining their solution

### Avoiding Over-Assessment

A word of caution: don't let assessment squeeze out the joy. Physical computing should be playful, creative, and exploratory. If children feel constantly observed and evaluated, they may become risk-averse and stop experimenting.

Balance formative assessment with genuine open-ended play. Not every session needs formal observation. Sometimes the most valuable learning happens when children are simply given time, tools, and permission to explore.

!!! question "Reflection Prompt"
    How do you currently assess hands-on, practical learning in your classroom? What strategies might transfer to physical computing? What new approaches might you need?

---

## 1.10 Looking Ahead: Your Journey Through This Course

You've now explored the foundations of physical computing and its place in primary education. You understand what physical computing is, why it matters, how it connects to CT, and how it integrates across the curriculum. You've considered practical issues of classroom management and assessment.

Now it's time to get hands-on.

### What's Coming Next

**Section 2: Robots in the Classroom**

We'll explore floor robots like Bee-Bot, Pro-Bot, and Thymio. You'll learn how these simple devices teach sequencing, debugging, and spatial reasoning—and how to integrate them into maths, literacy, and geography.

**Section 3: Tangible Interfaces**

We'll examine tools where programming happens through physical manipulation: Cubetto, Scottie Go!, Makey Makey, Osmo, and more. These are particularly powerful for young children and tactile learners.

**Section 4: Programmable Microcontrollers**

We'll dive into the BBC micro:bit and related devices. You'll explore sensors, data, and more complex programming—opening up science, design, and creative projects.

**Section 5: Mechanical Logic Toys**

We'll investigate tools like Turing Tumble and Gravity Maze that teach computational concepts through mechanical systems—no electricity required. You'll discover how marbles and gears can teach binary, logic gates, and algorithmic thinking in uniquely concrete ways.

**Section 6: Designing and Assessing Lessons**

We'll consolidate everything into practical guidance for planning, teaching, and assessing physical computing lessons in your classroom.

**Section 7: Bringing It All Together**

We'll step back and consider the bigger picture: building sustainable practice, supporting colleagues, and continuing your development.

### Your Fieldwork

Throughout this course, you'll choose three different tools from three different sessions to try in your own classroom. Document these experiences with photographs and reflections. Consider:

- What worked well?
- What was challenging?
- What did children learn?
- What would you do differently?

Your fieldwork is an opportunity to translate theory into practice and to learn from real classroom experience.

### Your Reflective Diary

Keep a reflective diary throughout the course. Record not just what you did, but what you thought and felt:

- What surprised you?
- What challenged your assumptions?
- How is your confidence developing?
- What questions are emerging?

This diary will support your presentation and will become a valuable professional resource.

### Embrace the Experiment

Here's a secret: things will go wrong. Devices won't charge. Programs won't work. Children will do unexpected things. Marbles will roll under furniture. This is not failure—it's learning.

The teachers who get the most from physical computing are those who embrace experimentation, model resilience, and learn alongside their students. You don't need to be an expert. You need to be curious, persistent, and willing to say, "I don't know—let's figure it out together."

!!! quote "From the Research"
    "The best learning experiences happen when teachers position themselves as learners alongside their students, exploring and discovering together."
    
    — Mitchel Resnick, *Lifelong Kindergarten* (2017, p. 52)

### What Do You Hope to Learn?

Before you move on, take a moment to reflect:

- What are you most curious about?
- What are you most nervous about?
- What do you hope to learn from this course?
- What do you hope your students will experience?

Write your thoughts in your reflective diary. Return to them at the end of the course and see how your thinking has evolved.

---

!!! question "Final Reflection Prompt"
    As you complete this first section, consider: What is one thing you're now excited to try? What is one thing you're still unsure about? Make a note of both—the excitement will fuel your learning, and the uncertainty will guide your questions.

---

## Summary: Key Takeaways from Section 1

1. **Physical computing brings CT to life** by connecting programming to real objects that move, sense, and respond in the physical world—including mechanical devices that compute without electricity.

2. **The pedagogical case is strong**: Embodied cognition, constructionism, immediate feedback, and motivation all support learning through physical computing.

3. **CT concepts become concrete**: Decomposition, pattern recognition, abstraction, and algorithms are visible and tangible when a robot enacts them or a marble triggers a gear.

4. **Physical computing adds more**: Design thinking, systems thinking, tinkering, creativity, collaboration, and real-world relevance.

5. **Integration is essential**: Physical computing should connect to mathematics, science, literacy, art, and other subjects—not exist in isolation.

6. **Choose tools for learning purposes**: Start with outcomes, then select the simplest tool that supports them—whether that's a robot, a microcontroller, or a mechanical marble computer.

7. **Practical organisation matters**: Managing resources, organising classrooms, and planning time are essential for success.

8. **Assessment focuses on process**: Observation, documentation, and formative strategies capture learning that tests miss.

9. **Embrace experimentation**: Things will go wrong, and that's where much of the learning happens.

---

## References and Further Reading

### Cited in This Section

Berland, M., & Wilensky, U. (2015). Comparing virtual and physical robotics environments for supporting complex systems and computational thinking. *Journal of Science Education and Technology*, 24(5), 628-647. [https://doi.org/10.1007/s10956-015-9552-x](https://doi.org/10.1007/s10956-015-9552-x)

Bers, M. U. (2018). *Coding as a Playground: Programming and Computational Thinking in the Early Childhood Classroom*. Routledge. [https://www.routledge.com/Coding-as-a-Playground/Bers/p/book/9781138225626](https://www.routledge.com/Coding-as-a-Playground/Bers/p/book/9781138225626)

Bruner, J. S. (1966). *Toward a Theory of Instruction*. Harvard University Press.

IDEO (2012). *Design Thinking for Educators Toolkit* (2nd ed.). IDEO. Available free at: [https://www.ideo.com/post/design-thinking-for-educators](https://www.ideo.com/post/design-thinking-for-educators)

Kazakoff, E. R., & Bers, M. U. (2014). Put your robot in, put your robot out: Sequencing through programming robots in early childhood. *Journal of Educational Computing Research*, 50(4), 553-573. [https://doi.org/10.2190/EC.50.4.f](https://doi.org/10.2190/EC.50.4.f)

Kazakoff, E. R., Sullivan, A., & Bers, M. U. (2013). The effect of a classroom-based intensive robotics and programming workshop on sequencing ability in early childhood. *Early Childhood Education Journal*, 41(4), 245-255. [https://doi.org/10.1007/s10643-012-0554-5](https://doi.org/10.1007/s10643-012-0554-5)

Papert, S. (1980). *Mindstorms: Children, Computers, and Powerful Ideas*. Basic Books. Available free at: [http://worrydream.com/refs/Papert%20-%20Mindstorms%201st%20ed.pdf](http://worrydream.com/refs/Papert%20-%20Mindstorms%201st%20ed.pdf)

Resnick, M. (2017). *Lifelong Kindergarten: Cultivating Creativity through Projects, Passion, Peers, and Play*. MIT Press. [https://mitpress.mit.edu/books/lifelong-kindergarten](https://mitpress.mit.edu/books/lifelong-kindergarten)

Resnick, M., Maloney, J., Monroy-Hernández, A., Rusk, N., Eastmond, E., Brennan, K., Millner, A., Rosenbaum, E., Silver, J., Silverman, B., & Kafai, Y. (2009). Scratch: Programming for all. *Communications of the ACM*, 52(11), 60-67. [https://doi.org/10.1145/1592761.1592779](https://doi.org/10.1145/1592761.1592779)

Resnick, M., & Rosenbaum, E. (2013). Designing for tinkerability. In M. Honey & D. Kanter (Eds.), *Design, Make, Play: Growing the Next Generation of STEM Innovators* (pp. 163-181). Routledge. Available at: [https://web.media.mit.edu/~mres/papers/designing-for-tinkerability.pdf](https://web.media.mit.edu/~mres/papers/designing-for-tinkerability.pdf)

Sullivan, A., & Bers, M. U. (2016). Robotics in the early childhood classroom: Learning outcomes from an 8-week robotics curriculum in pre-kindergarten through second grade. *International Journal of Technology and Design Education*, 26(1), 3-20. [https://doi.org/10.1007/s10798-015-9304-5](https://doi.org/10.1007/s10798-015-9304-5)

Wilson, M. (2002). Six views of embodied cognition. *Psychonomic Bulletin & Review*, 9(4), 625-636. [https://doi.org/10.3758/BF03196322](https://doi.org/10.3758/BF03196322)

Wing, J. M. (2006). Computational thinking. *Communications of the ACM*, 49(3), 33-35. [https://doi.org/10.1145/1118178.1118215](https://doi.org/10.1145/1118178.1118215)

---

### Further Reading

#### On Computational Thinking

Grover, S., & Pea, R. (2013). Computational thinking in K-12: A review of the state of the field. *Educational Researcher*, 42(1), 38-43. [https://doi.org/10.3102/0013189X12463051](https://doi.org/10.3102/0013189X12463051)

Brennan, K., & Resnick, M. (2012). New frameworks for studying and assessing the development of computational thinking. *Proceedings of the 2012 Annual Meeting of the American Educational Research Association*. Available at: [https://web.media.mit.edu/~kbrennan/files/Brennan_Resnick_AERA2012_CT.pdf](https://web.media.mit.edu/~kbrennan/files/Brennan_Resnick_AERA2012_CT.pdf)

#### On Physical Computing in Education

Blikstein, P. (2013). Digital fabrication and 'making' in education: The democratization of invention. In J. Walter-Herrmann & C. Büching (Eds.), *FabLabs: Of Machines, Makers and Inventors* (pp. 203-222). Transcript Publishers.

Sentance, S., & Csizmadia, A. (2017). Computing in the curriculum: Challenges and strategies from a teacher's perspective. *Education and Information Technologies*, 22(2), 469-495. [https://doi.org/10.1007/s10639-016-9482-0](https://doi.org/10.1007/s10639-016-9482-0)

#### On Mechanical Computing

Anil, P. (2019). *Turing Tumble Educator Guide*. Upper Story LLC. Available at: [https://www.turingtumble.com/edu](https://www.turingtumble.com/edu)

CS Unplugged. (n.d.). *Computer Science Unplugged*. [https://csunplugged.org](https://csunplugged.org) — Free activities for teaching computing concepts without computers.

#### On Constructionism and Learning

Kafai, Y. B., & Burke, Q. (2014). *Connected Code: Why Children Need to Learn Programming*. MIT Press.

Harel, I., & Papert, S. (Eds.). (1991). *Constructionism*. Ablex Publishing.

---

### Useful Websites

- **BBC micro:bit**: [https://microbit.org](https://microbit.org) — Official resources, tutorials, and MakeCode editor
- **Scratch**: [https://scratch.mit.edu](https://scratch.mit.edu) — Free block-based programming environment
- **CS Unplugged**: [https://csunplugged.org](https://csunplugged.org) — Unplugged activities for computing education
- **Turing Tumble**: [https://www.turingtumble.com](https://www.turingtumble.com) — Mechanical marble computer
- **Barefoot Computing**: [https://www.barefootcomputing.org](https://www.barefootcomputing.org) — Free resources for primary computing (UK-based, but widely applicable)
- **Code.org**: [https://code.org](https://code.org) — Free coding courses and resources for K-12

---

**Ready to continue?** Head to [Section 2: Robots in the Classroom](section-2.md) to explore floor robots and how to use them in your teaching.
