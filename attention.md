---
permalink: /attention/
---
# Attention

## Machine Translation

Attention is a powerful mechanism that can be added to a basic encoder-decoder architecture to achieve decent performance in machine translation ([Bahdanau et al., 2016](https://arxiv.org/abs/1409.0473)). [Vaswani et al. (2017)](https://arxiv.org/abs/1706.03762) are able to establish a new single-model state-of-the-art BLEU score using attention mechanisms, dispensing with recurrence and convolutions entirely.

### References

* 2017 June 12, Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, and Illia Polosukhin. [Attention Is All You Need](https://arxiv.org/abs/1706.03762). *arXiv:1706.03762*.
* 2016 May 19, Dzmitry Bahdanau, Kyunghyun Cho, and Yoshua Bengio. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473). *arXiv:1409.0473*.

## Visual Attention

[Li et al. (2017)](https://arxiv.org/abs/1703.10332) added an additional continue/stop action to the Recurrent Visual Attention Model ([Mnih et al., 2014](https://arxiv.org/abs/1406.6247)), and saved the average computation time.

[Ablavatski et al. (2017)](https://arxiv.org/abs/1706.03581) proposed a fully differentiable model that employs the Spatial Transformer ([Jaderberg et al., 2016](https://arxiv.org/abs/1506.02025)) as the visual attention mechanism.

[Kosiorek et al. (2017)](https://arxiv.org/abs/1706.09262) propose a visual attention framework for tracking objects. Their spatial attention mechanism is based on 2-dimensional Gaussian grid filters. Terms for auxiliary tasks are augmented to the loss function to improve training convergence.

### References

* 2017 June 28, Adam R. Kosiorek, Alex Bewley, and Ingmar Posner. [Hierarchical Attentive Recurrent Tracking](https://arxiv.org/abs/1706.09262). *arXiv:1706.09262*.
* 2017 June 12, Artsiom Ablavatski, Shijian Lu, and Jianfei Cai. [Enriched Deep Recurrent Visual Attention Model for Multiple Object Recognition](https://arxiv.org/abs/1706.03581). *arXiv:1706.03581*.
* 2017 May 16, Dieterich Lawson, George Tucker, Chung-Cheng Chiu, Colin Raffel, Kevin Swersky, and Navdeep Jaitly. [Learning Hard Alignments with Variational Inference](https://arxiv.org/abs/1705.05524). *arXiv:1705.05524*.
* 2017 March 30, Zhichao Li, Yi Yang, Xiao Liu, Shilei Wen, and Wei Xu. [Dynamic Computational Time for Visual Attention](https://arxiv.org/abs/1703.10332). *arXiv:1703.10332*. [code](https://github.com/baidu-research/DT-RAM).
* 2016 May 19, Dzmitry Bahdanau, Kyunghyun Cho, and Yoshua Bengio. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473). *arXiv:1409.0473*.
* 2016 April 19, Kelvin Xu, Jimmy Ba, Ryan Kiros, Kyunghyun Cho, Aaron Courville, Ruslan Salakhutdinov, Richard Zemel, and Yoshua Bengio. [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044). *arXiv:1502.03044*.
* 2016 February 4, Max Jaderberg, Karen Simonyan, Andrew Zisserman, and Koray Kavukcuoglu. [Spatial Transformer Networks](https://arxiv.org/abs/1506.02025). *arXiv:1506.02025*.
* 2015 August 20, William Chan, Navdeep Jaitly, Quoc V. Le, and Oriol Vinyals. [Listen, Attend and Spell](https://arxiv.org/abs/1508.01211). *arXiv:1508.01211*.
* 2015 June 24, Jan Chorowski, Dzmitry Bahdanau, Dmitriy Serdyuk, Kyunghyun Cho, and Yoshua Bengio. [Attention-Based Models for Speech Recognition](https://arxiv.org/abs/1506.07503). *arXiv:1506.07503*.
* 2015 February 21, Yichuan Tang, Nitish Srivastava, and Ruslan Salakhutdinov. [Learning Generative Models with Visual Attention](https://arxiv.org/abs/1312.6110). *arXiv:1312.6110*.
* 2014 June 24, Volodymyr Mnih, Nicolas Heess, Alex Graves, and Koray Kavukcuoglu. [Recurrent Models of Visual Attention](https://arxiv.org/abs/1406.6247). *arXiv:1406.6247*.
