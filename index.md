Name：Eric Gu, Email:ergu@ucsd.edu

B01 GenAI for Good (Mentor: Ali Arsanjani)

**Question 1: What is the main focus of your project?**

The main focus of the project is to detect misinformation/disinformation of an news article using a hybrid model with both predictive AI and Google generative AI. We hope that our model can achieve an accurate veraicty score, helping readers to access true information.

**Question 2: What methods do you plan to use?**

We will store LiarPlus dataset in ChromaDB for RAG process. We will use factuality factors along with corresponding microfactors to explain the hybrid model focus. We will use techiques including prompt engineering, retrieval-augmented generation, fractal chain-of-thought,
and function calling to acheieve accurate veracity score for detection.


**Question 3: What are the expected challenges?**

One of the expected challenges can be building a website using Mesop, which we need to read Mesop documents and familiarize with the languages. Another challenge can be the methods of incorperate predictive AI and the generative AI. One of them can be providing the results
of predictive AI to the prompt in the generative AI and let the generative AI process. Another idea is to take the average between the predictive and generative AI based on reasonable weights. Furthermore, defining great functions for function calling can also be challenging,
which we need to implement NLP techniques such as tokenize, word embedding, etc.

**Question 4: What are your desired outcomes?**

The desired outcome of the project is to create an accurate hybrid model to detect misinformation/disinformation of a news article accurately. The model can address a wide array of scenarios, enhancing the adaptability of our generative AI system. The final veracity score should be as close to the expected score, helping the readers access articles with few misinformation.
