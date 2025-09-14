# Process Journal - Angelique
This process journal documents the iterative development of a wearable prototype for Task 2 and Task 3. The idea for the project created with in cooperation with my group for these tasks is the 'Mood Bracelet'. The project explores how responsive technology can support emotional awareness by translating physiological signals, specifically heart rate, into intuitive mood feedback. Across Weeks 6 to 8, I applied iterative design principles by continuously refining the concept, logic, research and reflection. Each stage involved purposeful improvements and adjustments: from shifting away from manual mood input to implementing automated detection using rolling averages for heart rate, to refining LED feedback for emotional clarity. 

## Week 6
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


## Week 7
Focus: Refining the bracelet’s functionality and begin planning the technical implementation. As well as, coding the core code for heart rate monitoring, spike detection, and mood logging.

Two bracelet modes: Calm represented as the colour blue and stressed represented as the colour red.

Mood Detection Mode – Automatic mood logging based on heart rate the could be detecting heart rate every 10-15 seconds.

Spike Logging Mode – Detects and stores heart rate spikes throughout the day.

Reflection Mode – End-of-day summary showcasing any major heart rate spikes

Selected micro:bit V2 as the controller for its built-in sensors and MakeCode compatibility.

Explored wearable assembly options using conductive thread and soft materials/fabrics.


JAVA BLOCK IN MAKECODE:
<p align="center" style="text-align: center;">
  <img src="images/Java-blocks.png" alt="Java blocks" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>


JAVA CODE IN MAKECODE:
<p align="center" style="text-align: center;">
  <img src="images/Java-code.png" alt="Java code" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

Reflections: Automating mood detection based on BPM changes simplifies the user experience and makes the bracelet more responsive. I decided to log “Stressed” if BPM exceeds the rolling average by 15%, and “Calm” otherwise. I also created code in makecode of both block form and javascript as seen above. I am unsure whether this code works or dos not as I haven't gained access to a micro:bit yet, but the main structure of code is complete and can be worked on if needed during the next step of the prototype making process for Task 3.


## Week 8
Focus: Start and completion of PowerPoint and Script components

Goals completed this week:

- Developed JavaScript code in Microsoft MakeCode to simulate BPM readings.

- Created conditional logic to log “Stressed” or “Calm” based on BPM thresholds.

- Designed LED feedback icons for each mood state.

POWERPOINT PRESENTATION CREATED IN CANVAS:
<p align="center" style="text-align: center;">
  <img src="images/powerpoint.png" alt="powerpoint" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

Reflections: The rolling average method worked well for detecting spikes. I added a 15% threshold to trigger “Stressed” mood. Timestamping events will be useful for future journaling features. I also realized the importance of visual clarity—LED icons need to be intuitive and emotionally resonant.






























