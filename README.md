# Response Helpfulness Evaluation with Deep Learning: A Comparative Study

### Tejas Chandramouli, Sailakshmi Gangisetty, Samhitha Pudipeddi, Sarah Rayen, Arya Shankardas

Hugging Face Spaces Deliverable Demo: [https://huggingface.co/tejasc/HelpSteer3-Proposal](https://huggingface.co/spaces/tejasc/helpfulness-scorer)


This project uses the Nvidia [**HelpSteer3**](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/nemo/resources/helpsteer3) dataset, a collection of preference-based data, to analyze user preferences and the factors that make certain LLM-generated responses more viable. The goal is to identify patterns in model preferences, understand specific contributions to a high-quality response, and develop a grading system that can evaluate future prompts using tokenized representations. If time permits, the project will also explore generating new prompts based on these graded evaluations.

This project explores the evaluation of textual response
helpfulness using neural techniques compared with traditional
normalization methods. Based on the HelpSteer dataset, we
develop a Deep Learning model that assigns helpfulness scores
to text responses given a context or question. Key methods
include a DistilBERT-based scoring architecture, preference
regression, and post-processing techniques for score distribu-
tion enhancement. The model achieves a direction accuracy
of 63 percent and Spearman correlation of 0.35-0.45 with
human judgments. We also implement and evaluate a browser-
based application that allows users to assess and compare
response quality, demonstrating practical applications in au-
tomated feedback systems and AI assistant evaluation
