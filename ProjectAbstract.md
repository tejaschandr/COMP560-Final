# Midterm Project Abstract

### Tejas Chandramouli, Sailakshmi Gangisetty, Samhitha Pudipeddi, Sarah Rayen, Arya Shankardas

Colab Link: https://colab.research.google.com/drive/1KfDRpeI9n-dPYKBg9JKjIvXI-hP1xS9R#scrollTo=MIk2dejIWrGq


This project uses the Nvidia [**HelpSteer3**](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/nemo/resources/helpsteer3) dataset, a collection of preference-based data, to analyze user preferences and the factors that make certain LLM-generated responses more viable. The goal is to identify patterns in model preferences, understand specific contributions to a high-quality response, and develop a grading system that can evaluate future prompts using tokenized representations. If time permits, the project will also explore generating new prompts based on these graded evaluations.

The dataset consists of a series of individual preferences paired with contextual information, where each entry includes detailed reasoning behind the user's choice. The primary goal of this project is to explore the use of transformer-based models, particularly **DistilBERT**, to perform text tokenization and subsequent sequence classification tasks, in order to predict overall preferences based on context and reasoning.

The project begins by extracting and preprocessing the relevant text data from the HelpSteer3 dataset. Key features such as **contexts** and **reasoning** are isolated and tokenized using the **DistilBERT tokenizer** from the Hugging Face library. Given the size of the dataset, which consists of over 20,000 samples, a subset of 5000 samples is selected and tokenized into tensors that are then saved in a PyTorch file for efficient access during training.

Once tokenized, the model will be trained to predict preferences based on the provided context and reasoning. This project explores various aspects of sequence classification and fine-tuning pre-trained language models for specific tasks, demonstrating how transformer models can be applied to preference prediction in a natural language processing (NLP) setting. This work contributes to the understanding of personalized recommendations and to actively monitor the evolution of LLM-generated responses, potentially benchmarking these evaluations against models like GPT-2.
