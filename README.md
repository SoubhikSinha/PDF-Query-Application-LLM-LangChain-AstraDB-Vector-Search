# LLM-Langchain-Cassandra-AstraDB-VectorDB

## Acknowledgement

I would like to extend my sincere thanks to  [Krish Naik](https://github.com/krishnaik06)  for his invaluable content and guidance, which helped me build this project. This project wouldn't have been possible without his educational resources.

<br>

## About the Project

The goal of this project is to create a _**PDF Query Application using LangChain and CassandraDB**_.

This project utilizes [DataStax](https://www.datastax.com/) to integrate [Apache Cassandra](https://cassandra.apache.org/_/index.html) for efficient [vector search](https://learn.microsoft.com/en-us/azure/search/vector-search-overview). It leverages [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) to convert text into vector representations, which are then stored in CassandraDB using DataStax.

To query the PDF, the application employs [Similarity Search](https://www.pinecone.io/learn/what-is-similarity-search/) along with [Text Embeddings](https://www.datacamp.com/blog/what-is-text-embedding-ai) to retrieve relevant content effectively.

<br>

## How to Run the Project ?

### **1. Clone the Repository**
Clone the repository to your local machine :
```bash
git clone git@github.com:SoubhikSinha/LLM-Langchain-Cassandra-AstraDB-VectorDB.git
```

<br>

### **2. Load the Notebook and PDF into Google Colab**
-   Open Google Colab.
-   Upload the following files to your Colab environment:
    -   **`PDFQuery_LangChain.ipynb`** (Jupyter notebook)
    -   **`budget_speech.pdf`** (PDF file)

<br>

### **3. Follow the Notebook Instructions**
-   Open `PDFQuery_LangChain.ipynb` in Google Colab.
-   Follow the step-by-step instructions provided in the notebook to set up and run the project.
