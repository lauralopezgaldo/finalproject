 # Fundamental of Computer Science - Final project

#### This repository corresponds to my final proyect, focused on *Perceptual Bistability* exercises - based on [A Spiking Neuron Model for Binocular Rivalry (Laing and Chow, 2002)](https://link.springer.com/article/10.1023/A:1014942129705) and [Noise-Induced Alternations in an Attractor Network Model of Perceptual Bistability (Moreno-Bote et al., 2007)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2702529/)
---
  __Perceptual Bistability__ refers to the switching phenomenon that occurs when we are exposed to two different stimulus. As we cannot  perceive them at the same time, our brain changes from one to the other.

Throughout this exercises, the duration of each stimulus, its dominance and dependance on specific characteristics is studied, following two different models.

The **first model** assumes that the excitatory activity of neurons is completely guided by the adaptation curve. Whenever the adaptation decays, the population stops being active, whereas when the adaptation goes up, the population becomes active. If setting the correct parameters, after solving a system of ODEs, we can observe that oscillations occur and we have a consecutive switching between active populations state, with a total correspondance between adaptation and neuron activity.

![Firstplot-firstmethod](https://github.com/lauralopezgaldo/finalproject/blob/master/Figures/Figure1.png)

The **second model**, on the other hand, states that adaptation on its own is not enough to guide swithing of populations, but noise is the real cause. In this case, instead of presenting a system of ODEs, the system is modeled with SDEs, in order to introduce a random noise variable. Depending on exact tunable parameters, the system is more or less dependent on noise.

![Firstplot-firstmethod](https://github.com/lauralopezgaldo/finalproject/blob/master/Figures/Figure2.png)
![Firstplot-firstmethod](https://github.com/lauralopezgaldo/finalproject/blob/master/Figures/Figure4.png)



