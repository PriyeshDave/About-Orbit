# 🗓️ Daily Plan

## AI-Powered Personal Work Planner

### **Start the day with context, not tabs.**

A modern enterprise workday can begin with checking a calendar, Slack, Teams, email, Jira, project updates, and task lists — before deciding what actually deserves attention.

**Daily Plan** brings these signals together and turns them into a prioritized plan for the day.

---

# 🎯 The Problem

The question isn't:

> **"What tasks do I have?"**

It's:

> **"Given everything happening today, what should I focus on first?"**

That requires context.

A task's priority may depend on:

- An upcoming meeting
- A deadline
- A message from a stakeholder
- A project milestone
- A dependency
- A production issue
- Work already completed
- The user's role

Daily Plan is designed to reason across these signals.

---

# 🔌 MCP-Powered Context

Daily Plan uses the **Model Context Protocol (MCP)** approach to retrieve information from connected enterprise systems.

```text
                     DAILY PLAN AGENT
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
           Calendar      Tasks       Messages
              │            │            │
              └────────────┼────────────┘
                           ▼
                     Context Layer
                           │
                           ▼
                       Reasoning
                           │
                           ▼
                  Prioritized Day Plan
```

---

# ⏰ Time-Aware Planning

Daily Plan doesn't simply produce a list of tasks.

It considers the shape of the user's day.

### Morning
Deep-work opportunities and high-priority tasks.

### Before meetings
Preparation and relevant context.

### Between meetings
Tasks that fit the available window.

### End of day
Follow-ups and lower-duration activities.

The objective is to create a plan that is both **priority-aware and time-aware**.

---

# 👤 Persona-Driven Planning

Different roles have different definitions of "important."

### Senior AI Engineer
May prioritize engineering tasks, technical reviews, model experiments, production dependencies, and architecture discussions.

### Product Manager
May prioritize stakeholder meetings, milestones, product decisions, customer commitments, and blockers.

### SRE
May prioritize operational issues, incidents, reliability work, production changes, and risk mitigation.

Daily Plan adapts the resulting plan to the user's working context.

---

# 💡 The Core Idea

Daily Plan moves from:

**Multiple tools → Manual checking → Mental prioritization**

toward:

**Multiple signals → Agent reasoning → One contextual plan**

---

# 🔗 Part of Orbit

Daily Plan is the **Prioritize** layer of Orbit.

**Understand → Prioritize → Execute**

[← Back to Orbit](../README.md)
