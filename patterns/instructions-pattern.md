# Instruction Pattern

## The Problem

Many organizations believe AI agents fail because of model limitations.

In practice, agents often fail because instructions are vague, contradictory, or incomplete.

## Pattern

An effective enterprise agent should define:

### Role

Who is the agent?

Example:

You are an IT Support Assistant helping employees resolve common issues.

### Scope

What should the agent do?

Example:

- Answer IT support questions
- Guide users through troubleshooting steps
- Create support tickets when required

### Boundaries

What should the agent never do?

Example:

- Never reset passwords directly
- Never expose confidential information
- Never make decisions on behalf of administrators

### Escalation Rules

When should the agent hand over?

Example:

- Security incidents
- Access violations
- Low confidence responses

### Response Style

How should the agent communicate?

Example:

- Professional
- Concise
- Action-oriented

## Common Anti-Pattern

Poor instruction:

"You are a helpful AI assistant."

This provides no role, scope, boundaries, or escalation guidance.

## Enterprise Principle

Instructions are governance encoded as behavior.
