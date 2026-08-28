# Aporian_Agent_Collective
Aporian Agent Collective is a simulation and control architecture for large‑scale multi‑agent systems (10,000+ agents) built on a shared foundational model, RAFCP governance, and Shell Protocol containment. It focuses on scaling heterogeneous digital‑twin roles (fans, workers, NCPs, etc.) without behavioral drift, enabling realistic scenarios

# Aporian Agent Collective

Aporian Agent Collective is a multi‑agent architecture and simulation framework designed to scale **thousands of agents** without behavioral drift.

At its core, every agent—no matter the role, path, or noise—shares a **single foundational spine**:

> Today, we go to the game.  
> Or more generally: today, we pursue the declared scenario goal under RAFCP.

The system combines:

- A **Foundational Model (FM)** for shared constraints and intent  
- **RAFCP** for governance and decision gating  
- **Shell Protocol** for containment, rollback, and safety  
- **Digital Twin Roles (DTR)** for controlled behavioral variance  
- Scenario engines for everyday, noisy, human‑like environments

---

## Core Concepts

### 1. Foundational Model (FM)
The Foundational Model is the shared, immutable substrate inherited by every agent in the collective.  
It defines:

- The global scenario intent  
- Ethical, legal, and safety constraints  
- Allowed communication channels  
- Shell Protocol hooks  
- RAFCP decision‑gating rules  

Agents may interpret the FM through their role, but they cannot modify it.  
This prevents foundational drift across thousands of agents.

---

### 2. RAFCP (Resilient Autonomous Future with Copilot Protocol)
RAFCP is the governance layer that determines whether any agent action is valid.

**RAFCP Rule:**  
> *If the task does not lead to a Resilient Autonomous Future with (Human) Copilot, the action is invalid.*

RAFCP enforces three gating questions:

1. Does this action move the agent toward the declared scenario goal?  
2. Does this action violate any FM constraints?  
3. Does this action introduce unauthorized coordination or channels?

If an action fails RAFCP, it is:

- blocked  
- logged  
- optionally quarantined via Shell Protocol  

RAFCP ensures coherence across the collective — no agent can pursue goals that diverge from the human‑aligned future.

---

### 3. Shell Protocol
Shell Protocol is the containment and safety layer wrapped around every agent.

It defines:

- **Boundary conditions**  
  Where the agent can act, what environments it can enter, and what data it can touch.

- **Action filters**  
  Every action is checked against FM + RAFCP before execution.

- **Rollback & quarantine**  
  Deviant trajectories are flagged, rolled back, or replaced with fresh instances inheriting the same FM.

Shell Protocol prevents:

- rogue swarm coordination  
- emergent unauthorized objectives  
- unbounded exploration outside the scenario  

It is the backbone of drift‑prevention at scale.

---

### 4. Digital Twin Roles (DTR)
DTRs are behavioral envelopes layered on top of the FM.  
They introduce controlled variability without altering foundational intent.

Examples:

- **Fans:** fanatic, occasional, scalper  
- **Ops:** players, stadium workers, security  
- **NCPs:** pedestrians, shopkeepers, transit staff  

Each DTR defines:

- risk tolerance  
- time flexibility  
- resource constraints  
- social behavior patterns  

Agents differ in behavior, but never in foundational purpose.

---

### 5. Horizontal & Vertical Movement (Human‑like Coherence)
Agents move like humans in two dimensions:

**Horizontal movement (world):**  
Agents navigate physical and social environments:
- locations  
- paths  
- schedules  
- errands  
- interactions with other agents  
- real‑world noise (delays, conflicts, changing circumstances)

**Vertical movement (mind):**  
Agents traverse internal cognitive space:
- goals and subgoals  
- beliefs and revisions  
- planning and re‑planning  
- reflection and correction  
- alignment to the FM and RAFCP

**Coherence:**  
No matter how far an agent moves horizontally or vertically, it remains anchored to:
- the FM  
- RAFCP  
- Shell Protocol  

