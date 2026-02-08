## KawrgoJumper  
Senior AI / ML Capstone Project — Port Logistics Optimization

KawrgoJumper is an AI/ML senior capstone project that explores how algorithmic planning and optimization can support real-world port logistics operations. The system assists operators by generating structured, step-by-step workflows for container loading, unloading, and ship balancing under realistic operational constraints.

This repository contains the **frontend application**, which visualizes logistics workflows and presents algorithm-informed decisions in a clear, human-readable format.

---

### Balancing Operation
<p align="center">
  <img src="kawrgojumper_screenshots/balance.png" width="800"/>
</p>

### Completion & Output
<p align="center">
  <img src="kawrgojumper_screenshots/summary.png" width="800"/>
</p>

---

## Project Context

Modern port operations must balance efficiency, safety, and legal constraints while handling large volumes of cargo under time pressure. Manual planning is error-prone and difficult to scale.

KawrgoJumper was developed as a **senior AI/ML capstone** to explore how algorithmic decision-making can:
- Reduce unnecessary container movements
- Maintain legal ship balance
- Provide interpretable, step-by-step guidance to operators
- Improve overall operational efficiency

The system models the ship and buffer as structured grids and generates action sequences that respect movement costs, balance rules, and operational constraints.

---

## AI / Algorithmic Focus

The broader capstone explored:
- **Search and optimization techniques** to minimize total container movement time
- **Constraint-based reasoning** for legal ship balancing
- **Fallback strategies** (e.g., SIFT-style balancing) when optimal solutions are not feasible
- Translating algorithm outputs into **interpretable sequences of actions**

While the machine learning and optimization logic informed system behavior, this frontend emphasizes **clarity, usability, and interpretability**, ensuring algorithmic decisions are actionable in real-world workflows.

---

## What This Application Does

- Accepts structured ship manifests
- Supports two primary tasks:
  - Load / unload containers
  - Balance ship containers
- Visualizes ship and buffer layouts as grids
- Guides users through container movements step by step
- Displays logs and summaries of completed actions
- Outputs updated manifests upon completion

## Screenshots

### Login & Manifest Upload
<p align="center">
  <img src="kawrgojumper_screenshots/login.png" width="800"/>
  <br/>
  <img src="kawrgojumper_screenshots/upload-manifest.png" width="800"/>
</p>

### Task Selection
<p align="center">
  <img src="kawrgojumper_screenshots/task-selection.png" width="800"/>
</p>

### Load / Unload Workflow
<p align="center">
  <img src="kawrgojumper_screenshots/unload-containers.png" width="800"/>
  <br/>
  <img src="kawrgojumper_screenshots/load-containers.png" width="800"/>
</p>

### Balancing Operation
<p align="center">
  <img src="kawrgojumper_screenshots/balance.png" width="800"/>
</p>

### Completion & Output
<p align="center">
  <img src="kawrgojumper_screenshots/summary.png" width="800"/>
</p>
---

## Tech Stack

- React (Create React App)
- React Router
- JavaScript
- CSS

---

## How to Run Locally

1. Install Node.js  
2. Clone the repository  
3. Navigate into the project directory  
4. Install dependencies:
   ```bash
   npm install
