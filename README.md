# Supplementary Material for the paper: Recurrent Stacking of Layers for Compact Neural Machine Translation Models

The PDF contains the supplementary material for our paper "Recurrent Stacking of Layers for Compact Neural Machine Translation Models" which was accepted in AAAI 2019. In this paper we showed that reusing parameters by stacking the same layer on top of itself N-1 times leads to a model whose translation quality approaches that of a model where N independent layers are stacked. By doing so, we lose about 1 BLEU point compared to a vanilla NMT model but reduce the model size by approximately 60%.

The main paper can be found at http://paraphrasing.org/~fujita/publications/coauthor/dabre-AAAI2019.pdf or at https://www.aaai.org/Papers/AAAI/2019/AAAI-DabreR.2192.pdf
The poster can be found at http://paraphrasing.org/~fujita/publications/coauthor/dabre-AAAI2019-poster.pdf

If you use the ideas presented in the main paper, poster or the supplementary material then kindly cite the following:

@article{dabre:aaai19:rsnmt,
    title={Recurrent Stacking of Layers for Compact Neural Machine Translation Models},
    author={Dabre, Raj and Fujita, Atsushi},
    booktitle = {Proceedings of the Thirty-Third AAAI Conference on Artificial Intelligence},
    series = {AAAI'19},
    year = {2019},
    location = {Honolulu, Hawaii, USA},
    pages = {xxxx--xxxx},
    numpages = {8},
    url = {http://paraphrasing.org/~fujita/publications/coauthor/dabre-AAAI2019.pdf},
    publisher = {AAAI Press},
}

This supplementary pdf contains the modifications to the Transformer implementation in tensor2tensor version 1.6 as well as the attention and entropy visualization for several sentence pairs. These visualizations span complete sentences as opposed to the partial visualizations we provided in the main paper due to lack of space.
