# LLM Assignment Solution

## Özgün Gizlenci

**Following documents including jupyter notebook file with a requirements:**
* **Video:** Short demonstration video is attached to the repo.


## Guideline

As collection of dataset provided article PDF documents are used for generating retrieval data.
The loaded text chunked into 1000 characters and vectorized for preparation of local database with ChromaDB.
Once the data is stored, a semantic search is conducted to retrieve similar chunks for generating appropriate responses with LLM.
LLM is provided with necessary prompts to gather answers required for article search.
Since OpenAI API has credit limit, Gemini Pro used as LLM and pipeline successfully demonstrated.