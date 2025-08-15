Finance AI Assistant
====================
Retrieval-Augmented Generation (RAG) for Financial Insights

This project is a Generative AI system that answers finance-related queries using official company annual reports, a finance glossary, and news articles. It integrates a FAISS vector database for retrieval and the FLAN-T5-Large model for answer generation.

Features
--------
- Document Retrieval: Extracts and searches through company annual reports (PDFs), finance glossary, and news articles.
- FAISS Vector Database: Enables fast similarity search.
- Generative AI: Uses FLAN-T5-Large to provide context-aware answers.
- Performance Analysis: Displays latency breakdown and retrieval efficiency.
- Ethical AI: Uses publicly available data sources and avoids storing personal user data.

Project Structure
-----------------
Generative/
    architecture_diagram.png
    latency_grouped.png
    latency_stacked.png
   
notebooks/
    Generative.ipynb  (Google Colab notebook)
index.html
requirements.txt
README.txt


Usage
-----
To run this project:
1. Open the Google Colab notebook:
   [Google Colab Link Here]
   
2. Click "Run All" to execute the full pipeline.
3. Modify input prompts in the provided cells to test different queries.

Performance
-----------
- Retrieval time: less than 1 second on average.
- LLM processing time varies depending on query complexity.
- Detailed latency metrics available in the /Generative folder.


Ethical Considerations
----------------------
- All data sources are publicly available.
- Responses are grounded in retrieved documents to reduce hallucinations.
- No personal user data is stored.


