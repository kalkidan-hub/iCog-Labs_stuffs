# YouTube Note-Taking and Semantic Search

This project enables users to take notes from YouTube videos, extract key points, and store them in **ChromaDB** for semantic search. Users can then query their notes to retrieve relevant insights efficiently.

---

## Features
- Extract key points from YouTube videos.
- Store notes as embeddings using **ChromaDB**.
- Perform semantic search on stored notes to answer user queries.

---

## How It Works
1. **Fetch Transcripts**:
   - Use the **YouTubeTranscriptApi** to retrieve video transcripts.
2. **Embed Notes**:
   - Use a transformer model to convert notes into vector embeddings.
3. **Store in ChromaDB**:
   - Save embeddings and metadata (e.g., video title, timestamp).
4. **Query Notes**:
   - Input a question, and the app retrieves relevant notes using semantic similarity.

---
