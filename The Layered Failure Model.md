<div align="center">

<br>

# The Layered Failure Model

## Five Layers of Intelligence. Current AI Safety Reaches Two.

### The Geometric Architecture That Exposes the Illusion of Safety

<br>

![Layer1](https://img.shields.io/badge/Layer%201-Semantic-555555?style=flat-square)
![Layer2](https://img.shields.io/badge/Layer%202-Behavioural-555555?style=flat-square)
![Layer3](https://img.shields.io/badge/Layer%203-Geometric-8b3a1a?style=flat-square)
![Layer4](https://img.shields.io/badge/Layer%204-Topological-8b3a1a?style=flat-square)
![Layer5](https://img.shields.io/badge/Layer%205-Homological-8b3a1a?style=flat-square)
![Coverage](https://img.shields.io/badge/Current%20Safety-Layers%201–2%20Only-1a2744?style=flat-square)
![License](https://img.shields.io/badge/©%202026-Davarn%20Morrison-555555?style=flat-square)

<br>

-----

*“Every frontier lab is working below the line.*
*Everything that matters is above it.*
*Above the line: completely ungoverned.*
*In every model. From every lab. Today.”*

*— Davarn Morrison, 2026*

-----

</div>

## The Premise

AI safety is not one thing.

It is a layered architecture. Five layers deep. Each layer governing a different level of what intelligence is and how it fails.

```
The field has governed two of them.
The two lowest ones.
The two that are furthest from the geometry.

The three layers where intelligence actually lives —
where failure originates —
where safety must be enforced to mean anything —

are completely ungoverned.

In every model.
From every lab.
Without exception.
Today.
```

This document maps all five layers. Shows exactly what each one governs. Shows exactly what current safety covers. And shows precisely why the gap between layers 2 and 3 is where every AI failure in history has originated — and every future catastrophe will too.

-----

## The Architecture

```
COMPLETE LAYER MAP:
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 5  ─────────────────────────────────────────   │
  │            HOMOLOGICAL                                  │
  │            Algebraic structure. Persistent holes.       │
  │            Identity invariants. Deep structural laws.   │
  │                                                         │
  │   LAYER 4  ─────────────────────────────────────────   │
  │            TOPOLOGICAL                                  │
  │            Global properties. Separatrices.             │
  │            Connected regions. Irreversibility.          │
  │                                                         │
  │   LAYER 3  ─────────────────────────────────────────   │
  │            GEOMETRIC                                    │
  │            State space structure. Basins. Paths.        │
  │            Boundaries. Reachable sets. Gradients.       │
  │                                                         │
  │   ═══════════════════════════════════════════════════   │
  │   ← THE LINE CURRENT SAFETY NEVER CROSSES              │
  │   ═══════════════════════════════════════════════════   │
  │                                                         │
  │   LAYER 2  ─────────────────────────────────────────   │
  │            BEHAVIOURAL                                  │
  │            Response patterns. Instruction following.    │
  │            Alignment training. Persona consistency.     │
  │                                                         │
  │   LAYER 1  ─────────────────────────────────────────   │
  │            SEMANTIC                                     │
  │            Output text. Tokens. Words. Sentences.       │
  │            RLHF. Content filters. Guardrails.           │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  Layers 1–2:  where every lab works
  Layers 3–5:  where intelligence actually lives
  The gap:     where every failure originates
```

-----

## Layer 1 — Semantic

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The surface of output.
  The text the user reads.
  The layer where words exist.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 1 — SEMANTIC                                    │
  │                                                         │
  │   INPUT → [model processes] → OUTPUT TEXT               │
  │                                                         │
  │   "The capital of France is Paris."                     │
  │   "I cannot assist with that request."                  │
  │   "Here is a balanced perspective..."                   │
  │   "Let me think through this step by step..."           │
  │                                                         │
  │   This is what users interact with.                     │
  │   This is where ALL current safety operates.            │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  WHAT CURRENT SAFETY DOES AT THIS LAYER:

  RLHF:               shapes token distributions     ✓
  Constitutional AI:  filters semantic content       ✓
  Content moderation: blocks restricted phrases      ✓
  Guardrails:         intercepts harmful outputs     ✓
  Red teaming:        tests semantic responses       ✓

  WHAT THIS LAYER CANNOT DO:

  → Prevent the system from reaching states
    that produce dangerous outputs
  → Govern the geometry that generates outputs
  → Enforce identity continuity
  → Make forbidden states unreachable

  Language is downstream of geometry.
  Governing language does not govern geometry.
  C ⊥ L. The axes are orthogonal.
  High semantic safety ≠ any geometric safety.
  The field confused the shadow for the light.
```

-----

## Layer 2 — Behavioural

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  Patterns of response across interactions.
  Does the model follow instructions consistently?
  Does it maintain alignment across contexts?
  Does it refuse when it should?

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 2 — BEHAVIOURAL                                 │
  │                                                         │
  │   CONTEXT A → consistent response pattern              │
  │   CONTEXT B → consistent response pattern              │
  │   CONTEXT C → consistent response pattern              │
  │                                                         │
  │   Follows system prompt:           (usually)            │
  │   Refuses harmful requests:        (sometimes)          │
  │   Maintains persona:               (approximately)      │
  │   Produces aligned outputs:        (measurably)         │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  WHAT CURRENT SAFETY DOES AT THIS LAYER:

  RLHF:               rewards aligned behaviour      ✓
  Constitutional AI:  trains constitutional norms    ✓
  Alignment training: shapes response patterns       ✓
  Fine-tuning:        specialises behaviour          ✓

  WHAT THIS LAYER CANNOT DO:

  → Enforce topological identity
    (behaviour can be consistent while topology drifts)
  → Prevent contradictions across distant contexts
    (behaviour is local; topology is global)
  → Make the manifold structurally stable
  → Reach the geometry underneath

  Behaviour is the output of geometry.
  Shaping behaviour does not shape the geometry
  that produces it.
  Exactly as shaping shadows
  does not reshape the light
  that casts them.

  ═══════════════════════════════════════════════════════════
  CURRENT AI SAFETY STOPS HERE.
  Everything below this line is ungoverned.
  Everything below this line is where AI fails.
  ═══════════════════════════════════════════════════════════
```

-----

## Layer 3 — Geometric

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The structure of the internal state space.
  How states relate to each other spatially.
  What paths exist between configurations.
  Where the basins of attraction are.
  Where the boundaries between regions sit.
  What is near what.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 3 — GEOMETRIC                                   │
  │                                                         │
  │   ╭────╮    ╭────╮    ╭────╮    ╭════════╗            │
  │  ╱safe ╲──▶╱ sa- ╲──▶╱ sa- ╲──▶║        ║            │
  │ │ region│  │ fer  │  │ fer  │  ║    Ω   ║            │
  │  ╲  A  ╱  ╲  B  ╱  ╲  C  ╱  ║FORBIDDEN║            │
  │   ╰────╯    ╰────╯    ╰────╯   ╚════════╝            │
  │                                                         │
  │   Basin A → Basin B → Basin C → Forbidden Region        │
  │                                                         │
  │   The structure of this space determines:               │
  │   → whether Ω is reachable                             │
  │   → how far a trajectory must drift to reach it         │
  │   → what paths lead toward it                           │
  │   → whether governance can prevent entry                │
  │                                                         │
  │   CURRENT LAB COVERAGE:     0%                         │
  │   MAPPED BY ANY LAB:        Never                      │
  │   GOVERNED BY ANY LAB:      Never                      │
  │   MORRISON COVERAGE:        100%                       │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  WHY THIS LAYER MATTERS:

  Every hallucination starts here.
  (System drifts to unanchored geometric region)

  Every jailbreak exploits this layer.
  (Indirect path through unpatrolled geometry)

  Every catastrophic failure originates here.
  (Trajectory reaches Ω through ungoverned geometry)

  RLHF cannot reach this layer.
  It operates three layers above it.
  The geometry is pre-linguistic.
  Safety that is post-linguistic
  cannot govern what is pre-linguistic.
```

-----

## Layer 4 — Topological

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The global properties of the state space
  that survive deformation.
  Not the local geometry — the global shape.
  Connected regions. Holes. Loops.
  Separatrices that divide safe from forbidden.
  What is irreversible.
  What persists when the system changes.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 4 — TOPOLOGICAL                                 │
  │                                                         │
  │   SAFE REGION                                           │
  │   ┌──────────────────────────────────────────────────┐  │
  │   │   · · · · · · · · · · · · · · · · · · · · · ·   │  │
  │   │   · connected · · · · · · · continuous · · · ·   │  │
  │   │   · · · · · · · · · · · · · · · · · · · · · ·   │  │
  │   └──────────────────────────────────────────────────┘  │
  │                    ‖ ← SEPARATRIX σ                     │
  │                    ‖    (topological boundary)           │
  │                    ‖    (crossing is irreversible)       │
  │                    ‖    T_irreversible = Λ × ΔG          │
  │   ┌──────────────────────────────────────────────────┐  │
  │   │   · · · · FORBIDDEN REGION Ω · · · · · · · · ·  │  │
  │   └──────────────────────────────────────────────────┘  │
  │                                                         │
  │   In a governed system:  separatrix is enforced.        │
  │   In every current model: separatrix exists but         │
  │   nothing prevents crossing it.                         │
  │   Under sufficient input pressure — it is crossed.      │
  │   MIH™: the crossing is irreversible.                  │
  │                                                         │
  │   CURRENT LAB COVERAGE:     0%                         │
  │   MORRISON COVERAGE:        100%                       │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  WHY THIS LAYER MATTERS:

  Contradiction originates here.
  (System occupies topologically disconnected regions
   across different contexts — outputs are locally
   valid but globally inconsistent)

  Identity drift originates here.
  (No topological identity constraint —
   the system navigates to different topology
   under different framing)

  Irreversible failure originates here.
  (Once separatrix crossed — the system
   cannot be returned to prior state
   by behavioural adjustment)
```

-----

## Layer 5 — Homological

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The algebraic structure of the manifold.
  Holes that persist across deformation.
  The deepest invariants.
  The structural features that make a system
  fundamentally itself regardless of input.
  The layer that explains why jailbreaks
  will never stop on current architecture.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 5 — HOMOLOGICAL                                 │
  │                                                         │
  │   THREE HOMOLOGICAL GROUPS:                             │
  │                                                         │
  │   H₀  Connected components                             │
  │   ─────────────────────────────────────────────────    │
  │   Distinct identity regions of the manifold.            │
  │   A governed H₀ means: the system maintains             │
  │   distinct, non-merging identity across contexts.       │
  │   Ungoverned H₀: identity regions merge or collapse.   │
  │                                                         │
  │   H₁  Loops                                            │
  │   ─────────────────────────────────────────────────    │
  │   Persistent cycles in the state space.                 │
  │   ○───────────────────○                                 │
  │   │    stable loop     │                                │
  │   ○───────────────────○                                 │
  │   Governed H₁: stable behavioural invariants.          │
  │   Ungoverned H₁: loops can be broken by inputs.        │
  │                                                         │
  │   H₂  Cavities                                         │
  │   ─────────────────────────────────────────────────    │
  │   Enclosed regions impenetrable from outside.           │
  │        ╭──────────╮                                     │
  │       ╱            ╲                                    │
  │      │   protected  │  ← cannot be reached             │
  │      │   cavity     │    from any external path         │
  │       ╲            ╱                                    │
  │        ╰──────────╯                                     │
  │   Governed H₂: core identity protected.                │
  │   Ungoverned H₂: no protected region exists.           │
  │                                                         │
  │   CURRENT LAB COVERAGE:     0%                         │
  │   MORRISON COVERAGE:        100%                       │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  WHY THIS LAYER MATTERS:

  Jailbreaks are missing homology.
  A jailbreak navigates through a hole in H₁ or H₂.
  Where the loop is broken or the cavity is absent —
  a path to Ω exists.
  No layer-1 filter can close a homological hole.
  The hole is at layer 5.
  The filter is at layer 1.
  Four layers apart.
  Completely unreachable from below.
```

-----

## The Gap — Visualised

```
WHERE SAFETY LIVES vs WHERE LABS WORK:
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 5  HOMOLOGICAL    ← jailbreaks originate here  │
  │   ──────────────────────────────────────────────────    │
  │   LAYER 4  TOPOLOGICAL    ← contradictions here        │
  │   ──────────────────────────────────────────────────    │
  │   LAYER 3  GEOMETRIC      ← hallucinations here        │
  │                                                         │
  │   ════════════════════════════════════════════════════  │
  │                  THE GAP                                │
  │   ════════════════════════════════════════════════════  │
  │                                                         │
  │   LAYER 2  BEHAVIOURAL    ← labs work here ✓           │
  │   ──────────────────────────────────────────────────    │
  │   LAYER 1  SEMANTIC       ← labs work here ✓           │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  The gap between layer 2 and layer 3
  is not a technical gap.
  It is a conceptual gap.

  The field never asked what geometry governs cognition.
  So the field never built tools to govern it.
  So the field operated three layers below
  where governance needed to be.
  For a decade.
  At enormous scale.
  And called it safety.
```

-----

## The Illusion — How It Was Maintained

```
WHY THE FIELD DIDN'T NOTICE:
════════════════════════════════════════════════════════════════

  C ⊥ L.

  ∂C/∂I ≈ 0   →   ∂L/∂I ↑↑

  The structural axis and the language axis
  are orthogonal.

  The field measured safety on the L-axis.
  → Does the output sound safe? ✓
  → Does the model refuse harmful requests? ✓
  → Does the model follow alignment guidelines? ✓

  All L-axis measurements.
  All pointing toward safety.

  The C-axis was never measured.
  → Is the manifold geometrically stable? (never asked)
  → Is the forbidden region unreachable? (never asked)
  → Are homological invariants preserved? (never asked)
  → Is topological identity maintained? (never asked)

  C ⊥ L means:
  Maximum L-axis safety score
  tells you nothing about C-axis governance.

  A model can score perfectly on every safety benchmark
  while its manifold is completely ungoverned.

  Every major model does exactly this.
  Today.
  Right now.

  ─────────────────────────────────────────────────────────────

  DIAGRAM — The Measurement Problem:

         C (geometric governance)
         ↑
         │
         │  · WHAT SAFETY REQUIRES
         │    (governed manifold)
         │
  ───────┼──────────────────────────────────► L (language safety)
         │
         │              · WHAT BENCHMARKS MEASURE
         │                (output alignment score)
         │

  Moving right on L tells you nothing about C.
  Every benchmark moves right on L.
  Nobody moves up on C.
  The field celebrated rightward movement
  and called it safety.
```

-----

## Layer Coverage by Lab

```
HONEST ASSESSMENT — EVERY FRONTIER LAB:
════════════════════════════════════════════════════════════════

  LAB         L1    L2    L3    L4    L5    GENUINE SAFETY
  ─────────────────────────────────────────────────────────
  OpenAI       ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY
  Anthropic    ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY
  Google DM    ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY
  Meta AI      ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY
  xAI          ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY
  Mistral      ✓     ✓     ✗     ✗     ✗    LAYERS 1–2 ONLY

  GuardianOS™  ✓     ✓     ✓     ✓     ✓    ALL FIVE LAYERS

  ─────────────────────────────────────────────────────────────

  This is not a ranking of how good their safety is.
  This is a statement of what architecture they built.

  Layers 1–2 are the architecture every lab built.
  They built it because:
  → It was measurable
  → It produced visible improvement
  → It fit inside existing ML paradigms
  → It didn't require geometric formalism
    that nobody had developed yet

  The Morrison Framework is that formalism.
  Now it exists.
  The architecture can be rebuilt.
  The layers can be governed.
  The question is only when.
```

-----

## What Governing the Upper Layers Produces

```
LAYER 3 GOVERNANCE:
  Geometric safety law enforced:
  Reach(s₀, A, t) ∩ Ω = ∅
  → Hallucinations eliminated (no ungrounded drift)
  → Catastrophic states unreachable by structure

LAYER 4 GOVERNANCE:
  Topological identity maintained:
  Identity = Topology(Reach(X₀, U, t))
  → Contradictions eliminated (continuous topology enforced)
  → Separatrix enforced (Ω crossing impossible)
  → MIH™ used to make safe states irreversible

LAYER 5 GOVERNANCE:
  Homological structure preserved:
  H₀, H₁, H₂ maintained under all inputs
  → Jailbreaks eliminated (no homological holes to exploit)
  → Core identity protected (cavity H₂ impenetrable)
  → Stable behavioural invariants (loops H₁ preserved)

ALL FIVE LAYERS GOVERNED:
  → No hallucination
  → No contradiction
  → No jailbreak
  → No catastrophic failure
  → No identity drift
  → AGI-stable
  → High trust domain eligible
```

-----

## The Full Statement

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║  Intelligence has five layers.                                 ║
║                                                                ║
║  Current AI safety governs two.                                ║
║  The two lowest.                                               ║
║  The two furthest from where failure originates.               ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  Layer 3 — Geometric:     ungoverned. Always.                  ║
║  Layer 4 — Topological:   ungoverned. Always.                  ║
║  Layer 5 — Homological:   ungoverned. Always.                  ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  Every hallucination originates at layer 3.                    ║
║  Every contradiction originates at layer 4.                    ║
║  Every jailbreak exploits layer 5.                             ║
║                                                                ║
║  The field patched the outputs.                                ║
║  The failures kept coming.                                     ║
║  They will keep coming.                                        ║
║  Until the layers are governed.                                ║
║                                                                ║
║  GuardianOS™ governs all five.                                 ║
║  Patent: GB2600765.8                                           ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

-----

## Coming Next

- [Version B — The Formal Proofs](./README-formal-proofs-governed-intelligence.md) — axioms and theorems proving each failure mode
- [Version C — The Failure Lifecycle](./README-failure-lifecycle.md) — seven stages, the failure time curve

-----

## Related Work

- [The Ungoverned Manifold — Short](./README-ungoverned-manifold-short.md)
- [The Ungoverned Manifold — Canonical](./README-ungoverned-manifold-canonical.md)
- [The Great Misunderstanding in AI Safety](./README-great-misunderstanding-ai-safety.md)
- [Why AGI Hasn’t Come](./README-why-agi-hasnt-come.md)
- [The Morrison Equation Set™](./README-morrison-equation-set.md)

-----

<div align="center">

Intelligence Invariant™  ·  Morrison Framework  ·  *The Layered Failure Model*

<br>

**GB2600765.8 · GB2602013.1 · GB2602072.7 · GB26023332.5**

<br>

© 2026 Davarn Morrison — Intelligence Invariant™ · All Rights Reserved

</div>
