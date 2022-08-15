---
layout: default
---

# Predator-prey self-play reinforcement learning

Here we describe the updates from my work on the bachelor thesis, the thesis is about "**Learning behavioural strategies for a multi-robot system in a predator-prey environment using Reinforcement Learning**"


If you like this work and intend to use this software or if the information inside has helped you in your work, I would be happy to cite it below. (Hopefully, a publication will be released later)


```
@software{Hamed_Learning_behavioral_strategies_2022,
  author = {Hamed, Hany and Klimchik, Alexandr and Nolfi, Stefano},
  doi = {10.5281/zenodo.1234},
  month = {6},
  title = {{Learning behavioral strategies for a predator and prey using Self-play Reinforcement Learning}},
  url = {https://github.com/hany606/Bachelor-Thesis22-Predator-prey-Self-Play-RL},
  version = {1.0.0},
  year = {2022}
}
```

# (15.06.2022) Thesis documents:

* Preprint: [link](https://drive.google.com/file/d/1J1bmWlP1J9skfXmwQXqdyMFVNwNfsgto/view)
* Presentation: [link](https://drive.google.com/file/d/1mgLtZNa14XSOrtyRj58-buWwY9n79iME/view)
* GitHub repository: [link](https://github.com/hany606/Bachelor-Thesis22-Predator-prey-Self-Play-RL)

# (14.06.2022) Thesis defense: Video results

<iframe width="560" height="315" src="https://www.youtube.com/embed/4IL2C57OIQ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

At the end of the thesis, I managed to implement a self-play algorithm with multiple variations of it. Furthermore, running multiple experiments on two environments for predator-prey to evaluate the self-play implemented algorithms.

An online version of the thesis will be provided soon, as well as a publication related to the work provided in the thesis.



# Updates (15.10.2021): initial results

The basic work that I did is to implement the training scripts based on [Bansal, T., Pachocki, J., Sidor, S., Sutskever, I., & Mordatch, I. (2017). Emergent complexity via multi-agent competition. arXiv preprint arXiv:1710.03748](https://arxiv.org/abs/1710.03748), later we will introduce some modifications based on the results that we have obtained.

The environment is based on predprey environment from [evorobotpy2 by professor Stefano Nolfi](https://github.com/snolfi/evorobotpy2/blob/master/lib/predprey.cpp).


Some initial results that we have obtained:

<iframe width="560" height="315" src="https://www.youtube.com/embed/NK2yCgMo1qk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this video, we show the visualization of the agent's evolution. We have trained the agents in an alternative manner as it is described in (Bansal et al. 2017) for 50 rounds(iteration/epoch), then we visually evaluate/test the predator agent of the ith round against the prey agent of ith round for all the rounds.
