### LLM to reduce admin strain
- Vector database to store all canon in memory
	- additional one for pending canon just in case
	- [Explanation article](https://www.analyticsvidhya.com/blog/2023/10/how-to-build-llm-apps-using-vector-database/#:~:text=LLMs%20and%20Vector%20Databases,-Large%20Language%20Models&text=These%20models%20rely%20on%20a,a%20binary%20representation%20called%20embeddings.)
	- [Lantern](https://lantern.dev/blog/hnsw-index-creation) Postgres plugin written in c++
	- [Marqo](https://github.com/marqo-ai/marqo) Open-source doc-in-doc-out VecDb written in python
- Process all pull requests to check for conflicting canon