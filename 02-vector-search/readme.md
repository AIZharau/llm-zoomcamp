# **Vector Search**

## **2.1 Getting Started with Vector Search and Qdrant**

Install qdrant and fastembed:
```python
pip install -q "qdrant-client[fastembed]>=1.14.2"
```

Run in Docker:
```bash
docker pull qdrant/qdrant

docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant
```