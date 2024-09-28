This repository accompanies an upcoming paper on a study of weights that did not change during finetuning. 

Title: Do not prune but interpret weights that did not change

Abstract: We empirically show that language models have a tiny set of weights that did not change after finetuning. Such weights, which we call __zero modes__, are essential for the model's functionality. They can be linked to various mechanisms that are ought to be learned during pretraining, such as induction heads or a neuron firing on the first sentence of an input. We make these claims concrete in one and two layer toy models trained on general code and finetuned on Python and three popular open-source pretrained-finetuned pairs of models. We find many similarities between the toy and large language models. For the LLMs, we not only show how the zero modes impact their performance on a wide variety of tasks, but also how they can affect hidden states and help select interesting (and universal) neurons.

A draft can be found [here](Do_not_prune_but_interpret.pdf)
