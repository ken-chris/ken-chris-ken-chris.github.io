---
title: ReHEarSE - Recognizing Hidden-in-the-Ear Silent Expressions using Ultrasonic Occluded Ear Canal Deformation Analysis 
author: Ken
date: 2023-09-15 11:33:00 +0800
categories: [Research]
tags: [audio, ultrasonic sensing, earbuds, HCI]
math: true
mermaid: true
image:
  path: /assets/img/ACP.png
  width: 600
  height: 400
  alt: 
description: Silently spoken (i.e., mouthed) letter recognition using an ultrasonic Orthogonal Frequency Division Multiplexing (OFDM) chirp, emitted by an earbud, to detect small changes in ear canal deformation resulting from jaw, tongue, and facial muscle movement.
venue: In Submission
paper:  
video: 

---


# Abstract:
Silent speech interaction (SSI) allows users to discreetly input text without using their hands. Existing wearable SSI systems typically require custom devices and are limited to a small lexicon, limiting their utility to a small set of command words.  This work proposes ReHEarSE, an earbud-based ultrasonic SSI system capable of generalizing to words that do not appear in its training dataset, providing support for nearly an entire dictionary's worth of words. As a user silently spells words, ReHEarSE uses autoregressive features to identify subtle changes in ear canal shape. ReHEarSE infers words using a deep learning model trained to optimize connectionist temporal classification (CTC) loss with an intermediate embedding that accounts for different letters and transitions between them. We find that ReHEarSE recognizes unseen words with an accuracy of \pmnice{89.3}{10.9}\%.


