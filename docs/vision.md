# AUREX — Vision Specification

## 0.1 Define AUREX

### 0.1.1 Identity

**Name:** AUREX

**Product type:** Personal AI Agent for Windows

**Inspiration:** A real-world, practical interpretation of the JARVIS-style personal assistant concept.

**Tagline:**

> Think. Plan. Act. Verify. Learn.

AUREX is not intended to be a fictional AI character. It is an engineering project whose goal is to progressively combine conversational AI, reasoning, tools, computer interaction, memory, automation, remote access, and controlled autonomy into one assistant.

---

## 0.1.2 Mission

AUREX exists to help its user:

> **Understand, learn, research, plan, create, solve, automate, and execute tasks across different domains through natural interaction with an AI system.**

As its capabilities grow, AUREX should be able to turn a user's goal into a plan, use appropriate tools, perform approved actions, verify the result, and learn from feedback.

AUREX should also eventually be capable of continuing authorized work while the user is physically away, using a secure remote communication and authorization channel when human guidance is required.

---

## 0.1.3 What AUREX Should Be Able To Do

### A. Conversation

AUREX should:

- Understand natural language.
- Support follow-up questions.
- Maintain the context of the current conversation.
- Explain ideas clearly.
- Ask for clarification when a request is ambiguous.
- Adapt explanations to the user's level.

### B. Learning & Education

AUREX should help the user:

- Learn college/university subjects.
- Understand chapters and difficult concepts.
- Create study plans.
- Explain topics from beginner to advanced levels.
- Generate examples, questions, quizzes, and revision material.
- Teach practical skills.

### C. Research & Knowledge

AUREX should eventually:

- Research a topic using appropriate sources.
- Summarize information.
- Compare information from multiple sources.
- Produce structured reports.
- Identify uncertainty and missing information.
- Help turn research into documents or presentations.

### D. Problem Solving

AUREX should be a general-purpose problem-solving system.

Given a problem, it should be able to:

1. Understand the problem.
2. Identify the objective.
3. Identify constraints and requirements.
4. Break the problem into smaller parts.
5. Gather relevant information.
6. Generate possible approaches.
7. Explain the proposed approach.
8. Create a roadmap or task plan.
9. Ask for approval when required.
10. Execute appropriate actions.
11. Verify the result.
12. Recover from failure where possible.
13. Record useful lessons for future tasks.

### E. Computer Interaction

AUREX should eventually be able to:

- Open applications.
- Read and interact with supported interfaces.
- Manage files and folders.
- Perform repetitive computer operations.
- Use browser-based tools.
- Work with documents and presentations.
- Execute approved commands and scripts.
- Report what it did and what happened.

### F. Development & Projects

AUREX should help with:

- Programming.
- Debugging.
- Project planning.
- Code explanation.
- Documentation.
- Testing.
- Research for technical projects.
- Creating presentations and reports.

### G. Productivity & Automation

AUREX should eventually:

- Automate repetitive workflows.
- Organize tasks.
- Prepare documents.
- Generate presentations.
- Assist with schedules and reminders.
- Chain multiple tools together to complete a goal.

### H. Memory

AUREX should eventually remember useful information such as:

- User preferences.
- Project context.
- Important decisions.
- Previous task outcomes.
- Useful lessons learned.

Memory should be purposeful and controllable rather than storing everything indiscriminately.

### I. Learning From Mistakes

AUREX should improve from:

- User corrections.
- Failed actions.
- Verified outcomes.
- Successful workflows.
- Explicit feedback.

The initial design principle is:

> **Learn from experience without allowing uncontrolled self-modification of the core system.**

### J. Decision Support

AUREX should help the user make decisions by:

- Understanding objectives.
- Identifying options.
- Explaining trade-offs.
- Showing relevant evidence.
- Identifying uncertainty.
- Separating facts from recommendations.

For consequential actions, the user should remain in control.

### K. Remote Presence & Delegated Autonomy

AUREX should eventually be able to work even when the user is physically away from the computer.

This means **physical absence is not the same as unrestricted permission**.

The user should be able to create a delegation such as:

> "Complete this project by Friday. You may edit project files, run tests, research technical issues, and prepare the final deliverables. Ask me before publishing, paying for anything, deleting important data, or communicating externally."

AUREX can then work independently within the granted boundaries.

When it reaches an action outside those boundaries, it should:

1. Pause or safely hold the action.
2. Explain what action is needed.
3. Explain why it is needed.
4. Send a request to a trusted remote device.
5. Allow the user to approve, reject, or provide additional instructions.
6. Continue if authorized.
7. Verify and report the outcome.

Possible remote devices include:

- Smartphone.
- Tablet.
- Another computer.
- Future dedicated AUREX interface.

The long-term objective is:

> **AUREX can be physically present at home while the user is elsewhere, continue authorized work, and request human guidance remotely when necessary.**

### L. Remote Status & Control

The user should eventually be able to remotely:

- Check AUREX's current task.
- See progress and recent actions.
- Receive important alerts.
- Approve or reject sensitive actions.
- Give additional instructions.
- Pause a task.
- Resume a task.
- Stop AUREX.
- Review completed work and logs.

