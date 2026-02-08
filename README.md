## KawrgoJumper (Senior AI/ML Capstone)

KawrgoJumper is an AI/ML senior capstone project that explores how algorithmic planning and optimization can support real-world port logistics operations. The system assists crane operators by generating efficient, step-by-step instructions for container loading, unloading, and ship balancing under realistic operational constraints.

This repository contains the **frontend application** used to visualize workflows, guide operators through tasks, and present algorithm-informed decisions.

---

## Screenshots

### Login & Manifest Upload
![Login](screenshots/login.png)
![Upload Manifest](screenshots/upload-manifest.png)

### Task Selection
![Task Selection](screenshots/task-selection.png)

### Load / Unload Workflow
![Unload Containers](screenshots/unload-containers.png)
![Load Containers](screenshots/load-containers.png)

### Balancing Operation
![Balance Containers](screenshots/balance.png)

### Completion & Output
![Summary](screenshots/summary.png)

---

## Project Overview

Ports operate under strict time, safety, and balance constraints. KawrgoJumper was designed to help operators:

- Load and unload containers efficiently
- Maintain legal ship balance
- Minimize total movement time
- Follow clear, step-by-step instructions to reduce human error

The system models the ship and buffer as grids and accounts for movement costs, buffer constraints, and operational rules while generating optimal or near-optimal sequences of actions.

---

## AI / Algorithmic Focus

The broader project explored:
- **Search and optimization strategies** for minimizing total container movement time
- **Constraint-based reasoning** for legal ship balancing
- **Fallback strategies** (e.g., SIFT-based balancing) when optimal solutions are not feasible
- Translating algorithm outputs into **human-readable, sequential instructions**

This frontend emphasizes **interpretability and usability**, ensuring that complex algorithmic decisions are actionable by operators in real time.

---

## What this application does

- Accepts structured ship manifests
- Supports two primary tasks:
  - Load / Unload containers
  - Balance ship containers
- Visualizes ship and buffer layouts as grids
- Guides users through container movements one step at a time
- Generates updated outbound manifests and completion summaries

---

## Tech Stack

- React (Create React App)
- React Router
- JavaScript
- CSS

---

## How to run locally

1. Install Node.js  
2. Clone the repository  
3. Navigate into the project directory  
4. Install dependencies:
   ```bash
   npm install
