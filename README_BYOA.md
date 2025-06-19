# AI Agents for IC Design: Towards a "Bring Your Own Agent" (BYOA) Future

This project demonstrates a framework for **Bring Your Own Agent (BYOA)** - a paradigm where individuals can easily develop specialized AI agents to automate their unique tasks, rather than relying solely on centralized AI solutions built by expert teams.

## The BYOA Vision

BYOA represents a complementary approach: **empowering individuals to develop their own AI agents tailored to their specific needs**.Currently, most enterprises rely on AI specialist teams and developers—to build shared AI solutions


## Our BYOA Examples


### IC Design Automation Agents

This implementation showcases BYOA principles through two specialized agents designed for IC design workflows:

- **Critical Path Analyzer Agent**: Automatically identifies and optimizes timing-critical paths in digital designs
- **Hardware Sharing Agent**: Intelligently manages and optimizes shared hardware resources

### Architecture: BYOA-Enabled Infrastructure

Our containerized architecture embodies BYOA principles by providing:

- **MinIO**: Private, secure data storage for individual agent workflows
- **VS Code with RooCode Extension**: Browser-based development environment eliminating setup barriers
- **MCP Server**: Standardized bridge to professional EDA tools
- **Containerized Agents**: Self-contained, easily deployable agent instances


## Getting Started with BYOA

This project is distributed across seven repositories, each representing a key component in the BYOA ecosystem:

### Agent Examples
1. **[Critical Path Analyzer Agent](https://github.com/mtkresearch/critical_path_analyze_agent)**
2. **[Hardware Sharing Agent](https://github.com/mtkresearch/hardware_sharing_agent)**

### Infrastructure Components
1. **[MinIO Storage](https://github.com/mtkresearch/minIO_server)**: A private S3-compatible object storage.
2. **[VS Code Environment](https://github.com/mtkresearch/codeserver)**: A browser-based development environment.
3. **[OpenLane MCP Server](https://github.com/mtkresearch/openlane_mcp_server)**: A remote Model Context Protocol (MCP) server that act as a bridge to EDA tools like OpenLane 2.
4. **[EDA tools](https://github.com/mtkresearch/openlane_docker)**: Flask server & Openlane2
5. **[RooCode Extension](https://github.com/mtkresearch/Roo-Code/tree/http_feat)**: The source code for the RooCode VS Code extension.




---

**Ready to experience BYOA?** Start with our infrastructure setup and begin building your first personal AI agent. The future of work isn't just AI-assisted—it's AI-empowered, with every individual capable of creating their own intelligent automation solutions.
