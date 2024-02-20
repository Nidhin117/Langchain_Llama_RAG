# Langchain_Llama_RAG
RAG QA over custom files using BGE embeddings, Llama2 70b LLM and chroma vector DB
In this project I have used Hugging face BGE embeddings. After experimenting with numerour other emdedding techniques I found that the BGE embeddings outperformed the rest for RAG specific tasks and this is also backed by the fact that BGE embeddings are ranked higher than Google and OpenAI embedding model on the embeddings leaderboard.
The Llama2 70b model was used through the TogetherAI LLM API wrapper available in Langchain.
I was able to get great results for my QA over custom file using BGE embeddings and Llama2 model when compared to Google's generative AI embeddings and gemini model.
