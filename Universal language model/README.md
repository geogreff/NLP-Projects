# Introduction [1]
- [ELMo](https://arxiv.org/abs/1802.05365), [ULMFiT](https://arxiv.org/abs/1801.06146) and [OpenAI transformer](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) shows that **pretrained language models** can achieve state-of-the-art results on a wide range of NLP tasks.
- Word vectors built by Word2vec or GloVe can only be used as initialization of **first layer** of deep networks.

# How to use pretrained language models [1]
- Use the pre-trained language model as a **fixed feature extractor** and incorporate its representation as features into a randomly initialized model, as used in ELMo
- **Fine-tune the entire language model**, as done by ULMFiT. Fine-tuning approach is what is typically done in CV where either the top-most or several of the top layers are fine-tuned. 

# Examples
## ELMo
## ULMFIT [2]
## OpenAI transformer
### Transformer [3]

Implementation: [pytorch](https://github.com/jadore801120/attention-is-all-you-need-pytorch), [tensorflow](https://github.com/Kyubyong/transformer)  
[self attention](https://www.paperweekly.site/papers/notes/339) 


# References
- [1] [NLP's ImageNet moment has arrived](https://thegradient.pub/nlp-imagenet/)
- [2] [blog](http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html)
- [3] [Transformer illustration](https://jalammar.github.io/illustrated-transformer/), [2.1](https://www.jiqizhixin.com/articles/2018-01-10-20), [2.2]()
