---
permalink: /multi-agent-learning/
---
# Multi-Agent Learning

[Le et al. (2017)](https://arxiv.org/abs/1703.03121) applied an [imitation learning](http://realai.org/imitation-learning/) approach to jointly learn a latent coordination model of multiple agents along with their individual policies.

## Communication

Low channel bandwith pressures agents to communicate in a language with high information content. For this communication to be effective, agents should build objective internal models of the environment. In this sense, a successful language among independent agents is a powerful regularizer that reduces overfitting, and helps the agents to develop "common sense". This is a promising line of research towards language grounding.

Language can emerge as a means for agents to collaborate, communicating in discrete actions ([Foerster, Assael et al., 2016](https://arxiv.org/abs/1605.06676)) or continuous vectors ([Sukhbaatar et al., 2016](https://arxiv.org/abs/1605.07736)). The emergent language can be made more interpretable by making changes to the game environment ([Lazaridou et al., 2016](https://arxiv.org/abs/1612.07182)), and can exhibit basic compositional structure ([Mordatch & Abbeel, 2017](https://arxiv.org/abs/1703.04908)). [Das & Kottur et al. (2017)](https://arxiv.org/abs/1703.06585) introduced goal-driven training for visual question answering and dialog agents.

[Seijen et al. (2016)](https://arxiv.org/abs/1612.05159) allowed communications between agents that are organized in a hierarchical way.

To interpret agents' learned messages, [Andreas et al. (2017)](https://arxiv.org/abs/1704.06960) proposed a method to match agent language with natural language by minimizing the difference of the beliefs induced by these two languages respectively.

Symbolic communication between neural networks can also be learned within an agent, as proposed in [deep symbolic reinforcement learning](https://arxiv.org/abs/1609.05518).

## Reinforcement Learning

[Leibo & Zambaldi et al. (2017)](https://arxiv.org/abs/1702.03037) employed multi-agent deep Q-learning to model the emergence of cooperation and conflict in sequential social dilemmas.

[Foerster & Farquhar et al. (2017)](https://arxiv.org/abs/1705.08926) propose the counterfactual multi-agent (COMA) policy gradient method that uses a centralized critic and decentralized actors to optimize the agents' policies. Using a counterfactural baseline, each agent learns from a reward that compares the global reward to the reward received when the action of the agent is replaced with a default action.

## References

* 2017 May 31, Serhii Havrylov and Ivan Titov. [Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols](https://arxiv.org/abs/1705.11192). *arXiv:1705.11192*.
* 2017 May 24, Jakob Foerster, Gregory Farquhar, Triantafyllos Afouras, Nantas Nardelli, and Shimon Whiteson. [Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926). *arXiv:1705.08926*.
* 2017 April 23, Jacob Andreas, Anca Dragan, and Dan Klein. [Translating Neuralese](https://arxiv.org/abs/1704.06960). *arXiv:1704.06960*. [code](https://github.com/jacobandreas/neuralese).
* 2017 April 3, Romain Laroche, Mehdi Fatemi, Joshua Romoff, and Harm van Seijen. [Multi-Advisor Reinforcement Learning](https://arxiv.org/abs/1704.00756). *arXiv:1704.00756*.
* 2017 March 29, Peng Peng, Quan Yuan, Ying Wen, Yaodong Yang, Zhenkun Tang, Haitao Long, and Jun Wang. [Multiagent Bidirectionally-Coordinated Nets for Learning to Play StarCraft Combat Games](https://arxiv.org/abs/1703.10069). *arXiv:1703.10069*.
* 2017 March 20, Abhishek Das, Satwik Kottur, José M. F. Moura, Stefan Lee, and Dhruv Batra. [Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning](https://arxiv.org/abs/1703.06585). *arXiv:1703.06585*.
* 2017 March 15, Igor Mordatch and Pieter Abbeel. [Emergence of Grounded Compositional Language in Multi-Agent Populations](https://arxiv.org/abs/1703.04908). *arXiv:1703.04908*. [blog](https://openai.com/blog/learning-to-communicate/).
* 2017 March 9, Hoang M. Le, Yisong Yue, and Peter Carr. [Coordinated Multi-Agent Imitation Learning](https://arxiv.org/abs/1703.03121). *arXiv:1703.03121*.
* 2017 February 17, Serhii Havrylov, and Ivan Titov. [Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols](https://openreview.net/forum?id=SkaxnKEYg). *OpenReview*.
* 2017 February 10, Joel Z. Leibo, Vinicius Zambaldi, Marc Lanctot, Janusz Marecki, and Thore Graepel. [Multi-agent Reinforcement Learning in Sequential Social Dilemmas](https://arxiv.org/abs/1702.03037). *arXiv:1702.03037*.
* 2016 December 21, Angeliki Lazaridou, Alexander Peysakhovich, and Marco Baroni. [Multi-Agent Cooperation and the Emergence of (Natural) Language](https://arxiv.org/abs/1612.07182). *arXiv:1612.07182*.
* 2016 December 15, Harm van Seijen, Mehdi Fatemi, Joshua Romoff, and Romain Laroche. [Separation of Concerns in Reinforcement Learning](https://arxiv.org/abs/1612.05159). *arXiv:1612.05159*.
* 2016 November 10, Emilio Jorge, Mikael Kågebäck, Fredrik D. Johansson, and Emil Gustavsson. [Learning to Play Guess Who? and Inventing a Grounded Language as a Consequence](https://arxiv.org/abs/1611.03218). *arXiv:1611.03218*.
* 2016 May 25, Sainbayar Sukhbaatar, Arthur Szlam, and Rob Fergus. [Learning Multiagent Communication with Backpropagation](https://arxiv.org/abs/1605.07736). *arXiv:1605.07736*.
* 2016 May 21, Jakob N. Foerster, Yannis M. Assael, Nando de Freitas, and Shimon Whiteson. [Learning to Communicate with Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1605.06676). *arXiv:1605.06676*.
