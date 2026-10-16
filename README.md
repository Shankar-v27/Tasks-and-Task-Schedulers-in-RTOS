# Tasks and Task Schedulers in Real-Time Operating Systems (RTOS)
### Interactive ECE & Embedded Systems Educational Learning Platform

An interactive, university-accredited educational platform designed for B.E./B.Tech ECE & CSE students, GATE aspirants, and engineers preparing for core embedded systems and firmware interviews.

---

## 🌟 Overview & Key Highlights

This repository contains a **complete, standalone, zero-dependency interactive learning module** covering:
- **RTOS Fundamentals**: Concurrency, determinism, Hard vs. Firm vs. Soft real-time systems.
- **Microscopic Mechanics**: Task Control Blocks (TCB), ARM Cortex-M hardware auto-stacking, dual stack pointers (MSP vs. PSP), and lowest-priority `PendSV` context switching.
- **Interactive Live Scheduling Simulator**:
  - Live Gantt chart visualization with execution timelines.
  - Multi-policy engine: **Rate Monotonic Scheduling (RMS)**, **Earliest Deadline First (EDF)**, **Preemptive Fixed Priority**, and **Round Robin Time Slicing**.
  - Real-time CPU utilization calculator ($U = \sum C_i / T_i$), hyperperiod (LCM), Liu & Layland bound checks, and deadline miss alerts.
- **Priority Inversion Remediation**: Detailed study of the 1997 Mars Pathfinder anomaly, Priority Inheritance Protocol (PIP), and Priority Ceiling Protocol (PCP).
- **Rigorous Mathematical Modeling**: Step-by-step derivations of Liu & Layland bounds, Exact Response Time Analysis (RTA) recurrence relations, and dynamic EDF bounds.
- **Solved Numerical Problems**: 3 comprehensive, progressive step-by-step problems including context switch overhead and mutex blocking times.
- **GATE Question Bank**: 10 original multi-choice questions with difficulty tags, automatic scoring, and detailed pedagogical explanations for every option.
- **Core Industry Interview Preparation**: 10 accordion-style interview questions tailored for roles at Qualcomm, TI, Apple, Bosch, STMicroelectronics, and NXP.
- **Interactive 10-Question Topic Mastery Quiz**: Complete self-assessment exam with instant scoring and performance feedback.

---

## 🚀 How to Run

The application is completely self-contained in [`index.html`](index.html). It requires **no web server, no Node.js, and no internet connection**.

1. Clone the repository:
   ```bash
   git clone https://github.com/Shankar-v27/ESIOT.git
   ```
2. Open [`index.html`](index.html) in any modern browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari):
   - Simply **double-click** `index.html` from your file manager, or
   - Right-click and choose **Open With &rarr; Google Chrome / Microsoft Edge**.

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| [`index.html`](index.html) | The full standalone interactive learning web application (HTML, CSS, JS, SVG, Canvas). |
| [`RTOS_Tasks_and_Task_Schedulers_Master_Prompt.txt`](RTOS_Tasks_and_Task_Schedulers_Master_Prompt.txt) | Specification master prompt covering all course criteria and learning objectives. |
| [`README.md`](README.md) | Project documentation, setup guide, and module reference. |

---

## 🛠️ Technology Stack
- **Structure & Content**: Semantic HTML5 with SVG vector schematics.
- **Design & Styling**: Modern Vanilla CSS design system (Dark & Light mode, Glassmorphism, Print-to-PDF stylesheet).
- **Simulators & Logic**: Pure Vanilla JavaScript with HTML5 Canvas (Zero external CDN/framework dependencies).

---

## 👨‍💻 Author & Attribution
- **Repository**: [https://github.com/Shankar-v27/ESIOT](https://github.com/Shankar-v27/ESIOT)
- **Target Curriculum**: B.E. / B.Tech Embedded Systems and IoT (ESIOT), RTOS, and GATE Examination Syllabus.
