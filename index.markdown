---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h1>{{ "Learning Agent-Aware Affordances for Closed-Loop Interaction with Articulated Objects."}}</h1>
<a href="https://asl.ethz.ch/the-lab/people/person-detail.MjY0OTk4.TGlzdC8xNTg0LDEyMDExMzk5Mjg=.html">Giulio Schiavi*</a> &nbsp; 
<a href="https://asl.ethz.ch/the-lab/people/person-detail.MjA0OTUz.TGlzdC8yMDMwLDEyMDExMzk5Mjg=.html">Paula Wulkop*</a> &nbsp; 
<a href="https://mavt.ethz.ch/people/person-detail.MjMyMjQy.TGlzdC81NTksLTE3MDY5NzgwMTc=.html">Giuseppe Rizzi</a> &nbsp; 
<a href="http://www.ott.ai/">Lionel Ott</a> &nbsp; 
<a href="https://asl.ethz.ch/the-lab/people/person-detail.Mjk5ODE=.TGlzdC8yMDI4LDEyMDExMzk5Mjg=.html">Roland Siegwart</a> &nbsp; 
<a href="http://jenjenchung.github.io/anthropomorphic/">Jen Jen Chung<sup>1</sup></a>\
\* equal contribution

Authors are with the [Autonomous Systems Lab](https://asl.ethz.ch), ETH Zurich, Switzerland.\
<sup>1</sup>Also with the [School of ITEE](https://itee.uq.edu.au/), The University of Queensland, Australia.

This paper was accepted at the [2023 IEEE International Conference on Robotics and Automation (ICRA)](https://icra2023.org/).

You can find more information here:
<a href="https://arxiv.org/abs/2209.05802">[Paper]</a> 
<a href="https://github.com/giuschio/agent_aware_affordances">[Code]</a> 
<br>

## Abstract
 Interactions with articulated objects are a challenging but important task for mobile robots. To tackle this challenge, we propose a novel closed-loop control pipeline, which integrates manipulation priors from affordance estimation with sampling-based whole-body control. We introduce the concept of agent-aware affordances which fully reflect the agent's capabilities and embodiment and we show that they outperform their state-of-the-art counterparts which are only conditioned on the end-effector geometry. Additionally, closed-loop affordance inference is found to allow the agent to divide a task into multiple non-continuous motions and recover from failure and unexpected states. Finally, the pipeline is able to perform long-horizon mobile manipulation tasks, i.e. opening and closing an oven, in the real world with high success rates (opening: 71%, closing: 72%).

## Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/A_v5GPFaLwU" title="YouTube video player" frameborder="0" allow="autoplay; picture-in-picture" allowfullscreen></iframe>
<br>

## Citation
Please cite our paper as:
```
@misc{schiavi2022learning,
  title={Learning Agent-Aware Affordances for Closed-Loop Interaction with Articulated Objects},
  author={Giulio Schiavi and Paula Wulkop and Giuseppe Rizzi and Lionel Ott and Roland Siegwart and Jen Jen Chung},
  year={2022},
}
```

## Acknowledgment
This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 101017008 ([Harmony](https://harmony-eu.org/)).