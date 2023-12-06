# Whisper

We used a model-centric approach to improve our model.
Initially, we updated a learning rate, according to the [original paper](https://arxiv.org/pdf/2212.04356.pdf). However,
it turned out to be too high, and we lowered it, according
to [these](https://github.com/vasistalodagala/whisper-finetune) recommendations.

The results can be compared here:

[Basic model](https://huggingface.co/SofiaK/training-v1/)

[Improved model](https://huggingface.co/SofiaK/training-v2)