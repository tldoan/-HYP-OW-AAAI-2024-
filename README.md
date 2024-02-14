# Hyp-OW: Exploiting Hierarchical Structure Learning with Hyperbolic Distance Enhances Open World Object Detection (AAAI 2024)
## Official Implementation
[![arXiv](https://img.shields.io/badge/📜arXiv-2306.14291-red)](https://arxiv.org/abs/2306.14291) [![Static Badge](https://img.shields.io/badge/🖼️pdf-Poster-blue)](https://github.com/boschresearch/Hyp-OW/blob/main/img/Poster_Hyp_AAAI.pdf)  [![Static Badge](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Model-Green)](https://huggingface.co/tldoan/Hyp-OW/tree/main) [![Static Badge](https://img.shields.io/badge/🎥Youtube-Video-orange)](https://youtu.be/dXaF0WpNFlA) [![Static Badge](https://img.shields.io/badge/👨‍💻Python-code-cyan)](https://github.com/boschresearch/Hyp-OW/tree/main)




#### [Thang Doan](https://tldoan.github.io/), Xin Li, Sima Behpour, [Wenbin He](https://hewenbin.github.io/), Liang Gou, [Liu Ren](https://sites.google.com/site/liurenshomepage/) ####


### Abstract

Open World Object Detection (OWOD) is a challenging and realistic task that extends beyond the scope of standard Object Detection task. It involves detecting both known and unknown objects while integrating learned knowledge for future tasks. However, the level of "unknownness" varies significantly depending on the context. For example, a tree is typically considered part of the background in a self-driving scene, but it may be significant in a household context. We argue that this contextual information should already be embedded within the known classes. In other words, there should be a semantic or latent structure relationship between the known and unknown items to be discovered. Motivated by this observation, we propose Hyp-OW, a method that learns and models hierarchical representation of known items through a SuperClass Regularizer. Leveraging this representation allows us to effectively detect unknown objects using a similarity distance-based relabeling module. Extensive experiments on benchmark datasets demonstrate the effectiveness of Hyp-OW, achieving improvement in both known and unknown detection (up to 6 percent). These findings are particularly pronounced in our newly designed benchmark, where a strong hierarchical structure exists between known and unknown objects.

<img src=".Poster_Hyp_OW.pdf" alt="hypow" width="100%" height="100%">
