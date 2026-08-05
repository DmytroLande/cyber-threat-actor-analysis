# Structured Agent Prompts

This directory documents the prompt transformation stage of the proposed methodology.

Unlike conventional prompt engineering, the methodology automatically transforms an initial analytical request into a structured executable AgentFlow scenario.

The transformation is performed using the published AgentFlow framework.

## Workflow

Primary Analytical Prompt

↓

AgentFlow Framework

↓

Structured Agentic Prompt

↓

Execution by the Virtual Expert Swarm

↓

Semantic Graph Construction

---

## Directory Structure

### input/

Contains the original analytical task formulated by the researcher.

Current file:

- first_prompt.txt

This prompt specifies the analytical objectives without defining the execution strategy.

---

### generated/

Contains the structured AgentFlow prompt automatically generated from the primary prompt.

Current file:

- agentic_prompt.txt

The generated prompt explicitly defines:

- analytical functions;
- virtual expert roles;
- execution order;
- iterative procedures;
- data flow;
- output schemas.

---

The AgentFlow framework responsible for this transformation is described in the publications listed in the **Scientific Foundations** section of this repository.
