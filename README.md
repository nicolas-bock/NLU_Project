# Natural language understanding from traditional methods to large language models

Intent classification (IC) and slot-labeling (SL) are two main key components of the natural language understanding (NLU) block in a dialogue system.

There is dependency between the intent type (eg: play music) and possible slots (eg: artist name, song, genre). Traditional systems often use a cascaded approach or a naive joint approach, where the error in intent classification affects the slot labeling task.

A proper way of addressing both the tasks can help improve the performance and also efficiency of the dialogue systems. Instruction-tuned large language models are able to do the task jointly.

The goal of this project is to compare traditional methods to the more recent large language model based methods for NLU.

- IC and SL using methods based on word-embeddings (Word2Vec).
- IC and SL by fine-tuning a pre-trained language model (BERT).
- IC and SL using incontext-learning without any finetuning (Google Flan-T5-base).

All the above experiments are done on the NLU-evaluation benchmark dataset.

References:
Liu et al: Benchmarking Natural Language Understanding Services for building Conversational Agents
Dataset: NLU-Evaluation Benchmark
Weld et al: A survey of joint intent detection and slot-filling models in natural language understanding
Han et al: Bi-directional Joint Neural Networks for Intent Classification and Slot Filling
hugging-face: transformers for pre-trained models.
