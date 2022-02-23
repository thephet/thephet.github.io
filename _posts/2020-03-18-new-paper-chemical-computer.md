---
title: "New paper: A Chemical Computer"
excerpt: "Finally the BZ Chemical Computer paper is published! This has been, by far, the project I have spent most time on."
---

Finally the BZ Chemical Computer paper is published! This has been, by far, the project I have spent most time on. 
Probably because for a very long time I had no idea what I was doing, and I am not sure I do know now.

The "BZ project" as we call it (BZ from Belousov–Zhabotinsky, which is a type of oscillating chemical reaction) was started by some other people (Cooper and Donkers as they are named in the paper). 
As far as I knew the project was going OK, until Kevin (Donkers) left the group, and then the project was orphan for maybe 1-2 years, until I tried to recover it from the ashes. 
I have to say I don't know much about unconvential computation and quantum computers. 
As a computer scientist I know about your standard computers, but still today I am not sure how a quantum computer works. 

Anyway, the initial idea was that I was going to improve the platform from an engineering perspective, and then someone else was going to help me do the experiments. 
I completely revamped the platform, changed the electronics, improved the Computer Vision side of things, and use some AI to close the loop between chemistry and automation, but then, once the platform was working and it was stable enough, I did not really know how to make a "computer". 
I tried to do some basic stuff, like binary logic gates, with the BZ reaction, but the chemistry was very unstable and not very reproducible.

I was in a sort of a dead-end, and I decided to use the opportunity to learn about Deep Learning.
This project, in particular, uses Convolutional Neural Network to "learn" how the chemical reaction works from a visual perspective, and then it uses a Neural Network Autoencoder to transform between automation and chemical oscillations.

The name of the paper is ["A programmable chemical computer with memory and pattern recognition"](https://www.nature.com/articles/s41467-020-15190-3), and it was published on the journal [Nature Communications](https://www.nature.com/ncomms/), which is a journal were, for some reason, I am publishing all my major papers. And the best thing is that the article is Open Access, so if you click on that link, you can read it for free.

It has been published just as the world is being hit by the virus Covid-19, and that's why I think the "impact metrics" of the paper are not amazing (or so I hope).
Before it being published on Nature Communications, we did publish a draft version of it on [chemRxiv](https://chemrxiv.org/articles/A_programmable_chemical_computer_with_memory_and_pattern_recognition/7712564), and this "rxiv" draft did very well, with almost 11k views and 1.8k downloads, being one of the best performing papers on chemRxiv, while sadly, as said, the main paper in Nat Comms is not doing that well.
