# `Axis`
### Chrysanthemum

> A modern runtime that upgrades your shell.

**`Axis`** is a fast, local-first intelligence layer for your terminal.
It enhances your existing shell with smarter navigation, contextual prompts, and powerful command history - with zero configuration required.

Install once. Your shell gets better everywhere.

---

## The Problem

Modern terminal workflows are fragmented.

You install one tool for your prompt, another for history, another for navigation - and they rarely feel cohesive. Configuration grows over time, performance suffers, and switching machines becomes painful.

`Axis` solves this by providing a single, unified runtime that improves the core interactions you use every day.

You keep your shell.
`Axis` upgrades the experience.

---

## What `Axis` Does

`Axis` focuses on three things - the actions you repeat constantly:

### 1. See where you are

A fast, context-aware prompt that understands:

* Working directory
* Git repositories
* Exit status
* Runtime context (when detectable)

Designed for clarity and speed, with <10 ms render targets.

---

### 2. Move where you want

Smarter navigation that learns from how you work.

```bash
axis cd proj
```

`Axis` ranks locations based on frequency and recency, so the most relevant destination appears first.

---

### 3. Reuse what you’ve done

Powerful history search to find commands instantly.

```bash
axis search docker
```

Features:

* Fuzzy matching
* Frequency ranking
* Recency weighting
* Local storage
* No cloud dependency

---

## Why `Axis` Feels Different

`Axis` is built around a few principles:

* **Shell-agnostic** - works across Bash, Zsh, and Fish
* **Fast by default** - performance is a feature
* **Local-first** - your data stays on your machine
* **Composable** - enhances your workflow instead of replacing it
* **Zero-config** - works immediately after install

`Axis` is designed to disappear into your workflow - not demand attention.

---

## Installation

Initial Installer curl-

```bash
curl -fsSL https://raw.githubusercontent.com/divijg19/Axis/main/install.sh | sh
axis init
```

Eventually-

```bash
curl -fsSL https://Axis.sh/install | sh
axis init
```

`Axis` detects your shell and configures integration automatically.

---

## Core Commands

```bash
 axis init        # initialize shell integration
 axis doctor      # diagnose setup issues
 axis search      # search command history
 axis history     # view stored history
 axis cd          # smart directory navigation
 axis config      # manage configuration
 axis version     # show version
 axis uninstall   # remove Axis
```

---

## Configuration

Configuration lives at:

```
~/.config/Axis/config.toml
```

`Axis` works without configuration.
Customization is optional.

---

## Architecture

`Axis` is intentionally simple:

* Single CLI binary
* Lightweight shell hooks
* Local embedded database
* High-performance prompt renderer

Future versions will add deeper context awareness and extensibility without sacrificing speed.

---

## Roadmap

Planned evolution:

* Context engine
* Plugin system
* Session awareness
* Optional TUI control plane
* Advanced command intelligence

`Axis` is built to grow without compromising simplicity.

---

## Status

`Axis` is early in development.
Expect rapid iteration and improvements.

---

## Contributing

Contributions are welcome.

Helpful areas:

* Shell integration
* Performance optimization
* Cross-platform support
* Documentation
* Testing

---

## License

MIT License.

---

## Name

`Axis` represents the central coordination point of your terminal environment.

Internal codename: **Chrysanthemum**.

---

## Vision

`Axis` aims to become the intelligence layer for modern developer terminals: fast, local, and deeply integrated with how people actually work.

---

**Install once. Stay in flow.**
