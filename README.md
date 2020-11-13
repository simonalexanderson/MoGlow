# MoGlow: Probabilistic and controllable motion synthesis using normalising flows
Gustav Eje Henter*, Simon Alexanderson* and Jonas Beskow

All from KTH Royal Institute of Technology
*) Joint first Authors

---

## Abstract
Data-driven modelling and synthesis of motion is an active research area with applications that include animation, games, and social robotics. This paper introduces a new class of probabilistic, generative, and controllable motion-data models based on normalising flows. Models of this kind can describe highly complex distributions, yet can be trained efficiently using exact maximum likelihood, unlike GANs or VAEs. Our proposed model is autoregressive and uses LSTMs to enable arbitrarily long time-dependencies. Importantly, is is also causal, meaning that each pose in the output sequence is generated without access to poses or control inputs from future time steps; this absence of algorithmic latency is important for interactive applications with real-time motion control. The approach can in principle be applied to any type of motion since it does not make restrictive, task-specific assumptions regarding the motion or the character morphology. We evaluate the models on motion-capture datasets of human and quadruped locomotion. Objective and subjective results show that randomly-sampled motion from the proposed method outperforms task-agnostic baselines and attains a motion quality close to recorded motion capture.

### Video
<iframe width="560" height="315" src="https://drive.google.com/file/d/1-Xqol5tzRnTy7Ud6dKDX2FT7z8eHmtUC/view?usp=sharing" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Paper
The paper is available <a href="https://arxiv.org/abs/1905.06598">here</a>

### Code and Data
- <a href="https://github.com/simonalexanderson/StyleGestures">Code for reproducing the results</a>.
 

### Citing
```
}
```

  



