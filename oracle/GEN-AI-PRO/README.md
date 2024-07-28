# OCI Generative AI Professional

## Practice Exam

1. Which statement is true about Fine-tuning and Parameter-Efficient Fine-Tuning (PEFT)?
   - [ ] PEFT requires replacing the entire model architecture with a new one designed specifically for the new task, making it significantly more data-intensive than Fine-tuning.
   - [ ] Fine-tuning and PEFT do not involve model modification; they differ only in the type of data used for training, with Fine-tuning requiring labeled data and PEFT using unlabeled data.
   - [x] Fine-tuning requires training the entire model on new data, often leading to substantial computational costs, whereas PEFT involves updating only a small subset of parameters, minimizing computational requirements and data needs.
   - [ ] Both Fine-tuning and PEFT require the model to be trained from scratch on new data, making them equally data and computationally intensive.

2. What is the purpose of Retrieval Augmented Generation (RAG) in text generation?
   - [ ] To retrieve text from an external source and present it without any modifications
   - [x] To generate text using extra information obtained from an external data source
   - [ ] To generate text based only on the model's internal knowledge without external data
   - [ ] To store text in an external database without using it for generation

3. How are documents usually evaluated in the simplest form of keyword-based search?
   - [ ] Based on the number of images and videos contained in the documents
   - [ ] By the complexity of language used in the documents
   - [x] Based on the presence and frequency of the user-provided keywords
   - [ ] According to the length of the documents

4. Why is it challenging to apply diffusion models to text generation?
   - [ ] Because diffusion models can only produce images
   - [ ] Because text generation does not require complex models
   - [ ] Because text is not categorical
   - [x] Because text representation is categorical unlike images

5. When is fine-tuning an appropriate method for customizing a Large Language Model (LLM)?
   - [ ] When the LLM already understands the topics necessary for text generation
   - [ ] When the LLM requires access to the latest data for generating outputs
   - [x] When the LLM does not perform well on a task and the data for prompt engineering is too large
   - [ ] When you want to optimize the model without any instructions

6. Which is a characteristic of T-Few fine-tuning for Large Language Models (LLMs)?
   - [x] It selectively updates only a fraction of the model's weights.
   - [ ] It increases the training time as compared to Vanilla fine-tuning.
   - [ ] It updates all the weights of the model uniformly.
   - [ ] It does not update any weights but restructures the model architecture.

7. In which scenario is soft prompting appropriate compared to other training styles?
   - [ ] When the model needs to be adapted to perform well in a domain on which it was not originally trained
   - [ ] When the model requires continued pretraining on unlabeled data
   - [x] When there is a need to add learnable parameters to a Large Language Model (LLM) without task-specific training
   - [ ] When there is a significant amount of labeled, task-specific data available

8. When does a chain typically interact with memory in a run within the LangChain framework?
   - [ ] Before user input and after chain execution
   - [ ] Only after the output has been generated
   - [ ] Continuously throughout the entire chain execution process
   - [x] After user input but before chain execution, and again after core logic but before output

9. What does accuracy measure in the context of fine-tuning results for a generative model?
   - [ ] The proportion of incorrect predictions made by the model during an evaluation
   - [ ] The number of predictions a model makes, regardless of whether they are correct or incorrect
   - [ ] The depth of the neural network layers used in the model
   - [x] How many predictions the model made correctly out of all the predictions in an evaluation

10. Accuracy in vector databases contributes to the effectiveness of Large Language Models (LLMs) by preserving a specific type of relationship. What is the nature of these relationships, and why are they crucial for language models?
    - [ ] Temporal relationships; necessary for predicting future linguistic trends
    - [ ] Linear relationships; they simplify the modeling process
    - [x] Semantic relationships; crucial for understanding context and generating precise language
    - [ ] Hierarchical relationships; important for structuring database queries

11. What do prompt templates use for templating in language model applications?
    - [ ] Python's str.format syntax
    - [ ] Python's lambda functions
    - [ ] Python's class and object structures
    - [x] Python's list comprehension syntax

12. How does the structure of vector databases differ from traditional relational databases?
    - [ ] It uses simple row-based data storage.
    - [ ] A vector database stores data in a linear or tabular format.
    - [x] It is based on distances and similarities in a vector space.
    - [ ] It is not optimized for high-dimensional spaces.

