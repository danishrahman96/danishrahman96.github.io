---
title: "Design of an Actuated Upper Limb Orthosis for Patients with Neurodegenerative Diseases"
excerpt: "As part of a team of graduate engineers, I designed, modeled and simulated a 5 DOF arm orthosis to enhance reaching and grasping functionality for patients of early stage ALS and Parkinson's."
collection: personalprojects
permalink: /personalprojects/ArmOrthosis
---

The project began with an exhaustive literature review of existing orthoses, identifying the present limitations within orthosis design. The modeled orthosis is retractable and can be mounted onto a stationary chair or a wheelchair, and utilizes a series of stepper motors and electromyography sensors along the arm to optimally move the hand towards the desired location. 

<div style="display: flex;">
  <img src="/images/Orthosis1.jpg" alt="Orthosis 1" style="width: 50%;">
  <img src="/images/Orthosis2.png" alt="Orthosis 2" style="width: 50%;">
</div>
---

This motion study was broken into two aspects - a forward extension of the arm and a lateral abduction of the arm. This study also included the novel implementation of a robust control scheme to account for random forearm tremors, a common symptom of Parkinson's disease. Initial simulation through MATLAB found that the control law moved the hand to the desired end-position with a success rate of 93%. Currently, I am working on building a physical orthosis and optimizing the control scheme. You can find our paper [here](https://drive.google.com/file/d/1mLjgc84zsuDjYVY6H29e8d5glaiHPgP1/view?usp=sharing).
