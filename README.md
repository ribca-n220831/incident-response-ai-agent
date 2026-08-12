# Incident Response AI Agent

An AI agent for analyzing and responding to software incidents using
persistent memory with Hindsight.

## Overview

I built this incident-response agent using n8n as a no-code workflow
orchestration layer.

The agent receives incident information, analyzes the available
evidence, retrieves relevant historical context using Hindsight,
and generates an incident response.

The goal is to prevent every incident from being treated as a
completely new problem.
#Architecture
Incident Input
      ↓
n8n Workflow
      ↓
Incident Analysis
      ↓
Hindsight Memory
      ↓
Relevant Previous Incidents
      ↓
LLM Reasoning
      ↓
Incident Response
      ↓
Store Incident Outcome
<img width="1139" height="530" alt="Screenshot 2026-08-12 234311" src="https://github.com/user-attachments/assets/a4038677-ff60-4e10-b90f-b796621fe129" />

