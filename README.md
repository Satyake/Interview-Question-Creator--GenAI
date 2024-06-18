# Interview-Question-Creator--GenAI

This is a Interview Question and Answer creator.
The App uses a RAG application with openai GPT 3.5-turbo model.
The model creates a vectorDB on FAISS and creates questions using a custom prompt.
For those custom prompts the model perform vector search/similarity search and augments and creates answers
by refering to the vectorDB.  (Augmented-Generation)

Front end is built with Fast API.
