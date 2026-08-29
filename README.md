# Devlify VectorDB

**High-Performance Vector Database by [Devlify Marketplace](https://github.com/devlify-marketplace)**

A cloud-native vector database built for AI applications. Efficiently stores, indexes, and searches billions of embedding vectors for semantic search, RAG, and recommendation systems.

## Features

- Written in Go + C++ with CPU/GPU hardware acceleration
- **Kubernetes-native** distributed architecture — scales to billions of vectors
- Real-time streaming data ingestion
- Multiple deployment modes: Lite (pip install), Standalone (Docker), Distributed (K8s)
- Rich query API with filtering, hybrid search, and multi-vector support

## Quick Start

```python
pip install pymilvus

from pymilvus import MilvusClient
client = MilvusClient("devlify_vectors.db")

client.create_collection(
    collection_name="my_collection",
    dimension=768,
)
```

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.

---

*Part of the [Devlify Marketplace](https://github.com/devlify-marketplace) ecosystem.*
