# 🚀 RevOps Patrol: Autonomous Revenue Recovery AI Agent

An autonomous enterprise agent built for the **Agents for Business Track** during the Kaggle Intensive Vibe Coding Course with Google.

## 📌 Project Overview
Enterprise sales teams lose significant revenue annually due to stalled mid-market deals dropping out of sight without active monitoring. **RevOps Patrol** automates active detection, evaluating deal-level stagnation alongside client background context to protect revenue streams.

## 🛠️ Technical Strategy & Architecture
This system is built utilizing **Google’s Agent Development Kit (ADK 2.0)** principles as a code-first, graph-based agent pipeline:
* **Stateful Graph Design:** The agent sequences raw data through consecutive analysis, strategy generation, and evaluation loops.
* **Tool Integration / MCP Capabilities:** Simulates an MCP database client lookup tool (`RevOpsTools`) to pull live corporate payment records dynamically.
* **Safety Evaluation Guardrail:** Incorporates an isolated verification node evaluating generated advice text for safe deployment before dispatching to enterprise users.

## 🚀 Quick Start
1. Install dependencies:
   ```bash
   pip install google-genai
