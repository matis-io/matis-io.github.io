---
layout: post
title:  "Gamepad as an Instrument"
date:   2019-09-04
tags: [music, tech]
---

**Unlocking the Creative Potential of Unconventional Inputs**

![DualShock Controller](/images/MaxDualShock.png)

I was interested in learning how to use Max for Live, and while searching for an interesting project, I discovered the possibility of connecting a game controller and using its input in Max for Live. Realising the potential of controlling music with an unconventional controller, I decided to utilise my Sony DualShock 4 game controller - an input device initially designed for video games, but with untapped potential for music production. My goal was to transform the controller's input messages into MIDI data that could be used to control instruments within Ableton Live, allowing me to use these unique ergonomics and input capabilities to manipulate multiple parameters at once using different finger movements.

**Diving into Max for Live**

To kickstart my learning, I turned to two invaluable resources: the comprehensive documentation within the Max program itself, and a course from Kadenze called "Programming Max: Structuring Interactive Software for Digital Arts." The course, created in collaboration with Stanford University, proved to be an excellent starting point, as it delved into the fundamental concepts and techniques of working with Max. With these, I was able to gradually build my understanding and start crafting the necessary patches to connect the game controller to Ableton Live.

**Mapping the Controller**

![Controller Mapping](/images/MaxL2andR2.png)

Max for Live allowed me to create and connect different "objects" to form custom devices. These could seamlessly integrate with the Live software, enabling me to translate the inputs from the game controller into meaningful MIDI data

One of the key steps in this project was mapping the various inputs from the game controller to the desired parameters within Ableton Live. This involved a meticulous process of identifying each button, trigger, and analogue stick, and then assigning them to specific MIDI messages or control changes.

![Controller Patch](/images/MaxPatch.png)

Through a combination of sub-patches and routing, I was able to create a well-organised and intuitive system that allowed me to control various aspects of my music, from note triggering to real-time parameter manipulation. The ability to fine-tune the mapping and experiment with different configurations was crucial in finding the right balance between functionality and creative expression.

**Integrating with Ableton Live**

![Max Device](/images/MaxDDevice.png)

With the Max for Live patch in place, the final step was to seamlessly integrate the game controller into my Ableton Live workflow. By routing the MIDI output from the Max for Live device to a virtual MIDI interface, I was able to map the various control changes to specific parameters within Ableton's built-in instruments and effects.

The result was a highly customisation and responsive interface that allowed me to explore new ways of interacting with my music. Whether it was fine-tuning the cutoff frequency of a synth or adjusting the LFO rate in real-time, the game controller provided a level of tactile control and immediacy that was both engaging and inspiring.

The whole Max device:

![Full Max Device](/images/MaxDeviceFull.png)

**Conclusion**

Along the process I was able to learn all the nits and bits of operating Max for Live, but also discovered I was able to approach music production with a fresh perspective, experimenting with new ways of manipulating sound and shaping the overall musical experience.

The game controller, with its unique input capabilities, encouraged me to think beyond the confines of the keyboard and mouse, and to explore more intuitive and expressive methods of music creation.

So, if you're looking to add a fresh perspective to your music creation process while learning a new tool, I encourage you to consider integrating and exploring the possibilities of game controllers and other unconventional input devices with Max for Live. The journey may be challenging, but the rewards can be truly transformative.

I've uploaded the whole Max for Live project on my [GitHub](https://github.com/matis-io/MdCR){:target="\_blank"}, where you can explore it further. If you open the patch in Max you will also see a discription of all the devices as I've documented everything.

![DualShock Controller](/images/MaxDeviceFull.png)

**2024 update**: Max 8.6 now introduces "gamepad" object, so the very long process of maping the controller is no longer neccessary in the newer version. However, it is still a good way of learning how to program in Max.