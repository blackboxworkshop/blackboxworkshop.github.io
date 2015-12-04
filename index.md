---
layout: default
title: Black Box Learning and Inference
---

## Keynote Talks
<table>
<tr>
<td width="50%"><img src="{{site.baseurl}}/images/tenenbaum.jpg" width="100px" align="bottom"></td>
<td width="50%"><img src="{{site.baseurl}}/images/salakutdinov.jpg" width="100px" align="bottom"></td>
</tr>
<tr>
<td>Josh Tenenbaum</td>
<td>Ruslan Salakutdinov</td>
</tr>
</table>

## Research Talks
<table>
<tr>
<td width="50%"><img src="{{site.baseurl}}/images/kingma.jpg" width="100px" align="bottom"></td>
<td width="50%"><img src="{{site.baseurl}}/images/kucukelbir.jpg" width="100px" align="bottom"></td>
</tr>
<tr>
<td>Durk Kingma</td>
<td>Alp Kucukelbir</td>
</tr>
<tr>
<td width="50%"><br/><br/><img src="{{site.baseurl}}/images/tran.jpg" width="100px" align="bottom"></td>
<td width="50%"><br/><br/><img src="{{site.baseurl}}/images/vdm.jpg" width="100px" align="bottom"></td>
</tr>
<tr>
<td>Dustin Tran</td>
<td>Jan-Willem van de Meent</td>
</tr>
</table>

## Panel
<table>
<tr>
<td width="50%"><img src="{{site.baseurl}}/images/wood.jpg" width="100px" align="bottom"></td>
<td width="50%"><img src="{{site.baseurl}}/images/salakutdinov.jpg" width="100px" align="bottom"></td>
</tr>
<tr>
<td>Frank Wood</td>
<td>Ruslan Salakutdinov</td>
</tr>
<tr>
<td width="50%"><br/><br/><img src="{{site.baseurl}}/images/blei.jpg" width="100px" align="bottom"></td>
<td width="50%"><br/><br/><img src="{{site.baseurl}}/images/ghahramani.jpg" width="100px" align="bottom"></td>
</tr>
<tr>
<td>Dave Blei</td>
<td>Zoubin Ghahramani</td>
</tr>
</table>

## Languages and Systems Presentations
- Koray Kavukcuoglu (Torch)
- Yi Wu (BLOG)
- Avi Pfeffer (Figaro)
- Chung-chieh Shan (Hakaru)
- Alp Kucukelbir (Stan)
- Vikash Mansinghka (Venture)

## Overview

Probabilistic models have traditionally co-evolved with tailored algorithms for efficient learning and inference. One of the exciting developments of recent years has been the resurgence of black box methods, which make relatively few assumptions about the model structure, allowing application to broader model families. 

In probabilistic programming systems, black box methods have greatly improved the capabilities of inference back ends.  Similarly, the design of connectionist models has been simplified by the development of black box frameworks for training arbitrary architectures. These innovations open up opportunities to design new classes of models that smoothly negotiate the transition from low-level features of the data to high-level structured representations that are interpretable and generalize well across examples.

This workshop brings together developers of black box inference technologies, probabilistic programming systems, and connectionist computing frameworks. The goal is to formulate a shared understanding of how black box methods can enable advances in the design of intelligent learning systems. Topics of discussion will include:

* Black box techniques for gradient ascent, variational inference, Markov chain- and sequential Monte Carlo.
* Implementation of black box techniques in probabilistic programming systems and computing frameworks for connectionist model families. 
* Models that integrate top-down and bottom-up model representations to perform amortized inference: variational autoencoders, deep latent Gaussian models, restricted Boltzmann machines, neural network based proposals in MCMC. 
* Applications to vision, speech, reinforcement learning, motor control, language learning.
