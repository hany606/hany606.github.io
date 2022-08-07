---
layout: default
---

# Predator-prey self-play reinforcement learning

Here we describe the updates from my work on the bachelor thesis, the thesis is about "**Learning behavioural strategies for a multi-robot system in a predator-prey environment using Reinforcement Learning**"



# Thesis defense: Video results (14.06.2022)

<iframe width="560" height="315" src="https://www.youtube.com/embed/4IL2C57OIQ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

At the end of the thesis, I have managed to implement self-play simple algorithm besides multiple variations of it. Furthermore, running multiple experiments on two environments for predator-prey to evaluate the self-play implemented algorithms.

An online version of the thesis will be provided soon, as well as a publication related to the work provided in the thesis.



# Updates (15.10.2021): initial results

The basic work that I did is to implement the training scripts based on [Bansal, T., Pachocki, J., Sidor, S., Sutskever, I., & Mordatch, I. (2017). Emergent complexity via multi-agent competition. arXiv preprint arXiv:1710.03748](https://arxiv.org/abs/1710.03748), later we will introduce some modifications based on the results that we have obtained.

The environment is based on predprey environment from [evorobotpy2 by professor Stefano Nolfi](https://github.com/snolfi/evorobotpy2/blob/master/lib/predprey.cpp).


Some initial results that we have obtained:

<iframe width="560" height="315" src="https://www.youtube.com/embed/NK2yCgMo1qk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this video, we show the visualization of evaluation the agents. We have trained the agents in an alternative manner as it is described in (Bansal et al. 2017) for 50 rounds(iteration/epoch), then we visually evaluate/test the predator agent of ith round against the prey agent of ith round for all the rounds.

### Note: 

Note: the codes will be released later after obtaining the desired results
