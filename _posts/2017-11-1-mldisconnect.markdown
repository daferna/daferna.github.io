---
layout: post
title:  "Theory vs Systems"
date: 2017-11-1
categories:
---

There's recently been a big concern among ML researchers that advisarial examples are something to actually be concerned about: [https://blog.openai.com/adversarial-example-research/](https://blog.openai.com/adversarial-example-research/)

To me, this highlights some of the big differences between theoreticians and applied, systems thinking people like myself.

If you look at any of these "crafted noise" perturbations, it's clear that the noise is too high frequency to be ever imaged due to Abbe's diffraction limit. And some have tried this in practice and shown that, if anything, adding noise may improve classification performance: [https://arxiv.org/abs/1707.03501](https://arxiv.org/abs/1707.03501)

The divide between theoretical vs applied ML research, I think, is only going to become even larger over the next few years. Thanks to the new field of reinforcement learning, entirely simulated environments (like the OpenAI gym) can be used to test different reinforment learning algorithms and policies. But, what will happen when we try and apply these policies to actual robots? Is Machine Learning without real-world data running a fool's errand? And I'm not just talking about making a [paperclip maximizer](https://en.wikipedia.org/wiki/Instrumental_convergence).
