# Day 5 – Memory and RAG

## Project: Sweet Crumbs Home Bakery AI Agent

### Objective
Enhance the existing bakery AI agent by implementing conversation memory and Retrieval-Augmented Generation (RAG).

### Topics Covered
1. Three types of memory: Conversation Memory, Customer Memory and Business Knowledge.
2. Conversation memory using LangGraph checkpointers.
3. Managing separate conversations using thread IDs.
4. Embeddings and semantic search.
5. Vector databases using ChromaDB.
6. Creating and storing FAQ knowledge bases.
7. Document retrieval using semantic search.
8. Building a RAG search tool using LangChain.
9. Integrating memory and RAG into an AI agent.

### Technologies Used
- Python
- Google Colab
- LangChain
- Groq LLM
- LangGraph
- ChromaDB
- Google Sheets

### Implementation
- Restored the bakery's existing menu, pricing and opening-hours tools.
- Implemented conversation memory using `InMemorySaver()`.
- Tested separate customer conversations using thread IDs.
- Created a practice FAQ knowledge base containing 12 entries.
- Stored FAQ documents in ChromaDB.
- Experimented with semantic search and retrieval ranking.
- Created a LangChain `search_faq` tool.
- Integrated the FAQ retrieval tool with the existing bakery AI agent.

### Testing and Results
- Verified conversation memory using separate customer threads.
- Successfully retrieved relevant FAQ documents using ChromaDB.
- Tested the `search_faq` tool.
- Integrated four tools into the final AI agent:
  - `get_price`
  - `is_open`
  - `log_order`
  - `search_faq`
- Tested the final agent's ability to answer delivery-related questions using retrieved information.

### Important Note
The additional FAQ policies used in this workshop are practice data from the tutorial and are not all verified real-world policies of Sweet Crumbs Home Bakery.

### Learning Outcomes
- Understood different types of memory in AI agents.
- Learned how checkpointers maintain conversation history.
- Understood embeddings, vector databases and semantic search.
- Learned the working principles of Retrieval-Augmented Generation.
- Built an AI agent that combines conversation memory with knowledge retrieval.

### Notebook
`Day5_Memory_and_RAG.ipynb`
