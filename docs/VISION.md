# Neonmem Micro-AI — Vision

> Early project. This page describes **what we're building and why**. It is a
> vision document, not a spec.

## Small, stateful AI

Most of the industry is racing to build **bigger** models. We think a lot of real
problems get solved by going **smaller** — the way microservices and micro
frontends once untangled monoliths.

The big models are brilliant generalists, but they're **stateless**: every
conversation starts from zero, and training them costs a fortune. So they need
memory bolted on after the fact.

We start from the memory. **Neonmem Micro-AI** is a small, **stateful** AI whose
knowledge lives in a portable **memory cartridge** — not baked into billions of
weights. Because it doesn't have to *memorize* a whole domain, it can be small,
fast, private, and run on hardware you already own.

## The mental model

> A micro-AI is like *a developer who finished the courses and has all the
> project's docs in front of them* — not a PhD in computer science.

It won't out-reason a frontier model. But for the everyday work of a real
engineer — reading logs, recalling what was decided, flagging "we've hit this
before," reminding, advising — a focused specialist with the right knowledge in
front of it is fast, cheap, and **private**.

## A fleet, not a giant

One micro-AI knows one field. Point it at a body of knowledge — your docs, your
codebase, a domain's references — and it becomes a specialist for *that*. An
**orchestrator** then coordinates many of these specialists to take on bigger
tasks together, the way a control plane coordinates services.

Small experts + smart coordination, instead of one enormous generalist.

## Why it matters

- **Private & offline** — your knowledge stays on your machine; no data leaves.
- **Affordable** — small models, your own hardware, no per-token meter running.
- **Auditable** — answers trace back to a source you can inspect, not a black box.
- **Portable** — a micro-AI *is* a cartridge: shareable, versionable, yours.
- **Yours** — built to help you work, not to replace you.

## Principles

Offline, local, and private by default · auditable answers · built on
public-domain foundations · prove it small, then scale.

---

*Part of the Neonmem family. [Neonmem](https://neonmem.com) gives your AI agent a
living memory cartridge; Neonmem Micro-AI turns cartridges into small stateful
assistants.*
