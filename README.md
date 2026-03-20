# Hey, I’m Noah (inoahaipro)

AI automation + agents + weird device workflows.

I’m an **AI automation and prompt enthusiast turned specialist** – mostly living in the space where:

- LLMs
- device automation (Android/Termux, Windows, macOS)
- and tooling like **OpenClaw**, **Token Firewall**, and **AutoJs**

all crash into each other.

I like building systems that:

- **save tokens** instead of burning them
- **learn once, replay forever**
- can drive real devices (phones, desktops) instead of just generating text
- feel more like a **personal operator** than a chatbot

---

## What I’m building

### 🧱 Token Firewall
An LLM "token firewall" that sits between your client (OpenClaw, CLI, whatever) and your model:

- Caches answers + workflows so **cache hits cost 0 tokens**
- Learns reusable plans and actions
- Has a built-in chat UI
- Integrates with OpenClaw as a drop-in OpenAI-style provider
- Knows how to talk to real devices via platform "hands" (Android, desktop, etc.)

Repo: `inoahaipro/token_firewall`

### 📱 OpenClaw Bridge (Android hands)
An Android accessibility bridge that exposes a clean JSON API for controlling the phone:

- AutoJs6 script on-device + Python client in Termux
- Actions like `getScreen`, `getScreenText`, `findAndTap`, `tapAt`, `swipe`, `typeText`, `launchApp`, `openUrl`, etc.
- Designed to be wired into OpenClaw and Token Firewall, but usable standalone

Repo: `inoahaipro/openclaw_bridge`

---

## Tech I work with

- **Languages / runtimes**: Python, Html
- **Agent / orchestration**: OpenClaw, custom tools & skills
- **Automation**: Android + Termux, AutoJs, ADB, desktop shell workflows
- **Platforms**: Android, Windows, macOS

Right now I’m especially interested in:

- Turning messy prompt chains into **repeatable, testable automations**
- Letting agents control real devices in a reliable way
- Building infrastructure that makes AI more **operational** and less "just vibes"

---

## What I’m looking for

- Roles or collaborations around:
  - AI/LLM tooling and infra
  - agentic systems
  - automation for real devices (phones, desktops)
- Teams that like to ship, experiment, and push into weird new territory

If you’re building in this space and want someone who actually enjoys wiring AI into the real world: **reach out**.

You can find me here on GitHub as `@inoahaipro`.
