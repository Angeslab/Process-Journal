# Process Journal - Angelique Haynes (1184477), Group: Jade and Sandikshya,  Project: Mood Bracelet
This process journal documents the iterative development of a wearable prototype for Task 2 and Task 3. The idea for the project created with in cooperation with my group for these tasks is the 'Mood Bracelet'. The project explores how responsive technology can support emotional awareness by translating physiological signals, specifically heart rate, into intuitive mood feedback. Across Weeks 6 to 8, I applied iterative design principles by continuously refining the concept, logic, research and reflection. Each stage involved purposeful improvements and adjustments: from shifting away from manual mood input to implementing automated detection using rolling averages for heart rate, to refining LED feedback for emotional clarity. 

## Week 6: Concept Exploration and Initial Design
Focus: Exploring the concept of responsive technology and brainstorm ideas for a wearable prototype.

Activities Completed
- Reviewed course materials and examples of context-aware and wearable technologies.
- Brainstormed initial ideas for a bracelet that responds to emotional states.
- Researched similar projects
- Sketched a prototype design.
- Identified potential use cases: emotional regulation, stress tracking.
- Began researching micro:bit capabilities.
- Developed JavaScript code in Microsoft MakeCode to simulate BPM readings.
- Created conditional logic to log “Stressed” or “Calm” based on BPM thresholds.
- Designed LED feedback icons for each mood state.

SKETCH OF THE MOOD BRACELET:
<p align="center" style="text-align: center;">
  <img src="images/sketch.png" alt="Sketch of Bracelet Concept" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>


Reflections: I was inspired by the idea of mood jewellery and combining emotional states through visible and trackable. Most wearables focus on fitness, but I wanted something that supports reflection. This week I also found my group; Jade and Sandikshya. We all agreed on the idea and the direction of the project from the combination of our own individual research into the topic.


## Week 7: Functional Planning and Core Coding
Focus: Refining the bracelet’s functionality and begin planning the technical implementation. As well as, coding the core code for heart rate monitoring, spike detection, and mood logging.

- Two bracelet modes: Calm represented as the colour blue and stressed represented as the colour red.

- Mood Detection Mode – Automatic mood logging based on heart rate the could be detecting heart rate every 10-15 seconds.

- Spike Logging Mode – Detects and stores heart rate spikes throughout the day.

- Reflection Mode – End-of-day summary showcasing any major heart rate spikes

- Selected micro:bit V2 as the controller for its built-in sensors and MakeCode compatibility.

- Explored wearable assembly options using conductive thread and soft materials/fabrics.


JAVA BLOCK IN MAKECODE:
<p align="center" style="text-align: center;">
  <img src="images/Java-blocks.png" alt="Java blocks" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>


JAVA CODE IN MAKECODE:
<p align="center" style="text-align: center;">
  <img src="images/Java-code.png" alt="Java code" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

Reflections: Automating mood detection based on BPM changes simplifies the user experience and makes the bracelet more responsive. I decided to log “Stressed” if BPM exceeds the rolling average by 15%, and “Calm” otherwise. I also created code in makecode of both block form and javascript as seen above. I am unsure whether this code works or dos not as I haven't gained access to a micro:bit yet, but the main structure of code is complete and can be worked on if needed during the next step of the prototype making process for Task 3.


## Week 8: Presentation Development and Journal Framing
Focus: Start and completion of PowerPoint and Script components

Activites completed this week and with group members:

- Developed the PowerPoint and completed, checks off all points from the rubric.
- Created basic script and continuing to work on it such as adding details; in a collaborative workpace.
- Wrote introduction paragraph for this jorunal.

POWERPOINT PRESENTATION CREATED IN CANVA:
<p align="center" style="text-align: center;">
  <img src="images/powerpoint.png" alt="powerpoint" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

Reflections: This week, our group successfully completed the PowerPoint presentation, ensuring it aligned with all rubric requirements for content, clarity, and visual design. We also began drafting the presentation script in a shared workspace, allowing for real-time collaboration and ongoing refinement. The script currently covers key points and is being expanded with transitions and supporting detail. Additionally, I wrote the introduction paragraph for this journal to frame our progress and set the tone for reflective documentation.


## Week 9: Setup and Bluetooth Communication
Focus: This week focused on initiating the hardware development of the wearable prototype using the ESP32 microcontroller. I also explored theoretical frameworks such as Human-Computer Interaction (HCI) and embodied cognition to inform the design.

Technical Progress:
- Programmed the ESP32 to serve as the core of the wearable bracelet.
- Implemented Bluetooth communication protocols to enable wireless data exchange between the bracelet and a mobile/web interface.
- Began testing connectivity and responsiveness of the ESP32 in a wearable context.

Conceptual Development: 
- Considered how the bracelet could respond to both environmental and physiological data to support staff wellbeing.
- Reflected on embodied cognition and how physical sensations (e.g. stress, calm) could be translated into wearable feedback.

Reflections: Bluetooth integration was a foundational step that enabled real-time interaction. The theoretical lens of embodied cognition reinforced the importance of designing for both emotional and physical responsiveness in high-stress environments like hospitality.



## Week 10: LED Feedback Prototyping with ESP32
Focus: This week I explored visual feedback mechanisms using LED lights controlled by the ESP32 to represent emotional states or environmental triggers.

Technical Progress
- Programmed LED light patterns (e.g. soft blue for calm, flashing red for stress).
- Tested brightness, color, and responsiveness to simulated input.
- Evaluated the feasibility of integrating LEDs into the bracelet design.

Reflections: LEDs provided a simple and intuitive feedback method. However, I noted challenges with visibility in bright environments and power consumption. This experimentation helped clarify the need for a more expressive and integrated display solution.

<p align="center" style="text-align: center;">
  <img src="images/redlightgreenlight.mov" alt="LEDs" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

## Week 11: Transition to Micro:bit and Emotional Display
Focus: After evaluating the limitations of the ESP32 for visual output, I transitioned to using the micro:bit for its built-in LED matrix and simplified programming environment.

Technical Progress:
- Reprogrammed the prototype using the micro:bit.
- Created emotive icons on the LED matrix: a happy face for calm and a sad face for stress.
- Mapped emotional states to sensor input thresholds.

Reflections: The micro:bit’s built-in display offered a more compact and expressive solution than external LEDs. This shift improved the bracelet’s usability and streamlined the design, making it more suitable for real-world deployment.



## Week 12: Pulse Sensor Integration and Design Refinement
Focus: This week focused on integrating physiological sensing and finalizing the physical layout of the bracelet.

Technical Progress:
- Integrated a pulse sensor with the micro:bit and merged it with the existing emotional display code.
- Conducted placement tests and determined that the pulse sensor must be positioned under a finger (not on the wrist) for accurate readings.
- Adjusted the bracelet design to accommodate this requirement, considering modular or clip-on extensions.

Reflections: Integrating the pulse sensor brought the project full circle, enabling the bracelet to respond to real-time physiological data. This final integration phase clarified the physical constraints of the design and informed a more ergonomic and accurate layout.













