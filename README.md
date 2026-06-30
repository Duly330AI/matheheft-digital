# Matheheft Digital

**Matheheft Digital** is an educational math training app for practicing written calculation methods.

The project was built as a focused learning tool for students who need step-by-step practice with arithmetic and basic algebra tasks. It supports profile creation, exercise selection, written calculation grids, feedback, scoring, leaderboards, and a teacher dashboard with learning insights.

The app was primarily tested as a web app. An Android APK build was also created and tested, but mobile behavior may still need additional polish depending on device and screen size.

## Status

**Usable learning prototype / portfolio project**

Matheheft Digital is functional and usable for training purposes.  
It is not a commercial EdTech product, but a private educational project with a strong focus on deterministic task generation, structured feedback, and transparent learning progress.

## Features

- Student profile creation with avatar selection
- Exercise selection by topic and difficulty
- Practice modes:
  - Classic
  - Time
  - Test/Exam mode
- Written calculation grid
- Addition, subtraction, multiplication, division basics
- 1x1 practice
- Basic algebra/term exercises
- Step-by-step feedback
- Score and session summary
- Highscore/leaderboard view
- Teacher dashboard with learning insights
- Skill profile visualization
- Basic cognitive-load / focus indicators
- Deterministic task generation
- Developer diagnostic overlay

## Screenshots

```md
![Profile selection](docs/screenshots/matheheft-profile.png)
![Create profile](docs/screenshots/matheheft-create-profile.png)
![Exercise selection](docs/screenshots/matheheft-exercises.png)
![Written calculation](docs/screenshots/matheheft-calculation.png)
![Session complete](docs/screenshots/matheheft-session-complete.png)
![Leaderboard](docs/screenshots/matheheft-leaderboard.png)
![Teacher dashboard](docs/screenshots/matheheft-teacher-dashboard.png)
![Error feedback](docs/screenshots/matheheft-feedback.png)
````

## Tech Stack

* React
* TypeScript
* Tailwind CSS
* Vite
* Framer Motion
* Vitest

## Architecture Highlights

The project is structured around deterministic and testable learning flows:

* **Math engines:** deterministic calculation logic
* **Grid system:** matrix-based written calculation layout
* **Pedagogy layer:** feedback and error analysis
* **State machine controller:** session and task flow management
* **Adaptive task generator:** seed-based task generation
* **UX flow engine:** focus handling, navigation, and guided input
* **Observability tools:** telemetry, replay, and diagnostic overlay

## Developer Tools

Press:

```text
CTRL + ALT + D
```

to open the diagnostic overlay.

The diagnostic view shows internal state, seed data, expected values, and validation results.

## Getting Started

### Prerequisites

* Node.js

### Install dependencies

```bash
npm install
```

### Run tests

```bash
npm run test
```

### Run locally

```bash
npm run dev
```

The app is available at:

```text
http://localhost:3000
```

## Android Build Note

An Android APK build was created and tested during development.
The desktop/web version currently provides the most stable layout. Some Android screen sizes may require additional UI polish.

## Notes

This project was built as a private educational tool and learning/portfolio project. It demonstrates interactive training flows, deterministic task generation, feedback-driven learning, and dashboard-style learning analytics.



## Screenshots

<img width="714" height="427" alt="Screenshot 2026-06-30 155820" src="https://github.com/user-attachments/assets/3813125f-2ffb-450c-9056-e5a0549902d0" />

<img width="704" height="623" alt="Screenshot 2026-06-30 155840" src="https://github.com/user-attachments/assets/e03b9794-1861-4e9e-bfc3-8d72804993ca" />

<img width="437" height="777" alt="Screenshot 2026-06-30 155857" src="https://github.com/user-attachments/assets/d0236eb9-d949-4ca3-ba8f-b70b61f92358" />

<img width="1481" height="836" alt="Screenshot 2026-06-30 155951" src="https://github.com/user-attachments/assets/1769ebad-a2b1-4b96-a6aa-b1e81e0320c3" />

<img width="1466" height="843" alt="Screenshot 2026-06-30 160243" src="https://github.com/user-attachments/assets/87d20cf6-ac1a-461f-bc3d-014e1e200d2b" />

<img width="390" height="483" alt="Screenshot 2026-06-30 160002" src="https://github.com/user-attachments/assets/68650943-fbb9-4e43-8552-7108d0ffa7c8" />

<img width="1477" height="843" alt="Screenshot 2026-06-30 160609" src="https://github.com/user-attachments/assets/4f4684df-f23a-4c51-9f36-b69df97916fe" />

<img width="1482" height="835" alt="Screenshot 2026-06-30 160545" src="https://github.com/user-attachments/assets/a9642347-3ff7-4c52-8e30-21c864179326" />