13. What is the purpose of Retrievers in LangChain?
    - [ ] To combine multiple components into a single pipeline
    - [ ] To train Large Language Models
    - [x] To retrieve relevant information from knowledge bases
    - [ ] To break down complex tasks into smaller steps

14. Given the following code block: history = StreamlitChatMessageHistory(key="chat_messages")
memory = ConversationBufferMemory(chat_memory=history)
    - [ ] A given StreamlitChatMessageHistory will not be shared across user sessions.
    - [ ] A given StreamlitChatMessageHistory will NOT be persisted.
    - [ ] StreamlitChatMessageHistory will store messages in Streamlit session state at the specified key.
    - [x] StreamlitChatMessageHistory can be used in any type of LLM application.

15. How can the concept of "Groundedness" differ from "Answer Relevance" in the context of Retrieval Augmented Generation (RAG)?
    - [ ] Groundedness measures relevance to the user query, whereas Answer Relevance evaluates data integrity.
    - [ ] Groundedness refers to contextual alignment, whereas Answer Relevance deals with syntactic accuracy.
    - [x] Groundedness pertains to factual correctness, whereas Answer Relevance concerns query relevance.
    - [ ] Groundedness focuses on data integrity, whereas Answer Relevance emphasizes lexical diversity.

16. Which statement is true about string prompt templates and their capability regarding variables?
    - [x] They support any number of variables, including the possibility of having none.
    - [ ] They are unable to use any variables.
    - [ ] They can only support a single variable at a time.
    - [ ] They require a minimum of two variables to function properly.

17. In the context of generating text with a Large Language Model (LLM), what does the process of greedy decoding entail?
    - [ ] Selecting a random word from the entire vocabulary at each step
    - [ ] Using a weighted random selection based on a modulated distribution
    - [ ] Picking a word based on its position in a sentence structure
    - [x] Choosing the word with the highest probability at each step of decoding

18. What does the RAG Sequence model do in the context of generating a response?
    - [ ] It modifies the input query before retrieving relevant documents to ensure a diverse response.
    - [ ] It retrieves a single relevant document for the entire input query and generates a response based on that alone.
    - [x] For each input query, it retrieves a set of relevant documents and considers them together to generate a cohesive response.
    - [ ] It retrieves relevant documents only for the initial part of the query and ignores the rest.

19. What does the Loss metric indicate about a model's predictions?
    - [ ] Loss describes the accuracy of the right predictions rather than the incorrect ones.
    - [x] Loss is a measure that indicates how wrong the model's predictions are.
    - [ ] Loss indicates how good a prediction is, and it should increase as the model improves.
    - [ ] Loss measures the total number of predictions made by a model.

20. What is LangChain?
    - [ ] A Ruby library for text generation
    - [ ] A JavaScript library for natural language processing
    - [x] A Python library for building applications with Large Language Models
    - [ ] A Java library for text summarization

21. In the simplified workflow for managing and querying vector data, what is the role of indexing?
    - [ ] To convert vectors into a nonindexed format for easier retrieval
    - [ ] To compress vector data for minimized storage usage
    - [x] To map vectors to a data structure for faster searching, enabling efficient retrieval
    - [ ] To categorize vectors based on their originating data type (text, images, audio)

22. How does a presence penalty function in language model generation?
    - [ ] It penalizes only tokens that have never appeared in the text before.
    - [ ] It penalizes all tokens equally, regardless of how often they have appeared.
    - [x] It penalizes a token each time it appears after the first occurrence.
    - [ ] It applies a penalty only if the token has appeared more than twice.

23. What does a cosine distance of 0 indicate about the relationship between two embeddings?
    - [ ] They are similar in direction
    - [ ] They are unrelated
    - [ ] They are completely dissimilar
    - [x] They have the same magnitude

24. How does the temperature setting in a decoding algorithm influence the probability distribution over the vocabulary?
    - [ ] Temperature has no effect on probability distribution; it only changes the speed of decoding.
    - [ ] Increasing the temperature flattens the distribution, allowing for more varied word choices.
    - [ ] Decreasing the temperature broadens the distribution, making less likely words more probable.
    - [x] Increasing the temperature removes the impact of the most likely word.

25. Which LangChain component is responsible for generating the linguistic output in a chatbot system?
    - [x] LLMs
    - [ ] Documents Loaders
    - [ ] Vector Stores
    - [ ] LangChain Application
