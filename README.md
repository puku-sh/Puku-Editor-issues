# Puku Editor — Issues

> **The AI-native code editor that gets out of your way.**

## Introduction

Puku is an AI-native code editor — a fork of VS Code where AI understands your entire codebase, not just the line you're typing.

### What is Puku?

Puku combines the full VS Code editing experience with a deeply integrated AI layer. It indexes your project semantically on open, so every suggestion, chat response, and edit prediction is grounded in your actual code — not just what's visible on screen.

Unlike AI plugins that sit on top of an editor, Puku's AI is built into the workbench itself. This means faster responses, better context, and features that aren't possible through a plugin API alone.

---

## About this repository

This repository is the **public issue tracker** for [Puku Editor](https://puku.sh). The Puku source code lives in private repositories — **this repo exists for one purpose: so you can file bugs, request features, and tell us what's broken.** Every issue lands directly in front of the team.

---

##  Reporting a Bug

Before opening a new issue, please:

1. **Search existing issues** — your bug may already be tracked.
2. **Update to the latest Puku build** — check `Help → About` for your version.
3. **Reproduce in a clean window** — `Cmd/Ctrl+Shift+P → Developer: Reload Window` rules out stale state.

Then [open a new issue](../../issues/new/choose) with:

- **Puku version** (`Help → About`)
- **OS + version** (e.g. macOS 14.5, Ubuntu 24.04, Windows 11)
- **Steps to reproduce** — numbered, minimal, copy-pasteable
- **What you expected** vs **what happened**
- **Logs** if the editor crashed or chat misbehaved:
  - `Help → Toggle Developer Tools → Console`
  - `View → Output → Puku` (or `Puku Chat`)
- **Screenshots / screen recordings** for UI bugs — they save us hours

> **Please do not include API keys, access tokens, file contents you can't share publicly, or anything else sensitive.** Sanitize logs before pasting.

---

## ✨ Requesting a Feature

We love feature requests. To make yours land:

- **One feature per issue.** Don't bundle.
- **Lead with the problem, not the solution.** "I can't easily X" beats "Add a button that does Y."
- **Tell us who it helps and how often you'd hit it.** Frequency matters when we prioritize.
- **Link prior art** if another tool does this well — screenshots welcome.

---

## 🔒 Security Issues

**Do not file security vulnerabilities as public issues.** use GitHub's private vulnerability reporting on this repo. We respond within 48 hours.

---

##  Other Channels
- **Website** → [puku.sh](https://puku.sh)

---

## 📋 Issue Labels — what they mean

| Label | Meaning |
|---|---|
| `bug` | Something is broken |
| `enhancement` | New feature or improvement |
| `chat` | AI chat / agent issues |
| `completions` | Inline / FIM completions |
| `editor` | Editor UI / VS Code fork issues |
| `performance` | Slowness, latency, memory |
| `auth` | Sign-in / OAuth / sessions |
| `needs-repro` | We can't reproduce — please add steps |
| `good first issue` | Friendly entry point if you'd like to help |

---

## Code of Conduct

Constructive feedback — including harsh criticism — is welcome; personal attacks, harassment, or hostility toward other users are not. Issues that violate this will be closed without discussion.

---

**Thanks for using Puku Editor.** Every issue you file makes it better for everyone.