Remote access must use strong authentication and secure communication when implemented.

### M. Security & Controlled Access

Security is a later development level, but it is part of the long-term vision.

AUREX should eventually support:

- User identity.
- Profiles and roles.
- Permission boundaries.
- Confirmation for sensitive actions.
- Protection of confidential files.
- Detection of suspicious or unusual actions.
- Multi-user access with different permissions.
- Trusted remote devices.
- Secure remote authorization.
- Audit logs for important actions.
- Safe child/guided-learning profiles.

Security is intentionally **not part of the first implementation stage**.

---

## 0.1.4 Core Operating Model

The long-term AUREX interaction model is:

**Understand → Think → Plan → Explain → Approve → Act → Verify → Learn**

For delegated tasks, the loop becomes:

**Delegate → Understand → Plan → Execute → Verify → Request Guidance When Needed → Continue → Report**

### Understand
Determine what the user actually wants.

### Think
Reason about the problem and available information.

### Plan
Break the objective into achievable steps.

### Explain
Tell the user what AUREX intends to do when explanation is useful.

### Approve
Ask for confirmation when an action is sensitive, irreversible, ambiguous, or outside previously granted authority.

### Act
Use the appropriate AI capability, tool, application, or computer interaction.

### Verify
Check whether the intended result actually occurred.

### Learn
Use the outcome and user feedback to improve future behavior.

---

## 0.1.5 Capability Model

AUREX will be developed around eight major capability levels:

| Level | Capability | Main Goal |
|---|---|---|
| 0 | Vision | Define the system |
| 1 | Talk | Natural voice conversation |
| 2 | Act | Computer control |
| 3 | See | Screen/visual understanding |
| 4 | Plan & Solve | Multi-step problem solving |
| 5 | Remember | Long-term memory |
| 6 | Automate & Remote Work | Advanced workflows and delegated execution |
| 7 | Secure & Multi-user | Identity, permissions, trusted devices, and remote authorization |
| 8 | Improve | Controlled continuous improvement |

The levels are a development roadmap, not a requirement to build everything at once.

---

## 0.1.6 Example Future Scenario — Remote Freelance Work

A future AUREX workflow could look like this:

### Before leaving home

User:

> "AUREX, finish the client's website task by 8 PM. You may edit the project, install approved dependencies, run tests, research technical issues, and prepare the final package. Ask me before publishing, sending anything to the client, spending money, or deleting important files."

AUREX records the delegation and its boundaries.

### While the user is away

AUREX:

- Inspects the requirements.
- Works through the project.
- Runs tests.
- Finds and fixes errors.
- Researches technical problems.
- Builds the final package.
- Creates documentation.
- Verifies the result.

### When human authorization is required

AUREX sends a remote notification:

> **AUREX needs your approval**
>
> Action: Send final deliverables to client  
> Reason: External communication is outside the current delegation.  
>
> **Approve / Reject / Give Instructions**

The user responds from a trusted device.

AUREX then continues according to the response.

### Completion

AUREX reports:

- What it completed.
- What it could not complete.
- What approvals were received.
- Important actions performed.
- Test/verification results.
- Any remaining issues.

This is a future capability, not a Level 1 requirement.

---

## 0.1.7 First Real Milestone

The first working version should be intentionally simple.

### V1 target

The user can say:

> "Hey AUREX."

AUREX responds with natural speech, understands the user's request, answers conversationally, and handles follow-up questions using the current conversation context.

### V1 should NOT attempt to do everything.

No full computer control, advanced memory, remote unattended execution, multi-agent system, autonomous self-modification, or complex security system is required at this stage.

The principle is:

> **Build a simple working AUREX first. Then give it hands, eyes, planning, memory, automation, remote presence, and security one capability at a time.**

---

## 0.1.8 Success Criteria for Level 0.1

Level 0.1 is complete when:

- [x] AUREX has a defined name.
- [x] AUREX has a clear product identity.
- [x] AUREX has a mission statement.
- [x] AUREX's long-term capabilities are documented.
- [x] General problem solving is defined.
- [x] Remote presence and delegated autonomy are defined.
- [x] Remote permission/guidance requests are defined.
- [x] The core interaction loop is defined.
- [x] The development levels are defined.
- [x] The first practical milestone is defined.
- [x] The project explicitly follows incremental development.
- [x] Human control is identified as a long-term design principle.
- [x] Security is acknowledged as a future level rather than an early implementation requirement.

**Status: COMPLETE**

---

## 0.1.9 What Comes Next

After Level 0.1, the next planning step is to define the technical foundations required to build Level 1 — Talk.

That will cover:

- AI model/API
- Speech-to-text
- Text-to-speech
- Voice interaction flow
- Conversation state
- Python project structure
- Environment configuration
- Basic conversation memory
- First runnable AUREX prototype

Remote presence and delegated autonomy will be implemented much later, after AUREX can reliably reason, use tools, verify actions, and enforce permissions.
