# Summarization of CNN/DAILY MAIL Data-set using BART
BART stands for bidirectional autoregressive transformer, a reference to its neural network architecture. BART proposes an architecture and pre-training strategy that makes it useful as a sequence-to-sequence model (seq2seq model) for any NLP task, like summarization, machine translation, categorizing input text sentences, or question answering under real-world conditions. In this article, we'll focus on its summarization capabilities.

<img width="938" alt="Screenshot 2023-05-01 at 11 37 51 PM" src="https://user-images.githubusercontent.com/32895071/235503168-c37a2bdf-ef0e-47f0-b1c5-e354a2ffacd0.png">


Here are the reasons of choosing BART over other models:

 1. Most Resilient to Real-World Noisy Data
 2. Acceptable Results Out-of-the-Box Across Many Domains
3. Produces Grammatically Correct Summaries
4. Overcome Limitations of GPT-3

References : https://arxiv.org/pdf/1910.13461.pdf

Other powerful models such as MoCa, PEGASUS, GPT 4, could also be used, however due to gpu limitations, we are using BART. 
