# PL Nastalli

**Systems programming • Rust • Operating systems**

I build low-level software with a focus on Rust, kernel architecture, performance, and user-controlled computing.

## Current focus

### [Nastalli](https://github.com/PLNastalli/Nastalli)

An experimental operating system kernel written primarily in Rust, currently targeting **x86_64 + UEFI + QEMU/OVMF**.

Nastalli is being designed around:

- memory safety by default;
- explicit kernel / HAL / architecture boundaries;
- `no_std` Rust and low-level systems programming;
- owner-controlled security and trust;
- evidence-based engineering and documentation;
- long-term architectural independence.

> **The machine belongs to its owner.**

## What I work on

- Rust systems programming
- Operating-system and kernel development
- x86_64 architecture
- UEFI and boot infrastructure
- Memory management and scheduling
- Low-level performance work
- Security-oriented system design

## Engineering approach

I prefer small, verifiable changes over speculative abstractions. Current work on Nastalli is developed with documented milestones, CI, tests, explicit `unsafe` boundaries, and a roadmap toward isolated userspace and a stable production-grade baseline.

## Main project

| Project | Status | Stack |
|---|---|---|
| **[Nastalli](https://github.com/PLNastalli/Nastalli)** | Active development | Rust, `no_std`, x86_64, UEFI, QEMU |

## GitHub

Most experimental and older repositories are kept private so the public profile stays focused on actively maintained work.

For technical details, architecture, roadmap, and current implementation status, see the **[Nastalli repository](https://github.com/PLNastalli/Nastalli)**.
