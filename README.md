# Live Codebase Copilot – Agentic AI with Pathway

# Track

Track 1: Agentic AI (Applied GenAI)

# Team

Mindspark  

#Team Lead: Ishita Chowdhury



## Problem

Developer codebases and documentation evolve continuously.

Traditional RAG systems rely on static indexing pipelines, which quickly become outdated and require costly re-indexing and redeployment.

This leads to stale AI responses and poor developer experience.


## Solution

**Live Codebase Copilot** is an agentic AI system built using **Pathway** that continuously monitors a live codebase folder and updates its vector index in real time.

Any file addition, modification, or deletion is immediately reflected

in the AI’s responses — without restarting the system.



## Why Pathway?

Pathway’s streaming-first architecture enables:

\- Real-time document ingestion

\- Incremental vector indexing

\- Exactly-once data processing

\- Low-latency reaction to changes



These capabilities make Pathway ideal for agentic AI systems that must

react to real-world data instantly.



## Agentic Behavior

The AI agent:

\- Observes live changes in the codebase directory

\- Maintains an always up-to-date semantic index

\- Reasons over the latest system state

\- Answers developer queries using current context only



## Architecture Overview

\- File system acts as a live data stream

\- Pathway DocumentStore handles parsing, chunking, and indexing

\- Vector retrieval powers contextual reasoning

\- API server exposes the agent for interaction



## Demo Flow (Conceptual)

1\. Add or modify a `.py`, `.md`, or `.txt` file in the `codebase/` folder

2\. Pathway detects the change and updates the index incrementally

3\. Developer asks a question

4\. The agent responds using the updated codebase context



## Status

This repository demonstrates:

\- Correct use of Pathway’s live document indexing

\- An agentic system aligned with Track 1 requirements

\- A realistic, production-oriented developer tooling use case



Docker-based execution and UI integration are planned for future iterations.





