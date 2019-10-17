# Diffusion-Decision-Model

DDM provides a way to investigate decision-making process, in which evidence accumulate from a starting point until reaching one side of the boundary (Ratcliff & McKoon 2008). With the diffusion decision model, we can quantify the latent cognitive processes and statistically separate the different components of the cognitive process, such as bias, threshold, and drift rate. In this paper, we consider 6 parameters in DDM. They are (1) threshold, the amount of information that is considered for a decision (2) non-decision time, lower bound for the duration of the non-decision period (3) inter-trial-variability of non-decision time (4) starting point, the priori bias in the evidence accumulation process (5) drift rate, the speed of the evidence accumulation process, and (6) inter-trial-variability of drift rate (Ratcliff & McKoon 2008). The parameters we listed above are label as a, t0, st0, z, v, sv. Because we have four stimulus classes, each participant has four drift rates, and all other parameters should be shared across all stimulus classes. In total, our model has 9 parameters per individual data set. Then, we used maximum likelihood to estimate the parameters in DDM for each participant.

Instruction: 
(1) Run "Modelling" first 
(2) Assess the fitness of the model with other files