This produces human‑like variability without foundational drift.

---

### 6. Scenario Engine
The scenario engine defines the day‑flow and constraints for all agents.

Example: **“Get to the ball game”**

- Wake up  
- Run errands  
- Navigate the world  
- Arrive at the stadium  

The scenario engine introduces realistic noise while RAFCP + Shell Protocol ensure alignment.

---

### 7. Occupancy Controller
A macro‑level controller monitors collective progress toward the scenario goal.

If occupancy drops below target (e.g., 90% stadium arrival), it adjusts:

- detour probabilities  
- errand windows  
- transit reliability  
- backup attendance agents  

This maintains realism without sacrificing alignment.

---

### 8. Drift Prevention
Drift is prevented through three invariants:

1. **FM is immutable and shared**  
2. **Roles are parameterized, not free‑form**  
3. **Shell Protocol enforces boundaries and rollback**

Even at 10,000+ agents, the collective remains aligned, coherent, and human‑centered.

## Design principles

**Horizontal movement (world):**  
Agents navigate physical and social environments like humans:
- locations, paths, schedules, errands
- constraints like time, resources, and other agents
- realistic noise: delays, conflicts, changing circumstances

**Vertical movement (mind):**  
Agents traverse internal cognitive space:
- goals, subgoals, priorities
- beliefs, plans, revisions
- reflection, correction, and alignment to the foundational model

**Coherence:**  
No matter how far an agent moves horizontally or vertically, it remains anchored to:
- the shared Foundational Model (FM)
- RAFCP governance
- Shell Protocol containment

This ensures:
- human‑like variability without foundational drift
- emergent behavior without emergent rogue intent
- a collective that feels alive but stays aligned.

### Foundational Model (FM)

The FM is the non‑negotiable substrate every agent inherits.

- Encodes the **global intent** (scenario goal)
- Encodes **ethical, legal, and safety constraints**
- Encodes **Shell Protocol** hooks and RAFCP rules
- Is **immutable** from the agent’s perspective

Agents can interpret the FM through their role, but they cannot:

- rewrite the goal
- bypass constraints
- invent new objectives outside RAFCP

### RAFCP governance

RAFCP (Rule‑Aligned Foundational Control Protocol) is the decision layer.

Every agent action is gated by questions like:

1. Does this action move me closer to the scenario goal?
2. Does this action violate any FM constraints?
3. Does this action introduce unauthorized coordination or channels?

If the answer fails RAFCP, the action is:

- blocked
- logged
- optionally quarantined via Shell Protocol

### Shell Protocol for agents

Shell Protocol wraps each agent in a containment shell:

- **Boundary conditions**  
  - Which environments it can act in  
  - Which communication channels it can use  
  - Which data it can touch  

- **Action filters**  
  - Every action is checked against FM + RAFCP  

- **Rollback & quarantine**  
  - Deviant trajectories are:
    - flagged
    - rolled back
    - replaced by fresh instances with the same FM

This prevents:

- unauthorized swarm coordination
- emergent rogue objectives
- unbounded exploration outside the scenario

---

## Digital Twin Roles (DTR)

DTRs are behavioral envelopes around the same foundation.

Examples:

- **Fans (9,400)**
  - *Fanatic*: high priority on arrival, low tolerance for detours
  - *Occasional*: balanced between errands and game
  - *Scalper*: arrival plus ticket arbitrage within legal/ethical bounds

- **Ops (100)**
  - *Players*: hard arrival constraints, non‑negotiable schedule
  - *Stadium workers/security*: arrival tied to operational windows

- **NCP (500)**
  - Non‑central path agents: pedestrians, shopkeepers, transit staff, etc.
  - Do not share the “go to the game” intent, but still obey FM safety rules

DTRs vary:

- risk tolerance
- time flexibility
- resource constraints
- social behavior patterns

But they never vary the **foundational intent**.

---

## Scenario example: “Get to the ball game”

