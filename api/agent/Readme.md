# CRAG Agent Layer

This module handles:
- Retrieval from FAISS
- Chunk grading
- Query rewriting
- Reflection loop
- Confidence scoring
- Response generation

Pipeline Flow:
1. Retrieve chunks
2. Grade chunks
3. Rewrite query if needed
4. Retrieve again
5. Generate grounded response
