---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focus is on incorporating temporal logic formalism with machine learning framework in order to capture and alter system behaviors from data.

Formal methods are originally developed for specification and verification of software systems. These methods aim to provide mathematical analysis and proofs to system's performance. In particular, temporal logic is a formal method which is initially used for verification. 

Recent works in control field benefit from temporal logic to specify system's behavior, constraints, and task objectives for systems. Specifications written in temporal logic formalism can be used for application areas like control synthesis, motion planning. However, for many systems, specifying system's behavior can be challenging even in plain English. We can get help from system trajectories to understand the underlying rules. Inferring information from data calls machine learning and data analysis into the scene. 
---

# Safe Preference Learning

In this project, we aim to capture user preferences for driving task to generate personalized and safe behaviors. We use temporal logic formalism to specify the safety. To capture the user preferences, we utilize preference learning methods. Specifically, we ask pairwise questions that compare two behaviors.

## Relevant Publications
- A Safe Preference Learning Approach for Personalization with Applications to Autonomous Vehicles ([paper](https://ieeexplore.ieee.org/abstract/document/10465615)/[code](https://github.com/ruyakrgl/SPL-WSTL.git))
- Incorporating Logic in Online Preference Learning for Safe Personalization of Autonomous Vehicles([paper](https://dl.acm.org/doi/abs/10.1145/3641513.3650129)/ code will be available soon!)

--- 
# Classification Using Temporal Logic

In this project, we utilize temporal logic formalism to classify driving behaviors. The goal is to infer an STL formula that can distinguish two classes of behaviors. By using this formula, we can synthesise new behaviors that belong to the desired class.

## Relevant Publications
- Classification of Driving Behaviors using STL Formulas: A Comparative Study ([paper](https://doi.org/10.1007/978-3-031-15839-1_9))
---