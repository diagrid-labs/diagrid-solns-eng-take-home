# Diagrid Solutions Engineer – Take-Home Assignment

Build an autonomous agent of your choice, run it with Diagrid, and prepare a short presentation showcasing:

- The problem you are solving
- Why Diagrid is a good fit and what problems it solves
- The architecture and technology that is used
- How Diagrid helps manage, observe and operate the system

The goal is to create the application, explain the problem that the agent is solving, and demonstrate that you have thought about production considerations.

## Requirements

Your agent must:

- Use one of the following AI Agent frameworks:
  - Dapr Agents
  - LangGraph
  - CrewAI
  - Strands
  - Google ADK
  - Microsoft Agent Framework
  - OpenAI Agents
  - Pydantic AI
  - Deep Agents
  - Claude Agents

  **Agents framework:** https://docs.diagrid.io/develop/agents/#framework-requirements

- Be demonstrated using Diagrid:
  - Showcasing the agent running
  - Visualizing application topology, components, and past executions
  - Explaining what Diagrid does in addition to the agent

- Be implemented in one or more of the following languages:
  - Java
  - .NET
  - Python
  - Go

### Agent Scenarios

Choose one of these scenarios or come up with your own:

- Invoice intake agent that reads invoices from a location to extract and reason on data from them
- Support triage agent that picks up new tickets, clarifies urgency and uses a knowledge base to provide a response
- Lead enrichment agent that enhances basic leads with information from the internet

Additional inspiration: 
 - https://docs.diagrid.io/dapr/use-cases/ai-agents
 - https://github.com/dapr/dapr-agents/tree/main/examples

## Deliverables

**Application source code:** GitHub repository code and a README containing the following:

  - Agent scenario
  - Architecture overview including agent framework used
  - How to run the application locally

**Diagrid Demo**: 20-30 minute (approx.) live demo on a scheduled interview panel call showcasing the following:

  - Application architecture and behavior
  - Agent in action
  - Diagrid visualization and insights
  - Future production considerations

## Evaluation Criteria

You will be evaluated on:

- Effective use of an Agent framework
- Potential business value of the solution using Diagrid
- Presentation clarity and communication skills
- Code quality and completeness
- Future production considerations (scalability, resiliency, security, etc.)

### Bonus Points

- Use a Dapr API or MCP server in a cohesive way
- Demonstration of failure scenarios and recovery
- Thoughtful discussion of architectural trade-offs and design decisions
- Mapping the solution to a realistic customer use case

## About Diagrid

Diagrid is an agentic durable execution platform for governing, securing, and running agents and workflows in production. It gives every workload — an agent, a workflow, an MCP server, or an application — a verifiable identity, durable execution, and policy-driven access, without writing security or infrastructure code in your application. With Diagrid, teams can:

- Orchestrate and understand complex business processes with end-to-end visibility
- Build autonomous AI agents without sacrificing reliability, security, or auditability
- Connect and secure apps and agents across any platform, cloud, region, or compute
- Accelerate development and time-to-production with a unified programming model on open-source Dapr
- Enforce governance and enable collaboration with organization and project constructs
- Integrate and swap cloud services and LLMs without rewrites using Dapr components

#### Resources

- Sign up for a free Diagrid Cloud account here: https://www.diagrid.io/catalyst
- Connect to Diagrid for local dev/test: https://docs.diagrid.io/develop/connect/
