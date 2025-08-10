# CI/CD with GitHub Actions – Starter

[![Build Status](https://github.com/<YOUR_USER>/<YOUR_REPO>/actions/workflows/ci.yml/badge.svg)](https://github.com/<YOUR_USER>/<YOUR_REPO>/actions/workflows/ci.yml)

A minimal CI/CD example that runs on every push and pull request:
- Build the project
- Run unit tests
- Run a quick quality check (lint or basic security scan)
- Show results as PR checks and a status badge

> **Goal:** prove you understand CI basics end-to-end with a clean, reproducible repo.

---

## 🔎 What’s inside

- **Tiny app** (choose Python *or* Node—both instructions below)
- **1–2 unit tests** to produce a clear pass/fail signal
- **GitHub Actions workflow** (`.github/workflows/ci.yml`)
- **PR checks** that block merge if the pipeline is red
- **Docs**: screenshots of a green run, a failing run, and PR checks

---

## 🗂 Project structure

