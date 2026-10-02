# AUREX

### Personal AI Agent for Windows

> **Think. Plan. Act. Verify. Learn.**

AUREX is a long-term personal AI agent project for Windows. It is being built incrementally, starting with natural voice conversation and progressively gaining the ability to understand context, use computer tools, see the screen, solve problems, remember useful information, automate workflows, and operate remotely under controlled delegated authority.

## Vision

AUREX should become a general-purpose personal AI assistant that can help its user:

- Learn and understand any subject
- Research information and produce useful reports
- Solve problems by understanding goals, constraints, and context
- Plan tasks and projects
- Interact with a Windows computer through approved tools
- Automate repetitive workflows
- Help with programming and technical projects
- Prepare documents, presentations, and other work
- Remember useful long-term information
- Verify important actions and learn from feedback
- Adapt its explanations and interaction style to the user's needs
- Continue approved work when the user is physically away
- Request guidance or permission remotely when necessary

## Remote Presence & Delegated Autonomy

AUREX should eventually be able to continue working on an authorized task even when the user is away from the home computer.

The user can delegate a task together with boundaries, constraints, deadlines, and allowed actions. AUREX can then work independently within those boundaries.

If AUREX reaches an action that requires additional authority, it should send a permission or guidance request to a trusted device such as the user's phone.

The goal is:

> **The user does not need to be physically present for AUREX to work, but the user remains in control of important decisions.**

Example:

1. User assigns AUREX a freelance development task.
2. User specifies the deadline and allowed actions.
3. User leaves home.
4. AUREX works on the project, runs tests, researches problems, and prepares deliverables.
5. AUREX reaches a sensitive action such as publishing or sending the final deliverable.
6. AUREX sends a request to the user's trusted device.
7. User approves, rejects, or provides additional instructions.
8. AUREX continues and verifies the result.
9. AUREX reports the completed work and important actions taken.

This capability is planned for a later development stage and is not part of the first implementation.

## Core Interaction Loop

**Understand → Think → Plan → Explain → Approve → Act → Verify → Learn**

Not every action requires approval. Low-risk actions can eventually be automated, while sensitive or irreversible actions should require appropriate confirmation.

## Development Philosophy

AUREX will be built in stages rather than as one huge system.

1. **Level 0 — Vision:** Define what AUREX is and what it should become.
2. **Level 1 — Talk:** Natural voice conversation.
3. **Level 2 — Act:** Computer control and tool use.
4. **Level 3 — See:** Screen and visual understanding.
5. **Level 4 — Plan & Solve:** Multi-step reasoning and problem solving.
6. **Level 5 — Remember:** Long-term memory and personal knowledge.
7. **Level 6 — Automate & Remote Work:** Advanced workflows, unattended execution within delegated authority, and remote task interaction.
8. **Level 7 — Secure & Multi-user:** Identity, permissions, trusted devices, remote authorization, profiles, and safety controls.
9. **Level 8 — Improve:** Controlled improvement based on feedback and previous learnings.

## Current Status

**Level 0.1 — Vision Definition**

The repository is currently focused on defining the project's purpose, scope, architecture direction, and development roadmap before implementation begins.

## Project Principles

- Build a working core before adding complexity.
- Keep the human in control of important actions.
- Allow autonomy only within explicitly defined authority.
- Prefer explicit permissions over unrestricted computer access.
- Learn from feedback and errors without allowing uncontrolled self-modification.
- Keep the architecture modular so capabilities can be replaced or upgraded.
- Verify important actions instead of assuming they succeeded.
- Document major decisions and changes.
- Treat privacy and security as first-class requirements as capabilities expand.
- Never assume that physical absence means permission for every action.

## Long-Term Goal

Build a capable, reliable, extensible AI assistant that can understand the user's intent, reason about problems, use tools, interact with the computer, complete useful tasks, and continue authorized work remotely while keeping the user in control.

---

**Project:** AUREX  
**Type:** Personal AI Agent  
**Platform:** Windows  
**Status:** Early development
