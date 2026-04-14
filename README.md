<h1 align="center">🖥️ Lizerium.Software.Structs 🖥️</h1>

<p align="center">
  Structural map of core software products, system modules, and application nodes within the Lizerium ecosystem
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Language: </strong>
  
  <a href="./README.ru.md" style="color: #F5F752; margin: 0 10px;">
    🇷🇺 Russian
  </a>
  | 
  <span style="color: #0891b2; margin: 0 10px;">
    ✅ 🇺🇸 English (current)
  </span>
</div>

---

> [!NOTE]
> This project is part of the **Lizerium** ecosystem and belongs to the following direction:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> If you are looking for related engineering and supporting tools, start there.

## Purpose

This repository serves as a **structural index of the core software layer** within the **Lizerium** ecosystem.

It is not a primary implementation, but acts as:

- a map of key software components
- a navigation entry point into the ecosystem’s software architecture
- a description of roles for application-level systems
- a place for logical classification of core software products
- an architectural overview layer of the operational software domain

---

## Role in the Ecosystem

This repository helps to understand:

- which projects belong to the core software products of Lizerium
- how server, client, administrative, and game system nodes are separated
- where the entry points to key software solutions are located
- how interaction logic between software components is structured
- which applications form the operational core of the ecosystem

---

## What’s Included in This Direction

### 1. 🌐 Server & Administrative Infrastructure

Core server and administrative systems that provide management and operational support for the ecosystem.

- [`LizeriumServer`](https://github.com/Lizerium/LizeriumServer)
- [`Lizerium.FLAdmin`](https://github.com/Lizerium/Lizerium.FLAdmin)
- [`LizeriumAccauntManager`](https://github.com/Lizerium/LizeriumAccauntManager)

---

### 2. 🚀 Distribution & Launch

Software solutions responsible for application launch, updates, and delivery of game components.

- [`LizeriumSteam`](https://github.com/Lizerium/LizeriumSteam)

---

### 3. 🎮 Game Application Systems

Core game-facing application products and system modules interacting with the classical game branch.

- [`LizeriumFLHook`](https://github.com/Lizerium/LizeriumFLHook)
- [`FLGameCompanion`](https://github.com/Lizerium/FLGameCompanion)

---

## Architecture Diagram

```text
Lizerium.Software.Structs
├── Infrastructure
│   ├── LizeriumServer
│   └── Lizerium.FLAdmin
│
├── Distribution
│   └── LizeriumSteam
│
└── Game Software
    ├── LizeriumFLHook
    └── FLGameCompanion
```
