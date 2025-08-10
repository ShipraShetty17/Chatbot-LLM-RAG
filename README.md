Wikipedia Knowledge Graph RAG System
Python LangChain Neo4j OpenAI Wikipedia

An intelligent question-answering system powered by knowledge graphs, combining Neo4j database and Wikipedia data for efficient Retrieval-Augmented Generation (RAG).

 Features
Smart Retrieval - Hybrid vector and graph-based search Knowledge Construction - Automated Wikipedia entity relationship extraction  Context Aware - Multi-turn conversation memory Real-time Updates - Dynamic Wikipedia data synchronization

Requirements
Python 3.8+
LangChain 0.3.7
Neo4j Database
OpenAI API access

Environment Variables
Create a .env file with:
AURA_INSTANCENAME=your_instance
NEO4J_URI=your_uri
NEO4J_USERNAME=your_username
NEO4J_PASSWORD=your_password
NEO4J_DATABASE=your_database
OPENAI_API_KEY=your_key
OPENAI_ENDPOINT=your_endpoint

Installation
pip install -r requirements.txt

Usage
python wikipedia_kg_rag.py

graph TD
    A[Wikipedia Data] -->|Extract| B[Data Processor]
    B -->|Store| C[Neo4j Graph]
    B -->|Embed| D[Vector Store]
    E[User Query] -->|Input| F[Query Engine]
    F -->|Search| C
    F -->|Match| D
    C -->|Context| G[Response Generator]
    D -->|Similar Docs| G
    G -->|Generate| H[Final Answer]



