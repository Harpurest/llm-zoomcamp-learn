```bash
docker pull qdrant/qdrant

docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant
```

```JavaScript
{
  "limit": 948,
  "color_by": {
    "payload": "course"
  }
}
```