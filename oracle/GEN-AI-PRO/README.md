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
    - [x] Python's str.format syntax
    - [ ] Python's lambda functions
    - [ ] Python's class and object structures
    - [ ] Python's list comprehension syntax

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
Which statement is NOT true about StreamlitChatMessageHistory?
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
    - [x] They are similar in direction
    - [ ] They are unrelated
    - [ ] They are completely dissimilar
    - [ ] They have the same magnitude

24. How does the temperature setting in a decoding algorithm influence the probability distribution over the vocabulary?
    - [ ] Temperature has no effect on probability distribution; it only changes the speed of decoding.
    - [x] Increasing the temperature flattens the distribution, allowing for more varied word choices.
    - [ ] Decreasing the temperature broadens the distribution, making less likely words more probable.
    - [ ] Increasing the temperature removes the impact of the most likely word.

25. Which LangChain component is responsible for generating the linguistic output in a chatbot system?
    - [x] LLMs
    - [ ] Documents Loaders
    - [ ] Vector Stores
    - [ ] LangChain Application

## Skill Check

### Fundamentals of Large Language Models

1. What does in-context learning in Large Language Models involve?
   - [ ] Training the model using reinforcement learning
   - [ ] Adding more layers to the model
   - [ ] Pretraining the model on a specific domain
   - [x] Conditioning the model with task-specific instructions or demonstrations

2. What does the term "hallucination" refer to in the context of Language Large Models (LLMs)?
   - [x] The phenomenon where the model generates factually incorrect information or unrelated content as if it were true
   - [ ] The model's ability to generate imaginative and creative content
   - [ ] The process by which the model visualizes and describes images in detail
   - [ ] A technique used to enhance the model's performance on specific tasks

3. What is the role of temperature in the decoding process of a Large Language Model (LLM)?
   - [x] To adjust the sharpness of probability distribution over vocabulary when selecting the next word
   - [ ] To determine the number of words to generate in a single decoding step
   - [ ] To increase the accuracy of the most likely word in the vocabulary
   - [ ] To decide to which part of speech the next word should belong

4. Which statement accurately reflects the differences between these approaches in terms of the number of parameters modified and the type of data used?
   - [x] Fine-tuning modifies all parameters using labeled, task-specific data, whereas Parameter Efficient Fine-Tuning updates a few, new parameters also with labeled, task-specific data.
   - [ ] Soft prompting and continuous pretraining are both methods that require no modification to the original parameters of the model.
   - [ ] Fine-tuning and continuous pretraining both modify all parameters and use labeled, task-specific data.
   - [ ] Parameter Efficient Fine Tuning and Soft prompting modify all parameters of the model using unlabeled data.

5. What is prompt engineering in the context of Large Language Models (LLMs)?
   - [ ] Training the model on a large data set
   - [ ] Adding more layers to the neural network
   - [ ] Adjusting the hyperparameters of the model
   - [x] Iteratively refining the ask to elicit a desired response

### OCI Generative AI Service Deep Dive

1. What is the main advantage of using few-shot model prompting to customize a Large Language Model (LLM)?
   - [ ] It allows the LLM to access a larger data set.
   - [ ] It eliminates the need for any training or computational resources.
   - [x] It provides examples in the prompt to guide the LLM to better performance with no training cost.
   - [ ] It significantly reduces the latency for each model request.

2. Which is a distinctive feature of GPUs in Dedicated AI Clusters used for generative AI tasks?
   - [x] The GPUs allocated for a customer’s generative AI tasks are isolated from other GPUs.
   - [ ] Each customer's GPUs are connected via a public Internet network for ease of access.
   - [ ] GPUs are shared with other customers to maximize resource utilization.
   - [ ] GPUs are used exclusively for storing large data sets, not for computation.

3. What is the purpose of frequency penalties in language model outputs?
   - [ ] To reward the tokens that have never appeared in the text
   - [x] To penalize tokens that have already appeared, based on the number of times they have been used
   - [ ] To ensure that tokens that appear frequently are used more often
   - [ ] To randomly penalize some tokens to increase the diversity of the text

4. What is the purpose of embeddings in natural language processing?
   - [ ] To translate text into a different language
   - [ ] To compress text data into smaller files for storage
   - [ ] To increase the complexity and size of text data
   - [x] To create numerical representations of text that capture the meaning and relationships between words or phrases

5. What happens if a period (.) is used as a stop sequence in text generation?
   - [ ] The model stops generating text after it reaches the end of the current paragraph.
   - [x] The model stops generating text after it reaches the end of the first sentence, even if the token limit is much higher.
   - [ ] The model ignores periods and continues generating text until it reaches the token limit.
   - [ ] The model generates additional sentences to complete the paragraph.

### Building Blocks for an LLM Application

1. What do embeddings in Large Language Models (LLMs) represent?
   - [ ] The grammatical structure of sentences in the data
   - [x] The semantic content of data in high-dimensional vectors
   - [ ] The color and size of the font in textual data
   - [ ] The frequency of each word or pixel in the data

2. What differentiates Semantic search from traditional keyword search?
   - [ ] It is based on the date and author of the content.
   - [ ] It depends on the number of times keywords appear in the content.
   - [x] It involves understanding the intent and context of the search.
   - [ ] It relies solely on matching exact keywords in the content.

3. What does the Ranker do in a text generation system?
   - [ ] It sources information from databases to use in text generation.
   - [x] It evaluates and prioritizes the information retrieved by the Retriever.
   - [ ] It generates the final text based on the user's query.
   - [ ] It interacts with the user to understand the query better.

4. What is the function of the Generator in a text generation system?
   - [ ] To collect user queries and convert them into database search terms
   - [ ] To store the generated responses for future use
   - [x] To generate human-like text using the information retrieved and ranked, along with the user's original query
   - [ ] To rank the information based on its relevance to the user's query

5. Which is a key characteristic of Large Language Models (LLMs) without Retrieval Augmented Generation (RAG)?
   - [x] They rely on internal knowledge learned during pretraining on a large text corpus.
   - [ ] They always use an external database for generating responses.
   - [ ] They cannot generate responses without fine-tuning.
   - [ ] They use vector databases exclusively to produce answers.

### Build an LLM Application using OCI Generative AI Service

1. How are chains traditionally created in LangChain?
   - [ ] Declaratively, with no coding required
   - [ ] By using machine learning algorithms
   - [ ] Exclusively through third-party software integrations
   - [x] Using Python classes, such as LLM Chain and others

2. What is the function of "Prompts" in the chatbot system?
   - [ ] They are responsible for the underlying mechanics of the chatbot.
   - [ ] They store the chatbot's linguistic knowledge.
   - [x] They are used to initiate and guide the chatbot's responses.
   - [ ] They handle the chatbot's memory and recall abilities.

3. What is the purpose of memory in the LangChain framework?
   - [ ] To act as a static database for storing permanent records
   - [x] To store various types of data and provide algorithms for summarizing past interactions
   - [ ] To retrieve user input and provide real-time output only
   - [ ] To perform complex calculations unrelated to user interaction

4. How are prompt templates typically designed for language models?
   - [ ] To be used without any modification or customization
   - [ ] As complex algorithms that require manual compilation
   - [ ] To work only with numerical data instead of textual content
   - [x] As predefined recipes that guide the generation of language model prompts

5. What is LCEL in the context of LangChain Chains?
   - [ ] A programming language used to write documentation for LangChain
   - [x] A declarative way to compose chains together using LangChain Expression Language
   - [ ] An older Python library for building Large Language Models
   - [ ] A legacy method for creating chains in LangChain
