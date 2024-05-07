# 510_lab6

# How to Run
Open the terminal and run the following commands:
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py

# What's include
app.py - main running application.  
.gitignore - tells Git which files or directories to ignore in a project.  
requirements.txt - list all the dependencies that the project needs to run correctly.  
README.md - includes the text info of the basic introduction of this GitHub Repository, how to run, what's included, lessons learned, questions / uncertainties.  

# Lesson Learned

Nature and Function of Large Language Models (LLMs):
LLMs are AI models that process and generate human-like text by learning from vast amounts of data. They use deep learning techniques and are trained on diverse datasets to understand a wide range of topics and styles. Their applications include translation, summarization, content creation, and more.
Transformer Architecture and Self-Attention Mechanism:
LLMs utilize transformer architecture, which helps the model weigh the importance of different words for understanding context and generating responses. The self-attention mechanism within transformers allows the model to focus on different parts of the input text, aiding in the generation of coherent and contextually appropriate text.
Tokenization and Embeddings:
Input text is broken down into smaller units called tokens, which can include words, parts of words, or punctuation. These tokens are then converted into numerical vectors using embeddings, which help capture the semantic and syntactic meanings of words and make the textual information processable by the model.
Applications and Limitations of LLMs:
LLMs are versatile in handling various NLP tasks like Named Entity Recognition (NER), classification, and creative content generation. However, they also have limitations such as generating hallucinated (incorrect or misleading) content, dealing with a limited context window, and high operational costs.
Alternative Solutions and Techniques for Overcoming Limitations:
For sensitive data or specific tasks, alternatives to proprietary LLMs like open-source models (e.g., Llama family) and traditional NLP tools (e.g., NLTK, SpaCy) are available. Techniques such as prompt engineering, Retrieval Augmented Generation (RAG), and fine-tuning are useful for enhancing the performance of LLMs and mitigating their limitations.


# questions
When using large language models (LLMs) for text generation, we often face issues with the authenticity and accuracy of the generated content, referred to as 'hallucinations.' To reduce the occurrence of these issues and improve the credibility of the text, how can we more effectively use prompt engineering and Retrieval Augmented Generation (RAG) techniques? What are the limitations and challenges of these techniques in practical applications?


