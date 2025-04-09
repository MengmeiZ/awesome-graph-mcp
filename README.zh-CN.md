# 图相关MCP资源

由于平时使用需要，最近调研了一下graph相关的模型上下文协议(Model Context Protocol, MCP)，整理了一份资源列表。

[English](README.md) | [中文](README.zh-CN.md)

## 什么是MCP？

模型上下文协议（Model Context Protocol，MCP）是一个开放标准，使Claude等大型语言模型（LLM）能够与外部系统交互、访问数据并执行其训练数据之外的操作。MCP充当了LLM与各种工具、数据库和服务之间的桥梁。

要了解更多关于MCP的信息以及如何使用LLM构建自己的MCP服务器，请查看[使用LLM构建MCP的官方教程](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms)。

## 目录

- [知识图谱记忆](#知识图谱记忆)
- [图数据库集成](#图数据库集成)
- [混合搜索](#混合搜索)
- [数据分析](#数据分析)
- [专业应用](#专业应用)

## 知识图谱记忆

- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - 基于知识图谱的持久记忆系统，用于维护上下文。
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) - 通过本地知识图谱为Claude提供持久记忆的MCP服务器 - 专注于本地开发的分支。 
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) - 增强的基于图的记忆，专注于AI角色扮演和故事生成。
- [topoteretes/cognee](https://github.com/topoteretes/cognee) - 用于AI应用和代理的记忆管理器，使用各种图和向量存储，并允许从30多个数据源进行摄取。
- [serverless-stack/sst-mcp-memory-graph](https://smithery.ai/server/@serverless-stack/sst-mcp-memory-graph) - 采用云原生架构的MCP记忆图的无服务器实现。
- [markprompt/mcp-knowledge](https://smithery.ai/server/@markprompt/mcp-knowledge) - 用于在Claude中实现长期记忆的知识图谱工具，具有文档向量化功能。

## 图数据库集成

- [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) - Memgraph MCP服务器 - 包含一个工具，用于对Memgraph运行查询和一个模式资源。
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) - 与Neo4j的模型上下文协议（运行查询、知识图谱记忆、管理Neo4j Aura实例）。
- [neo4j-labs/claude-neo4j](https://smithery.ai/server/@neo4j-labs/claude-neo4j) - 通过MCP实现的官方Neo4j与Claude集成，支持Cypher查询执行。
- [johnymontana/dgraph-mcp-server](https://github.com/johnymontana/dgraph-mcp-server) - Dgraph数据库连接器。
- [tigrisdata/mcp-tigris-graph](https://smithery.ai/server/@tigrisdata/mcp-tigris-graph) - Tigris Graph数据库的MCP接口，具有模式探索功能。

## 混合搜索

- [rileylemm/graphrag_mcp](https://github.com/rileylemm/graphrag_mcp) - 用于与混合图RAG数据库交互的MCP服务器。 
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) - Weaviate向量图数据库与Claude的连接器，具有混合搜索功能。

## 数据分析

- [eno-graph/mcp-server-google-analytics](https://smithery.ai/server/@eno-graph/mcp-server-google-analytics) - 用于集成Google Analytics数据与基于图的分析的MCP服务器。
- [graphlytic/mcp-analytics](https://smithery.ai/server/@graphlytic/mcp-analytics) - 具有模式和社区检测功能的MCP图分析工具包。

## 专业应用

- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) - 从Slack、Discord、网站、Google Drive、Linear或GitHub中摄取任何内容到Graphlit项目中，然后在MCP客户端（如Cursor、Windsurf或Cline）中搜索和检索相关知识。
- [ontology-labs/mcp-schema-graph](https://smithery.ai/server/@ontology-labs/mcp-schema-graph) - 知识图谱的模式可视化和管理工具。

## 贡献

欢迎贡献！请随时提交拉取请求。

## 许可证

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
