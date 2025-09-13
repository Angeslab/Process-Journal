# Process Journal - Angelique
This process journal documents the iterative development of my wearable prototype, the Mood + Heart Insight Bracelet. The project explores how responsive technology can support emotional awareness by translating physiological signals—specifically heart rate—into intuitive mood feedback. Across Weeks 6 to 8, I applied iterative design principles by continuously refining the concept, logic, and user experience based on research, testing, and reflection. Each stage involved purposeful adjustments: from shifting away from manual mood input to implementing automated detection using rolling averages, to refining LED feedback for emotional clarity. The journal captures not just what I built, but how and why I evolved each decision—balancing technical feasibility, emotional intelligence, and user empathy throughout the design process.
## Week 6
Focus: Exploring the concept of responsive technology and brainstorm ideas for a wearable prototype.

Activities Completed
- Reviewed course materials and examples of context-aware and wearable technologies.
- Brainstormed initial ideas for a bracelet that responds to emotional states.
- Sketched early concepts combining mood input and physiological sensing.
- Identified potential use cases: emotional regulation, stress tracking.
- Began researching micro:bit capabilities.

SKETCH OF THE MOOD BRACELET:
![Sketch of Bracelet Concept](images/sketch.png)

Reflections: I was inspired by the idea of mood jewellery and combining emotional states through visible and trackable. Most wearables focus on fitness, but I wanted something that supports reflection. This week I also found my group; Jade and 

## Week 7
Focus: Refining the bracelet’s functionality and begin planning the technical implementation.

Two bracelet modes: Calm and stressed

Mood Detection Mode – automatic mood logging based on heart rate

Spike Logging Mode – detects and stores heart rate spikes

Reflection Mode – end-of-day summary via logo touch


Selected micro:bit V2 as the controller for its built-in sensors and MakeCode compatibility.

Chose pulse sensor for BPM tracking and NeoPixels for visual feedback.

Explored wearable assembly options using conductive thread and soft materials.

JAVA BLOCK IN MAKECODE:
![Java blocks](images/Java-blocks.png) 

JAVA CODE IN MAKECODE:
<p align="center" style="text-align: center;">
  <img src="images/Java-code.png" alt="Java code" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

Reflections: Automating mood detection based on BPM changes simplifies the user experience and makes the bracelet more responsive. I decided to log “Stressed” if BPM exceeds the rolling average by 15%, and “Calm” otherwise. 

## Week 8
Focus: Coding the core code for heart rate monitoring, spike detection, and mood logging.

Goals completed this week:

- Developed JavaScript code in Microsoft MakeCode to simulate BPM readings.

- Created conditional logic to log “Stressed” or “Calm” based on BPM thresholds.

- Designed LED feedback icons for each mood state.


Reflections: The rolling average method worked well for detecting spikes. I added a 15% threshold to trigger “Stressed” mood. Timestamping events will be useful for future journaling features. I also realized the importance of visual clarity—LED icons need to be intuitive and emotionally resonant.


























SKETCH OF THE MOOD BRACELET:

<p align="center" style="text-align: center;">
  <img src="images/sketch.png" alt="Sketch of Bracelet Concept" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>


JAVA BLOCK IN MAKECODE:

<p align="center" style="text-align: center;">
  <img src="images/Java-blocks.png" alt="Java blocks" style="display: block; margin-left: auto; margin-right: auto;"/>
</p>

JAVA CODE IN MAKECODE:



