# Awesome Graph MCP：Graph相关MCP资源列表

调研图相关的 Model Context Protocol (MCP) 资源列表。
[English](https://github.com/MengmeiZ/awesome-graph-mcp/blob/main/README.md) | [中文](https://github.com/MengmeiZ/awesome-graph-mcp/blob/main/README.zh-CN.md)

## 什么是 MCP？
Model Context Protocol（MCP）是一个面向AI应用的开放标准，使得像Claude这样的⼤型语⾔模型（LLM）能够与外部系统交互、访问数据并执行其训练数据之外的操作。MCP 作为 LLM 与各种工具、数据库和服务之间的桥梁。
想了解更多关于 MCP 以及如何使用 LLM 构建自己的 MCP 服务器，请查阅[官方"用LLM构建MCP"教程](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms)。

## 知识图谱记忆

- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - 基于知识图谱的持久化记忆，用于跨对话记住用户信息。🎖️官方实现
- [topoteretes/cognee](https://github.com/topoteretes/cognee) - 使用可扩展、模块化的ECL（提取、认知、加载）流水线，结合知识图谱和向量数据库，构建动态Agent记忆。【star 2k+】
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) - 使用本地知识图谱实现的改进型持久化记忆，支持自定义 `--memory-path`。
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) - MemoryMesh 是为AI模型设计的知识图谱服务器，专注于文本RPG和互动叙事，帮助AI在对话中保持一致、结构化的记忆，实现更丰富和动态的交互。
- [rebots-online/mcp-chat-analysis-server](https://github.com/rebots-online/mcp-chat-analysis-server) - 通过向量嵌入和知识图谱实现聊天语义分析的MCP服务器。提供分析聊天数据、语义搜索、概念提取和对话模式分析等工具。<Neo4j><Qdrant>
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) - 本地优先的知识管理系统，从Markdown文件构建语义图，实现LLM对话的持久记忆。
- [T1nker-1220/memories-with-lessons-mcp-server](https://github.com/T1nker-1220/memories-with-lessons-mcp-server) - 基于本地知识图谱的基础持久化记忆实现，让Claude跨对话记住用户信息，并通过"教训系统"从过去错误中学习。
- [yodakeisuke/mcp-memory-domain-knowledge](https://github.com/yodakeisuke/mcp-memory-domain-knowledge) - 基于本地知识图谱的持久化记忆实现，让Claude跨对话记住用户信息。
- [gannonh/memento-mcp](https://github.com/gannonh/memento-mcp) - 可扩展、高性能的知识图谱记忆系统，具备语义检索、上下文回忆和时间感知，提供有韧性、自适应和持久的长期本体记忆。
- [j3k0/mcp-elastic-memory](https://github.com/j3k0/mcp-elastic-memory) - 基于Elasticsearch的强大知识图谱系统，具备持久记忆、智能搜索、上下文回忆和记忆分区。
- [BRO3886/mcp-memory-custom](https://github.com/BRO3886/mcp-memory-custom) - 为MCP团队的Memory服务器添加新功能，支持通过LLM交互创建和管理知识图谱。
- [itseasy21/mcp-knowledge-graph](https://github.com/itseasy21/mcp-knowledge-graph) - 使用本地知识图谱实现的改进型持久化记忆，支持自定义memory路径。
- [jovanhsu/mcp-neo4j-memory-server](https://github.com/jovanhsu/mcp-neo4j-memory-server) - 基于Neo4j图数据库的知识图谱记忆服务器，用于AI助手与用户交互过程中的信息存储与检索。
- [bneil/mcp-memory-pouchdb](https://github.com/bneil/mcp-memory-pouchdb) - 基于PouchDB的改进型持久化记忆实现，支持强健的文档存储、自定义memory路径和时间戳。
- [evangstav/python-memory-mcp-server](https://github.com/evangstav/python-memory-mcp-server) - 提供知识图谱功能的mcp服务器，用于管理内存中的实体、关系和观察，并通过严格的校验规则保证数据一致性。
- [noahgorstein/mcp-server-stardog](https://github.com/noahgorstein/mcp-server-stardog) - 允许开发者与Stardog知识图谱API交互，实现自动化和交互能力。
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) - 本地构建持久语义图的知识管理系统。
- [merill/lokka/tree/HEAD/src/mcp](https://github.com/merill/lokka/tree/HEAD/src/mcp) - Lokka是一个用于查询和管理Azure及Microsoft 365租户的MCP服务器，基于Microsoft Azure/Graph API。
- [okooo5km/memory-mcp-server](https://github.com/okooo5km/memory-mcp-server) - 提供持久化知识图谱系统，支持跨对话维护结构化记忆，支持实体和关系的创建、查询和管理。Swift实现的[TypeScript Memory MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)官方版本。
- [spences10/mcp-memory-libsql](https://github.com/spences10/mcp-memory-libsql) - 基于libSQL的高性能持久化记忆系统，支持向量搜索和高效知识存储。

## 图数据库

- [neo4j-contrib/mcp-neo4j/](https://github.com/neo4j-contrib/mcp-neo4j/) - 让你可以在Claude Desktop或其他MCP客户端（VS Code、Cursor、Windsurf）中用自然语言操作Neo4j和Aura账户。
- [PsiACE/nebulagraph-mcp-server](https://github.com/PsiACE/nebulagraph-mcp-server) - 提供对[NebulaGraph](https://github.com/vesoft-inc/nebula)的访问的MCP服务器实现。
- [FalkorDB/FalkorDB-MCPServer](https://github.com/FalkorDB/FalkorDB-MCPServer) - FalkorDB的MCP服务器，使AI模型能够查询和交互图数据库。
- [AGE-MCP-Server](https://github.com/rioriost/homebrew-age-mcp-server?tab=readme-ov-file) - [Apache AGE™](https://age.apache.org/) 是兼容PostgreSQL分布式资产的图数据库，利用图数据结构分析和利用数据中的关系与模式。
- [johnymontana/dgraph-mcp-server](https://github.com/johnymontana/dgraph-mcp-server) - Dgraph数据库连接器。
- [tigrisdata/mcp-tigris-graph](https://smithery.ai/server/@tigrisdata/mcp-tigris-graph) - Tigris图数据库的MCP接口，支持模式探索。
- [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) - 连接Memgraph的MCP服务器，Memgraph是为实时流处理构建的开源图数据库，兼容Neo4j。
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) - 使LLM能够与GraphQL API交互的MCP服务器。
- [keonchennl/mcp-graphdb](https://github.com/keonchennl/mcp-graphdb) - 提供[Ontotext GraphDB](https://www.ontotext.com/products/graphdb/)只读访问的MCP服务器，可探索RDF图和执行SPARQL查询。
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) - 允许LLM探索大型GraphQL模式而不增加上下文负担。
- [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) - 社区构建的Neo4j图数据库交互服务器。
- [saewoohan/mcp-graphql-tools](https://github.com/saewoohan/mcp-graphql-tools) - 提供GraphQL API交互能力，使AI助手通过标准化工具与GraphQL API交互。
- [JanithSilva/MCP-Server](https://github.com/JanithSilva/MCP-Server) - 基于Python的服务器应用，支持从SharePoint检索元数据和通过语义相似性搜索从Neo4j知识图谱检索实体。
- [YUZongmin/sqlite-literature-management-fastmcp-mcp-server](https://github.com/YUZongmin/sqlite-literature-management-fastmcp-mcp-server) - 灵活管理多种来源（论文、书籍、网页等）并与知识图谱（SQLite数据库）集成的系统。
- [rioriost/homebrew-age-mcp-server](https://github.com/rioriost/homebrew-age-mcp-server) - 通过Apache AGE图扩展将Claude与PostgreSQL数据库连接，实现自然语言执行Cypher查询、图操作、关系分析和数据可视化，无需复杂SQL。
- [amir-bengherbi/shopify-mcp-server](https://github.com/amir-bengherbi/shopify-mcp-server) - 集成Shopify的GraphQL API，实现全面的商店管理，包括商品、客户、订单和折扣操作。
- [psiace/nebulagraph-mcp-server](https://github.com/psiace/nebulagraph-mcp-server) - 为NebulaGraph 3.x图数据库提供轻量级访问的服务器，支持图模式探索、查询执行及路径查找、邻居发现等高级图操作。
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) - 通过专用工具支持AI模型探索和理解GraphQL模式，包括查询操作、类型定义查找、模式匹配和简化字段信息获取。

## 搜索

- [rileylemm/graphrag_mcp](https://github.com/rileylemm/graphrag_mcp) - 用于混合图RAG数据库交互的MCP服务器。
  - 数据库：Neo4j（图数据库）+ Qdrant（向量数据库）
  - 特性：
    - 文档被分块并根据类别及与其他文档的关系以图数据形式保存
    - 支持混合搜索，结合图和向量结果（先用向量数据库做语义搜索，再从图数据库检索相关文档）
- [NightTrek/Serper-search-mcp](https://github.com/NightTrek/Serper-search-mcp) - 通过Serper API将Google搜索功能集成到MCP应用中，提供丰富的搜索结果、可配置参数和高效响应处理。

## 其他应用

- [MattMorgis/nuanced-mcp](https://github.com/MattMorgis/nuanced-mcp) - 使LLM能够通过函数调用图理解和分析代码结构，让AI助手探索函数间关系并分析Python仓库中的依赖。
- [ontology-labs/mcp-schema-graph](https://smithery.ai/server/@ontology-labs/mcp-schema-graph) - 知识图谱的可视化与管理。
- [CartographAI/mcp-server-codegraph](https://github.com/CartographAI/mcp-server-codegraph) - 提供为代码库生成和查询图表示的工具。
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) - 为AI代理提供区块链索引数据的MCP服务器 [TheGraph](https://thegraph.com/zh/)。
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) - 与[CodeLogic](https://codelogic.com/)交互的软件智能平台，图化复杂代码和数据架构依赖，提升AI准确性和洞察力。
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) - 通过Resource Graph查询检索Azure订阅下的资源信息。

## 图数据分析

-

## 贡献

欢迎贡献！请随时提交Pull Request。

## 许可证

![](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)
