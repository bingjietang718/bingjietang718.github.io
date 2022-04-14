---
layout: post
title:  "Learning Multi-action Tabletop Rearrangement Policies"
date:   2022-03-27
image: /images/icra2022.png
categories: research
author: "Bingjie Tang, Gaurav S. Sukhatme"
authors: "<strong>Bingjie Tang</strong>, Gaurav S. Sukhatme"
venue: "IEEE International Conference on Robotics and Automation (IROS), in submission."
pdf: /pdfs/rearrange2022.pdf
video: https://youtu.be/NpjiBYt39bw
---
The ability to rearrange a physical environment depends to varying degrees on perceptual skill, the ability to navigate unstructured environments, manipulate objects effectively, and long-horizon task planning. We propose a feature-based method that jointly learns two action primitives and a  rearrangement planning policy in a table-top setting. Two separate fully-connected networks map visual observations to actions and another deep neural network learns rearrangement planning conditioned on the goal specification, perceptual input and selected action primitive.