A Wikipedia Knowledge based Graph RAG System built using Python,LangChain, Neo4j ,OpenAI API, Wikipedia API.An intelligent question-answering system powered by knowledge graphs, combining Neo4j database and Wikipedia data for efficient Retrieval-Augmented Generation (RAG).

Features include:Smart Retrieval for hybrid vector and graph-based search Knowledge Construction , Automated Wikipedia entity relationship extraction, Context Aware - Multi-turn conversation,memory Real-time Updates and Dynamic Wikipedia data synchronization

Requirements: Python 3.8+,LangChain 0.3.7,Neo4j Database,OpenAI API access

Environment Variables-- Create a .env file with:
AURA_INSTANCENAME=your_instance
NEO4J_URI=your_uri
NEO4J_USERNAME=your_username
NEO4J_PASSWORD=your_password
NEO4J_DATABASE=your_database
OPENAI_API_KEY=your_key
OPENAI_ENDPOINT=your_endpoint


Usage
python wikipedia_kg_rag.py



