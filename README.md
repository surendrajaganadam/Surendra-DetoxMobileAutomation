# Surendra-DetoxMobileAutomation

This repository contains the complete codebase and learning resources used during the Detox training sessions by Surendra. It bundles the example mobile app source, the Detox end-to-end test scripts created during the training, artifacts (screenshots, logs) produced while running tests, and presentation materials so anyone can download and explore the full training materials in one place.

## What you'll find here

- `luckytrainings/` — mobile app source (React Native / Expo project used in the sessions).
- `e2e/` — Detox end-to-end tests, Jest configuration and example test scripts used during training.
- `artifacts/` — test artifacts such as simulator logs and screenshots captured during runs.
- `presentations/` — slides and supporting material (PowerPoint / scripts) used for the training.
- `components/`, `assets/`, `ios/`, `android/`, etc. — supporting source and native project files.

## Goals

This repo is a single-note collection of all Detox resources from the training so learners can:

- Inspect the app source and test code together.
- Reproduce the exercises locally (with the required environment).
- Download slides and artifacts for offline study.

## Quick download

Clone the repository:

```bash
git clone https://github.com/surendrajaganadam/Surendra-DetoxMobileAutomation.git
```

Then open the project folder:

```bash
cd Surendra-DetoxMobileAutomation
```

## Quick pointers to get started

- App source: `luckytrainings/`
- Tests: `e2e/` (example tests: `e2e/firstScript.js`, `e2e/second.test.js`)
- Artifacts (screenshots/logs): `artifacts/`
- Presentations: `presentations/`

Detox requires a local development environment (Node.js, Yarn/npm, Detox CLI, Android SDK and/or Xcode for iOS). This README intentionally keeps run steps minimal — see the test folder to inspect the scripts and `e2e/jest.config.js` for test runner config.

If you want a short try-it checklist for running tests locally, the typical steps are:

1. Install dependencies: `npm install` or `yarn` in the app folder (`luckytrainings/`).
2. Install Detox and build the app for the target (Android/iOS) per Detox docs.
3. Run the example tests from the repository `e2e/` using the configured runner.

For exact, environment-specific commands (Xcode simulators, Android emulators, or CI setup), consult the official Detox docs: https://wix.github.io/Detox/docs/introduction/getting-started

## License & contact

Owner: surendrajaganadam

If you have questions about the materials, open an issue in the repo or contact the owner.
