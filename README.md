# Awesome Graph MCP: A curated list of awesome graph-related Model Context Protocol (MCP) resources

A curated list of graph-related Model Context Protocol (MCP) resources.
[English](https://www.notion.so/README.md) | [中文](https://www.notion.so/README.zh-CN.md)

## What is MCP?

Model Context Protocol (MCP) is an open standard for AI applications that enables Large Language Models (LLMs) like Claude to interact with external systems, access data, and perform actions outside their training data. MCP serves as a bridge between LLMs and various tools, databases, and services.
For more information on MCP and how to build your own MCP servers using LLMs, check the [official Building MCP with LLMs tutorial](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms).

## Contents

- 

## Knowledge Graph Memory

- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory for remembering information about the user across chats. 🎖️Official implementation
- [topoteretes/cognee](https://github.com/topoteretes/cognee) - Build dynamic Agent memory using scalable, modular ECL (Extract, Cognify, Load) pipelines, using knowledge graph and vector database. 【star 2k+】
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) - An improved implementation of persistent memory using a local knowledge graph with a customizable `--memory-path`.
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) - MemoryMesh is a knowledge graph server designed for AI models, with a focus on text-based RPGs and interactive storytelling. It helps AI maintain consistent, structured memory across conversations, enabling richer and more dynamic interactions.
- [rebots-online/mcp-chat-analysis-server](https://github.com/rebots-online/mcp-chat-analysis-server) - An MCP server that enables semantic analysis of chat conversations through vector embeddings and knowledge graphs. This server provides tools for analyzing chat data, performing semantic search, extracting concepts, and analyzing conversation patterns. <Neo4j><Qdrant>
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) - Local-first knowledge management system that builds a semantic graph from Markdown files, enabling persistent memory across conversations with LLMs.
- [T1nker-1220/memories-with-lessons-mcp-server](https://github.com/T1nker-1220/memories-with-lessons-mcp-server) - A basic implementation of persistent memory using a local knowledge graph. This lets Claude remember information about the user across chats and learn from past errors through a lesson system.
- [yodakeisuke/mcp-memory-domain-knowledge](https://github.com/yodakeisuke/mcp-memory-domain-knowledge) -  An implementation of persistent memory using a local knowledge graph. This lets Claude remember information about the user across chats.
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) - Scalable, high performance knowledge graph memory system with semantic retrieval, contextual recall, and temporal awareness. Provide resilient, adaptive, and persistent long-term ontological memory.
- [j3k0/mcp-elastic-memory](https://github.com/j3k0/mcp-elastic-memory) - A robust, Elasticsearch-backed knowledge graph system with persistent memory, smart search, contextual recall, memory zones.
- [BRO3886/mcp-memory-custom](https://github.com/BRO3886/mcp-memory-custom) - This project adds new features to the Memory server offered by the MCP team. It allows for the creation and management of a knowledge graph that captures interactions via LLM.
- [itseasy21/mcp-knowledge-graph](https://github.com/itseasy21/mcp-knowledge-graph) - An improved implementation of persistent memory using a local knowledge graph with a customizable memory path.
- [jovanhsu/mcp-neo4j-memory-server](https://github.com/jovanhsu/mcp-neo4j-memory-server) - A knowledge graph memory server based on the Neo4j graph database, used for storing and retrieving information during the interaction process between AI assistants and users.
- [bneil/mcp-memory-pouchdb](https://github.com/bneil/mcp-memory-pouchdb) - An improved implementation of persistent memory with PouchDB for robust document-based storage, custom memory paths and timestamping.
- [evangstav/python-memory-mcp-server](https://github.com/evangstav/python-memory-mcp-server) - A mcp server that provides knowledge graph functionality for managing entities, relations, and observations in memory, with strict validation rules to maintain data consistency.
- [noahgorstein/mcp-server-stardog](https://github.com/noahgorstein/mcp-server-stardog) - It allows developers to interact with Stardog Knowledge Graph APIs, enabling automation and interaction capabilities.
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) - Knowledge management system that builds a persistent semantic graph in markdown, locally.
- [merill/lokka/tree/HEAD/src/mcp](https://github.com/merill/lokka/tree/HEAD/src/mcp) - Lokka is an MCP server for querying and managing your Azure and Microsoft 365 tenants using the Microsoft Azure/Graph APIs.
- [okooo5km/memory-mcp-server](https://github.com/okooo5km/memory-mcp-server) - Provides a persistent knowledge graph system for maintaining structured memory across conversations, enabling creation, querying, and management of entities and relationships through specialized graph operation tools. This is a Swift implementation of the official [TypeScript Memory MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory).
- [spences10/mcp-memory-libsql](https://github.com/spences10/mcp-memory-libsql) - A high-performance, persistent memory system for the Model Context Protocol (MCP) powered by libSQL. This server provides vector search capabilities and efficient knowledge storage using libSQL as the backing store.

## Graph Database Integrations

- [neo4j-contrib/mcp-neo4j/](https://github.com/neo4j-contrib/mcp-neo4j/) - This lets you use Claude Desktop, or any other MCP Client (VS Code, Cursor, Windsurf), to use natural language to accomplish things with Neo4j and your Aura account.
- [PsiACE/nebulagraph-mcp-server](https://github.com/PsiACE/nebulagraph-mcp-server) - A MCP server implementation that provides access to [NebulaGraph](https://github.com/vesoft-inc/nebula).
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) - A MCP server for FalkorDB, allowing AI models to query and interact with graph databases.
- [AGE-MCP-Server](https://github.com/rioriost/homebrew-age-mcp-server?tab=readme-ov-file) - [Apache AGE™](https://age.apache.org/) is a PostgreSQL Graph database compatible with PostgreSQL's distributed assets and leverages graph data structures to analyze and use relationships and patterns in data.
- [johnymontana/dgraph-mcp-server](https://github.com/johnymontana/dgraph-mcp-server) - Dgraph database connector.
- [tigrisdata/mcp-tigris-graph](https://smithery.ai/server/@tigrisdata/mcp-tigris-graph) - MCP interface for Tigris Graph database with schema exploration.
- [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) - It is a MCP server to connect Memgraph, which is an open source graph database built for real-time streaming and compatible with Neo4j.
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) - A MCP server that enables LLMs to interact with GraphQL APIs.
- [keonchennl/mcp-graphdb](https://github.com/keonchennl/mcp-graphdb) - A MCP server that provides read-only access to [Ontotext GraphDB](https://www.ontotext.com/products/graphdb/), to explore RDF graphs and execute SPARQL queries.
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) - Allow LLMs to explore large GraphQL schemas without bloating the context.
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) - A community built server that interacts with Neo4j Graph Database.
- [saewoohan/mcp-graphql-tools](https://github.com/saewoohan/mcp-graphql-tools) - It provides GraphQL API interaction capabilities, enabling AI assistants to interact with GraphQL APIs through standardized tools.
- [JanithSilva/MCP-Server](https://github.com/JanithSilva/MCP-Server) - A Python-based server application that provides tools for metadata retrieval from SharePoint and entity retrieval from a Neo4j knowledge graph using semantic similarity search.
- [YUZongmin/sqlite-literature-management-fastmcp-mcp-server](https://github.com/YUZongmin/sqlite-literature-management-fastmcp-mcp-server) - A flexible system for managing various types of sources (papers, books, webpages, etc.) and integrating them with knowledge graphs (SQLite database).
- [rioriost/homebrew-age-mcp-server](https://github.com/rioriost/homebrew-age-mcp-server) - Bridges Claude with PostgreSQL databases using Apache AGE graph extension, enabling natural language execution of Cypher queries for graph operations, relationship analysis, and data visualization without complex SQL.
- [amir-bengherbi/shopify-mcp-server](https://github.com/amir-bengherbi/shopify-mcp-server) - Integrates with Shopify's GraphQL API to enable comprehensive store management, including product, customer, order, and discount operations.
- [psiace/nebulagraph-mcp-server](https://github.com/psiace/nebulagraph-mcp-server) - Provides a lightweight server for seamless access to NebulaGraph 3.x graph databases, enabling graph schema exploration, query execution, and advanced graph-based operations like path finding and neighbor discovery.
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) - Enables AI models to explore and understand GraphQL schemas through specialized tools for querying operations, looking up type definitions, pattern matching, and retrieving simplified field information

## Hybrid Search

- [rileylemm/graphrag_mcp](https://github.com/rileylemm/graphrag_mcp) - MCP server for interacting with hybrid graph RAG database.
  - Database: Neo4j (graph db) + Qdrant (vector db)
  - Features:
    - Documents are splitted into chunks and saved as graph data based on its category and relationship with other docs
    - Support hybrid search, which features both graph and vector results (do semantic search with vector db first, then retrieve related documents from graph db)
- [NightTrek/Serper-search-mcp](https://github.com/NightTrek/Serper-search-mcp) - Enables integration of Google search functionality into MCP-enabled applications using the Serper API, providing rich search results, configurable parameters, and efficient response handling.

## Other Applications

- [MattMorgis/nuanced-mcp](https://github.com/MattMorgis/nuanced-mcp) - An MCP server that enables LLMs to understand and analyze code structure through function call graphs, allowing AI assistants to explore relationships between functions and analyze dependencies in Python repositories.
- [ontology-labs/mcp-schema-graph](https://smithery.ai/server/@ontology-labs/mcp-schema-graph) - Schema visualization and management for knowledge graphs.
- [CartographAI/mcp-server-codegraph](https://github.com/CartographAI/mcp-server-codegraph) - Provide tools to generate and query a graph representation for your codebase.
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) - An MCP server that powers AI agents with indexed blockchain data [TheGraph](https://thegraph.com/zh/).
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) - Interact with [CodeLogic](https://codelogic.com/), a Software Intelligence platform that graphs complex code and data architecture dependencies, to boost AI accuracy and insight.
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) - retrieve information about Azure resources across your subscriptions using Resource Graph queries.

## Graph Data Analytics

-

## Contributing

Contributions welcome! Please feel free to submit a pull request.

## License

![](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)
