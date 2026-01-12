# Section 2: Robots in the Classroom — Directional Thinking and Early Algorithms

---

## 2.1 Introduction: Why Floor Robots?

In Section 1, you explored the foundations of physical computing and its connection to computational thinking. Now we turn to one of the most accessible and powerful tools for bringing CT to life in primary classrooms: floor robots.

Floor robots are programmable devices that move through physical space according to children's instructions. They're called "floor robots" because they typically operate on the floor (or a tabletop), navigating mats, mazes, and obstacle courses that children create. Unlike screen-based programming, where code produces virtual effects, floor robots make algorithms visible and tangible. When a child programs a sequence, they watch their robot execute it in real space, with all the drama of success, failure, and unexpected outcomes that entails.

For primary teachers, floor robots offer a particularly compelling entry point into physical computing. They require minimal technical setup, work with children from Early Years through upper primary, and integrate naturally with subjects across the curriculum. A Bee-Bot navigating a story mat is simultaneously a literacy lesson, a maths lesson, and a computing lesson. A Pro-Bot drawing geometric shapes connects programming to mathematical reasoning in ways that textbooks cannot.

In this section, we'll explore the landscape of floor robots available for primary education, examine how they develop specific CT skills, consider practical classroom strategies, and work through detailed examples of cross-curricular integration. By the end, you'll have a clear understanding of how to select, deploy, and assess learning with floor robots in your own teaching context.

---

## 2.2 The Floor Robot Landscape

The market offers a range of floor robots designed for educational use. Understanding the differences between them helps you choose the right tool for your learners and your learning intentions.

### The Bee-Bot Family

