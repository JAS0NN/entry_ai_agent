# AI Agents for IC Design: Unlock Your "Bring Your Own Agent" (BYOA) Future

Imagine an AI agent that works exactly the way you do, designed by you, for your unique tasks. That's the power of **Bring Your Own Agent (BYOA)**. This project introduces a framework that empowers *individuals* to develop specialized AI agents, moving beyond the traditional reliance on centralized AI solutions built by large teams.

## Why BYOA? Empowering *You* with AI

-----

Today, AI development is often centralized, with specialist teams building solutions for everyone. But what if you could have an AI agent perfectly tailored to *your* specific needs and workflows?

**BYOA offers a powerful alternative:** it empowers you to be the architect of your own AI solutions. This isn't just about using AI; it's about **creating your own intelligent automation**, designed to solve your unique challenges and enhance your productivity.

## See BYOA in Action: IC Design Automation Agents

-----

To demonstrate the potential of BYOA, we've developed two specialized AI agents for common IC design workflows:

  * **Critical Path Analyzer Agent**: Tackle timing bottlenecks early. This agent identifies critical timing paths and proposes optimizations directly at the RTL level, helping you proactively resolve issues and accelerate your design workflow before synthesis.
  * **Hardware Sharing Agent**:  Optimize your resources and reduce costs. This agent analyzes your RTL designs to detect redundant arithmetic units (like adders or multipliers) and automatically generates optimized code that shares hardware, reducing resource usage without compromising functionality.

## The Containerized Infrastructure

-----

Our containerized infrastructure enables your agents to seamlessly connect with the RooCode coding agent and other tools via the Model Context Protocol (MCP) configured on RooCode. This setup includes:

  * **MinIO**: A private data storage.
  * **VS Code with RooCode Extension**: A browser-based development environment.
  * **Remote MCP Server**: A standardized bridge to Electronic Design Automation (EDA) tools.
  * **OpenLane2**: An open-source EDA flow that provides automated synthesis, place-and-route, and other critical steps for chip design.

## Get Started: Build Your Own Agent Today

-----

Ready to step into the future of personalized AI? This project is distributed across seven interconnected repositories.

### Agent Examples

Explore our ready-to-use examples to see BYOA in action or use them as a starting point for your own creations:

1.  **[Critical Path Analyzer Agent](https://github.com/mtkresearch/critical_path_analyze_agent)**
2.  **[Hardware Sharing Agent](https://github.com/mtkresearch/hardware_sharing_agent)**

### Infrastructure Components

These repositories provide the foundational tools to set up your BYOA environment:

1.  **[MinIO Storage](https://github.com/mtkresearch/minIO_server)**: Your personal S3-compatible object storage.
2.  **[VS Code Environment](https://github.com/mtkresearch/codeserver)**: Your browser-based development hub.
3.  **[OpenLane MCP Server](https://github.com/mtkresearch/openlane_mcp_server)**: The bridge to EDA tools like OpenLane 2.
4.  **[EDA tools](https://github.com/mtkresearch/openlane_docker)**: The Flask server and OpenLane2 integration.
5.  **[RooCode Extension](https://github.com/mtkresearch/Roo-Code/tree/http_feat)**: The source code for the essential RooCode VS Code extension.

-----

**Ready to unleash the power of personalized AI?**

### **Follow our installation guide [here](https://github.com/JAS0NN/entry_ai_agent/blob/main/installation.md)**
