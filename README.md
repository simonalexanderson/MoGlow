# MoGlow: Probabilistic and controllable motion synthesis using normalising flows
Gustav Eje Henter\*, Simon Alexanderson\* and Jonas Beskow

All from KTH Royal Institute of Technology

\*) Joint first authors

---
![image](media/teaser.jpg)

MoGlow is a new deep-learning architecture for creating high-quality animation. Its key advantages include:1. It is *general*. Unlike most prior work in motion generation, the same method works for generating a wide variety of motion types, such as diverse human locomotion, dog locomotion, and arm and body gestures driven by speech.2. It is *controllable*: Output motion can be conditioned on an arbitrary control input, such as which direction to walk, used to achieve interactive control over the output motion without algorithmic latency.3. It is *probabilistic*, and learns an entire distribution of plausible output motions that are consistent with the desired control.Evaluations show that MoGlow produces convincingly natural motion and approaches state-of-the-art performance on each application we tested it on – despite the fact that MoGlow is completely general and free from task-specific assumptions, whereas each state-of-the-art method is custom-designed for a single task only.For more information, please [see our introduction video]() below and [our main paper published at SIGGRAPH Asia 2020](). [Code and motion data are publicly available on GitHub](). We have also published follow-up work where [we extended the method to allow stylistic control and applied it to gesture generation](), and [applied similar ideas to generate facial expressions in response to a conversation partner](). The approach has won and been nominated for several awards.

## Abstract
Data-driven modelling and synthesis of motion is an active research area with applications that include animation, games, and social robotics. This paper introduces a new class of probabilistic, generative, and controllable motion-data models based on normalising flows. Models of this kind can describe highly complex distributions, yet can be trained efficiently using exact maximum likelihood, unlike GANs or VAEs. Our proposed model is autoregressive and uses LSTMs to enable arbitrarily long time-dependencies. Importantly, is is also causal, meaning that each pose in the output sequence is generated without access to poses or control inputs from future time steps; this absence of algorithmic latency is important for interactive applications with real-time motion control. The approach can in principle be applied to any type of motion since it does not make restrictive, task-specific assumptions regarding the motion or the character morphology. We evaluate the models on motion-capture datasets of human and quadruped locomotion. Objective and subjective results show that randomly-sampled motion from the proposed method outperforms task-agnostic baselines and attains a motion quality close to recorded motion capture.

### Video
<iframe width="560" height="315" src="https://youtu.be/Zgp_pYPwwKc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Paper
The paper is available <a href="https://arxiv.org/abs/1905.06598">here</a>

### Code and Data
- <a href="https://github.com/simonalexanderson/StyleGestures">Code for reproducing the results</a>.
 

### Citing
```
{% raw %}
@article{henter2020moglow,
  author = {Henter, Gustav Eje and Alexanderson, Simon and Beskow, Jonas},
  doi = {10.1145/3414685.3417836},
  journal = {ACM Transactions on Graphics},
  number = {4},
  pages = {236:1--236:14},
  publisher = {ACM},
  title = {{M}o{G}low: {P}robabilistic and controllable motion synthesis using normalising flows},
  volume = {39},
  year = {2020}
}
{% endraw %}
```

  



