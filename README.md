![MINDCA Logo](assets/mindca-header-logo.png)

# MINDCA – LEGO® Mindstorms DevOps Control & Automation

**MINDCA** = *Mindstorms DevOps Control & Automation*

A complete toolkit to bring modern DevOps practices to the legendary LEGO® Mindstorms EV3 and NXT 2.0 platforms — combining automation, observability, and scripting power in a unified Python-based environment.

This project brings old-school robotics into the modern age with tools like Ansible, n8n, Home Assistant, Git, and Grafana — while keeping the original firmware and nostalgic experience intact.

> While this project centers around LEGO® Mindstorms, it is a fully independent, community-driven effort with no official affiliation to the LEGO Group.

## 🧭 Introduction

If you're like me and grew up building robots with LEGO® Mindstorms EV3 and NXT 2.0, you probably remember how magical it felt. But as official support fades and SPIKE Prime becomes the new standard (with a very limited audience in mind), many of us are left with amazing hardware — and no modern tools to use it.

I’m a systems engineer with a love for automation, scripting, and observability — and I’ve found a way to bring my childhood robots into the 21st century with tools like:

- **EV3dev** (Debian-based OS for EV3)
- **nxt-python** (Python control for NXT 2.0)
- **Ansible**, **n8n**, **Home Assistant**, or any control method you can script (like a DualShock 4 controller)
- **Grafana + Prometheus** for live metrics and sensor insights
- **Git + VSCode** for CI/CD-style DevOps development

This repository contains all the scripts, setup guides, and configuration files I use to control and monitor my Mindstorms robots — and now I’m sharing it with the world **for you all to enjoy**.

---

## 🧩 The Problem

- LEGO® Mindstorms EV3 and NXT 2.0 are officially **discontinued** and unsupported.
- **SPIKE Prime** replaces them with a platform that’s:
  - Designed primarily for children
  - Extremely limited in flexibility
  - Quickly outgrown after a few years
- The original tools (like NXT-G and EV3 Home Edition) are not only **outdated**, but were also **rebranded into Scratch-based block editors** that lack depth or extensibility.
- And for those of us who grew up with the original software, the new tools simply lack that classic LEGO® vibe — the nostalgic charm, UI, and feel are gone.
- Modern engineers, developers, and tinkerers are left without a bridge between classic LEGO hardware and current dev workflows.

## 🚀 The Solution: Modern Automation for Classic Bricks

By using `ev3dev` and `nxt-python`, you can build a system that is:

- 💻 **Flexible** — control your robots from any Python-capable device
- 🧱 **Non-destructive** — the original LEGO firmware is left **completely intact**
- 📡 **Wireless** — control NXT bricks via Bluetooth or USB from EV3, Raspberry Pi, laptop, VM, or more
- 🧰 **Tool-agnostic** — integrate with:
  - **Ansible** for deployments
  - **n8n** for drag-and-drop automation
  - **Home Assistant** for smart home triggers
  - **DualShock 4 controllers**, MQTT, shell scripts, and more

> Unlike the EV3, the NXT cannot run full Debian/Linux — but it can be remotely controlled by any machine that does. Whether that’s an EV3, Raspberry Pi, VM, or even an old laptop with USB/Bluetooth, it works seamlessly.

All of this is driven by Python, making the code consistent, hackable, and easy to integrate into any modern toolchain.

> Bonus: Because the original firmware remains untouched, you can still switch back and enjoy the official LEGO® software whenever you're feeling nostalgic — no permanent changes, no risks.

## 📈 Observability with Grafana & Prometheus

- Push real-time sensor, motor, and battery data to a **Prometheus Pushgateway**
- Visualize it all in **Grafana** dashboards
- Run background scripts in `tmux` or systemd for persistent monitoring
- Mix robot state with other home automation or infrastructure metrics

## 🔧 What's in This Repository

- ✅ Python scripts for EV3/NXT control and sensor reading
- ✅ Bluetooth pairing setup for multiple NXT bricks
- ✅ Pushgateway-ready monitoring scripts
- ✅ Ansible playbooks for robot setup
- ✅ Sample Grafana dashboards (battery, sensor, motor state)
- ✅ Home Assistant / n8n automation examples
- ✅ Git-based DevOps workflow using VSCode

## 🧑‍💻 About Me

I'm a system engineer with a passion for automation, Linux, and making things smarter. I built this as a personal project to revive my beloved LEGO robots — not just for nostalgia, but to explore how far you can push classic hardware using modern engineering principles.

Expect tutorials, diagrams, and walkthroughs soon — either in this repo, on my website, or linked through my knowledge base.

## 🤝 Contribute or Fork It

This project is public and open-source. Feel free to fork it, remix it, or contribute your own improvements. I'm always happy to connect — so if you have questions, ideas, or just want to share what you built, **reach out to me!**

> LEGO® is a trademark of the LEGO Group, which does not sponsor or endorse this project.

## 🔗 References / Upstream Projects

- [ev3dev GitHub](https://github.com/ev3dev/ev3dev) – A full Debian-based operating system for the LEGO® EV3 brick.
- [nxt-python GitHub](https://github.com/Eelviny/nxt-python) – A Python library to control LEGO® NXT 2.0 bricks via USB or Bluetooth.

---

## ⚠️ Legal Note: Original LEGO Software Files

Out of respect for LEGO's licensing, **this repository does not and will not include original LEGO software application files** (such as installers for NXT-G or EV3 Home Edition).

If you legally own these tools, you are responsible for backing them up. You can usually still find them through LEGO’s archived support pages or trusted educational resources.