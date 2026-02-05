# **Bridging Classic and Modern English: An NLP Approach to Translation and Educational Chatbots**

 This repository contains the research and implementation details for our paper on leveraging **Large Language Models (LLMs)** and **Transfer Learning** to make classical English literature more accessible through interactive AI tools.

### 🚀 **Project Overview**

Traditional methods of teaching literature often struggle to engage students with the complex themes and archaic language of classical texts. Our research addresses this by:


**1. Archaic-to-Modern Translation**: Fine-tuning a T5 model to translate Shakespearean and other archaic texts into contemporary English while preserving poetic nuance.


**2. Literary Chatbot (LlaMA-3)**: A fine-tuned LlaMA-3 model that acts as an interactive narrator or specific character, allowing users to "talk" to the literature.


**3. Contextual Entity Extraction**: Utilizing SpaCy’s NER framework to identify and explain key characters, locations, and historical references.


### 📊 **Key Results**

**1. Translation Superiority**: T5 outperformed BERT in maintaining narrative flow, achieving higher BLEU scores across training epochs.


**2. Chatbot Performance**: Quantitative analysis using a custom dataset for The Merchant of Venice yielded a BLEU score of ~0.6, indicating high accuracy in character-specific Q&A.


### 🛠️ **Methodology**

**1. Classification**: Input text is identified as either classical or modern.


**2. Translation**: Classical text is routed through the T5 translation module.


**3. NER Analysis**: Entities are extracted using the SpaCy architecture.


**4. Interaction**: Users engage with the fine-tuned LlaMA-3 model based on the processed modern text.


### 👥 **Authors**


Monark Dixit (University of Maryland | NMIMS Alumni)


Shreshtha Bhowmik 


Shreelekha Lotankar 


Ami Munshi
