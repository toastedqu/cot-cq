# Multimodal Chain-of-Thought Object Relation Inference using Clarifying Questions

![](https://github.com/toastedqu/cot-cq/blob/main/method.png)

Collaborators: Yankai Li, Hong Lyu

This project attempts to tackle the issue of object relation inference in VQA (Visual Question-Answering) using VLMs (Vision-Language Models) and LLMs (Large Language Models). Inspired by [PromptCap](https://arxiv.org/abs/2211.09699), we utilize the chain-of-thought reasoning capability of contemporary LLMs to interact with the VLM with clarifying questions. The VLM is responsible for providing the LLM with sufficient text information about the image and answering whatever clarifying question the LLM asks. The LLM is responsible for understanding the text information provided by the VLM, acquiring more useful information through clarifying questions, and ultimately answering the input question. We experimented on the GQA dataset, and our results show that adding the LLM did not necessarily improve the performance of the state-of-the-art VLMs on object relation inference. While GPT-3.5 was able to understand and utilize concepts from text information properly, the whole system was very limited by the capabilities of the VQA module and many other limitations. We suggest further research to tackle these issues.
