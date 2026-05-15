# Agentic AI Industrial Visual Inspection & Root Cause Intelligence Platform

An enterprise-grade AI system for industrial defect inspection, anomaly detection, root cause reasoning, corrective action planning, and intelligent workflow routing.

This project demonstrates how Computer Vision, LLMs, and Agentic AI can be integrated into real-world industrial quality assurance and maintenance workflows.


## Project Vision

Industrial inspections are often manual, fragmented, and reactive.

A defect may be detected visually, but identifying **why it happened**, **how severe it is**, **what action should be taken**, and **who should handle it** often requires multiple teams and delayed decision-making.

This platform reimagines that workflow using AI agents.

Instead of a standalone defect detection model, this system acts as an **AI-powered industrial operations assistant** that:

- Detects visual defects from uploaded inspection images
- Assesses severity and operational risk
- Performs root cause reasoning
- Recommends corrective actions
- Routes cases to relevant departments
- Generates structured inspection reports
- Maintains auditable inspection workflows

## System Architecture

<img width="1536" height="1024" alt="ChatGPT Image May 15, 2026, 03_58_10 PM" src="https://github.com/user-attachments/assets/ab174515-fe98-4880-88f9-47cd05f64748" />


## Multi-Agent Architecture

The system is designed around specialized AI agents:

### Vision Inspection Agent
Analyzes industrial images to detect defects, anomalies, or visible quality issues.

Examples:
- Surface cracks
- Corrosion
- Missing components
- Structural wear
- Surface damage

### Severity Assessment Agent
Determines issue criticality using defect type, confidence score, and operational context.

Outputs:
- Low
- Medium
- High
- Critical

### Root Cause Intelligence Agent
Performs reasoning over defect evidence and metadata to suggest likely failure causes.

Examples:
- Material fatigue
- Corrosion exposure
- Process variation
- Improper handling
- Maintenance neglect
- Environmental stress

### Corrective Action Agent
Recommends actionable remediation steps.

Examples:
- Immediate replacement
- Maintenance intervention
- Safety escalation
- Reinspection scheduling
- Procurement request generation

### Workflow Routing Agent
Routes inspection cases to relevant business functions.

Examples:
- Quality Assurance
- Maintenance
- Safety
- Procurement
- Operations Management

### Report Generation Agent
Creates structured inspection summaries for audit and decision-making.

---

## Development Philosophy

This project will be built incrementally in production-style phases.

Like real enterprise systems, functionality will evolve from a backend MVP into a multi-agent intelligent platform.

Planned build phases:

Phase 1 — Computer Vision Inspection
Phase 2 — Backend MVP  
Phase 3 — Agentic Intelligence Layer  
Phase 4 — Database + Audit Trail  
Phase 5 — Streamlit Dashboard  
Phase 6 — Production Polish + Deployment

---

## Tech Stack

### Backend
- Python 3.10+
- FastAPI
- Pydantic
- Uvicorn

---

### AI / Agentic Layer
- LLM-powered reasoning
- structured JSON agent outputs
- modular agent orchestration

Potential frameworks:
- LangGraph
- CrewAI
- custom orchestrator

---

### Computer Vision
- OpenCV
- Pillow
- TensorFlow / Keras OR PyTorch
- pretrained CNN experimentation

---

### Database
Phase progression:

- Phase 1 → in-memory storage
- Phase 4 → SQLite + SQLAlchemy
- future-ready → PostgreSQL

---

### Dashboard
- Streamlit
- Plotly / charts
- inspection analytics visualizations

---

## Current Status

Currently building **Phase 1: CV**
