# Awesome Graph MCP

A curated list of awesome graph-related Model Context Protocol (MCP) resources.

[English](README.md) | [中文](README.zh-CN.md)

## What is MCP?

Model Context Protocol (MCP) is an open standard for AI applications that enables Large Language Models (LLMs) like Claude to interact with external systems, access data, and perform actions outside their training data. MCP serves as a bridge between LLMs and various tools, databases, and services.

For more information on MCP and how to build your own MCP servers using LLMs, check the [official Building MCP with LLMs tutorial](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms).

## Resource Distribution Analysis

### Statistics (as of April 2025)

| Category | Number of Resources | Approximate Avg. Stars* |
|----------|---------------------|-------------------------|
| Knowledge Graph Memory | 8 | ~80 |
| Graph Database Integrations | 7 | ~102 |
| Hybrid Search | 3 | ~131 |
| Data Analytics | 2 | Unknown |
| Specialized Applications | 3 | ~75 |
| **Total** | **23** | **~97** |

*Note: Average star counts are based on limited samples we've collected and may differ from actual figures. These numbers are provided as reference only to indicate relative trends.

## Contents

- [Knowledge Graph Memory](#knowledge-graph-memory)
- [Graph Database Integrations](#graph-database-integrations)
- [Hybrid Search](#hybrid-search)
- [Data Analytics](#data-analytics)
- [Specialized Applications](#specialized-applications)
- [Resource Distribution Analysis](#resource-distribution-analysis)

## Knowledge Graph Memory

- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory system for maintaining context.
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) - MCP server enabling persistent memory for Claude through a local knowledge graph - fork focused on local development. ⭐ 126
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) - Enhanced graph-based memory with a focus on AI role-play and story generation.
- [topoteretes/cognee](https://github.com/topoteretes/cognee) - Memory manager for AI apps and Agents using various graph and vector stores and allowing ingestion from 30+ data sources.
- [serverless-stack/sst-mcp-memory-graph](https://smithery.ai/server/@serverless-stack/sst-mcp-memory-graph) - Serverless implementation of a memory graph for MCP with cloud-native architecture.
- [markprompt/mcp-knowledge](https://smithery.ai/server/@markprompt/mcp-knowledge) - Knowledge graph tool for implementing long-term memory in Claude with document vectorization.
- [graphsignal/mcp-memory](https://github.com/graphsignal/mcp-memory) - Enhanced knowledge graph memory for Claude with visualization capabilities. ⭐ 45
- [remember-ai/graph-memory](https://github.com/remember-ai/graph-memory) - Graph-based memory server for MCP with focus on entity relationships and context-aware retrieval. ⭐ 68

## Graph Database Integrations

- [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) - Memgraph MCP Server - includes a tool to run a query against Memgraph and a schema resource.
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) - Model Context Protocol with Neo4j (Run queries, Knowledge Graph Memory, Manage Neo4j Aura Instances).
- [alanse/mcp-neo4j-server](https://github.com/alanse/mcp-neo4j-server) - MCP server for Neo4j integration.
- [neo4j-labs/claude-neo4j](https://smithery.ai/server/@neo4j-labs/claude-neo4j) - Official Neo4j integration for Claude via MCP with Cypher query execution.
- [arangodb/claude-arango](https://github.com/arangodb/claude-arango) - ArangoDB MCP connector for Claude allowing graph queries and traversals. ⭐ 120
- [dgraph-io/dgraph-mcp](https://github.com/dgraph-io/dgraph-mcp) - Dgraph database connector for Claude with GraphQL support. ⭐ 85
- [tigrisdata/mcp-tigris-graph](https://smithery.ai/server/@tigrisdata/mcp-tigris-graph) - MCP interface for Tigris Graph database with schema exploration.

## Hybrid Search

- [rileylemm/graphrag_mcp](https://github.com/rileylemm/graphrag_mcp) - MCP server for interacting with hybrid graph RAG database. ⭐ 2
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) - Weaviate vector-graph database connector for Claude with hybrid search capabilities.
- [qdrant/mcp-qdrant-hybrid](https://github.com/qdrant/mcp-qdrant-hybrid) - Hybrid search combining vector and knowledge graph capabilities. ⭐ 195

## Data Analytics

- [eno-graph/mcp-server-google-analytics](https://smithery.ai/server/@eno-graph/mcp-server-google-analytics) - MCP server for integrating Google Analytics data with graph-based analysis.
- [graphlytic/mcp-analytics](https://smithery.ai/server/@graphlytic/mcp-analytics) - Graph analytics toolkit for MCP with pattern and community detection.

## Specialized Applications

- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) - Ingest anything from Slack, Discord, websites, Google Drive, Linear or GitHub into a Graphlit project - and then search and retrieve relevant knowledge within an MCP client like Cursor, Windsurf or Cline.
- [knowledge-canvas/graph-explorer-mcp](https://github.com/knowledge-canvas/graph-explorer-mcp) - Interactive graph exploration tool integrated with Claude. ⭐ 75
- [ontology-labs/mcp-schema-graph](https://smithery.ai/server/@ontology-labs/mcp-schema-graph) - Schema visualization and management for knowledge graphs.

## Contributing

Contributions welcome! Please feel free to submit a pull request.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)