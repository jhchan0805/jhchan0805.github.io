---
title: ReLeaPS: "ReLeaPS: Reinforcement Learning-based Illumination Planning for Generalized Photometric Stereo"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-07-01
venue: 'International Conference of Computer Vision (ICCV)'
#paperurl: 'http://jhchan0805.github.io/files/jh_iccv23.pdf'
citation: '***Chan, Junhoong*** and Yu, Bohan and Guo, Heng and Ren, Jieji and Lu, Zongqing and Shi, Boxin. "ReLeaPS: Reinforcement Learning-based Illumination Planning for Generalized Photometric Stereo." In International Conference on Computer Vision, 2023.'
---
Illumination planning in photometric stereo aims to find a balance between surface normal estimation accuracy and image capturing efficiency by selecting optimal light configurations. It depends on factors such as the unknown shape and general reflectance of the target object, global illumination, and the choice of photometric stereo backbones, which are too complex to be handled by existing methods based on handcrafted illumination planning rules. This paper proposes a learning-based illumination planning method that jointly considers these factors via integrating a neural network and a generalized image formation model. As it is impractical to supervise illumination planning due to the enormous search space for ground truth light configurations, we formulate illumination planning using reinforcement learning, which explores the light space in a photometric stereo-aware, and reward-driven manner. Experiments on synthetic and real-world datasets demonstrate that photometric stereo under the 20-light configurations from our method is comparable to, or even surpasses that of using lights from all available directions.

[Download paper here](http://jhchan0805.github.io/files/jh_iccv23.pdf)

Citation: ***Chan, Junhoong*** and Yu, Bohan and Guo, Heng and Ren, Jieji and Lu, Zongqing and Shi, Boxin. "ReLeaPS: Reinforcement Learning-based Illumination Planning for Generalized Photometric Stereo." In International Conference on Computer Vision, 2023.