<div align="center">
  <h2 align="center">✨ Awesome A2A (Agent2Agent Protocol) ✨ </h2>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/73dab1ee-dc61-4da0-b4e6-a4989feef916" alt="a2a to build imaginative agent society" width="600">
  </p>
  <p align="center">
     A curated list of A2A (Agent 2 Agent) Client、Server、Tools、Toturial etc.
  </p>
  <h4 align="center">
    <a href="https://awesome.re">
      <img src="https://awesome.re/badge.svg" alt="Awesome" />
    </a>
    <a href="CONTRIBUTING.md"> <!-- Link to your contributing file -->
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
    </a>
  </h4>
</div>

## 🤔 What is A2A?

A2A aims to provide a open standards protocal for agent to agent connecting, unlock collaborative. (https://github.com/google/A2A/tree/main for detail)
- Seamless Agent Collaboration: Introduces a standard protocol for autonomous, opaque agents built on different frameworks and by various vendors to communicate and collaborate effectively with each other and with users, addressing the current lack of agent interoperability.
- Simplifies Enterprise Agent Integration: Provides a straightforward way to integrate intelligent agents into existing enterprise applications, allowing businesses to leverage agent capabilities across their technology landscape.
- Supports Key Enterprise Requirements: Offers core functionalities essential for secure, enterprise-grade agent ecosystems, including capability discovery, user experience negotiation, task and state management, and secure collaboration.
![image](https://github.com/user-attachments/assets/0197f9c3-2db6-44aa-9ac3-251a61bf36fa)


## 🆚 Difference between A2A and MCP
A2A is not conflict with MCP（model context protocal). 
- MCP (Model Context Protocol) for tools and resources
  - Connect agents to tools, APIs, and resources with structured inputs/outputs.
  - Google ADK supports MCP tools. Enabling wide range of MCP servers to be used with agents.
- A2A (Agent2Agent Protocol) for agent-agent collaboration
  - Dynamic, multimodal communication between different agents without sharing memory, resources, and tools
  - Open standard driven by community.
  - Samples available using Google ADK, LangGraph, Crew.AI
 
## 🎬 Demos/Tuturials
- [A2A communication between different agent frameworks](https://storage.googleapis.com/gweb-developer-goog-blog-assets/original_videos/A2A_demo_v4.mp4)
- [ADK: Agent Development Kit](https://www.youtube.com/watch?v=Geo8LzCHoMQ) - make it easy to build multi-agent applications using A2A
 
## Agents (using A2A)
- [Demo Web App](showcases agents talking to other agents over A2A.)
- [Host Applications with A2A server](https://github.com/google/A2A/tree/main/samples/python)
- [✨ Movie Agent](https://github.com/google/A2A/blob/main/samples/js/src/agents/movie-agent/README.md) - uses the TMDB API to answer questions about movies.
- [✨ Coder Agent](https://github.com/google/A2A/blob/main/samples/js/src/agents/coder/README.md) - simple code-writing agent that emits full code files as artifacts.
- [✨ CrewAI Agent](https://github.com/google/A2A/blob/main/samples/python/agents/crewai/README.md) - A2A client using crewAI to generate images based on text promots.
- [✨ LangGraph Currency Agent](https://github.com/google/A2A/blob/main/samples/python/agents/langgraph/README.md) -  Demonstrates a currency conversion agent built with LangGraph and exposed through the A2A protocol
