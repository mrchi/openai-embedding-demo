# openai-embedding-demo

[![Linters](https://github.com/mrchi/openai-embedding-demo/actions/workflows/linting.yaml/badge.svg)](https://github.com/mrchi/openai-embedding-demo/actions/workflows/linting.yaml)
[![Unit Testing](https://github.com/mrchi/openai-embedding-demo/actions/workflows/unittest.yaml/badge.svg)](https://github.com/mrchi/openai-embedding-demo/actions/workflows/unittest.yaml)

## Usage

1. Install PostgreSQL and pgvector. Refer [pgvector installation document](https://github.com/pgvector/pgvector#installation).
2. Create PostgreSQL database and table by following `cookbooks/db.ipynb`.
3. Prepare knowledge base data by following `cookbooks/prepare.ipynb`.
4. Query knowledge base data by following `cookbooks/query.ipynb`.

## Reference

- [如何基于llm构建知识库系统](https://volnet.hashnode.dev/how-to-build-a-knowledge-base-system-based-on-llm)
- [基于RDS PostgreSQL构建由LLM驱动的专属ChatBot](https://help.aliyun.com/document_detail/2357332.html)
- [高维向量相似度搜索（pgvector）](https://help.aliyun.com/document_detail/2369789.htm)
- [pgvector/pgvector: Open\-source vector similarity search for Postgres](https://github.com/pgvector/pgvector)
