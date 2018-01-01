### -1, 2017
- [Advances in Pre-Training Distributed Word Representations](http://arxiv.org/abs/1712.09405v1), Tomas Mikolov, Edouard Grave, Piotr Bojanowski, Christian Puhrsch, Armand Joulin

Many Natural Language Processing applications nowadays rely on pre-trained
word representations estimated from large text corpora such as news
collections, Wikipedia and Web Crawl. In this paper, we show how to train
high-quality word vector representations by using a combination of known tricks
that are however rarely used together. The main result of our work is the new
set of publicly available pre-trained models that outperform the current state
of the art by a large margin on a number of tasks.

- [Differentially Private Distributed Learning for Language Modeling Tasks](http://arxiv.org/abs/1712.07473v2), Vadim Popov, Mikhail Kudinov, Irina Piontkovskaya, Petr Vytovtov, Alex Nevidomsky

One of the big challenges in machine learning applications is that training
data can be different from the real-world data faced by the algorithm. In
language modeling, users' language (e.g. in private messaging) could change in
a year and be completely different from what we observe in publicly available
data. At the same time, public data can be used for obtaining general knowledge
(i.e. general model of English). We study approaches to distributed fine-tuning
of a general model on user private data with the additional requirements of
maintaining the quality on the general data and minimization of communication
costs. We propose a novel technique that significantly improves prediction
quality on users' language compared to a general model and outperforms gradient
compression methods in terms of communication efficiency. The proposed
procedure is fast and leads to an almost 70% perplexity reduction and 8.7
percentage point improvement in keystroke saving rate on informal English
texts. Finally, we propose an experimental framework for evaluating
differential privacy of distributed training of language models and show that
our approach has good privacy guarantees.


