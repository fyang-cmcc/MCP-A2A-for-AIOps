# MCP/A2A for AIOps @ IETF 127 Side Meeting
This repository is used to organize and publish materials, problem statements, use-case discussions, and follow-up work related to the MCP/A2A for AIOPS Side Meeting at IETF 127.

The content of this repository consists of community discussion materials and does not represent formal IETF standards, working group conclusions, or consensus.

# Background
The rapid development of AI in the agent direction prompts us to consider whether networks can leverage AI capabilities to provide more efficient operations and maintenance.

We focus on the network fault handling scenario and explore how to combine AI Agents, operations knowledge, and standardized protocol capabilities to improve fault localization and troubleshooting efficiency in multi-vendor network environments.

# Target Scenario
Consider a multi-vendor network composed of controllers and network elements, where the controllers and network elements are provided by different vendors.

Traditional fault localization is usually triggered by monitoring system alarms or user complaint tickets. After receiving a ticket, operations personnel need to log in to a series of network elements along the faulty path according to the fault symptoms, perform hop-by-hop checks, collect information, and manually determine the root cause. This approach relies heavily on expert experience, and cross-vendor and cross-system troubleshooting is costly and inefficient.

## Working Approach
A network management and control system can learn from operations experience, including operations manuals and historical cases, automatically orchestrate troubleshooting processes based on fault symptoms, interact with network elements through MCP/A2A protocols, and execute troubleshooting steps step by step, thereby significantly improving operations efficiency.

In this scenario:

* MCP can be used to encapsulate the capabilities of network elements into standardized, invocable tools and resources;

* A2A can be used for collaboration and task orchestration among different Agents and different vendors' management and control systems;

* For network elements that do not directly support the relevant protocols, adaptation can be performed by controllers or a proxy layer.

# Disclaimer
This repository is only for community exchange and material organization for the MCP/A2A for AIOPS Side Meeting at IETF 127. It does not constitute IETF standards, formal working group documents, or any vendor product commitments.

