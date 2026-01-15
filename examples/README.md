# D2 Agent Workflow Examples

This directory contains example D2 diagrams showing different agent workflow patterns.

## Files

### simple-workflow.d2
A comprehensive multi-agent orchestration example showing:
- User interaction with an orchestrator agent
- Specialized agents for code generation, testing, and review
- Sequential task delegation and result aggregation
- Clear labeling of communication steps

### parallel-workflow.d2
Demonstrates parallel processing pattern with:
- A coordinator distributing work to multiple worker agents
- Simultaneous execution by specialized workers
- Result aggregation from all workers
- Efficient parallel task execution

### sequential-pipeline.d2
Shows a linear processing pipeline with:
- Data flowing through multiple transformation stages
- Each agent specializing in one transformation step
- Clear input-to-output flow
- Simple sequential processing pattern

### feedback-loop.d2
Illustrates iterative refinement with:
- Planning, execution, and evaluation cycle
- Feedback loop for continuous improvement
- Success criteria evaluation
- Conditional flow based on evaluation results

## Viewing the Diagrams

To render these D2 diagrams, you can:

1. **Install D2**: Follow instructions at https://d2lang.com
2. **Render a diagram**: 
   ```bash
   d2 simple-workflow.d2 simple-workflow.svg
   ```
3. **Use online tools**: Copy the D2 code to an online D2 playground

## Usage with the Agent

These examples serve as templates for the `d2-agentic-workflow.agent.md` agent. The agent can:
- Generate similar diagrams from natural language descriptions
- Explain the patterns demonstrated in these examples
- Help you create custom workflows based on these patterns
- Adapt these patterns to your specific use case

## Pattern Selection Guide

- **Simple Workflow**: Use when you need a clear orchestrated multi-step process
- **Parallel Workflow**: Use when tasks can be executed simultaneously
- **Sequential Pipeline**: Use for data transformation or processing pipelines
- **Feedback Loop**: Use when iterative refinement or validation is needed

## Customization

All these examples use:
- Color coding to distinguish agent types
- Clear labels for all connections
- Shape variations (hexagon for coordinators, rectangles for workers, etc.)
- Style properties for visual emphasis

Feel free to adapt these patterns for your specific agent architectures!
