# Matheheft Digital

**Matheheft Digital** is an educational math training app for practicing written calculation methods.

The app focuses on structured practice, guided feedback, and a clean learning flow for arithmetic exercises. It was built as a usable learning prototype and portfolio project.

## Status

**Usable learning prototype / portfolio project**

The app was primarily tested as a web app. An Android APK build was also created and tested, but mobile behavior may still need additional polish depending on device/screen size.

Matheheft Digital is not a certified educational product or complete school platform. It is a private learning and portfolio project focused on deterministic task generation, structured feedback, and transparent learning progress.

## Live Demo

Try the app here:

[Open Matheheft Digital](https://matheheft-digital.vercel.app)

## Features

* Student profile creation with avatar selection
* Exercise selection by topic and difficulty
* Practice modes for classic, timed, and test-style sessions
* Written calculation grid
* Addition, subtraction, multiplication, and division practice
* 1x1 / basic arithmetic practice
* Basic algebra and term exercises
* Step-by-step feedback
* Score and session summary
* Highscore / leaderboard view
* Teacher dashboard with learning insights
* Skill profile visualization
* Basic cognitive-load and focus indicators
* Deterministic task generation
* Developer diagnostic overlay

## Screenshots

<img width="714" height="427" alt="Screenshot 2026-06-30 155820" src="https://github.com/user-attachments/assets/3813125f-2ffb-450c-9056-e5a0549902d0" />

<img width="704" height="623" alt="Screenshot 2026-06-30 155840" src="https://github.com/user-attachments/assets/e03b9794-1861-4e9e-bfc3-8d72804993ca" />

<img width="437" height="777" alt="Screenshot 2026-06-30 155857" src="https://github.com/user-attachments/assets/d0236eb9-d949-4ca3-ba8f-b70b61f92358" />

<img width="1481" height="836" alt="Screenshot 2026-06-30 155951" src="https://github.com/user-attachments/assets/1769ebad-a2b1-4b96-a6aa-b1e81e0320c3" />

<img width="1466" height="843" alt="Screenshot 2026-06-30 160243" src="https://github.com/user-attachments/assets/87d20cf6-ac1a-461f-bc3d-014e1e200d2b" />

<img width="390" height="483" alt="Screenshot 2026-06-30 160002" src="https://github.com/user-attachments/assets/68650943-fbb9-4e43-8552-7108d0ffa7c8" />

<img width="1477" height="843" alt="Screenshot 2026-06-30 160609" src="https://github.com/user-attachments/assets/4f4684df-f23a-4c51-9f36-b69df97916fe" />

<img width="1482" height="835" alt="Screenshot 2026-06-30 160545" src="https://github.com/user-attachments/assets/a9642347-3ff7-4c52-8e30-21c864179326" />

## Tech Stack

* React
* TypeScript
* Vite
* Tailwind CSS
* Vitest

## Architecture Highlights

The project is structured around deterministic and testable learning flows:

* Math engines for written calculation tasks
* Matrix-based written calculation layout
* Feedback and error analysis layer
* Session and task-flow controller
* Seed-based task generation
* Focus handling, navigation, and guided input
* Telemetry, replay, and diagnostic tooling

## Developer Tools

Press `CTRL + ALT + D` to open the diagnostic overlay.

The diagnostic view shows internal state, seed data, expected values, and validation results.

## Getting Started

### Prerequisites

* Node.js

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm run dev
```

The dev server uses the Vite script from `package.json` and runs on:

```text
http://localhost:3000
```

### Run tests

```bash
npm run test
```

## Android Build Note

The app was primarily tested as a web app. An Android APK build was also created and tested, but mobile behavior may still need additional polish depending on device/screen size.

## Notes

This is a portfolio/learning prototype, not a certified educational product. The focus is on interactive math practice, deterministic task generation, feedback-driven learning, and dashboard-style learning analytics.

## License

MIT License. See [LICENSE](LICENSE).
