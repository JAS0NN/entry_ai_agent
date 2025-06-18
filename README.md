# Multi-Agents for IC Design

Welcome to the Multi-Agents for IC Design project\! This project provides a comprehensive framework for utilizing multiple AI agents to automate and assist in the Integrated Circuit (IC) design process. The ecosystem is supported by a robust, containerized infrastructure that ensures modularity and ease of use.

This README serves as the central entry point to the various repositories that constitute this project. It provides a high-level overview and a step-by-step guide to installing the necessary components. For detailed instructions, please refer to the `README.md` within each respective repository.

## Overview

The core of this project revolves around two specialized agents: a **Critical Path Analyzer Agent** and a **Hardware Sharing Agent**. These agents work in tandem to optimize IC designs.

To facilitate their operation, we have established an infrastructure that includes:

  * **MinIO**: A private S3-compatible object storage.
  * **VS Code (code-server) with RooCode Extension**: A web-based development environment for interacting with the entire system.
  * **MCP Servers**: Micro-Component Protocol (MCP) servers that act as a bridge to powerful EDA tools like OpenLane 2.

### Containerized Architecture with Podman

A key architectural feature of this project is the use of **Podman** containers. Major components including **MinIO, VS Code (code-server), the OpenLane MCP Server, the OpenLane + Flask server, and the Agents** are all packaged as containers. This approach makes the system highly modular, allowing individual components to be easily modified, updated, or replaced without disrupting the entire environment.

## Repositories

This project is distributed across the following seven repositories:

1.  **[MinIO](https://www.google.com/search?q=https://link-to-your-minio-repo)**: Contains the setup and Podman configuration for our private S3 object storage.
2.  **[VS Code with RooCode Extension](https://www.google.com/search?q=https://link-to-your-vscode-roocode-repo)**: Provides the customized VS Code (code-server) environment, containerized with Podman. The pre-compiled RooCode extension (`.vsix`) is included.
3.  **[OpenLane Remote MCP Server](https://www.google.com/search?q=https://link-to-your-openlane-mcp-repo)**: The containerized server that exposes OpenLane 2 functionalities via MCP.
4.  **[OpenLane + Flask Server](https://www.google.com/search?q=https://link-to-your-openlane-flask-repo)**: A containerized Flask-based server that provides a higher-level API for interacting with OpenLane.
5.  **[Critical Path Analyzer Agent](https://www.google.com/search?q=https://link-to-your-agent1-repo)**: The containerized Critical Path Analyzer Agent.
6.  **[Hardware Sharing Agent](https://www.google.com/search?q=https://link-to-your-agent2-repo)**: The containerized Hardware Sharing Agent.
7.  **[RooCode Source Code](https://www.google.com/search?q=https://link-to-your-roocode-source-repo)**: The source code for the RooCode VS Code extension. **Note:** You do not need to build or install this repository for setup.

## Installation Guide

The installation is divided into two main parts: Infrastructure and Agents. The Agents can be installed independently at any time.

### Part 1: Infrastructure Setup

To get the core system up and running, please follow the installation steps in the order outlined below. Each step directs you to the relevant repository, which contains detailed instructions for deploying the Podman container.

**Step 1: Set Up MinIO Storage**
Start by deploying the MinIO container, which is essential for data management.

➡️ **Installation Instructions**: [MinIO Repository README](https://www.google.com/search?q=https://link-to-your-minio-repo/blob/main/README.md)

**Step 2: Set Up the OpenLane + Flask Server**
Deploy the container for the Flask server, which provides a high-level API for EDA tool interaction.

➡️ **Installation Instructions**: [OpenLane + Flask Repository README](https://www.google.com/search?q=https://link-to-your-openlane-flask-repo/blob/main/README.md)

**Step 3: Set Up the OpenLane Remote MCP Server**
Deploy the container for the MCP server, which acts as the bridge to the OpenLane 2 EDA tool.

➡️ **Installation Instructions**: [OpenLane Remote MCP Server Repository README](https://www.google.com/search?q=https://link-to-your-openlane-mcp-repo/blob/main/README.md)

**Step 4: Deploy the VS Code Environment**
Finally, deploy the VS Code (code-server) container. This is your primary interface for the project and comes with the RooCode extension pre-loaded.

➡️ **Installation Instructions**: [VS Code with RooCode Extension Repository README](https://www.google.com/search?q=https://link-to-your-vscode-roocode-repo/blob/main/README.md)

-----

### Part 2: Agent Installation

The containerized agents can be installed independently of the infrastructure. Please refer to their respective repositories for setup instructions.

  * **Critical Path Analyzer Agent**:
    ➡️ **Installation Instructions**: [Agent1 Repository README](https://www.google.com/search?q=https://link-to-your-agent1-repo/blob/main/README.md)

  * **Hardware Sharing Agent**:
    ➡️ **Installation Instructions**: [Agent2 Repository README](https://www.google.com/search?q=https://link-to-your-agent2-repo/blob/main/README.md)

## Getting Started

Once the infrastructure components are deployed, you can start interacting with the system through the VS Code web interface. The RooCode extension will allow you to connect to the MCP servers and, once the agents are deployed, invoke them to work on your IC design projects. For specific usage instructions and examples, please refer to the documentation within the agent repositories.
