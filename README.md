**Overview**

This repository contains the implementation of a Generative Pre-Training (GPT) model based on Kolmogorov-Arnold Networks (KAN) instead of traditional Multi-Layer Perceptrons (MLPs). The KAN-based GPT model is designed to leverage the strengths of KANs in modeling complex nonlinear relationships and capturing long-range dependencies in sequential data.

**Architecture**

The KAN-based GPT model consists of the following components:

1. **KAN Encoder**: A KAN encoder is used to encode the input sequence of tokens into a continuous representation. The KAN encoder consists of a stack of KAN layers, each of which applies a non-linear transformation to the input sequence.
2. **Attention Mechanism**: A multi-head attention mechanism is used to compute the weighted sum of the input sequence, allowing the model to focus on specific parts of the input sequence.
3. **Output Layer**: A linear layer is used to transform the output of the KAN encoder into a probability distribution over the vocabulary.


**Advantages**

The KAN-based GPT model has several advantages over traditional MLP-based GPT models:

1. **Improved modeling of complex relationships**: KANs are able to model complex nonlinear relationships between input features, allowing the model to capture long-range dependencies and contextual information.
2. **Improved handling of sequential data**: KANs are able to effectively handle sequential data, allowing the model to capture the temporal relationships between input tokens.
3. **Improved generalizability**: KANs are able to generalize well to out-of-distribution data, allowing the model to perform well on unseen data.

**Future Work**

Future work includes exploring the use of KAN-based GPT models for other NLP tasks, such as text classification, sentiment analysis, and machine translation. Additionally, the development of more advanced KAN architectures and training objectives is an area of ongoing research.
