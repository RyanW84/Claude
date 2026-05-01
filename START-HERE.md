# Workspace Blueprint - How to Read this Template

## What this is

This is  a teaching template for building  **agent-native workspaces** - folder structures
designed so AI agents (Claude code, Cursor, Copilot, etc..) can drop in, understand the
work, and produce high quality output without you babysitting every prompt.

it's not a file organisation system. It's a **Context delivery system**

---

## The Problem This Solves

When you given an agent a task, it needs three things:

1. **What am I doing?** (The Task)
2. **How should I do it?** (reference docs, voice, standards, tools)
3. **What should I NOT load?** (everything else - context windows are finite)

Most people dump everything into one folder, write on massive prompt, and wonder why the agent loses the thread halfway through. Or they build 30 small files with no routing and the agent doesn't know which ones matter.

This system solves both problems with a **3-layer routing architecture.** // fdfdfdskdfglksdfdf

---

## The 3 Layers

```

CLAUDE.md                           Layer 1: THE MAP
                                    Always loaded. Shows every folder , every ID system,
                                    every file placement rule. The agent's GPS

CONTEXT.md                          Layer 2: THE ROUTER