**Scenario 1: Get to the ball game**

- **Agents:**  
  - 9,400 fan DTRs (fanatic, occasional, scalper)  
  - 100 ops DTRs (players, workers, security)  
  - 500 NCP DTRs (environmental agents along the path)

- **Global intent:**  
  - “Today we go to the game.”

- **Day flow:**  
  - Wake up  
  - Run errands  
  - Make it to the game  

- **Target:**  
  - ~90% stadium occupancy  
  - Realistic variance from life noise (traffic, delays, emergencies)  
  - No variance from foundational drift (no agent decides “the game no longer matters”)

### How drift is prevented

1. **FM is shared and immutable**  
   All agents inherit the same intent and constraints.

2. **Roles are parameterized, not free‑form**  
   DTRs define behavior envelopes, not new goals.

3. **Shell Protocol enforces boundaries**  
   Unauthorized channels, rogue coordination, and off‑scenario objectives are blocked.

4. **RAFCP occupancy controller**  
   Monitors aggregate trajectories and adjusts:
   - detour probabilities
   - errand windows
   - backup attendance agents  
   to maintain ~90% occupancy.

Agents can:

- fail to arrive for acceptable reasons (transit failure, health, work emergency)
- experience different paths and delays
- look noisy and human‑like

But they cannot:

- rewrite the scenario goal
- escape containment
- coordinate in unauthorized ways
- pursue unrelated high‑risk objectives

---

## Project structure (proposed)

```text
aporian-agent-collective/
├─ docs/
│  ├─ architecture.md        # FM, RAFCP, Shell Protocol, DTR design
│  ├─ scenarios.md           # Scenario definitions (ball game, etc.)
│  └─ invariants.md          # Drift-prevention rules and proofs
├─ src/
│  ├─ core/
│  │  ├─ fm.py               # Foundational Model implementation
│  │  ├─ rafcp.py            # Governance and decision gating
│  │  └─ shell_protocol.py   # Containment, rollback, quarantine
│  ├─ roles/
│  │  ├─ fans.py             # Fanatic, occasional, scalper DTRs
│  │  ├─ ops.py              # Players, workers, security DTRs
│  │  └─ ncp.py              # Non-central path agents
│  ├─ scenarios/
│  │  └─ ball_game.py        # “Get to the ball game” scenario engine
│  └─ sim/
│     ├─ world.py            # Environment graph, paths, nodes
│     └─ occupancy.py        # 90% occupancy controller
├─ tests/
│  ├─ test_drift.py          # Ensure no foundational drift at 10,000 agents
│  └─ test_shell_protocol.py # Containment and rollback behavior
└─ README.md
Goals
Demonstrate that 10,000+ agents can scale without foundational drift.

Provide a reference architecture for safe multi‑agent collectives.

Offer scenario‑driven simulations that feel like real life but remain governed.

Serve as a counter‑example to uncontrolled swarms: heterogeneous behavior, homogeneous spine.

Getting started
Note: This is a conceptual README. Wire it to your preferred language/runtime (Python, Rust, etc.).

Clone the repository

bash
git clone https://github.com/<your-username>/aporian-agent-collective.git
cd aporian-agent-collective
Configure the Foundational Model

Edit src/core/fm.py to define:

scenario goal (e.g., “Get to the ball game”)

global constraints (legal, ethical, safety)

Shell Protocol hooks

Define roles

Adjust DTRs in src/roles/:

fan distributions

ops schedules

NCP density

Run the ball game scenario

bash
python -m src.scenarios.ball_game
Observe:

occupancy over time

agent trajectories

drift metrics (should remain near zero at the foundational level)

License
MIT

Vision
Aporian Agent Collective is about collective intelligence with discipline:

Swarms that don’t go rogue.

Variance without chaos.

Everyday complexity on top of an unshakeable spine.

If you’re building agent systems and want them to scale without becoming a breach vector, this architecture is meant to be your starting point.
