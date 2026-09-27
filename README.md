# 🚀 Orbit

## An Agentic AI Workspace for Enterprise AI & Data Teams

**From information → context → decisions → action.**

Orbit is an agentic AI workspace designed to bring together the fragmented information, conversations, tasks, meetings, and project signals that enterprise teams work with every day.

Modern teams operate across a large ecosystem of tools — messaging, email, meetings, project management, documentation, service management, source control, design, analytics, and more.

The information exists.

The challenge is **connecting it, understanding it, and turning it into action.**

Orbit explores what an AI-native workspace could look like when agents can reason across these different sources of enterprise context.

---

# 🎯 The Problem

A typical workday can involve jumping between:

**Slack · Outlook · Teams · Jira · Confluence · ServiceNow · SharePoint · GitHub · Figma · Power BI · and more.**

This creates several recurring problems:

### Meetings create information, but not always action

A 45-minute meeting can contain decisions, commitments, risks, and dependencies — but extracting them often requires manually revisiting the transcript or notes.

### Planning requires context from multiple systems

Before deciding what to work on, employees may need to check their calendar, messages, project trackers, emails, and pending tasks.

### Project readiness is difficult to determine

Questions like:

> **"Are we ready to ship?"**

often require manually collecting updates from multiple people and systems.

### Context is fragmented

The information needed to make a decision is rarely stored in one place.

**Orbit is designed around this problem.**

---

# 🧠 The Orbit Concept

Orbit acts as an **intelligence layer across enterprise tools**.

Instead of asking employees to manually navigate through every system, agents can retrieve relevant context, reason over it, and present the result in a way that is useful for the person and the task at hand.

```text
                    ENTERPRISE TOOLS
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
    Meetings          Projects          Communication
       │                 │                 │
       └─────────────────┼─────────────────┘
                         ▼
                 ┌───────────────┐
                 │     ORBIT     │
                 │ Intelligence  │
                 │    Layer      │
                 └───────┬───────┘
                         │
            ┌────────────┼────────────┐
            ▼            ▼            ▼
        Catch Up     Daily Plan   Readiness
            │            │            │
            └────────────┼────────────┘
                         ▼
                 ACTIONABLE CONTEXT
```

---

# 🧩 Three Agentic Experiences

Orbit brings three complementary experiences into one workspace.

### 📝 Catch Up

**Understand what happened.**

Turn meeting conversations into structured, actionable intelligence.

→ Decisions  
→ Action items  
→ Risks  
→ Priorities  
→ Follow-ups

[Explore Catch Up →](./Catch-Up/README.md)

### 🗓️ Daily Plan

**Understand what matters today.**

Connect context across enterprise tools and turn it into a prioritized, time-aware plan.

→ Calendar  
→ Messages  
→ Tasks  
→ Meetings  
→ Deadlines  
→ Priorities

[Explore Daily Plan →](./Daily-Plan/README.md)

### 🚦 Readiness

**Understand whether you're ready to execute.**

Use multiple specialized agents to investigate project readiness across documentation, dependencies, tasks, risks, and other signals.

→ Research  
→ Risk analysis  
→ Dependencies  
→ Planning  
→ Communication  
→ Readiness assessment

[Explore Readiness →](./Readiness/README.md)

---

# 👤 Persona-Driven Experience

One of Orbit's core design principles is that **AI should adapt to the person, not just the task.**

The same enterprise context can mean very different things to different roles.

Orbit therefore includes **persona-driven dashboards**.

### Example personas

- **Senior AI Engineer**
- **Data Analyst**
- **Product Manager**
- **SRE**
- **UX Researcher**
- **UI Engineer**

Each persona experiences Orbit through a different contextual lens.

The underlying workspace remains the same, but the **information hierarchy, priorities, recommendations, and suggested actions change based on the role.**

## 🎭 Persona → Context → Action

```text
             PERSONA
                │
                ▼
        ┌───────────────┐
        │ User Context  │
        └───────┬───────┘
                │
                ▼
       Enterprise Signals
                │
       ┌────────┼────────┐
       ▼        ▼        ▼
    Meetings  Tasks   Messages
       │        │        │
       └────────┼────────┘
                ▼
             ORBIT
          Intelligence
                │
                ▼
       Prioritized Context
                │
                ▼
             ACTION
```

This allows Orbit to move beyond a generic AI assistant toward a **role-aware AI workspace**.

---

# 🔗 Enterprise Context

Orbit is designed around the idea that useful intelligence requires context.

| Category | Examples |
|---|---|
| Communication | Slack, Teams |
| Calendar & Email | Outlook |
| Project Management | Jira |
| Documentation | Confluence, SharePoint |
| Service Management | ServiceNow |
| Engineering | GitHub |
| Design | Figma |
| Analytics | Power BI |
| Meetings | Meeting transcripts |

The objective is not to replace these systems.

**Orbit sits above them and reasons across them.**

---

# 🧠 Agentic Architecture

Orbit demonstrates several agentic patterns:

- Sequential reasoning
- Tool-using agents
- Parallel tool execution
- Multi-agent orchestration
- Context-aware recommendations

These patterns allow Orbit to progressively transform distributed enterprise information into useful decisions and actions.

---

# 🔌 MCP as the Connectivity Layer

Orbit uses the **Model Context Protocol (MCP)** concept to connect agents with enterprise capabilities.

```text
                    ORBIT AGENTS
                         │
                         ▼
                    MCP LAYER
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
     Slack            Jira             GitHub
        │                │                │
        └────────────────┼────────────────┘
                         ▼
             Enterprise Context & Signals
```

---

# 📊 Observability & Efficiency

Agentic systems should not be evaluated only by how impressive their outputs look.

Orbit also explores visibility into:

- LLM calls
- Cost
- Latency
- Tool calls
- Agent execution
- Workflow performance

> **Capability matters. Observability matters. Efficiency matters.**

---

# 🏢 Designed for Enterprise Work

Orbit is particularly relevant to teams operating in complex enterprise environments where:

- Information is distributed across multiple systems
- Teams collaborate across functions
- Decisions require multiple sources of context
- Projects have many dependencies
- Employees spend significant time searching for information
- Status gathering creates operational overhead

The goal is simple:

> **Reduce the distance between knowing and doing.**

---

# 🎥 Experience Orbit

**Live Demo:**  
http://34.59.189.48/

**Demo Password:** `Orbit@2026`

The demo includes multiple personas so you can experience how the same workspace changes based on the user's role and context.

> **Demo environment only. Please do not enter confidential, personal, proprietary, or production information.**

---

# 🗺️ Orbit at a Glance

| Experience | Question it answers |
|---|---|
| **Catch Up** | What happened? |
| **Daily Plan** | What should I focus on today? |
| **Readiness** | Are we ready to execute? |
| **Persona Dashboard** | What matters to me? |

Together:

**Understand → Prioritize → Execute**

---

# 🌐 Vision

What if enterprise AI wasn't another destination?

What if it became an **intelligence layer across the systems employees already use?**

Instead of:

**Tool → Search → Read → Interpret → Decide → Act**

Orbit explores:

**Context → Reason → Decide → Act**

---

## ⭐ Explore the Experiences

- [Catch Up](./Catch-Up/README.md)
- [Daily Plan](./Daily-Plan/README.md)
- [Readiness](./Readiness/README.md)

### Built to explore the future of enterprise AI and agentic work.

**Orbit — From information to action.**
