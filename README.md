# erc-hackathon

# Electronics

During the hackathon, my journey began with learning Arduino programming and using Tinkercad for simulations. My initial idea was quite basic, which meant that I needed some time to grasp the concepts. As a team, we dove into exploring metal detectors, understanding their working principles, and acknowledging their limitations through sources like YouTube and various other platforms.

Simultaneously, I was delving into the mechanics of a differential drive system. We researched the types of materials commonly found in mines, which greatly influenced the sensitivity required for our mine detector.

In the initial phases, I contemplated utilizing two 555 timers to generate a square AC wave. The plan was to then convert this wave into a sinusoidal form using PWM and a combination of different resistors and capacitors. However, this approach seemed a bit intricate. Considering that PWM could be efficiently managed by Arduino itself, I switched to using MOSFETs for switching purposes. Their ability to operate at high switching frequencies made them a suitable choice.

My next learning point was the 7-segment display. While attempting to operate it solely with an Arduino, I realized that it would consume a significant number of pins. To simplify this, I decided to incorporate the CD4511 7-segment decoder IC. This IC takes binary code as input and effectively drives the 7-segment display.

The journey didn't stop there. I took the initiative to install Eagle, a PCB design software. Through various online resources and YouTube tutorials, I grasped the fundamentals of PCB designing and learned how to navigate the Eagle software effectively.

This hackathon experience enriched my knowledge of electronics, from programming Arduino and utilizing simulation tools like Tinkercad, to understanding the intricacies of different components like MOSFETs and 7-segment display decoders. It also introduced me to the world of PCB design, sparking a new realm of possibilities for future projects.
