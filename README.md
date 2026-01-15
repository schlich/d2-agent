# d2-agent

A custom GitHub Copilot agent for visualizing agentic workflows using D2 diagrams.

## Overview

This repository contains a custom GitHub Copilot agent (`d2-agentic-workflow.agent.md`) that helps users design, visualize, and document multi-agent system architectures and agent-to-agent communication workflows using D2 (a modern diagram scripting language).

## Features

- **Agent Workflow Visualization**: Create clear diagrams showing how agents interact
- **Agent-to-Agent Protocol**: Demonstrates common patterns for agent communication
- **D2 Integration**: Uses D2's declarative syntax for creating professional diagrams
- **Multiple Patterns**: Includes examples of sequential, parallel, feedback loop, and hierarchical workflows

## What's Inside

### d2-agentic-workflow.agent.md

A custom GitHub Copilot agent that:
- Generates D2 diagrams for agent workflows
- Explains agent-to-agent protocol patterns
- Provides examples of common multi-agent architectures
- Helps document complex agentic systems

## Example Workflows

The agent includes examples of:

1. **Multi-Agent Orchestration** (`simple-workflow.d2`): A main orchestrator coordinating specialized agents (code, test, review)
2. **Parallel Processing** (`parallel-workflow.d2`): Multiple agents working simultaneously
3. **Sequential Pipeline** (`sequential-pipeline.d2`): Agents processing data in sequence
4. **Feedback Loop** (`feedback-loop.d2`): Agents with iterative refinement
5. **Hierarchical Delegation**: Multi-level agent hierarchies (demonstrated in the agent file)

See the [`examples/`](examples/) directory for complete D2 diagram files demonstrating these patterns.

## Usage

The agent file can be used with GitHub Copilot to help you:
- Design new multi-agent systems
- Document existing agent workflows
- Understand agent-to-agent communication patterns
- Generate D2 diagrams for your architecture

## About D2

D2 is a modern diagram scripting language that turns text into diagrams. It's perfect for:
- Version control (text-based)
- Code reviews (readable syntax)
- Documentation (integrated with markdown)
- Automation (scriptable)

Learn more at: https://d2lang.com

## License

See [LICENSE](LICENSE) file for details.