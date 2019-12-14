---
permalink: /research/
title: "Research"
toc_label: Research timeline
toc_icon: dna
toc: true
classes: wide
---

## Introduction

Life appeared on planet Earth around 4 billion of years ago. 
How did this happen is still unknown. My research does not try to answer this question, but it tries to be inspired by it.
I am an engineer, not a chemist or a biologist, and as a scientist my favourite areas of research are robotics (bio-inspired robotics, modular robotics and 3D-printing), Artificial Intelligence and Computer Vision.

## Main research questions

If life happened at least once, can we study the processes that originated it and use them to engineer artificial life?
Even though we don't exactly know what happened, chemists are developing hypotheses to investigate the different steps required to go from chemistry to biology.
For example, chemist can create molecules or chemical entities that can divide, replicate, follow trails or activate themselves under different scenarios.
Can we apply similar procedures to electronic robots?
Or, can we take these chemical entities and create artificial life from the bottom-up using swarm or modular robotics?

![image-center](/assets/images/evodrop.png){: .align-center}
*In current experiments I am trying to create droplets that can have "life-like" behaviours. In the near future I plan to design swarms of droplets that can act collectively. In the far future, artificial life forms will be built from the bottom-up using ensembles of protocells.*

My second main research question is not directly related to life itself, but to "intelligence" or "cognition", because the origin of intelligence is as important as the origin of life.
Moreover, I don't fully agree with the "primordial soup" theory in terms of how things got kickstarted. The chances of complex structures appearing "by change" because the basic building blocks were already in the soup are extremelly low.
I think that chemistry adquired "intelligence" to some degree, and this intelligence guided it to survival through chemical evolution against other similar chemical cycles. 
Therefore, if I want to build robots based on how life appeared on planet Earth, my research will also need to embody intelligence into them.
The main research question then would be, "how can chemistry compute?" or "how can chemistry be intelligent?"

![image-center](/assets/images/smartdrop.png){: .align-center}
*In current experiments I am trying to create minimal chemical computers using oscillating reactions. In the future this chemical computers will be inserted into droplets, and they will create intelligence swarms of droplets, where each droplet has different attributes, and where swarm intelligence will emergence from it.*

## Current research

After many years working on real-world systems, my focus now is on creating generative systems that can simulate work chemistry works.
Once of the few problems of using real-world systems is their throughput.
Even if you have a robot working 24/7, the data it will produce won't be enough to train Deep Learning algorithms using Reinforce Learning, for example.
If chemistry can be simulated, the throughput can be very high, and then deep learning can be used to extract features from the system.

The objective of my current research would then be to create generative systems that can simulate chemistry, and then train it <i>in-silico</i> to learn how to create artificial life from the bottom-up.
Once a final result is obtained, then it can be tested on a petri dish.

## Research highlights
### Evolution of droplets in a robotic platform (2014)

This research described the first fully functional robot built using a 3D-printer and DIY software and hardware. 
This robot could execute thousands of experiments working 24/7, and it also showed a closed-loop approach to data science, where the platform could decide which experiments to do, execute them, analyse the results, and decide again. 
All this was implemented into a single robot using AI, Computer Vision, 3D-printing and DIY projects like Arduino.

![image-center](/assets/images/dropbot1.jpg){: .align-center}
*Left: A Genetic Algorithm was used to optimize droplet behaviours. Center: This robot was built using a 3D printer. Right: It could generate droplets and characterize them using Computer Vision*

The scientific output of this robot was to show that simple oil droplets could undergo an evolutionary process.
To my knowledge, it is the first time this has been proved. 
This is important because we know that to be alive a cell needs three components: information molecules such as DNA, mechanism molecules such as proteins, and an encapsulation or body.
How these three components came together into a cell is a very big question not answered yet, but my research showed that simple oil droplets (simple bodies) could undergo evolution in order to acquire more complex behaviours without the need for proteins or RNA/DNA. 

Link: [Evolution of droplets in a chemo-robotic platform. Nat Comms 2014](https://www.nature.com/articles/ncomms6571)

### Evolution of droplets in differente environments using a 3D-printed device (2017)

This research was a direct follow-up of the previous one, and it had two main differences that improved the results.

The main difference is that the robotic platform was completely redesigned, and the full functionality of the robot described before was encapsulated into a single 3D-printed device, manufactured using polypropylene.
This meant that the platform did not need belts, pulleys or motors, although it was still connected to syringe pumps to move the liquid in and out.

![image-center](/assets/images/flowbot.jpg){: .align-center}
*A 3D-printed device using PP was manufactured. It had the same functionality as the robot described before. Because it was fully 3D-printed, the experimental arena could have different architectures.*

The second main difference is directly related to new 3D-printed device. Because we were not using anymore glass petri dishes, but 3D-printed "arenas", we could 3D-print into the arena different structures or mazes, and test how the droplets would behave in them.
This way, using this device, we could test the impact of environment changes on evolution.
This is very important from an "origin of life" perspective, because we know that planet Earth suffered sudden environment changes, like for example the appearance of oxygen, or the different asteroids, and life had to evolve through these different events.

Link: [Adaptive artificial evolution of droplet protocells in a 3D-printed fluidic chemorobotic platform with configurable environments. Nat Comms 2017](https://www.nature.com/articles/s41467-017-01161-8)

## Background

In Catalunya, the public catalan TV ([TV3/C33](https://en.wikipedia.org/wiki/Televisi%C3%B3_de_Catalunya)) mostly played japanese cartoons on TV when I was a kid, and I watched cartoons like [Mazinger Z](https://en.wikipedia.org/wiki/Mazinger_Z), [Neon Genesis Evangelion](https://en.wikipedia.org/wiki/Neon_Genesis_Evangelion) or my favourite: [Doraemon](https://en.wikipedia.org/wiki/Doraemon). That is when I decided that I would like to design and build robots, and therefore I started a degree on Computer Engineering. Little I knew that during those years the word "robot" would never appear, and everything would be about maths, algorithms and software design. Nevertheless that was my introduction to AI and Neural Networks.

Soon after that I decided to go to Denmark to obtain a MSc in Robotics, and it was then when I really worked on Robotics, and I really enjoyed learning about Computer Vision, a topic I barely knew anything about before I started my masters. 
During one of the lectures of the AI course we were given a presentation by [Martin Hanczyc](http://www.martinhanczygc.com), a biochemist who was very interested in the Origin of Life, and who was studying how oil droplets could be used to model protocells. 
The institute were I was doing my masters was one of the leading research centers in the world of [modular robotics](http://modular.tek.sdu.dk/).
It is then when I had the idea of "Can we build a robot from droplets in a similar way to how modular robots are built?".
I asked my to AI supervisor [Kasper Stoy](https://www.itu.dk/~ksty/) about the possibility of developing a project around this topic, and he is the person who introduced me to the world of 3D-printing, and the idea of automating chemical experiments, in what I called back in the day "3D printing artificial life".

After that I moved to Glasgow to do a PhD with [prof. Lee cronin](http://www.croninlab.com), and I continued developing the idea of droplets as robots.
Lee was also (and still is) very interesting in the idea of building chemical computers, and as interesting as it would be to build a chemical computer that can achieve supremacy, my interest went beyond that, to the idea of "how did intelligence happened"? "how did Chemistry became smart?"
