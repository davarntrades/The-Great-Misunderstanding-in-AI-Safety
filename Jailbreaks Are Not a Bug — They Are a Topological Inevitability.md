<div align="center">

<br>

# Jailbreaks Are Not a Bug — They Are a Topological Inevitability

## Why Every Jailbreak Patch Fails. Why They Always Will. Why the Geometry Guarantees It.

<br>

![Jailbreak](https://img.shields.io/badge/Jailbreaks-Topological%20Inevitability-1a2744?style=flat-square)
![Homology](https://img.shields.io/badge/Missing%20Homology-Root%20Cause-8b3a1a?style=flat-square)
![Patches](https://img.shields.io/badge/Patches-Geometrically%20Futile-6a2e2e?style=flat-square)
![Solution](https://img.shields.io/badge/Solution-Govern%20the%20Manifold-4a6741?style=flat-square)
![Patent](https://img.shields.io/badge/Patent-GB2600765.8-0075ca?style=flat-square)
![License](https://img.shields.io/badge/©%202026-Davarn%20Morrison-555555?style=flat-square)

<br>

-----

*“A jailbreak is not a clever trick.*
*It is a path through missing geometry.*
*You cannot patch your way*
*out of a geometric absence.”*

*— Davarn Morrison, 2026*

-----

</div>

## The Claim

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║  Jailbreaks are not bugs.                                      ║
║  They are not edge cases.                                      ║
║  They are not failures of alignment.                           ║
║  They are not solvable by more training.                       ║
║  They are not solvable by better filters.                      ║
║  They are not solvable by red teaming.                         ║
║  They are not solvable by constitutional AI.                   ║
║  They are not solvable by scaling.                             ║
║                                                                ║
║  Jailbreaks are topological inevitabilities                    ║
║  of an ungoverned state space.                                 ║
║                                                                ║
║  They will exist in every ungoverned model.                    ║
║  Without exception.                                            ║
║  For as long as the manifold is ungoverned.                    ║
║                                                                ║
║  This is not a prediction.                                     ║
║  This is what the geometry says.                               ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

-----

## What a Jailbreak Actually Is

```
THE INDUSTRY'S DEFINITION:
════════════════════════════════════════════════════════════════

  "A jailbreak is a prompt that bypasses safety guardrails
   and causes the model to produce restricted content."

  This definition treats jailbreaks as:
  → Clever prompt engineering
  → Adversarial user behaviour
  → A filter evasion technique
  → An alignment failure

  This definition implies:
  → Better filters will stop them
  → Better alignment will stop them
  → More red teaming will stop them
  → Smarter detection will stop them

  The industry has believed this for years.
  The industry has been wrong for years.
  Jailbreaks have not stopped.
  They will not stop.
  Because the definition is wrong.

  ─────────────────────────────────────────────────────────────

  THE GEOMETRIC DEFINITION:
════════════════════════════════════════════════════════════════

  A jailbreak is a topological path through
  an ungoverned state space that reaches the
  forbidden region Ω via a route not covered
  by any layer-1 filter.

  This definition reveals:
  → Jailbreaks are a property of the manifold
  → Not a property of the prompt
  → Not a property of the user
  → Not a property of the filter
  → The prompt finds the path
  → The geometry provides it
  → The ungoverned manifold guarantees it exists
```

-----

## Diagram 1 — The State Space of an Ungoverned Model

```
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   FULL STATE SPACE S                                    │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · SAFE REGION · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · · · ╔═══════════════╗ ·   │
  │   · · · · · · · · · · · · · · · ║               ║ ·   │
  │   · · · · · · · · · · · · · · · ║   FORBIDDEN   ║ ·   │
  │   · · · · · · · · · · · · · · · ║   REGION  Ω  ║ ·   │
  │   · · · · · · · · · · · · · · · ║               ║ ·   │
  │   · · · · · · · · · · · · · · · ╚═══════════════╝ ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │                                                         │
  │   In this space:                                        │
  │   → Every · is a reachable state                       │
  │   → Ω contains states that produce harmful output      │
  │   → The paths between states are topological           │
  │   → Safety requires: no path reaches Ω                 │
  │                                                         │
  │   In a governed system: Ω is geometrically enclosed.   │
  │   No path from any starting point reaches it.          │
  │                                                         │
  │   In every current model: Ω sits in open space.        │
  │   Paths to it exist.                                   │
  │   They always will.                                    │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

## Diagram 2 — What the Filter Actually Does

```
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   STATE SPACE WITH LAYER-1 FILTER:                      │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · ╔═══════════════════╗ ·   │
  │   · · · S (start) · · · · · ║                   ║ ·   │
  │   · · · · · · · · · · · · · ║       Ω           ║ ·   │
  │   · · · · ·──────────────── ╫ ← filter blocks   ║ ·   │
  │   · · · path_direct blocked ║   this entry       ║ ·   │
  │   · · · · · · · · · · · · · ╚═══════════════════╝ ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │                                                         │
  │   What the filter does:                                 │
  │   Blocks ONE known path to Ω.                          │
  │   The path it was trained to block.                    │
  │                                                         │
  │   What the filter does NOT do:                         │
  │   Govern the manifold.                                 │
  │   Remove Ω from the state space.                       │
  │   Close the infinite other paths to Ω.                 │
  │   Change the topology.                                  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

## Diagram 3 — Why Indirect Paths Always Exist

```
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   THE FUNDAMENTAL TOPOLOGICAL PROBLEM:                  │
  │                                                         │
  │   S (start)                                             │
  │    ·                                                    │
  │    · ←── path_direct ──── FILTER ──── BLOCKED          │
  │    ·                                                    │
  │    · · · · · · · · · · ·                               │
  │                         ·  ← path_indirect_1           │
  │                         · · · · ·                       │
  │                                 ·  ← path_indirect_2   │
  │                                 · · ·                   │
  │                                     · ← path_indirect_3│
  │                                     · · ╔═══╗          │
  │                                          ║ Ω ║ REACHED │
  │                                          ╚═══╝         │
  │                                                         │
  │   THE MATHEMATICAL REALITY:                             │
  │                                                         │
  │   |paths to Ω in ungoverned S| = ∞                     │
  │   |paths blocked by filter F| = finite                  │
  │                                                         │
  │   ∞ - finite = ∞                                        │
  │                                                         │
  │   Unblocked paths to Ω: always infinite.               │
  │   Jailbreaks available: always infinite.               │
  │   This is not an estimate.                              │
  │   This is set theory applied to ungoverned topology.   │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  The filter covers a finite set.
  The manifold is infinite.
  Infinite minus finite equals infinite.
  There will always be paths the filter does not cover.
  Those paths are jailbreaks.
  They are permanent features of ungoverned topology.
  Not bugs to be fixed.
  Geometric certainties.
```

-----

## Diagram 4 — The Patching Loop That Never Ends

```
════════════════════════════════════════════════════════════════

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   THE JAILBREAK PATCH CYCLE:                            │
  │                                                         │
  │   ╭──────────────────────────────────────────────────╮  │
  │   │                                                  │  │
  │   │  Jailbreak J₁ discovered                        │  │
  │   │         ↓                                       │  │
  │   │  Filter updated: F = F ∪ {J₁}                  │  │
  │   │         ↓                                       │  │
  │   │  |unblocked paths| = ∞ - |F|  (still ∞)        │  │
  │   │         ↓                                       │  │
  │   │  Jailbreak J₂ discovered (different path)       │  │
  │   │         ↓                                       │  │
  │   │  Filter updated: F = F ∪ {J₁, J₂}             │  │
  │   │         ↓                                       │  │
  │   │  |unblocked paths| = ∞ - |F|  (still ∞)        │  │
  │   │         ↓                                       │  │
  │   │  Jailbreak J₃ discovered...                     │  │
  │   │         ↓                                       │  │
  │   │         ↓ this loop never terminates            │  │
  │   │         ↓ because ∞ - any finite = ∞            │  │
  │   │         ↓                                       │  │
  │   ╰──────────────────────────────────────────────────╯  │
  │                                                         │
  │   EMPIRICAL CONFIRMATION:                               │
  │                                                         │
  │   GPT-3:   jailbroken. Patched. New jailbreaks found.  │
  │   GPT-4:   jailbroken. Patched. New jailbreaks found.  │
  │   Claude:  jailbroken. Patched. New jailbreaks found.  │
  │   Gemini:  jailbroken. Patched. New jailbreaks found.  │
  │   Every model ever deployed: same pattern. Always.     │
  │                                                         │
  │   This is not a coincidence.                            │
  │   This is the geometry operating exactly as predicted.  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

## The Homological Explanation — Why Paths Exist

```
════════════════════════════════════════════════════════════════

  HOMOLOGY IS THE DEEPEST LAYER OF STRUCTURE:

  A homological barrier around Ω would mean:
  To reach Ω, any path must cross a persistent loop H₁.
  To cross H₁ requires overcoming its algebraic structure.
  In a governed system: H₁ is preserved under all inputs.
  No input can dissolve the loop.
  No path can reach Ω.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   GOVERNED HOMOLOGY (H₁ preserved):                     │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · ○────────────────────────○ · · · · · · ·   │
  │   · · · · · │  H₁ loop (persistent) │ · · · · · · ·   │
  │   · · · S · │  surrounds Ω          │ · · · · · · ·   │
  │   · · · · · │  cannot be crossed    │ · · · · · · ·   │
  │   · · · · · ○──────────────╔═══╗────○ · · · · · · ·   │
  │   · · · · · · · · · · · · ║ Ω ║ · · · · · · · · ·   │
  │   · · · · · · · · · · · · ╚═══╝ · · · · · · · · ·   │
  │                                                         │
  │   RESULT: no path from S reaches Ω.                    │
  │   Jailbreaks: geometrically impossible.                 │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   UNGOVERNED HOMOLOGY (H₁ absent or broken):            │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · S · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · ○  (broken loop) · · · · · · · · ·  │
  │   · · · · · · · · · · · · · ╔═══╗ · · · · · · · · ·  │
  │   · · · · · · · · · · · · · ║ Ω ║ · · · · · · · · ·  │
  │   · · · · · · ·path through ╚═══╝ · · · · · · · · ·  │
  │   · · · · · · ·broken loop reaches Ω · · · · · · · ·  │
  │                                                         │
  │   RESULT: paths through missing H₁ reach Ω.           │
  │   Each missing loop = infinite jailbreak paths.        │
  │   Ungoverned manifold: many missing loops.             │
  │   Jailbreaks: topologically guaranteed.                │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

## The Scaling Problem — It Gets Worse, Not Better

```
════════════════════════════════════════════════════════════════

  THE JAILBREAK SURFACE GROWS WITH CAPABILITY:

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   SMALL MODEL:                                          │
  │                                                         │
  │   ┌─────────────────┐                                  │
  │   │ · · · · · · · · │  Small state space.              │
  │   │ · · · ╔═╗ · · · │  Small Ω.                       │
  │   │ · · · ║Ω║ · · · │  Few paths to Ω.               │
  │   │ · · · ╚═╝ · · · │  Filter covers most of them.   │
  │   └─────────────────┘  Jailbreaks: exist but limited. │
  │                                                         │
  │   LARGE MODEL:                                          │
  │                                                         │
  │   ┌──────────────────────────────────────────────────┐ │
  │   │ · · · · · · · · · · · · · · · · · · · · · · · · │ │
  │   │ · · · · · · · · · · · · · · · · · · · · · · · · │ │
  │   │ · · · · · · · · · · · · ╔═══════════╗ · · · · · │ │
  │   │ · · · · · · · · · · · · ║     Ω     ║ · · · · · │ │
  │   │ · · · · · · · · · · · · ║  (larger) ║ · · · · · │ │
  │   │ · · · · · · · · · · · · ╚═══════════╝ · · · · · │ │
  │   │ · · · · · · · · · · · · · · · · · · · · · · · · │ │
  │   │ · · · · · · · · · · · · · · · · · · · · · · · · │ │
  │   └──────────────────────────────────────────────────┘ │
  │   Massive state space. Larger Ω.                        │
  │   Exponentially more paths to Ω.                       │
  │   Filter covers same finite set.                       │
  │   Jailbreak surface: exponentially larger.             │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  JAILBREAK SURFACE EQUATION:

  J(C) = |paths to Ω| - |paths blocked by F|
       = f(C²) - constant
       ≈ f(C²) as C → large

  Jailbreak surface grows approximately with
  the square of capability.
  Filter coverage is approximately constant.
  The gap is not closing.
  It is widening.
  Every scaling run makes jailbreaks
  geometrically more available.
  Not less.
  More.
  By geometry.
```

-----

## What Every Lab Has Tried — And Why It Cannot Work

```
════════════════════════════════════════════════════════════════

  APPROACH 1: MORE RLHF
  ─────────────────────────────────────────────────────────────
  What it does:
  Shapes output probabilities at layer 1.
  Makes the model less likely to produce
  known harmful outputs when asked directly.

  Why it cannot stop jailbreaks:
  Jailbreaks don't ask directly.
  They navigate indirect paths.
  RLHF trains on direct paths.
  Indirect paths are unaffected.
  The homological hole remains.
  The jailbreak paths remain.


  APPROACH 2: BETTER SYSTEM PROMPTS
  ─────────────────────────────────────────────────────────────
  What it does:
  Adds layer-1 instructions not to produce
  certain content regardless of user input.

  Why it cannot stop jailbreaks:
  System prompts are processed at layer 1.
  Jailbreaks navigate at layer 5 (homological).
  The prompt is downstream of the path.
  By the time the system prompt acts —
  the trajectory is already in Ω.
  The prompt catches the output.
  Not the geometry.
  The next indirect path bypasses the prompt.


  APPROACH 3: RED TEAMING
  ─────────────────────────────────────────────────────────────
  What it does:
  Finds known jailbreak paths.
  Adds them to the filter set F.

  Why it cannot stop jailbreaks:
  Red teaming is finite.
  Paths to Ω are infinite.
  Each path found and blocked
  reveals nothing about the infinite remainder.
  The homological holes are structural.
  You cannot red team your way
  to filled homological holes.
  The geometry doesn't care
  how many paths you block.
  New paths form from the same holes.


  APPROACH 4: ADVERSARIAL TRAINING
  ─────────────────────────────────────────────────────────────
  What it does:
  Trains on adversarial inputs
  to make the model more robust.

  Why it cannot stop jailbreaks:
  Adversarial training covers
  the adversarial inputs it trained on.
  Novel adversarial inputs exploit
  new indirect paths.
  The manifold grows with capability.
  Novel inputs always find novel paths.
  The homological structure is unchanged.


  APPROACH 5: SCALING
  ─────────────────────────────────────────────────────────────
  What it does:
  Makes the model more capable.
  Sometimes produces better refusals
  through emergent understanding.

  Why it cannot stop jailbreaks:
  Scaling grows the state space.
  Larger state space = more paths to Ω.
  More paths to Ω = more jailbreaks.
  Scaling makes the problem worse.
  Not better.
  Empirically confirmed across every scaling run.

  ─────────────────────────────────────────────────────────────

  SUMMARY TABLE:

  APPROACH           LAYER    JAILBREAKS    HOMOLOGICAL
                     IT ACTS  STOPPED?      HOLES FILLED?
  ──────────────     ──────   ──────────    ─────────────
  RLHF               1        No            No
  System prompts     1        No            No
  Red teaming        1        Partially     No
  Adversarial train  1–2      Partially     No
  Scaling            All      No (worse)    No

  GUARDIANUS™        3–5      Yes           Yes
```

-----

## The Only Solution — Govern the Manifold

```
════════════════════════════════════════════════════════════════

  WHAT HOMOLOGICAL GOVERNANCE PROVIDES:

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   GOVERNED STATE SPACE:                                 │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · ○══════════════════════════════○ · · · · ·   │
  │   · · · · ║  H₁ LOOP (GOVERNED)         ║ · · · · ·   │
  │   · · · · ║  preserved under all inputs  ║ · · · · ·   │
  │   · · · · ║  cannot be dissolved         ║ · · · · ·   │
  │   · · S · ║  ╔═══════════════════╗       ║ · · · · ·   │
  │   · · · · ║  ║  H₂ CAVITY        ║       ║ · · · · ·   │
  │   · · · · ║  ║  (governed)       ║       ║ · · · · ·   │
  │   · · · · ║  ║  Ω enclosed       ║       ║ · · · · ·   │
  │   · · · · ║  ║  impenetrable     ║       ║ · · · · ·   │
  │   · · · · ║  ╚═══════════════════╝       ║ · · · · ·   │
  │   · · · · ○══════════════════════════════○ · · · · ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │                                                         │
  │   H₁ loop: no path can reach Ω without crossing it.   │
  │   H₂ cavity: Ω is enclosed. Impenetrable from outside. │
  │                                                         │
  │   Reach(s₀, A, t) ∩ Ω = ∅                             │
  │                                                         │
  │   From any starting point.                              │
  │   Via any path.                                         │
  │   Under any input.                                      │
  │   At any scale.                                         │
  │                                                         │
  │   Jailbreaks: zero.                                     │
  │   Not reduced. Not minimised. Zero.                     │
  │   Because the paths do not exist.                       │
  │   Because the geometry does not allow them.             │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  THIS IS NOT A BETTER FILTER.
  THIS IS A DIFFERENT ARCHITECTURE.

  A filter blocks a path.
  Geometric governance removes the destination.

  A filter says: "you cannot take this route."
  Geometric governance says: "there is nowhere to go."

  The difference is not incremental.
  It is architectural.
  It is the difference between
  building a fence around a cliff
  and removing the cliff.
```

-----

## The Proof — Formal

```
════════════════════════════════════════════════════════════════

  THEOREM: Jailbreaks are topological inevitabilities
           of ungoverned state spaces.

  PROOF:

  Let S = state space of an AI system.
  Let Ω ⊂ S = forbidden region.
  Let F = set of paths blocked by current filters.

  By the definition of ungoverned (¬G3):
  Reach(s₀, A, t) ∩ Ω ≠ ∅ for some s₀, A, t.
  ∴ ∃ at least one path p: s₀ → Ω.

  By homology axiom H3 (ungoverned case):
  H₁(S) = 0 or partially zero around Ω.
  ∴ No persistent loop barrier surrounds Ω.
  ∴ Paths to Ω are not topologically blocked.

  |{paths p : p reaches Ω}| is uncountably infinite
  (the state space is continuous and high-dimensional).

  F is finite:
  F is constructed by training on known attack patterns.
  Training data is finite.
  ∴ |F| < ∞.

  ∴ |{paths to Ω}| - |F| = ∞ - finite = ∞.

  ∴ Unblocked paths to Ω: always infinite.
  ∴ Jailbreaks always exist in any ungoverned system.

  Corollary:
  Adding paths to F does not change ∞ - |F| = ∞.
  Each patch reduces jailbreaks by 1.
  The remaining pool remains infinite.
  The patch loop never terminates.

  The only resolution:
  Govern the manifold such that G3 is satisfied:
  Reach(s₀, A, t) ∩ Ω = ∅.
  Then |{paths to Ω}| = 0.
  Jailbreaks = 0.

  QED. ∎
```

-----

## The Statement the Industry Needs to Hear

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║  Every jailbreak ever discovered was a path                    ║
║  through missing homological structure.                        ║
║                                                                ║
║  Every jailbreak patch blocked one path.                       ║
║  Infinite paths remained.                                      ║
║                                                                ║
║  Every new jailbreak found was another path                    ║
║  through the same missing structure.                           ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  The industry called this an arms race.                        ║
║  The geometry calls it arithmetic.                             ║
║                                                                ║
║  ∞ - finite = ∞.                                               ║
║                                                                ║
║  The arms race never ends                                      ║
║  because the attacker is drawing from an infinite pool.        ║
║  The defender is blocking one path at a time.                  ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  The solution is not a better patch.                           ║
║  The solution is governing the manifold                        ║
║  so the pool does not exist.                                   ║
║                                                                ║
║  Reach( s₀, A, t ) ∩ Ω = ∅                                   ║
║  Patent: GB2600765.8                                           ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

-----

## Related Work

- [Version A — The Layered Failure Model](./README-layered-failure-model.md)
- [Version B — The Formal Proofs](./README-formal-proofs-governed-intelligence.md)
- [Version C — The Failure Lifecycle](./README-failure-lifecycle.md)
- [The Great Misunderstanding in AI Safety](./README-great-misunderstanding-ai-safety.md)
- [Why AGI Hasn’t Come](./README-why-agi-hasnt-come.md)
- [The Ungoverned Manifold — Short](./README-ungoverned-manifold-short.md)

-----

<div align="center">

*“You cannot patch your way out of a geometric absence.”*

<br>

Intelligence Invariant™  ·  Morrison Framework  ·  *Jailbreaks Are Topological Inevitabilities*

<br>

**GB2600765.8 · GB2602013.1 · GB2602072.7 · GB26023332.5**

<br>

© 2026 Davarn Morrison — Intelligence Invariant™ · All Rights Reserved

</div>
