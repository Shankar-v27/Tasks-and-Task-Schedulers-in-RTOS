# RTOS Academy — Interactive Engineering Learning Platform
### Tasks and Task Schedulers in Real-Time Operating Systems

An engineering-grade, university-accredited interactive learning platform designed for B.E./B.Tech ECE, CSE, and EEE students, GATE aspirants, and embedded firmware engineers.

[![Platform: Standalone HTML5](https://img.shields.io/badge/Platform-Zero--Dependency%20HTML5-00d4ff)](index.html)
[![RTOS: ARM Cortex-M](https://img.shields.io/badge/Architecture-ARM%20Cortex--M%20(PendSV%2FSysTick)-6366f1)](index.html)
[![Algorithms: RMS%20%7C%20EDF%20%7C%20Priority%20%7C%20RR](https://img.shields.io/badge/Algorithms-RMS%20%7C%20EDF%20%7C%20Priority%20%7C%20RR-10b981)](index.html)

---

## 🌟 The 7 Platform Workspaces

RTOS Academy is structured into 7 distinct, cohesive workspaces connected via a zero-lag SPA navigation router:

1. **🚀 Engineering Landing Page**:
   - Modern hero section with live simulated ARM Cortex-M4 task stream and SysTick/PendSV execution telemetry.
   - Core feature cards and curriculum roadmap preview.
2. **📊 Student Dashboard**:
   - Course progress telemetry (completion %, completed lessons count, GATE accuracy, lab challenges solved).
   - Prominent "Continue Learning" focal card and categorized curriculum progress tracking.
   - Recent activity feed logging quiz attempts, simulator runs, and assembly explorations.
3. **📖 3-Region Lesson Workspace**:
   - **Left Sidebar**: Expandable curriculum navigation with module breakdown and active lesson indicators.
   - **Center Canvas**: In-depth explanations, 4-phase ARM Cortex-M hardware auto-stacking diagrams, syntax-highlighted assembly (`PendSV_Handler`), and callout panels.
   - **Right Sidebar**: On-page TOC navigation, key mathematical formulas ($U = \sum C_i/T_i$), and kernel glossary.
4. **🔬 Signature Scheduler Lab**:
   - Interactive dual-track Gantt timeline rendered on high-DPI HTML5 Canvas.
   - Live scheduler simulation supporting **Rate Monotonic Scheduling (RMS)**, **Earliest Deadline First (EDF)**, **Fixed-Priority Preemptive**, **Round Robin (RR)**, and **First-Come, First-Served (FCFS)**.
   - Real-time Liu & Layland bound calculation, CPU utilization monitoring, hyperperiod calculation (LCM), and deadline miss detection flags.
   - Play/Pause, Step Forward, and Reset controls with simulation speed tuning.
   - Instant preset scenario loaders (`RMS Success` and `RMS Infeasible / EDF Pass`).
5. **🔄 Task-State Explorer**:
   - Interactive 5-state lifecycle automaton (Ready, Running, Blocked, Suspended) with vector directional transition paths.
   - Transition trigger simulator (`Dispatch`, `Preempt`, `vTaskDelay`, `Semaphore Event`).
   - Deep kernel state inspector displaying RTOS API calls and C-structure pointers (`pxCurrentTCB`).
6. **🎯 Practice Arena**:
   - Filterable question bank: **GATE ECE/CS Numericals** and **Qualcomm/TI Firmware Interview Scenarios**.
   - Instant scoring with detailed mathematical step-by-step derivations and architectural explanations.
7. **🗺️ Learning Roadmap**:
   - Visual progression path across 3 mastery stages: Beginner (Core Task Foundations), Intermediate (Schedulers & Context Switching), and Advanced (Real-Time Synchronization & Safety).

---

## ⚡ Keyboard Shortcuts & Quick Actions

- `Ctrl + K` / `Cmd + K`: Open Global Command Palette to search lessons, concepts, and lab presets.
- `Escape`: Close modals and search overlays.
- Theme Switcher: Toggle between Dark Engineering Theme and High-Contrast Light Mode with local storage persistence.

---

## 🚀 How to Run

The entire platform is completely self-contained in [`index.html`](index.html). It requires **no web server, no Node.js, and no internet connection**.

1. Clone this repository:
   ```bash
   git clone https://github.com/Shankar-v27/ESIOT.git
   ```
2. Open [`index.html`](index.html) in any modern browser:
   - Double-click `index.html`, or
   - Right-click and choose **Open With &rarr; Google Chrome / Microsoft Edge / Firefox / Safari**.

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| [`index.html`](index.html) | The full standalone single-file RTOS Academy platform (HTML5, Vanilla CSS Design System, Canvas Gantt Engine, Automaton). |
| [`RTOS_Tasks_and_Task_Schedulers_Master_Prompt.txt`](RTOS_Tasks_and_Task_Schedulers_Master_Prompt.txt) | Specification master prompt covering all course criteria and learning objectives. |
| [`README.md`](README.md) | Platform documentation, architecture overview, and user guide. |

---

## 🛠️ Technology Stack
- **Architecture**: Single Page Application (SPA) with zero external library dependencies.
- **Styling**: Curated Vanilla CSS Design System with CSS Custom Properties, sleek dark mode (`#070b12`), and high-contrast light mode.
- **Rendering**: HTML5 Canvas for real-time scheduling Gantt charts, SVG for task-state machines.
- **Fonts**: System fallback typography stack with monospace formatting for code and timing parameters.

---

## 👨‍💻 Repository & Attribution
- **Repository**: [https://github.com/Shankar-v27/ESIOT](https://github.com/Shankar-v27/ESIOT)
- **Target Audience**: B.E./B.Tech ECE, CSE & EEE students, GATE aspirants, and embedded software developers.

