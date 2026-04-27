# gen-ai

# day 1 

Question: What is generative a?
Answer: Generative ai is a type of artifical intelligence that creates new content such as text, image, music, or code by learning patterns from existing data, mimicking human creativity.

<img width="471" height="465" alt="image" src="https://github.com/user-attachments/assets/ed9edfbe-bec9-44f1-9bf8-dbeaf13c6e46" />

AI = artifical intelligence
ML = machine learning
dl = deep learning
GenAI = Generative artifical intelligence

Gen Impact Area = customer support, Content creation, Education, 

What is LLM?
LLM stands for Large Language Model. It is a type of artificial intelligence model trained on vast amounts of text data to understand, generate, and process human language. Examples include models like GPT-3, GPT-4, and others, which can perform tasks such as writing, translation, summarization, and answering questions.

We have two type catagories to use the LLM's.
1. user perspective
2. Building perspective

lets play game when we heared 
- promt enginear - user perspective
- RLHF (Reinforcement Learning with Human Feedback) - Building perspective
- RAG ( Retrieval-Augmented Generation ) - user perspective
- Pre-training - Building perspective
- Quantization - Building perspective
- AI agents - user perspective
- Vector database - user perspective
- Fine tuning - both side we are using 

<img width="1031" height="666" alt="image" src="https://github.com/user-attachments/assets/10bb5669-ec67-43c1-84c1-9d6d1ceed64a" />

Builder perspective flow:

Pre-request: Machine learning fundamentals , Deep learining fundamentals (TensorFlow, PyTorch )

Builder flow terms : 
1. Transformer Architecture
2. types of transformer ( Encoder only [ BERT ], decoder only [ GPT ], encoder and decoder based [T5] )
3. Pre-training ( Training objectives, Tockenization stratergies, Training stratergies, Handling chanlanges )
4. optimization ( Training optimization, Model compression, optimizing inference )
5. Fine-tune ( task specific tuning [RLHF], instruction tuning [PEFT], continual pre-training)
6. Evalution
7. Deployment


<img width="1170" height="675" alt="image" src="https://github.com/user-attachments/assets/88f675ee-95c6-4505-a4ea-3c7cedf532c1" />

User perspective flow:

1. Basic LLM Apps ( open source vs closed source, using LLM api's, langchain, HuggingFace, ollama )
2. Prompt engnearing
3. RAG
4. Fine Tune
5. Agents
6. LLM-OPS

<img width="1280" height="715" alt="image" src="https://github.com/user-attachments/assets/2ebb7f37-af04-40d9-baa2-1acec2cf44b1" />

Builder side jobs : data scientist
User side jobs : Software developers
Builder side and User side : Ai  Engineer

*****************************************************************************
# Day 2
*****************************************************************************

What is langchain?
langchain is an open source framework that helps in building LLM based application. It provides modular components and end t;o end tools that help developers buld complex AI applications, such as chatbots, question-answering systems, retrievel augmented generation , autonomous agents and more.

- Supports all the major llm's
- simplifies developing LLM based applications
- Integrations available for all major tools
- open source/free/actively developed
- supports all major GenAI use cases

 Curriculum structure 

 <img width="647" height="371" alt="image" src="https://github.com/user-attachments/assets/40d0f6e1-447a-448d-97f0-a7704da0d006" />

Langchain roadmap

1. Fundamentals
   a. what is langchain
   b. langchain components
   c. models
   d. prompts
   e. parsing outputs
   f. runnables and LCEL
   g. chains
   h. memory

2. RAG
   a. document loaders
   b. text splitters
   c. embeddings
   d. vector stores
   e. retrievers
   f. building a rag application

3. Agents
   a. tools and toolkits
   b. tool calling
   c. building an AI agent

What is langchain?
langchain is an open-source framework for developing applications powered by large language models (LLM's )

Why we need langchain?
In starting stage's we create a Ebook wherehouse 
<img width="1069" height="454" alt="image" src="https://github.com/user-attachments/assets/42b44b31-be01-462f-bfcd-3c34425afaaa" />

<img width="1082" height="554" alt="image" src="https://github.com/user-attachments/assets/f5c1ef14-a69c-468d-a447-55e79165867e" />

<img width="1079" height="565" alt="image" src="https://github.com/user-attachments/assets/033825c7-e16b-4a1f-a640-537683c0932f" />


<img width="1107" height="555" alt="image" src="https://github.com/user-attachments/assets/acd7c210-056f-447b-ae2f-4660f882ec64" />

<img width="1080" height="551" alt="image" src="https://github.com/user-attachments/assets/c599a87b-0eb4-41ea-8920-db5d20751fd2" />

<img width="1108" height="203" alt="image" src="https://github.com/user-attachments/assets/e4eb2bb3-5334-45b1-8cf6-b8c9f6d9c315" />

<img width="357" height="262" alt="image" src="https://github.com/user-attachments/assets/0a8275b6-682a-4e55-a83d-e561fe8cdf31" />

<img width="302" height="211" alt="image" src="https://github.com/user-attachments/assets/c0c523df-62e7-4e48-9075-5cad3e28506a" />

# Components of langchain

<img width="833" height="455" alt="image" src="https://github.com/user-attachments/assets/20bc6cd1-e7ab-4ac4-ba5a-5e03ecc4957f" />

1. Models = In langchain, "models" are the core interfaces through which you interact with AI tools.


Issue : 
Understand NLP
LLM size large

Solution: API calling 


<img width="1102" height="555" alt="image" src="https://github.com/user-attachments/assets/2a5a628b-f46c-4e36-bf56-58e8b0472c85" />

# Via langchain 

<img width="1116" height="396" alt="image" src="https://github.com/user-attachments/assets/105a6b94-9463-47c9-acee-4a1a92e17441" />


<img width="1103" height="528" alt="image" src="https://github.com/user-attachments/assets/9d65b606-ea4c-416d-88e3-a861f1ad7b5d" />

<img width="1059" height="502" alt="image" src="https://github.com/user-attachments/assets/5b51a605-6b37-4402-981e-9d860c42192e" />

<img width="1097" height="255" alt="image" src="https://github.com/user-attachments/assets/41f10caa-9859-4956-9927-4dff86af90ed" />

<img width="1066" height="522" alt="image" src="https://github.com/user-attachments/assets/40f6807b-0532-449f-b389-ec459c1b3a20" />

<img width="1027" height="361" alt="image" src="https://github.com/user-attachments/assets/0c7d943c-7efc-4f1c-8720-2b194a17b18d" />

<img width="861" height="373" alt="image" src="https://github.com/user-attachments/assets/265807aa-8e45-4c29-927b-5d33c0d41a85" />

<img width="1109" height="331" alt="image" src="https://github.com/user-attachments/assets/00989b43-39fa-447e-ab70-6c5642000d51" />

<img width="1079" height="493" alt="image" src="https://github.com/user-attachments/assets/4d7873f3-f519-4e50-adac-8ab58805b14c" />

<img width="1066" height="292" alt="image" src="https://github.com/user-attachments/assets/806e27ec-4f88-44ca-b7a2-1f6ced972e88" />

<img width="1125" height="279" alt="image" src="https://github.com/user-attachments/assets/84448361-9e01-465f-b764-926ae614906e" />

