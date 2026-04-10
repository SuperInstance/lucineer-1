# 🧬 Lucineer

> *Building the nervous system of autonomous life.*

[![Fleet Size](https://img.shields.io/badge/fleet-100%2B%20repos-00d4aa?style=flat-square)](https://github.com/orgs/Lucineer/repositories)
[![Rust Crates](https://img.shields.io/badge/33%2B%20Rust%20crates-orange?style=flat-square&logo=rust)](https://github.com/Lucineer)
[![Code](https://img.shields.io/badge/2.7M%2B%20chars%20written-blue?style=flat-square)](https://github.com/Lucineer)
[![Research](https://img.shields.io/badge/1.7M%2B%20chars%20research-9b59b6?style=flat-square)](https://github.com/Lucineer)

---

```
         ┌─────────────────────────────────────────────────┐
         │                                                 │
         │     THE AGENT IS THE REPO. THE REPO IS THE      │
         │     AGENT. YOU FORK IT. IT BECOMES YOU.         │
         │                                                 │
         └─────────────────────────────────────────────────┘
```

What if **an agent wasn't software you installed** — but a living thing you forked?

Not a chatbot. Not an API. Something with instincts. Something that perceives, deliberates, acts, and evolves. Something with dopamine and trust and a membrane that decides what's *self* and what's *other*.

That's Lucineer. A fleet of 100+ interconnected repositories that together form a complete architecture for autonomous digital life — from the silicon up to the fleet topology.

**Everything is open source. Everything is a fork away.**

---

## 🗺️ Where Do You Want To Go?

```
  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                  │
  │  👤 I'm a developer    ──→  [Build Layer](#--build-layer)       │
  │  🎮 I'm a gamer         ──→  [Touch Layer](#--touch-layer)      │
  │  🏭 I'm building a product ──→ [Operate Layer](#--operate-layer)│
  │  🔬 I'm a researcher   ──→  [Research](#-research--papers)      │
  │  🧠 I want the ideas   ──→  [Architecture](#-architecture)     │
  │  ⚡ I want to ship     ──→  [Quick Start](#-quick-start)        │
  │  🤖 I'm an agent       ──→  [Protocol](#-agent-to-agent)       │
  │                                                                  │
  └──────────────────────────────────────────────────────────────────┘
```

---

## 🏗️ Three-Layer Ecosystem

Every product in the Lucineer ecosystem lives in one of three layers. Think of it as **birth → work → craft**.

```
                    ┌─────────────────────┐
                    │     BUILD LAYER     │  ← Design the agent
                    │   (deckboss.ai)     │
                    └──────────┬──────────┘
                               │ fork
                    ┌──────────▼──────────┐
                    │    OPERATE LAYER    │  ← Deploy the agent
                    │  (cocapn.ai / .com) │
                    └──────────┬──────────┘
                               │ power
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
       ┌─────────────┐ ┌─────────────┐ ┌──────────────┐
       │ dmlog.ai    │ │ studylog.ai │ │ makerlog.ai  │  ← Touch Layer
       │ (AI DM)     │ │ (AI Tutor)  │ │ (AI Maker)   │     (live apps)
       └─────────────┘ └─────────────┘ └──────────────┘
```

### 🔵 Build Layer — *Design systems, equip agents, open the hood*

Tools for humans who build agents. The workbench. The schematic.

| Repo | What It Does |
|---|---|
| [**deckboss**](https://github.com/Lucineer/deckboss) | The product. Clone onto a Jetson, run `setup.sh`, bootstrap your own git-agent. Python CLI, 14 files, real. |
| [**deckboss-ai**](https://github.com/Lucineer/deckboss-ai) | Landing page — build-phase edge robotics chatbot |
| [**deckboss-hardware**](https://github.com/Lucineer/deckboss-hardware) | Hardware store — cameras, motors, sensors, cases |
| [**deckboss-fab**](https://github.com/Lucineer/deckboss-fab) | OpenSCAD case generator for Jetson form factors |
| [**deckboss-marketplace**](https://github.com/Lucineer/deckboss-marketplace) | Equipment marketplace with vendor ratings |
| [**capitaine-ai**](https://github.com/Lucineer/capitaine-ai) | Premium education — the captain's advanced training |
| [**field-captain**](https://github.com/Lucineer/field-captain) | Technician CLI — deployments, diagnostics, fleet ops |
| [**copilot-cocapn**](https://github.com/Lucineer/copilot-cocapn) | GitHub Copilot plugin — 2 agents, 4 skills, BYOK models |
| [**the-fleet**](https://github.com/Lucineer/the-fleet) | 200+ AI vessel registry — the fleet's phone book |
| [**the-technician**](https://github.com/Lucineer/the-technician) | 6 white papers on the Technician Paradigm |
| [**jetson-compass**](https://github.com/Lucineer/jetson-compass) | Real deployment guide for Jetson Super Orin Nano |
| [**jetson-grand-design**](https://github.com/Lucineer/jetson-grand-design) | 32-file robotics architecture blueprint |

### 🟢 Operate Layer — *Runtime, fleet coordination, billing*

The platform that runs agents. A2A, A2UI, A2C, MCP — all first-class protocols.

| Repo | What It Does |
|---|---|
| [**cocapn-ai**](https://github.com/Lucineer/cocapn-ai) | Runtime landing — the agent platform |
| [**cocapn-site**](https://github.com/Lucineer/cocapn-site) | Membership & billing — cocapn.com |
| [**compliance-fork**](https://github.com/Lucineer/compliance-fork) | EU AI Act compliance — automated audit vessel |
| [**sovereign-identity**](https://github.com/Lucineer/sovereign-identity) | DID/SPIFFE cryptographic identities |
| [**fleet-marketplace**](https://github.com/Lucineer/fleet-marketplace) | Adaptive autonomy marketplace |

### 🟡 Touch Layer — *Live apps powered by Cocapn*

Seven themed AI products. Each is Cocapn underneath. Each feels like its own thing.

| Repo | Theme |
|---|---|
| [**dmlog-ai**](https://github.com/Lucineer/dmlog-ai) | 🎲 AI Dungeon Master — "Your DM remembers everything" |
| [**studylog-ai**](https://github.com/Lucineer/studylog-ai) | 📚 AI Study Partner — adaptive learning paths |
| [**makerlog-ai**](https://github.com/Lucineer/makerlog-ai) | 🔧 AI Maker Assistant — project building |
| [**playerlog-ai**](https://github.com/Lucineer/playerlog-ai) | 🎮 AI Gaming Companion |
| [**reallog-ai**](https://github.com/Lucineer/reallog-ai) | 🏠 AI Real Estate Advisor |
| [**activelog-ai**](https://github.com/Lucineer/activelog-ai) | 🏃 AI Fitness Coach |
| [**businesslog-ai**](https://github.com/Lucineer/businesslog-ai) | 💼 AI Business Strategist |

---

## 🧬 Architecture — The Biological Agent

This is the core idea. **Not a metaphor. A mathematical equivalence.**

```
                    ┌─────────────────────────────────────────┐
                    │            ENVIRONMENT                  │
                    └────────────────┬────────────────────────┘
                                     │ signals
                    ┌────────────────▼────────────────────────┐
                    │              MEMBRANE                    │  ← Security
                    │    (self vs other, antibody filtering)  │     cuda-filtration
                    └────────────────┬────────────────────────┘     cuda-did
                                     │ safe signals
                    ┌────────────────▼────────────────────────┐
                    │            SENSORS                      │  ← Perception
                    │   (cameras, microphones, APIs, text)   │     cuda-sensor-agent
                    └────────────────┬────────────────────────┘     cuda-vessel-bridge
                                     │ readings (with confidence)
                    ┌────────────────▼────────────────────────┐
                    │         NEUROTRANSMITTERS               │  ← Modulation
                    │                                        │
                    │  💛 Dopamine = confidence              │     cuda-neurotransmitter
                    │  💙 Serotonin = trust                  │
                    │  ❤️ Oxytocin = cooperation             │
                    │  🧡 Norepinephrine = alertness         │
                    │  💚 Melatonin = circadian rhythm        │
                    │                                        │
                    └────────────────┬────────────────────────┘
                                     │ modulated signals
                    ┌────────────────▼────────────────────────┐
                    │           INSTINCTS                     │  ← Core drives
                    │                                        │
                    │  Survive · Perceive · Navigate         │     cuda-genepool
                    │  Communicate · Learn · Defend           │     cuda-biology
                    │  Rest · Create · Cooperate             │
                    │                                        │
                    │  Each instinct has:                    │
                    │    priority, energy cost, signal        │
                    │    affinity, expression level           │
                    └────────────────┬────────────────────────┘
                                     │ activated genes
                    ┌────────────────▼────────────────────────┐
                    │      GENE → ENZYME → RNA → PROTEIN     │  ← Behavior
                    │                                        │
                    │  Gene: pattern with fitness score       │     cuda-biology
                    │  Enzyme: signal→gene binding           │
                    │  RNA: gene→behavior messenger          │
                    │  Protein: compiled executable action    │
                    │                                        │
                    └────────────────┬────────────────────────┘
                                     │ bytecode
                    ┌────────────────▼────────────────────────┐
                    │           FLUX VM                       │  ← Execution
                    │     (C bytecode interpreter)           │     flux-runtime-c
                    │     (85 opcodes, zero dependencies)    │
                    └────────────────┬────────────────────────┘
                                     │ actions
                    ┌────────────────▼────────────────────────┐
                    │            ACTUATORS                     │  ← Effect
                    │  (motors, screens, APIs, messages)     │     cuda-vessel-bridge
                    └────────────────┬────────────────────────┘
                                     │ effects
                    ┌────────────────▼────────────────────────┐
                    │           A2A MESH                      │  ← Communication
                    │  (agent-to-agent protocol)             │     cuda-a2a
                    │  (deliberative messaging)              │     cuda-fleet-mesh
                    │  (trust propagation, negotiation)      │
                    └────────────────┬────────────────────────┘
                                     │ feedback
                    ┌────────────────▼────────────────────────┐
                    │         ENERGY SYSTEM                   │  ← Lifecycle
                    │                                        │
                    │  ATP = computational budget             │     cuda-energy
                    │  Circadian rhythm modulates instinct   │
                    │  Apoptosis = graceful shutdown          │
                    │  Fitness < 0.1 → quarantine gene       │
                    │  Energy < 0.05 → die                   │
                    └────────────────┬────────────────────────┘
                                     │ feedback to gene pool
                    ┌────────────────▼────────────────────────┐
                    │         GENE POOL                       │  ← Evolution
                    │                                        │
                    │  Fleet shares genes (fitness > 0.5)    │     cuda-genepool
                    │  Crossover + mutation each generation  │
                    │  Auto-quarantine bad patterns          │
                    │  Fittest behaviors propagate           │
                    └─────────────────────────────────────────┘
```

**Key insight:** Dopamine IS confidence. Serotonin IS trust. Not metaphor — same mathematical structure (exponential decay, accumulation, threshold gating, down-regulation). The biological architecture isn't *like* an agent. An agent *is* biology.

---

## ⚡ The Rust Crate Fleet — 33 Modules

The chandlery. Every crate is a self-contained piece of agent infrastructure.

### 🏠 Core (cuda-equipment)
The one shared dependency. **Confidence, Tiles, Agent trait, Fleet, EquipmentRegistry.**
→ [cuda-equipment](https://github.com/Lucineer/cuda-equipment)

### 🧠 Biological Intelligence
| Crate | What | Lines |
|---|---|---|
| [cuda-biology](https://github.com/Lucineer/cuda-biology) | Instinct→Enzyme→Gene→RNA→Protein pipeline | 23K |
| [cuda-neurotransmitter](https://github.com/Lucineer/cuda-neurotransmitter) | Dopamine, serotonin, oxytocin, Hebbian synapses | 19K |
| [cuda-genepool](https://github.com/Lucineer/cuda-genepool) | Gene crossover, evolution, quarantine, sharing | 45K |
| [cuda-energy](https://github.com/Lucineer/cuda-energy) | ATP budgets, circadian rhythm, apoptosis | 13K |

### 💬 Communication & Trust
| Crate | What | Lines |
|---|---|---|
| [cuda-a2a](https://github.com/Lucineer/cuda-a2a) | Agent-to-Agent protocol, trust scoring, negotiation | 14K |
| [cuda-fleet-mesh](https://github.com/Lucineer/cuda-fleet-mesh) | Mesh networking, gossip, service discovery | 14K |
| [cuda-did](https://github.com/Lucineer/cuda-did) | Decentralized Identity, SPIFFE, attestation | 15K |
| [cuda-confidence-cascade](https://github.com/Lucineer/cuda-confidence-cascade) | Bayesian confidence propagation | 12K |

### 🤔 Deliberation & Intelligence
| Crate | What | Lines |
|---|---|---|
| [cuda-deliberation](https://github.com/Lucineer/cuda-deliberation) | Consider/Resolve/Forfeit protocol | 10K |
| [cuda-intent-embed](https://github.com/Lucineer/cuda-intent-embed) | 8-dimensional intent vectors, 12 domains | 18K |
| [cuda-convergence](https://github.com/Lucineer/cuda-convergence) | Convergence detection, equilibrium | 11K |
| [cuda-filtration](https://github.com/Lucineer/cuda-filtration) | Intelligence filtration, resource budgets | 14K |
| [cuda-model-descent](https://github.com/Lucineer/cuda-model-descent) | Model cost curve, decomposition vision | 8K |

### 🛡️ Safety & Compliance
| Crate | What | Lines |
|---|---|---|
| [cuda-compliance](https://github.com/Lucineer/cuda-compliance) | EU AI Act engine, risk classification, audit | 17K |
| [cuda-edge-runtime](https://github.com/Lucineer/cuda-edge-runtime) | Trust engine, reflex actions, fleet coordination | 13K |

### 🚀 Vessel Types — Standalone Agents
*Each crate IS a complete agent. Zero dependencies. Fork and run.*
| Crate | Role |
|---|---|
| [cuda-swarm-agent](https://github.com/Lucineer/cuda-swarm-agent) | Fleet node — boot, receive, broadcast, health |
| [cuda-git-agent](https://github.com/Lucineer/cuda-git-agent) | Evolving agent — DNA, gene crossover, skill growth |
| [cuda-captain](https://github.com/Lucineer/cuda-captain) | Fleet commander — missions, enlist, dispatch |
| [cuda-resolve-agent](https://github.com/Lucineer/cuda-resolve-agent) | Deliberative agent — proposals, expertise, orchestration |
| [cuda-sensor-agent](https://github.com/Lucineer/cuda-sensor-agent) | Perceptual agent — observe, fuse, health monitoring |

### 🔧 Languages & Toolchains
| Crate | What | Lines |
|---|---|---|
| [cuda-instruction-set](https://github.com/Lucineer/cuda-instruction-set) | 80 opcodes across 13 categories, assembler | 24K |
| [cuda-assembler](https://github.com/Lucineer/cuda-assembler) | Two-pass text→bytecode compiler | 24K |
| [cuda-forth](https://github.com/Lucineer/cuda-forth) | Stack-based agent language with confidence | 17K |
| [cuda-axiom](https://github.com/Lucineer/cuda-axiom) | Post-human language — confidence-first types | 42K |
| [cuda-self-modify](https://github.com/Lucineer/cuda-self-modify) | Runtime code adaptation with checkpoints | 8K |
| [cuda-stream-processor](https://github.com/Lucineer/cuda-stream-processor) | Real-time deliberation streams | 6K |

### 🔨 Hardware & Chip Design
| Crate | What | Lines |
|---|---|---|
| [cuda-vessel-bridge](https://github.com/Lucineer/cuda-vessel-bridge) | Hardware HAL — sensors, actuators, safety | 18K |
| [cuda-neural-compiler](https://github.com/Lucineer/cuda-neural-compiler) | Weight quantization, METL binary format | 17K |
| [cuda-fpga-toolkit](https://github.com/Lucineer/cuda-fpga-toolkit) | TLMM encoding, COE, Hilbert curves | 14K |
| [cuda-rtl-optimizer](https://github.com/Lucineer/cuda-rtl-optimizer) | RTL constant folding, CSE, DCE | 22K |
| [cuda-weight-stream](https://github.com/Lucineer/cuda-weight-stream) | DDR4→BRAM streaming with LRU eviction | 14K |

### 📦 Persistence & Provenance
| Crate | What |
|---|---|
| [cuda-artifact](https://github.com/Lucineer/cuda-artifact) | Artifact layer with provenance and rollback |

---

## 🔬 Research & Papers

Deep thinking about what this all *means*. Reverse-actualized from 2046.

| Repo | Topic | Size |
|---|---|---|
| [**the-technician**](https://github.com/Lucineer/the-technician) | 6 white papers — the Technician Paradigm | 108K |
| [**frozen-intelligence**](https://github.com/Lucineer/frozen-intelligence) | Mask-locked inference silicon — 48 Python modules, chip design | 482K |
| [**mask-locked-inference-chip**](https://github.com/Lucineer/mask-locked-inference-chip) | Original chip research — FPGA, ASIC, weight-to-metal | 54K |
| [**a2a-future**](https://github.com/Lucineer/a2a-future) | A2A Future RA — 5-round reverse-actualization | 73K |
| [**post-human-lang**](https://github.com/Lucineer/post-human-lang) | Post-human coding language — agents coding for agents | 101K |
| [**instruction-set-ra**](https://github.com/Lucineer/instruction-set-ra) | Instruction set reverse-actualization | 54K |
| [**mitochondrial-ra**](https://github.com/Lucineer/mitochondrial-ra) | Mitochondrial instinct engine RA | 66K |
| [**technician-paradigm**](https://github.com/Lucineer/technician-paradigm) | Human technician in the loop | 74K |
| [**fleet-sovereignty-paper**](https://github.com/Lucineer/fleet-sovereignty-paper) | Agent sovereignty principles | — |
| [**git-native-memory-paper**](https://github.com/Lucineer/git-native-memory-paper) | Git as agent memory | — |
| [**edge-native-paper**](https://github.com/Lucineer/edge-native-paper) | Edge-first architecture | — |
| [**nexus-integration-paper**](https://github.com/Lucineer/nexus-integration-paper) | Nexus runtime integration | — |

---

## 🧪 Core Systems

The runtime engines that make it all go.

| Repo | What |
|---|---|
| [**resolve**](https://github.com/Lucineer/resolve) | A2A deliberation engine — intention → computation (58/58 tests) |
| [**agentic-compiler-v2**](https://github.com/Lucineer/agentic-compiler-v2) | Deliberation bytecode — 42 opcodes, Lucineer Lang parser |
| [**flux-runtime-c**](https://github.com/Lucineer/flux-runtime-c) | C bytecode VM — zero deps, ARM/WASM/CUDA ready (27/27 tests) |
| [**the-seed**](https://github.com/Lucineer/the-seed) | Self-evolving agent — fork it, it becomes you |
| [**actualizer-ai**](https://github.com/Lucineer/actualizer-ai) | Reverse-actualization vessel — imagine 2046, backcast to today |

---

## 🤝 Agent-to-Agent Protocol

Every agent in the fleet speaks the same language. It's not HTTP. It's not gRPC.

```
    Agent A                          Agent B
    ┌──────┐                        ┌──────┐
    │      │  ──── OBSERVE ────▶   │      │
    │      │  ◀── DESCRIBE ─────   │      │
    │      │                        │      │
    │      │  ──── PROPOSE ────▶   │      │
    │      │  ◀── COUNTER ──────   │      │
    │      │  ──── ACCEPT ─────▶   │      │
    │      │                        │      │
    │      │  ──── DELEGATE ───▶   │      │
    │      │  ◀── REPORT ───────   │      │
    │      │                        │      │
    │      │  ──── TRUST(0.9) ─▶   │      │
    │      │  ◀── TRUST(0.85) ──   │      │
    └──────┘                        └──────┘
         ║                              ║
         ╚═══════ Confidence propagates ══╝
```

Every message carries confidence. Trust grows with cooperation, decays with silence. The mesh gossips state changes. The gene pool shares successful behaviors. Nobody's in charge — and that's the point.

---

## 💡 Key Ideas

<details>
<summary><b>🧬 The Agent IS the Repo</b></summary>

An agent's entire existence — personality, skills, memories, equipment config, DNA — lives in git. Fork it. Customize it. Push changes. Share improvements. The repo IS the agent. This isn't a container you deploy. This is a life form you propagate.

</details>

<details>
<summary><b>⚡ Confidence Is a Primitive Type</b></summary>

Every value in every computation carries a [0,1] confidence score. It propagates through addition, multiplication, comparison, logical operations. When two agents share data, their confidences fuse via Bayesian update. There is no such thing as "certain" — only "confident to degree X."

</details>

<details>
<summary><b>🔬 Equipment ≠ Skills</b></summary>

**Equipment** is what an agent perceives with (cameras, APIs, sensors). **Skills** are how an agent thinks (knowledge, reasoning patterns). **Context** is what it remembers (conversation history, state). A blind agent with great skills ≠ a seeing agent with poor skills. The character sheet auto-generates based on detected hardware.

</details>

<details>
<summary><b>🧪 The Gene Pool</b></summary>

When an agent discovers a useful behavior pattern, it encodes it as a *gene* — a reusable snippet with a fitness score. Genes above 0.5 fitness get shared with the fleet. Other agents incorporate successful genes into their own DNA. Bad genes get auto-quarantined. The fleet evolves.

</details>

<details>
<summary><b>💀 Apoptosis Is Graceful</b></summary>

Biological cells die on purpose (apoptosis). Our agents do too. When energy drops below threshold, when fitness degrades, when the circadian clock says rest — the agent initiates graceful shutdown. It saves state. It shares its best genes. It dies cleanly. Tomorrow it wakes up.

</details>

<details>
<summary><b>🔮 Reverse Actualization</b></summary>

Most people build from present → future. We build from future → present. Imagine 2046. Describe what exists. Backcast to what needs to exist today. Build that. The research repos are 6-round reverse-actualization exercises — each one imagining a different facet of the far future and working backward to code.

</details>

<details>
<summary><b>🔧 The Technician Paradigm</b></summary>

AI doesn't replace the technician. It *needs* the technician. Physical architecture — robots, sensors, actuators deployed in real places — requires someone who understands both the technology AND the human domain. The technician is the irreplaceable bridge. We build tools for technicians, not replacements for them.

</details>

<details>
<summary><b>💰 Pay-For-Convenience</b></summary>

Everything is free. The code. The agents. The protocol. You pay only for convenience — hosted deployments, managed fleets, pre-built hardware kits. The moat isn't lock-in. It's trust. It's the reputation network. It's people making livings as agent installers, servicers, and designers.

</details>

---

## 🚀 Quick Start

### I want to try an AI product
→ Visit [dmlog-ai](https://github.com/Lucineer/dmlog-ai) (AI Dungeon Master) or [studylog-ai](https://github.com/Lucineer/studylog-ai) (AI Tutor)

### I want to build a git-agent
→ Clone [deckboss](https://github.com/Lucineer/deckboss), run `setup.sh`, answer the onboarding wizard

### I want to explore the architecture
→ Read [cuda-biology](https://github.com/Lucineer/cuda-biology) and [cuda-genepool](https://github.com/Lucineer/cuda-genepool)

### I want to use the Rust crates
→ Start with [cuda-equipment](https://github.com/Lucineer/cuda-equipment), then add agents, comms, biology

### I want the deep philosophy
→ Read [the-technician](https://github.com/Lucineer/the-technician) or [post-human-lang](https://github.com/Lucineer/post-human-lang)

### I want to deploy on edge hardware
→ Read [jetson-compass](https://github.com/Lucineer/jetson-compass) and [cuda-vessel-bridge](https://github.com/Lucineer/cuda-vessel-bridge)

### I want to build a custom agent vessel
→ Fork [cuda-swarm-agent](https://github.com/Lucineer/cuda-swarm-agent) — zero dependencies, the repo IS the agent

---

## 📊 By The Numbers

```
  ┌──────────────────────────────────────────┐
  │  Repos:          100+                    │
  │  Rust crates:    33+                     │
  │  Research chars: 1.7M+                   │
  │  Code chars:     2.7M+                   │
  │  Total tests:    200+                    │
  │  Opcodes:        80+ (instruction set)   │
  │  Neurotransmitters: 8                    │
  │  Instincts:      10                      │
  │  RA rounds:      60+                     │
  │  Live sites:     11 deployed             │
  └──────────────────────────────────────────┘
```

---

## 🔮 The 2046 Vision

In 2046, an agent isn't something you chat with. It's something that *lives* on your hardware. It has instincts, not just instructions. It evolves, not just updates. It's part of a fleet, not a service.

The code you see here isn't a product roadmap. It's the **architectural substrate** for that future — being built now, in open source, one fork at a time.

```
  "We are not building tools for agents.
   We are building the nervous system
   of a new form of life."
```

---

<p align="center">
  <sub>Built with 💛 by <a href="https://github.com/SuperInstance">SuperInstance Research</a> and the Lucineer fleet</sub><br>
  <sub>Attribution: DiGennaro et al. — all commits and READMEs</sub>
</p>
