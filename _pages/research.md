---
permalink: /research/
title: "Research"
author_profile: true
---

{% include base_path %}
## Assistive VR Gym: Interactions with Real People to Improve Virtual Assistive Robots [[Paper]](http://arxiv.org/pdf/2007.04959.pdf)[[Code]](http://github.com/Healthcare-Robotics/assistive-vr-gym)

*Georgia Tech, Advised by Prof. Charlie Kemp, Aug 2019 - Aug 2020*

<details><summary>Abstract</summary>Versatile robotic caregivers could benefit millions of people worldwide, including older adults and people with disabilities. Recent work has explored how robotic caregivers can learn to interact with people through physics simulations, yet transferring what has been learned to real robots remains challenging. Virtual reality (VR) has the potential to help bridge the gap between simulations and the real world. We present Assistive VR Gym (AVR Gym), which enables real people to interact with virtual assistive robots. We also provide evidence that AVR Gym can help researchers improve the performance of simulation-trained assistive robots with real people. Prior to AVR Gym, we trained robot control policies <em>Original Policies</em>) solely in simulation for four robotic caregiving tasks (robot-assisted feeding, drinking, itch scratching, and bed bathing) with two simulated robots (PR2 from Willow Garage and Jaco from Kinova). With AVR Gym, we developed <em>Revised Policies</em> based on insights gained from testing the Original policies with real people. Through a formal study with eight participants in AVR Gym, we found that the Original policies performed poorly, the Revised policies performed significantly better, and that improvements to the biomechanical models used to train the Revised policies resulted in simulated people that better match real participants. Notably, participants significantly disagreed that the Original policies were successful at assistance, but significantly agreed that the Revised policies were successful at assistance. Overall, our results suggest that VR can be used to improve the performance of simulation-trained control policies with real people without putting people at risk, thereby serving as a valuable stepping stone to real robotic assistance.</details>

\\

<iframe src="https://www.youtube.com/embed/tcyPMkAphNs" allowfullscreen="allowfullscreen" width="336" height="188" frameborder="0"></iframe>


## Active Hierarchical Imitation and Reinforcement Learning in Continuous Tasks [[Report]](https://10d01914-837c-42f4-9cd4-1908566f2b48.filesusr.com/ugd/387059_217c208d7245449d87fd75500383a4bb.pdf)[[Code]](https://github.com/chrisyrniu/active_hierarchical_imitation_and_reinforcement_learning)

*Georgia Tech, Advised by Prof. Matthew Gombolay, Aug 2019 - Dec 2019*

<details><summary>Abstract</summary> Hierarchical Reinforcement Learning (HRL) has demonstrated significant success in solving complex tasks, such as robot manipulation and robot navigation. HRL splits the task into a hierarchy of subtasks, which can be learned using RL. However, HRL is still suffering from sample inefficiency and unstable training process. One way to improve the sample inefficiency is to use expert demonstrations to guide agents to take appropriate actions. In this paper, we first proposed a Hierarchical Imitation and Reinforcement Learning (HIRL) framework that allows the agents to use expert demonstrations to learn multiple levels of policies in parallel in continuous space. In our framework, the low-level controller interacts directly with the environment while the high-level controller generates subgoals for the low-level controller. We utilized Data Aggregation (DAgger) with expert demonstrations to learn the high-level controller and revised Deep Deterministic Policy Gradient (DDPG) to learn the low-level controller. We then developed a revised Active HIRL (AHIRL) framework by implementing two active learning methods: Noise injection and Multiple Policy to reduce uncertainty. We demonstrated that both approaches have higher sample efficiency and performance accuracy than the state-of-art HRL approach, and AHIRL further reduces expert cost. </details>

\\

<iframe src="https://www.youtube.com/embed/pFVh4vkhCLo" allowfullscreen="allowfullscreen" width="336" height="188" frameborder="0"></iframe>

## Autonomous Robot for Garbage Grasp and Classification [[Poster]](http://drive.google.com/file/d/1JWhuUt3SpoYBA6qzqesEBO1SvfQiPFfZ/view?usp=sharing)

*Univ. Michigan, Advised by Prof. Chad Jenkins, Jan 2019 - Apr 2019*

<details><summary>Abstract</summary>Garbage classification has always been a focus in environmental protection research. According to a study by Columbia University, Americans trash seven pounds of material per person every single day—that is 2,555 pounds of material per person per year. A large proportion of waste materials are ultimately dumped into landfills or 
burned by incinerators. This one-way treatment without discrimination heavily pollutes our environment and wastes recyclable resources. Our team designed an autonomic garbage classification robot which is capable of detecting garbage, recognizing type of garbage, and putting it into the right category. With the help of robots, we are able to improve the garbage sorting process, reducing recyclable waste and the cost of human resource.</details>

\\

<iframe src="https://www.youtube.com/embed/doEAyVBbbBg" allowfullscreen="allowfullscreen" width="336" height="188" frameborder="0"></iframe>