The [Bee-Bot](https://www.tts-group.co.uk/bee-bot-programmable-floor-robot/1015268.html){:target="_blank"} from TTS Group is perhaps the most widely recognised floor robot in primary education. Designed in the shape of a friendly bee, it has become a classroom staple in the UK and beyond since its introduction in the early 2000s.

**Key features of Bee-Bot:**

- Seven buttons on top: Forward, Back, Left Turn (90°), Right Turn (90°), Pause, Clear, and Go
- Each forward/back movement covers 15cm; each turn is exactly 90°
- Memory capacity of up to 40 steps (200 in newer models)
- Audio and visual feedback (beeps and flashing eyes)
- Rechargeable battery (via docking station) or standard batteries
- Robust construction suited to young children's handling

Bee-Bot's simplicity is its strength. There's no screen, no app required, and no complex setup. Children press buttons on the robot itself, building a sequence that executes when they press "Go". This directness makes Bee-Bot accessible to children as young as three or four years old, while still offering meaningful challenges for older primary learners.

**Blue-Bot** is Bee-Bot's more advanced sibling. It retains all of Bee-Bot's functionality but adds:

- Bluetooth connectivity for tablet/computer control via the free [Blue-Bot app](https://apps.apple.com/us/app/blue-bot/id957753068){:target="_blank"}
- 45° turns (when using the app)
- Repeat/loop functionality (when using the app)
- Transparent shell so children can see the internal components
- Robot-to-robot communication (Blue-Bots can detect each other)
- Audio recording capability (children can record sounds for each button)
- Compatibility with the TacTile Code Reader for tangible programming

Blue-Bot bridges the gap between simple button programming and more sophisticated screen-based coding, making it ideal for progression within Key Stage 1 and into Key Stage 2.

### Pro-Bot: Introducing Logo Programming

[Pro-Bot](https://www.terrapinlogo.com/probot.html){:target="_blank"} takes floor robot programming to the next level. Shaped like a car rather than a bee, Pro-Bot introduces children to Logo-style programming with precise distance and angle control.

**Key features of Pro-Bot:**

- LCD screen displaying the program
- Precise distance control (movements specified in centimetres)
- Precise angle control (any angle, not just 90°)
- Pen holder for drawing shapes and patterns
- Touch sensors and light sensor for interactive programming
- Procedure capability (children can define and reuse their own commands)
- USB connectivity for computer programming

Pro-Bot is particularly powerful for mathematics. When a child programs "FORWARD 50, RIGHT 90, FORWARD 50, RIGHT 90, FORWARD 50, RIGHT 90, FORWARD 50, RIGHT 90" to draw a square, they're directly experiencing the relationship between programming, geometry, and measurement. The pen holder makes the algorithm visible as a drawn shape—a compelling connection between abstract code and concrete result.

Pro-Bot is typically most suitable for children in Years 3–6, though confident Year 2 children can begin exploring its basic functions.

### Thymio: Sensors and Behaviours

[Thymio](https://www.thymio.org/){:target="_blank"} is an open-source educational robot developed by EPFL (the Swiss Federal Institute of Technology) and Mobsya. Unlike Bee-Bot's focus on sequential programming, Thymio emphasises sensor-based behaviours and event-driven programming.

**Key features of Thymio:**

- Multiple infrared sensors (front, back, and ground-facing)
- Accelerometer for detecting tilt and movement
- Microphone and speaker
- Multicolour LED display
- Six pre-programmed behaviour modes (indicated by colour)
- Programmable via VPL (Visual Programming Language), Blockly, Scratch, or text-based languages
- Open-source design with extensive documentation

Thymio's pre-programmed modes make it immediately accessible without any programming:

| Colour | Behaviour |
|--------|-----------|
| **Green** | Friendly — follows nearby objects |
| **Yellow** | Explorer — avoids obstacles |
| **Red** | Fearful — flees from nearby objects |
| **Purple** | Obedient — responds to button presses |
| **Cyan** | Investigator — follows lines |
| **Blue** | Attentive — responds to sound (claps) |

These modes allow children to explore cause-and-effect relationships before any formal programming. "Why does it follow my hand when it's green but run away when it's red?" This inquiry-based exploration builds intuitions about sensors and conditional logic.

When children progress to programming Thymio, they encounter event-driven concepts: "When the front sensor detects an obstacle, turn left." This if-then logic is fundamental to computing and connects directly to decision-making in everyday life.

### LEGO Education: Building and Programming

LEGO Education offers robotics solutions that combine the familiar joy of LEGO building with programmable motors and sensors. The two most relevant for primary education are:

**[LEGO Education SPIKE Essential](https://education.lego.com/en-us/products/lego-education-spike-essential-set/45345/){:target="_blank"}** is designed specifically for primary school (grades 1–5/ages 5–10). It includes:

- 449 LEGO elements including minifigure characters
- Small Hub with two motor/sensor ports
- One motor and one colour sensor
- Icon-based and word-block programming via the SPIKE App
- Curriculum-aligned lesson plans across literacy, maths, science, and social-emotional learning

SPIKE Essential differs from floor robots like Bee-Bot in that children build their own creations before programming them. This adds a design and construction phase that develops spatial reasoning and engineering thinking alongside CT skills.

**[LEGO Education WeDo 2.0](https://education.lego.com/en-us/products/lego-education-wedo-2-0-core-set/45300/){:target="_blank"}** (now retired but still widely available and supported until 2026) offers:

- 280 LEGO elements
- Smarthub (Bluetooth-enabled)
- One motor, one motion sensor, one tilt sensor
- Drag-and-drop programming via tablet or computer
- Science and engineering curriculum focus

WeDo 2.0's strength lies in its project-based approach. Children might build Milo the Science Rover, then program it to move, respond to obstacles, and collect data. This integration of building, programming, and scientific inquiry makes WeDo particularly powerful for cross-curricular work.

### Comparison Table: Choosing Your Robot

| Feature | Bee-Bot | Blue-Bot | Pro-Bot | Thymio | SPIKE Essential |
|---------|---------|----------|---------|--------|-----------------|
| **Age range** | 3–7+ | 4–9+ | 7–11+ | 5–11+ | 5–10+ |
| **Programming method** | Buttons on robot | Buttons, app, or TacTile | Keypad and LCD | Pre-programmed modes, VPL, Blockly | Icon/word blocks via app |
| **Movement precision** | 15cm steps, 90° turns | 15cm steps, 45°/90° turns | Any distance, any angle | Variable | Motor-controlled |
| **Sensors** | None | Robot detection | Touch, light | IR (×9), accelerometer, mic | Colour sensor |
| **Construction** | Fixed | Fixed | Fixed | Fixed | Child-built |
| **Screen required** | No | Optional | Built-in LCD | Optional | Yes (tablet/computer) |
| **Best for** | Early sequencing, pre-readers | Progression from Bee-Bot | Maths, geometry, Logo | Sensors, behaviours, inquiry | Building, cross-curricular projects |
| **Approximate cost (single unit)** | £70–90 | £90–120 | £100–130 | £130–180 | £250–300 (set) |

### Making Your Choice

The "best" robot depends on your context:

- **For Early Years and KS1 beginners**: Start with Bee-Bot. Its simplicity allows focus on sequencing without technical barriers.
- **For KS1/KS2 progression**: Blue-Bot extends Bee-Bot learning with app-based programming, loops, and 45° turns.
- **For upper KS2 mathematics**: Pro-Bot's precision and Logo-style commands make it ideal for geometry and measurement.
- **For inquiry-based science**: Thymio's sensors and behaviours support exploration of cause-and-effect and conditional logic.
- **For design and construction**: SPIKE Essential combines building with programming for engineering-focused projects.

Many schools find value in having multiple robot types available, using simpler robots for younger children and progressing to more complex ones as skills develop.

!!! tip "Starting Small"
    If budget is limited, start with a small set of Bee-Bots (6 is enough for paired work in rotations). You can always expand later based on what works in your classroom.

---

## 2.3 Programming Concepts Through Movement

Floor robots are powerful teaching tools because they make abstract programming concepts concrete and visible. Let's examine how specific CT and programming concepts emerge through floor robot activities.

### Sequencing: The Foundation

Sequencing—arranging instructions in the correct order—is the most fundamental programming concept, and floor robots teach it beautifully.

When a child programs a Bee-Bot to travel from one corner of a mat to another, they must think through each step:

1. Forward (one square)
2. Forward (one square)
3. Turn Right
4. Forward (one square)
5. Forward (one square)

The sequence matters. "Turn Right, Forward, Forward, Forward, Forward" produces a completely different result than "Forward, Forward, Turn Right, Forward, Forward." The robot reveals whether the sequence is correct—there's no hiding from the outcome.

**Teaching sequencing effectively:**

- Begin with short sequences (2–3 steps) and gradually increase complexity
- Have children predict what will happen before pressing Go
- Use planning cards or whiteboards to record sequences before programming
- Celebrate the process of sequencing, not just successful outcomes

### Direction and Spatial Reasoning

Floor robots demand spatial thinking. Children must:

- Understand left and right from the robot's perspective (not their own)
- Visualise the path before programming
- Mentally rotate their viewpoint to match the robot's orientation

This is genuinely challenging, especially for younger children. A child standing behind a Bee-Bot facing away from them must recognise that "Turn Left" means the robot's left, which appears as right from their viewpoint.

**Strategies for developing spatial reasoning:**

- "Be the robot": Children physically walk the path before programming, turning their bodies to match the robot's direction
- Stand behind the robot rather than facing it, so left and right match
- Use consistent starting orientations until children are confident
- Provide directional cards or arrows that children can manipulate

Research by Highfield and Mulligan (2008) found that Bee-Bot activities significantly improved young children's spatial reasoning and directional language, with effects persisting beyond the immediate learning context.

### Debugging: Learning from Failure

Perhaps no concept benefits more from floor robots than debugging. When a Bee-Bot misses its target, the error is visible to everyone. This creates a powerful, non-threatening context for error analysis.

**The debugging cycle with floor robots:**

1. **Observe**: What did the robot actually do?
2. **Compare**: What did I expect it to do?
3. **Locate**: At which step did it go wrong?
4. **Analyse**: Why might that step be incorrect?
5. **Revise**: Change the sequence
6. **Test**: Run it again

The visibility of the error transforms debugging from a frustrating hunt into a collaborative investigation. "Look—it turned left at the wrong place! Let's figure out why."

**Fostering productive debugging:**

- Normalise errors: "Mistakes help us learn!"
- Ask diagnostic questions: "Where did it start going wrong?"
- Resist fixing it for them—guide children to identify and correct errors themselves
- Celebrate debugging successes as much as first-time successes

### Loops and Repetition (Blue-Bot and Beyond)

When children programme a robot to trace a square, they initially write:

- Forward, Turn Right, Forward, Turn Right, Forward, Turn Right, Forward, Turn Right

With guidance, they recognise the pattern: "Forward, Turn Right" repeats four times. This is the foundation for understanding loops.

With Blue-Bot's app, children can explicitly program "Repeat 4 times: Forward, Turn Right". This abstraction is powerful—it reduces complexity and reveals the underlying structure.

**Introducing loops:**

- Start with physical patterns: clapping sequences, movement routines
- Identify repetition in existing robot programs: "I notice you did the same thing three times..."
- Introduce loop notation gradually: "What if we could tell the robot to repeat this part?"
- Connect to real-world examples: traffic light sequences, song choruses, dance routines

### Procedures and Abstraction (Pro-Bot)

Pro-Bot allows children to define their own procedures—named sequences they can reuse. For example, a child might define:

```
TO SQUARE
FORWARD 50
RIGHT 90
FORWARD 50
RIGHT 90
FORWARD 50
RIGHT 90
FORWARD 50
RIGHT 90
END
```

Once defined, they can simply write "SQUARE" to draw a square. They can then build more complex programs:

```
SQUARE
RIGHT 45
SQUARE
RIGHT 45
SQUARE
```

This is abstraction in action: hiding complexity behind a simple name. It's also the beginning of understanding functions—one of programming's most powerful concepts.

### Conditionals and Events (Thymio)

While Bee-Bot and Pro-Bot focus on sequential programming, Thymio introduces conditional logic and events:

- "**When** the front sensor detects an obstacle, **then** turn left"
- "**If** the ground sensor sees black, **then** follow it"
- "**When** I clap, **then** start moving"

This event-driven model is how most real-world software works. Apps respond to button presses, sensors trigger actions, and conditions determine behaviour.

**Introducing conditionals with Thymio:**

- Begin with the pre-programmed modes: observe and explain the behaviours
- Ask "what if" questions: "What will happen if I put my hand here?"
- Progress to simple VPL programming: one event, one action
- Build complexity gradually: multiple events, conditional combinations

---

## 2.4 Cross-Curricular Integration

Floor robots shouldn't exist as isolated "computing lessons." Their real power emerges when integrated across the curriculum. Here we'll explore detailed examples for major subject areas.

### Mathematics

The connections between floor robots and mathematics are rich and numerous.

**Measurement and Distance**

- Bee-Bot moves 15cm per step. How many steps to travel 45cm? 1 metre?
- Pro-Bot programs specify exact distances. Children measure, calculate, and verify.
- Estimate before programming: "How many steps do you think?" Then measure and check.

**Angles and Turns**

- Bee-Bot turns 90°. What's a 90° angle? Where else do we see 90° angles?
- Pro-Bot can turn any angle. Program a 60° turn. What shape has 60° angles?
- Explore full turns (360°), half turns (180°), quarter turns (90°)

**Shape and Geometry**

- Program Pro-Bot to draw a square, rectangle, triangle, hexagon
- What's the same about all square programs? What's different for a rectangle?
- Explore regular polygons: What's the relationship between number of sides and turning angle?

!!! example "Maths Activity: The Perimeter Challenge"
    **Learning intention**: Understand that different rectangles can have the same perimeter
    
    **Resources**: Pro-Bot with pen, large paper, rulers
    
    **Activity**:
    
    1. Challenge: "Program Pro-Bot to draw three different rectangles, each with perimeter 40cm"
    2. Children calculate possible side lengths (e.g., 15cm × 5cm, 12cm × 8cm, 10cm × 10cm)
    3. Program Pro-Bot to draw each rectangle
    4. Measure and verify: Does each perimeter equal 40cm?
    5. Extension: Which rectangle has the largest area? What if the perimeter was 60cm?
    
    **CT connections**: Decomposition (breaking the problem into steps), algorithmic thinking (precise sequences), debugging (when measurements don't match)

**Coordinates and Position**

- Grid mats use coordinate systems. "Move to (3, 4)"
- Describe paths using coordinates: "Start at (1, 1), end at (4, 3)"
- Connect to graph work: plotting points, reading coordinates

### Literacy

Floor robots offer surprising opportunities for literacy development.

**Instructional Writing**

Programming is, fundamentally, writing clear instructions. Children who program robots understand viscerally why precision matters. "Go forward a bit" doesn't work—you need "Forward 3 steps."

**Activity**: After programming a robot journey, children write the instructions in words. Compare written instructions with the actual program. Which is clearer? Why?

**Story Sequencing**

Create story mats showing scenes from familiar narratives. Children program robots to visit scenes in the correct order.

!!! example "Literacy Activity: Journey Through a Story"
    **Learning intention**: Sequence story events correctly; programme a robot to follow a narrative path
    
    **Resources**: Bee-Bot, mat with story scenes (e.g., *The Very Hungry Caterpillar* — egg, caterpillar, apple, pear, plum, strawberries, oranges, cake/pickle/etc., cocoon, butterfly)
    
    **Activity**:
    
    1. Read or recall the story together
    2. Identify the sequence of events on the mat
    3. Children plan a route visiting scenes in story order
    4. Program Bee-Bot to follow the route
    5. Retell the story as Bee-Bot visits each scene
    
    **Extension**: Create mats for other stories. Write new stories with paths for Bee-Bot to follow.
    
    **CT connections**: Sequencing (story order = programming order), abstraction (representing story as path)

**Speaking and Listening**

Robot activities naturally promote talk. Children discuss strategies, explain their thinking, debate solutions, and present their programs to others. This authentic context for speaking and listening is often more engaging than manufactured discussion tasks.

### Science

Physical computing aligns beautifully with scientific inquiry.

**Variables and Fair Testing**

- Change one thing at a time: "What happens if I add one more Forward?"
- Control other variables: same starting position, same mat
- Predict, test, observe, explain

**Cause and Effect**

- Thymio's sensor behaviours are cause-and-effect in action
- If I block the sensor, then the robot turns
- Explore systematically: which sensors cause which responses?

**Forces and Motion**

- How does the robot move? What makes it turn?
- Friction: Does Bee-Bot move the same distance on carpet vs. smooth floor?
- Experiment with surfaces, slopes, obstacles

!!! example "Science Activity: Surface Investigators"
    **Learning intention**: Investigate how surface type affects Bee-Bot's movement
    
    **Resources**: Bee-Bot, various surfaces (carpet, tile, paper, fabric, sandpaper), measuring tape, recording sheets
    
    **Activity**:
    
    1. Question: "Does Bee-Bot move the same distance on all surfaces?"
    2. Predict: Which surface will it move furthest on? Why?
    3. Method: Program Bee-Bot with exactly 5 forward steps. Measure total distance on each surface.
    4. Record results in a table
    5. Explain findings: Why might carpet be different from tile?
    
    **CT connections**: Systematic testing (algorithmic approach), debugging (ensuring fair tests), abstraction (focusing on relevant variables)

### Geography

Floor robots excel at teaching mapping, direction, and spatial concepts.

**Mapping and Navigation**

Create mats based on maps—your school, local area, a fictional town, or even a simplified Malta. Children program routes between locations.

**Cardinal Directions**

Use a compass rose on the mat. "Program Bee-Bot to travel North, then East, then South." Connect robot directions to geographical directions.

**Scale and Distance**

If each Bee-Bot square represents 100 metres, how far is the journey? Calculate real-world distances from robot paths.

!!! example "Geography Activity: Around Our School"
    **Learning intention**: Navigate a map using directional language; programme a route between locations
    
    **Resources**: Floor mat with simplified school map (or create one), Bee-Bot, direction cards
    
    **Activity**:
    
    1. Identify key locations on the map: classroom, hall, playground, office, library
    2. Give verbal directions first: "Start at the classroom. Go North to the hall, then East to the playground."
    3. Translate into Bee-Bot commands: Forward, Forward, Right, Forward, Forward
    4. Test the route
    5. Challenge: Find the shortest route between two points
    
    **CT connections**: Decomposition (breaking journey into steps), spatial reasoning, debugging

### Art and Design

Floor robots can be creative tools, not just problem-solving tools.

**Robot Art with Pro-Bot**

Pro-Bot's pen holder enables drawing. Children program geometric designs, patterns, and pictures.

**Design Challenges**

- Design a mat for a specific purpose (a story, a maths game, a geography activity)
- Design an obstacle course that requires specific programming skills

**Pattern and Symmetry**

- Program patterns that repeat (connecting to loops)
- Create symmetrical designs: one side programmed, then mirrored

---

## 2.5 Differentiation: Meeting Diverse Learners

Floor robots are inherently flexible, but thoughtful differentiation ensures all learners can access and be challenged by the activities.

### Supporting Younger and Less Confident Learners

**Reduce complexity:**

- Shorter sequences (2–3 steps to start)
- Simpler mats with fewer squares and clearer paths
- One robot between two children, with adult support nearby

**Provide scaffolding:**

- Physical planning aids: direction cards children arrange before programming
- "Be the robot" activities before using actual robots
- Step-by-step demonstrations with think-alouds

**Build confidence:**

- Guarantee early success with very achievable first tasks
- Celebrate process and effort, not just outcomes
- Pair less confident learners with supportive peers

### Challenging More Confident Learners

**Increase complexity:**

- Longer sequences with more turns
- Multiple destinations in one program
- Obstacles to navigate around

**Add constraints:**

- "Can you reach the goal in exactly 7 steps?"
- "Find the shortest possible route"
- "Use only left turns" (or other restrictions)

**Extend concepts:**

- Introduce loops and procedures earlier
- Progress to Pro-Bot for precise angles and distances
- Program Thymio with conditional behaviours

**Encourage creation:**

- Design mats for others to use
- Create challenges for classmates
- Document and explain strategies

### Supporting Specific Needs

**Motor difficulties:**

- Larger buttons (consider adapted devices if available)
- Partner programming: one child plans, another presses buttons
- Tablet control for Blue-Bot (may be easier than small buttons)

**Visual impairment:**

- High-contrast mats with tactile elements
- Verbal descriptions of robot movements
- Thymio's sound output for audio feedback

**Hearing impairment:**

- Visual feedback (LED lights) rather than sound
- Clear sight lines for demonstrations
- Written or visual instruction cards

**Cognitive differences:**

- Consistent routines and clear expectations
- Visual schedules for the activity structure
- Reduced options to avoid overwhelm
- Extended time for exploration and processing

### Universal Design Principles

Rather than retrofitting accessibility, design activities that work for everyone from the start:

- Multiple ways to engage (watching, doing, planning, recording)
- Multiple ways to represent information (visual, verbal, physical)
- Multiple ways to demonstrate learning (showing, explaining, drawing, writing)

---

## 2.6 Classroom Management with Floor Robots

Practical organisation makes the difference between productive learning and chaotic frustration. Here are strategies that experienced teachers find effective.

### Before the Session

**Check equipment:**

- Are all robots charged? (Nothing derails a lesson like flat batteries)
- Do all robots work correctly? (Test each one briefly)
- Are mats clean and flat?

**Prepare resources:**

- Planning sheets or whiteboards for recording sequences
- Challenge cards or task instructions
- Direction cards if using them

**Prepare the space:**

- Clear floor space (remove tripping hazards)
- Consider noise levels (multiple robots can be loud)
- Ensure good sight lines for demonstrations

### During the Session

**Establish routines:**

- Clear signal for "stop and listen" (essential when children are absorbed)
- Agreed rules for handling robots (carry carefully, don't throw, return to charger)
- Turn-taking protocols for paired work

**Structure the activity:**

- Whole-class introduction and demonstration (10 minutes)
- Paired/group activity time with circulating support (20–30 minutes)
- Whole-class reflection and sharing (10 minutes)

**Support without taking over:**

- Ask questions rather than giving answers: "What do you think went wrong?"
- Encourage children to help each other before asking you
- Model debugging strategies when you do intervene

### Grouping Strategies

**Pairs work well for most activities:**

- One "driver" (operates the robot), one "navigator" (directs and observes)
- Regular role swaps (every 5 minutes or every attempt)
- Encourages discussion and collaborative problem-solving

**Rotations work when robots are limited:**

- Robot station as one of several activities
- Clear instructions at each station
- Timer or signal for rotation

**Whole-class demonstrations:**

- Visualiser or large screen to show small robots
- Invite children up to program while others predict
- Good for introducing new concepts or reflecting on strategies

### After the Session

**Pack-away routine:**

- Return robots to charging station
- Fold and store mats
- Count equipment (things go missing!)

**Documentation:**

- Quick notes on what worked and what didn't
- Observations of individual children's learning
- Photos of interesting solutions or approaches

---

## 2.7 Example Lesson Sequences

Here are two detailed lesson sequences showing how floor robot learning might progress over multiple sessions.

### Early Years/Year 1: Introducing Bee-Bot (4 sessions)

**Session 1: Meeting Bee-Bot**

*Learning intention: Understand what Bee-Bot is and explore its buttons*

- Introduce Bee-Bot: "This is Bee-Bot. What do you notice about it?"
- Explore the buttons together. What might each button do?
- Demonstrate: Press Forward, then Go. What happened?
- Free exploration in pairs: Try different buttons and observe
- Gather and share: What did you discover?

**Session 2: Giving Instructions**

*Learning intention: Programme a simple sequence of 2–3 steps*

- Recall: What can Bee-Bot do?
- "Be the robot": Children give each other verbal instructions, then follow them
- Demonstrate: Programming Bee-Bot to reach a target in 2 steps
- Paired activity: Program Bee-Bot to reach targets in 2–3 steps
- Reflect: What did you have to think about?

**Session 3: Planning Before Programming**

*Learning intention: Plan a sequence before programming*

- Introduce planning cards (arrows for each direction)
- Model: Lay out cards, then press matching buttons
- Paired activity: Use cards to plan, then program, then check
- Challenge: Reach a target on a simple grid mat
- Reflect: Did planning help? Why?

**Session 4: Bee-Bot Story Mat**

*Learning intention: Program Bee-Bot to follow a story sequence*

- Introduce a story mat (e.g., *We're Going on a Bear Hunt* with locations)
- Recall the story sequence
- Model: Program Bee-Bot to visit the first two locations
- Paired activity: Program the full journey through the story
- Retell the story as Bee-Bot travels
- Reflect: What was tricky? What did you learn?

### Years 3–4: Progressing with Pro-Bot (4 sessions)

**Session 1: From Bee-Bot to Pro-Bot**

*Learning intention: Understand how Pro-Bot differs from Bee-Bot; programme basic movements*

- Recall Bee-Bot experience. What could Bee-Bot do?
- Introduce Pro-Bot: What's similar? What's different?
- Explore the keypad and LCD screen
- Key difference: We can choose exact distances and angles
- Demonstrate: FORWARD 50 (moves 50cm)
- Paired exploration: Try different distances and angles
- Reflect: What new possibilities does Pro-Bot offer?

**Session 2: Drawing Shapes**

*Learning intention: Programme Pro-Bot to draw regular polygons*

- Attach pen to Pro-Bot
- Demonstrate drawing a line: FORWARD 50
- Challenge: Draw a square with 10cm sides
- Unpack the maths: What angles? What distances?
- Paired activity: Draw squares, then rectangles, then triangles
- Compare results: What made some shapes more accurate?
- Reflect: What's the relationship between programming and geometry?

**Session 3: Patterns and Repetition**

*Learning intention: Recognise repetition in programs; begin to use repeat commands*

- Review square program: FORWARD 50, RIGHT 90, FORWARD 50, RIGHT 90...
- What do you notice? (It repeats!)
- Introduce REPEAT command: REPEAT 4 [FORWARD 50 RIGHT 90]
- Compare: Same result, fewer instructions. Why is this useful?
- Challenge: Draw a hexagon using REPEAT
- Extension: Create repeating patterns (spirals, stars)
- Reflect: How does repetition make programming more powerful?

**Session 4: Design Challenge**

*Learning intention: Apply programming skills to solve a design problem*

- Challenge: Design a floor plan for a new classroom (or garden, or playground)
- Constraints: Must include at least 3 different shapes; total perimeter must be under 2 metres
- Planning phase: Sketch design, calculate measurements
- Programming phase: Program Pro-Bot to draw the design
- Presentation: Show and explain your design
- Reflect: What was challenging? What would you do differently?

---

## 2.8 Assessment Approaches

Assessing learning with floor robots requires approaches that capture process as well as product.

### What to Observe

**Sequencing skills:**

- Can the child plan a sequence before programming?
- Are instructions in the correct order?
- Does sequence length and complexity increase over time?

**Debugging ability:**

- How does the child respond when the robot doesn't do what they expected?
- Do they systematically identify where the error occurred?
- Can they revise and improve their program?

**Spatial reasoning:**

- Does the child understand left/right from the robot's perspective?
- Can they visualise the path before programming?
- Do they anticipate where the robot will end up?

**Mathematical understanding (where relevant):**

- Can they estimate distances and angles?
- Do they connect programming to mathematical concepts?
- Can they calculate and verify measurements?

**Collaboration and communication:**

- Do they explain their thinking to partners?
- Can they describe their strategy to others?
- Do they work effectively in pairs/groups?

### Assessment Strategies

**Observation notes:**

Brief notes during sessions, focusing on significant moments:

- "Mia independently debugged her sequence by counting steps"
- "Jayden struggled with left/right but improved when he stood behind the robot"

**Photography and video:**

Capture evidence of:

- Planning sheets showing children's thinking
- Successful (and unsuccessful) robot journeys
- Children explaining their programs

**Child voice:**

Simple reflection prompts:

- "What did you find tricky today?"
- "What would you do differently next time?"
- "What did you learn about programming?"

**Challenge progressions:**

Track which challenges children can complete independently:

| Challenge | Date Attempted | Outcome |
|-----------|----------------|---------|
| Program 3-step sequence | 15/1 | ✓ Independent |
| Navigate around obstacle | 15/1 | With support |
| Plan before programming | 22/1 | ✓ Independent |
| Use repeat command | 22/1 | Not yet attempted |

### Rubric for Floor Robot Skills

| Skill | Beginning | Developing | Secure | Extending |
|-------|-----------|------------|--------|-----------|
| **Sequencing** | Presses buttons randomly; doesn't understand order matters | Understands sequence but makes frequent errors | Reliably programs correct sequences of 5+ steps | Plans complex sequences; recognises patterns and repetition |
| **Debugging** | Gives up or starts over when robot fails | Makes random changes hoping for improvement | Identifies where error occurred; makes logical corrections | Systematically tests and refines; explains debugging strategy |
| **Spatial reasoning** | Confused by left/right; limited path visualisation | Sometimes confuses direction; improving visualisation | Reliable direction from robot's perspective; can visualise simple paths | Navigates complex paths; anticipates movement accurately |
| **Explanation** | Cannot explain program | Describes what robot did, not why | Explains sequence and reasoning | Justifies choices; evaluates alternative approaches |

---

## 2.9 Resources and Further Reading

### Official Robot Resources

**Bee-Bot and Blue-Bot (TTS Group):**

- Product page and resources: [https://www.tts-group.co.uk/primary/computing-ict/bee-bots-blue-bots/](https://www.tts-group.co.uk/primary/computing-ict/bee-bots-blue-bots/){:target="_blank"}
- Downloadable lesson plans and activity cards
- Blue-Bot app available free on iOS and Android

**Pro-Bot (Terrapin/TTS):**

- Resources and tutorials: [https://www.terrapinlogo.com/probot.html](https://www.terrapinlogo.com/probot.html){:target="_blank"}
- Logo programming guides

**Thymio (Mobsya):**

- Official site with programming environments: [https://www.thymio.org/](https://www.thymio.org/){:target="_blank"}
- Extensive lesson plans and activities
- Open-source community resources

**LEGO Education:**

- SPIKE Essential: [https://education.lego.com/en-us/products/lego-education-spike-essential-set/45345/](https://education.lego.com/en-us/products/lego-education-spike-essential-set/45345/){:target="_blank"}
- WeDo 2.0 (legacy): [https://education.lego.com/en-us/product-resources/wedo-2/](https://education.lego.com/en-us/product-resources/wedo-2/){:target="_blank"}
- Curriculum-aligned lesson plans for each product

### Research and Professional Reading

**Key research on floor robots in education:**

- Highfield, K., & Mulligan, J. (2008). Young children's embodied action in problem-solving tasks using robotic toys. In *Navigating Currents and Charting Directions*, Proceedings of the 31st Annual MERGA Conference (pp. 259–266). This foundational study demonstrates how Bee-Bot activities develop spatial reasoning and mathematical thinking.

- Papadakis, S., & Kalogiannakis, M. (2022). Learning Computational Thinking Development in Young Children With Bee-Bot Educational Robotics. In *Research Anthology on Computational Thinking, Programming, and Robotics in the Classroom* (pp. 926–947). IGI Global. Reports significant learning gains in CT skills among preschool children using Bee-Bot.

- Seckel, M. J., Salinas, C., Font, V., & Sala-Sebastià, G. (2023). Guidelines to develop computational thinking using the Bee-bot robot from the literature. *Education and Information Technologies*. A systematic review of 25 studies providing evidence-based guidance for CT development with Bee-Bot.

- Schina, D., Esteve-González, V., & Usart, M. (2021). Teachers' Perceptions of Bee-Bot Robotic Toy and Their Ability to Integrate It in Their Teaching. In *Advances in Intelligent Systems and Computing*. Explores teacher perspectives on implementing floor robots in primary classrooms.

**Books for deeper exploration:**

- Bers, M. U. (2018). *Coding as a Playground: Programming and Computational Thinking in the Early Childhood Classroom*. Routledge. Essential reading on developmentally appropriate approaches to coding with young children.

- Resnick, M. (2017). *Lifelong Kindergarten: Cultivating Creativity through Projects, Passion, Peers, and Play*. MIT Press. The philosophy behind Scratch and LEGO robotics, with implications for all creative computing.

---

## 2.10 Summary: Key Takeaways from Section 2

1. **Floor robots make programming tangible.** When algorithms control physical movement, abstract concepts become visible and experiential.

2. **Different robots serve different purposes.** Bee-Bot excels at early sequencing; Blue-Bot adds progression with apps and loops; Pro-Bot connects to mathematical precision; Thymio introduces sensors and conditionals.

3. **Core CT concepts emerge naturally.** Sequencing, debugging, pattern recognition, and algorithmic thinking are built into floor robot activities by design.

4. **Integration is essential.** Floor robots aren't just for "computing lessons"—they enrich mathematics, literacy, science, geography, and more.

5. **Differentiation is achievable.** From simple 2-step sequences to complex multi-stage challenges, floor robots scale to meet diverse learners.

6. **Practical organisation matters.** Charged robots, clear routines, effective groupings, and structured sessions create conditions for learning.

7. **Assessment focuses on process.** Observation, documentation, and formative strategies capture learning that final products might miss.

8. **Start simple, then extend.** Begin with achievable challenges and build complexity as confidence grows—for you and your students.

---

!!! question "Reflection Prompt"
    Consider your own classroom context: What floor robot(s) do you have access to? What curriculum connections would be most valuable for your learners? What's one activity from this section you'd like to try in the coming weeks?

---

**Ready to continue?** Head to [Section 3: Tangible Interfaces](section-3.md) to explore tools where code becomes physical—Cubetto, Scottie Go!, Makey Makey, and more.

---

[← Back to Section 1](section-1.md) | [Home](index.md) | [Section 3 →](section-3.md)
