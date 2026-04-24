# PaiFlow — AI Agent Workflow Orchestration Platform

- Built an enterprise-grade AI Agent workflow orchestration platform similar to Dify and Coze, supporting visual drag-and-drop node editing with a **React + TypeScript** frontend and **Spring Boot (Java 21)** backend
- Designed and implemented a **DAG-based workflow engine** that parses JSON DSL into an executable directed acyclic graph, scheduling nodes (LLM, tool, input/output) in topological order with context passing between nodes
- Integrated **DeepSeek LLM API** (OpenAI-compatible protocol) with dynamic Prompt template rendering using a custom variable pool and recursive path resolver to support cross-node data references like `{{node.output.field}}`
- Deployed supporting infrastructure with **Docker** (Redis, MinIO) and **MySQL**, connected via **JWT authentication** and real-time execution feedback through **SSE (Server-Sent Events)**# PaiAgent
