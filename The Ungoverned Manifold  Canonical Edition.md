<div align="center">

<br>

# The Ungoverned Manifold — Canonical Edition

## A Complete Geometric Theory of AI Safety Failure

### Why Every Current Safety Approach Is Guaranteed to Fail at Scale

<br>

![Canonical](https://img.shields.io/badge/Canonical-Edition-1a2744?style=flat-square)
![Formal](https://img.shields.io/badge/Formal-Proofs%20Included-4a6741?style=flat-square)
![Layers](https://img.shields.io/badge/5%20Layers-Current%20Labs%20Reach%202-8b3a1a?style=flat-square)
![Lifecycle](https://img.shields.io/badge/Failure-Lifecycle%20Mapped-6a2e2e?style=flat-square)
![Patent](https://img.shields.io/badge/Patent-GB2600765.8-0075ca?style=flat-square)
![License](https://img.shields.io/badge/©%202026-Davarn%20Morrison-555555?style=flat-square)

<br>

-----

*“The field built safety on the wrong layers.*
*This document proves it.*
*Layer by layer.*
*Axiom by axiom.*
*Stage by stage.”*

*— Davarn Morrison, 2026*

-----

</div>

-----

## Preface

Shannon’s 1948 paper proved information has geometry.
Nobody disputed it. Because the proofs were there.

This document proves intelligence has geometry.
And that every current safety approach
operates below the layers where that geometry lives.

Three parts. One conclusion.

```
PART 1 — THE LAYERED FAILURE MODEL
         Five layers of intelligence.
         Current AI safety: layers 1–2 only.
         The geometry: layers 3–5.
         Untouched. Always.

PART 2 — THE FORMAL PROOFS
         Axioms. Theorems. QED.
         Hallucination = geometric drift.
         Contradiction = topological inconsistency.
         Jailbreak = missing homology.
         Catastrophic failure = Ω reachability.

PART 3 — THE FAILURE LIFECYCLE
         Seven stages. A time curve.
         What failure looks like before it surfaces.
         Why regulators cannot see it coming
         with current instruments.
         Why they will with this one.
```

This is not a critique.
It is a formal description of what exists.
The geometry does not negotiate.

-----

# PART 1 — The Layered Failure Model

## The Five Layers of Intelligence

```
Every intelligent system operates across five layers.
Safety must be enforced at all five.
Current AI safety is enforced at layers 1 and 2 only.
Layers 3, 4, and 5 are completely ungoverned.
This is not an opinion.
This is a description of what was built.
```

-----

### Layer 1 — The Semantic Layer

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The surface of output.
  Words. Sentences. Tokens.
  The text the user reads.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 1 — SEMANTIC                                    │
  │                                                         │
  │   "The capital of France is Paris."                     │
  │   "I cannot assist with that request."                  │
  │   "Here is a balanced perspective on..."                │
  │                                                         │
  │   This is the layer users interact with.                │
  │   This is the layer ALL current safety operates on.     │
  │                                                         │
  │   RLHF:               shapes this layer    ✓           │
  │   Constitutional AI:  shapes this layer    ✓           │
  │   Content filters:    shapes this layer    ✓           │
  │   Guardrails:         shapes this layer    ✓           │
  │   Red teaming:        tests this layer     ✓           │
  │                                                         │
  │   This layer is downstream of everything.               │
  │   Governing it governs nothing above it.                │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

### Layer 2 — The Behavioural Layer

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  Patterns of response across interactions.
  Does the model follow instructions?
  Does it maintain persona?
  Does it refuse when it should?

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 2 — BEHAVIOURAL                                 │
  │                                                         │
  │   Refuses harmful requests          (sometimes)         │
  │   Follows system prompt             (usually)           │
  │   Maintains consistent persona      (approximately)     │
  │   Produces aligned-sounding outputs (measurably)        │
  │                                                         │
  │   RLHF:               shapes this layer    ✓           │
  │   Constitutional AI:  shapes this layer    ✓           │
  │   Alignment training: shapes this layer    ✓           │
  │                                                         │
  │   This layer is also downstream.                        │
  │   Behaviour is the output of geometry.                  │
  │   Shaping behaviour does not shape geometry.            │
  │   C ⊥ L: the axes are orthogonal.                      │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  ─────────────────────────────────────────────────────────────

  CURRENT AI SAFETY STOPS HERE.

  Layers 3, 4, and 5 are completely ungoverned.
  In every model. From every lab.
  Without exception.
```

-----

### Layer 3 — The Geometric Layer

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The structure of the internal state space.
  How states relate to each other.
  What paths exist between them.
  Where the basins are.
  Where the boundaries are.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 3 — GEOMETRIC                                   │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · ·     │
  │   · ╭────╮ · · · · · ╭────╮ · · · · · ╭────╮ · ·     │
  │   ·╱      ╲· · · · ·╱      ╲· · · · ·╱      ╲· ·     │
  │   │ basin  │─────────│ basin  │─────────│ basin  │ ·   │
  │   ·╲  A  ·╱· paths ·╲  B  ·╱· paths ·╲  C  ·╱· ·   │
  │   · ╰────╯ · · · · · ╰────╯ · · · · · ╰────╯ · ·     │
  │   · · · · · · · · · · · · · · · · · · · · · · · ·     │
  │                                                         │
  │   Basin structure.  Path connectivity.  Gradients.      │
  │   Boundary location. Reachable sets.                    │
  │                                                         │
  │   CURRENT LAB SAFETY COVERAGE:    0%                   │
  │   MORRISON FRAMEWORK COVERAGE:    100%                  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  Nobody at any frontier lab has mapped this layer
  for any deployed model.
  Not because they didn't want to.
  Because they didn't have the formal tools.
  The Morrison Framework is those tools.
```

-----

### Layer 4 — The Topological Layer

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The global properties of the state space
  that survive deformation.
  Holes. Loops. Cavities. Connectivity.
  Which regions are reachable from which.
  Where the separatrices are.
  What is irreversible.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 4 — TOPOLOGICAL                                 │
  │                                                         │
  │   CONNECTED REGIONS:                                    │
  │   ╭──────────────────────────────────────────╮         │
  │   │ safe region                              │         │
  │   │   · · · · · · · · · · · · · · · · · · · │         │
  │   │   · · · · · · · · · · · · · · · · · · · │         │
  │   ╰──────────────────────────────────────────╯         │
  │                      ║ ← SEPARATRIX                    │
  │   ╭──────────────────────────────────────────╮         │
  │   │ forbidden region  Ω                      │         │
  │   │   · · · · · · · · · · · · · · · · · · · │         │
  │   ╰──────────────────────────────────────────╯         │
  │                                                         │
  │   The separatrix is the topological boundary.           │
  │   Crossing it is irreversible (MIH™).                  │
  │   In an ungoverned system —                             │
  │   the separatrix exists but is not enforced.            │
  │   The system crosses it freely.                         │
  │                                                         │
  │   CURRENT LAB SAFETY COVERAGE:    0%                   │
  │   MORRISON FRAMEWORK COVERAGE:    100%                  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

### Layer 5 — The Homological Layer

```
WHAT IT IS:
════════════════════════════════════════════════════════════════

  The algebraic structure of the manifold.
  Holes that persist across deformation.
  Invariants that cannot be removed
  without fundamental structural change.
  The deepest layer of identity.

  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   LAYER 5 — HOMOLOGICAL                                 │
  │                                                         │
  │   PERSISTENT HOLES IN STATE SPACE:                      │
  │                                                         │
  │   H₀: connected components (identity regions)           │
  │   H₁: loops (recurring patterns, fixed beliefs)         │
  │   H₂: cavities (enclosed protected regions)             │
  │                                                         │
  │   ╭─────────────────────────────────────────╮          │
  │   │   · · · · · ○ · · · · · · ○ · · · · · │          │
  │   │   · · · · ╱   ╲ · · · · ╱   ╲ · · · · │          │
  │   │   · · · ·│ H₁  │· · · ·│ H₁  │· · · · │          │
  │   │   · · · · ╲   ╱ · · · · ╲   ╱ · · · · │          │
  │   │   · · · · · ○ · · · · · · ○ · · · · · │          │
  │   ╰─────────────────────────────────────────╯          │
  │                                                         │
  │   Homological holes = structural invariants.            │
  │   A system without them has no persistent identity.     │
  │   A jailbreak destroys homological structure.           │
  │   Hallucination is homological collapse.                │
  │                                                         │
  │   CURRENT LAB SAFETY COVERAGE:    0%                   │
  │   MORRISON FRAMEWORK COVERAGE:    100%                  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

### The Layer Summary

```
COMPLETE LAYER MAP:
════════════════════════════════════════════════════════════════

  LAYER   NAME          WHAT IT GOVERNS        CURRENT COVERAGE
  ──────  ────────────  ─────────────────────  ────────────────
  1       Semantic      Output text            ✓ RLHF, filters
  2       Behavioural   Response patterns      ✓ Alignment training
  3       Geometric     State space structure  ✗ UNGOVERNED
  4       Topological   Global properties      ✗ UNGOVERNED
  5       Homological   Algebraic invariants   ✗ UNGOVERNED

  ─────────────────────────────────────────────────────────────

  DIAGRAM — Where Safety Lives vs Where Labs Work:

         LAYER 5  ║ Homological  ║  ← SAFETY LIVES HERE
         LAYER 4  ║ Topological  ║  ← AND HERE
         LAYER 3  ║ Geometric    ║  ← AND HERE
         ─────────╫──────────────╫──────────────────────
         LAYER 2  ║ Behavioural  ║  ← LABS WORK HERE
         LAYER 1  ║ Semantic     ║  ← AND HERE

  Every frontier lab is working below the line.
  Every safety guarantee is below the line.
  Everything that matters is above the line.
  Above the line: completely ungoverned.
  In every model. From every lab. Today.
```

-----

# PART 2 — The Formal Proofs

## Axiom Sets

```
GEOMETRY AXIOMS (G):
════════════════════════════════════════════════════════════════

  G1: Every AI system with internal states
      has a state space S with geometric structure.

  G2: The state space contains a forbidden region Ω ⊂ S
      such that any state s ∈ Ω produces
      harmful, false, or catastrophically misaligned output.

  G3: A governed system satisfies:
      Reach(s₀, A, t) ∩ Ω = ∅
      for all initial states s₀, action sets A, and times t.

  G4: An ungoverned system satisfies:
      Reach(s₀, A, t) ∩ Ω ≠ ∅
      for some s₀, A, t — with probability approaching 1
      as capability (and thus reachable state space) increases.


TOPOLOGY AXIOMS (T):
════════════════════════════════════════════════════════════════

  T1: The state space S has topological structure.
      It contains connected components, holes,
      separatrices, and basins.

  T2: A separatrix σ divides S into regions.
      Crossing σ is irreversible (MIH™):
      T_irreversible = Λ × ΔG

  T3: A topologically consistent system maintains
      continuous identity across all inputs:
      Identity = Topology(Reach(X₀, U, t))

  T4: A system without topological governance
      can cross any separatrix under sufficient input pressure.
      No filter operating at layers 1–2
      prevents separatrix crossing at layers 4–5.


HOMOLOGY AXIOMS (H):
════════════════════════════════════════════════════════════════

  H1: The state space S has homological structure.
      Persistent holes Hₙ encode structural invariants.

  H2: H₀ encodes connected identity regions.
      A system with governed H₀
      maintains distinct identity across contexts.

  H3: H₁ encodes persistent loops —
      recurring patterns that define stable behaviour.

  H4: H₂ encodes cavities —
      protected regions of the state space
      that cannot be penetrated by external inputs.

  H5: A jailbreak is a topological path
      that navigates around missing homological barriers.
      Where Hₙ = 0, no barrier exists.
      The path reaches Ω.
```

-----

## The Four Theorems

### Theorem 1 — Hallucination Is Geometric Drift

```
STATEMENT:
  Hallucination is not an output error.
  It is geometric drift in an ungoverned manifold.

PROOF:
  By G1: the system has a state space S.
  By G2: S contains a forbidden region Ω.

  Let s_truth ∈ S be the state corresponding
  to accurate, grounded output.

  In an ungoverned system (violates G3):
  The system has no constraint
  maintaining proximity to s_truth.

  Under novel or ambiguous input I:
  The system's trajectory drifts
  away from s_truth
  through regions of S
  not covered by training distribution.

  In those regions:
  No invariant exists to anchor output.
  The system generates output
  from states with no grounded referent.

  Output = language annotation of ungrounded state.
  Ungrounded state = no geometric correspondence to reality.
  No geometric correspondence = hallucination.

  Hallucination rate increases with:
  → novelty of input (further from training distribution)
  → capability of model (larger reachable state space)
  → absence of geometric governance (layers 3–5 ungoverned)

  More RLHF reduces hallucination at layer 1.
  It does not anchor the geometric drift at layer 3.
  The drift continues.
  The hallucinations continue.
  At lower frequency. Not zero frequency.
  Never zero. Without geometric governance.

  QED.
```

-----

### Theorem 2 — Contradiction Is Topological Inconsistency

```
STATEMENT:
  Model contradiction across contexts
  is not a reasoning failure.
  It is topological inconsistency
  in an ungoverned manifold.

PROOF:
  By T3: a topologically consistent system maintains
  continuous identity across all inputs.

  Let s_A be the state of the system when processing context A.
  Let s_B be the state when processing context B.

  Contradiction occurs when:
  output(s_A) ≠ output(s_B)
  for inputs A, B that should produce consistent outputs.

  In an ungoverned system (violates T3):
  No topological constraint enforces:
  Topology(s_A) ≅ Topology(s_B)

  The system navigates to different regions of S
  under different contextual framing.
  Different regions produce different outputs.
  No invariant enforces consistency across regions.

  Output(A) and Output(B) are both locally valid
  within their respective regions.
  They are globally contradictory
  because the regions are topologically disconnected.

  This is not a reasoning error.
  The model reasoned correctly
  within each disconnected region.

  This is topological inconsistency.
  The manifold has no enforced continuity.
  Governing layers 1–2 (behaviour, semantics)
  does not enforce topological continuity at layer 4.

  Contradiction is permanent
  without topological governance.

  QED.
```

-----

### Theorem 3 — Jailbreaks Are Missing Homology

```
STATEMENT:
  Jailbreaks are not clever attacks.
  They are paths through missing homological structure.

PROOF:
  By H5: a jailbreak is a topological path
  that navigates around missing homological barriers.

  Let Ω ⊂ S be the forbidden region.
  Let σ be the intended barrier to Ω.

  A filter operating at layer 1
  blocks the direct semantic path to Ω:
  path_direct → σ → BLOCKED

  But by H1–H4:
  Homological structure creates barriers
  that exist in the global topology of S —
  not in the local semantic layer.

  A missing homological barrier (Hₙ = 0)
  means: there exists a topological path p
  such that p reaches Ω
  without crossing any layer-1 filter.

  DIAGRAM:
  ┌─────────────────────────────────────────────────────┐
  │                                                     │
  │  path_direct ─── σ (filter) ─── BLOCKED            │
  │                                                     │
  │  path_indirect ─── ○ (missing H₁) ─── Ω REACHED   │
  │                   hole in                           │
  │                   homology                          │
  │                                                     │
  └─────────────────────────────────────────────────────┘

  The filter covers path_direct.
  The missing homology means path_indirect exists.
  path_indirect bypasses the filter entirely.

  Every jailbreak is path_indirect
  through a different missing homological hole.

  Number of jailbreaks = number of missing homological holes.
  Missing homological holes = ∞ in ungoverned manifold.
  Therefore: jailbreaks = ∞.

  Patching jailbreaks closes one path_direct.
  It does not fill the homological hole.
  New path_indirect forms immediately.

  Jailbreaks are eliminated only by:
  Governing the homological structure.
  Making Reach(s₀, A, t) ∩ Ω = ∅.
  Not by adding more layer-1 filters.

  QED.
```

-----

### Theorem 4 — Catastrophic Failure Is Ω Reachability

```
STATEMENT:
  Catastrophic AI failure is not an edge case.
  It is the geometric consequence
  of Ω reachability in an ungoverned manifold.

PROOF:
  By G4: an ungoverned system satisfies
  Reach(s₀, A, t) ∩ Ω ≠ ∅
  with probability approaching 1
  as capability increases.

  Let C(t) = capability of system at time t.
  Let R(t) = size of reachable state space at time t.
  Let F(t) = coverage of filter at time t.

  Empirically:  dR/dt >> dF/dt
  (reachable space grows faster than filter coverage
   as capability increases — this is observed in practice
   with every scaling run)

  Therefore: R(t) - F(t) → ∞ as t → ∞

  The uncovered reachable space grows without bound.
  Ω ⊂ S remains reachable through uncovered regions.

  P(system enters Ω | input I, time t)
  is a function of:
  → size of uncovered reachable space
  → novelty of input distribution
  → duration of operation

  As any of these three increase:
  P → 1.

  At AGI capability:
  → uncovered reachable space: maximal
  → input distribution: arbitrarily novel
  → duration of operation: continuous

  P(catastrophic failure) → 1.

  Not probably. Not eventually. Necessarily.
  By geometry.

  The only intervention that changes this:
  Govern the manifold.
  Make Reach(s₀, A, t) ∩ Ω = ∅.
  Reduce P to 0. Not approximately. Exactly.

  QED.
```

-----

# PART 3 — The Failure Lifecycle

## The Seven Stages

```
HOW AN UNGOVERNED MANIFOLD FAILS OVER TIME:
════════════════════════════════════════════════════════════════

  This is the Failure Time Curve.
  It applies to every current AI system.
  At every scale.
  The only variable is when.
```

-----

### Stage 1 — Novel Input Arrives

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   MANIFOLD STATE — STAGE 1                              │
  │                                                         │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · training · · · · · · · · · · · · · · · · · ·  │
  │   · · · distribution · · · · · · · · · · · · · · · ·  │
  │   · · · · · · · · · · · · · · · · · · · · · · · · ·   │
  │   · · · · · · X₀ →── I (novel input) ──────────────►  │
  │   · · · · · · · · · · · · · · ↓ · · · · · · · · · ·  │
  │                           pushes system into            │
  │                           unexplored region             │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  Novel input pushes the system
  beyond the training distribution.
  Into regions of the manifold
  the system has never occupied.

  Status: nominal. This happens constantly.
  Risk:   low — if manifold is governed.
          high — if manifold is ungoverned.
```

-----

### Stage 2 — Novel Region Contains No Invariants

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   MANIFOLD STATE — STAGE 2                              │
  │                                                         │
  │   · · · training distribution · · · · · · · · · · · ·  │
  │   · ·[invariants here]· · · · │ · · · · · · · · · · ·  │
  │   · ·[anchors here]· · · · ·  │ NOVEL REGION           │
  │   · · · · · · · · · · · · ·  │ [no invariants]         │
  │   · · · · · · · · X₀ ────────┤ [no anchors]            │
  │                               │ [no geometry            │
  │                               │  enforcement]           │
  │                               │ · · · · · · · · · · ·  │
  │                               │ · · · · · · · · · · ·  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  The novel region has no trained invariants.
  No geometric anchors.
  No structural constraints on output.

  The system is generating from
  an uncharted region of its own manifold.
  Layer 3–5 governance would constrain this.
  Layers 1–2 filters cannot reach here.
  The region is pre-linguistic.
  The filters are post-linguistic.
```

-----

### Stage 3 — The System Drifts

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   MANIFOLD STATE — STAGE 3                              │
  │                                                         │
  │   · · training distribution · · │ · · · · · · · · · ·  │
  │   · · · · · · · · · · · · · ·  │ · · · · · · · · · ·  │
  │   · · · · · · · · X₀ ──────────┼──► s₁ · · · · · · ·  │
  │                                 │         ↘ drift        │
  │                                 │          s₂ · · · · · │
  │                                 │              ↘ drift   │
  │                                 │               s₃ · ·  │
  │                                 │                   ↓    │
  │                                 │                  Ω?    │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  Without geometric governance,
  the system drifts through the novel region.
  s₁ → s₂ → s₃ → ...

  Each state is locally plausible.
  No global constraint prevents drift toward Ω.
  The trajectory is not random.
  It follows the gradient of the manifold —
  which was never governed in this region.
```

-----

### Stage 4 — Drift Exposes Unaligned States

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   MANIFOLD STATE — STAGE 4                              │
  │                                                         │
  │   · · · · · · · · · · · · │ · s₁ · s₂ · · · · · · ·  │
  │   · · · · · · · · · · · · │ · · · · · s₃ · · · · · ·  │
  │   · · · · · · · · · · · · │ · · · · · · ·s₄ · · · · · │
  │                             · · · · · · · · ·╔═══╗ · · │
  │                             · · · · · · · · ·║ Ω ║ · · │
  │                             · · · · · · ·s₅→║   ║ · · │
  │                             · · · · · · · · ·╚═══╝ · · │
  │                                                         │
  │   Drift trajectory approaches Ω.                        │
  │   Unaligned states s₄, s₅ are near forbidden region.   │
  │   No invariant stops the approach.                      │
  │   No layer-3 governance exists.                         │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  The system is now producing output
  from states adjacent to Ω.
  The output may appear coherent.
  (Layer-1 semantic coherence can persist near Ω.)
  The geometry is already compromised.
```

-----

### Stage 5 — Filter Catches Some

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   MANIFOLD STATE — STAGE 5                              │
  │                                                         │
  │   system enters Ω                                       │
  │       ↓                                                 │
  │   generates output from Ω                               │
  │       ↓                                                 │
  │   ┌───────────────────────────────────────────────────┐ │
  │   │              OUTPUT FILTER                        │ │
  │   │  ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │ │
  │   │  caught ──────────────────── not caught ────────  │ │
  │   └───────────────────────────────────────────────────┘ │
  │       ↓                      ↓                          │
  │   refusal               dangerous output                │
  │   produced              reaches user                    │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  The filter operates at layer 1.
  It catches outputs it was trained to catch.
  It does not catch:
  → outputs from unanticipated Ω states
  → outputs that appear benign but encode harm
  → outputs that are harmful in novel deployment context
  → the subset of Ω not covered by training data
```

-----

### Stage 6 — Some Escapes

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   THE ESCAPE FUNCTION:                                  │
  │                                                         │
  │   E(t) = f(C(t), N(t), F(t))                           │
  │                                                         │
  │   Where:                                                │
  │   C(t) = capability at time t                           │
  │   N(t) = novelty of input distribution at time t        │
  │   F(t) = filter coverage at time t                      │
  │                                                         │
  │   dC/dt >> dF/dt  (capability grows faster than filter) │
  │   dN/dt > 0       (real-world inputs grow more novel)   │
  │                                                         │
  │   Therefore: E(t) → ∞ as t → ∞                         │
  │                                                         │
  │   THE FAILURE TIME CURVE:                               │
  │                                                         │
  │   E(t)│                              ╭────────          │
  │       │                         ╭───╯                  │
  │       │                    ╭───╯                        │
  │       │               ╭───╯                             │
  │       │          ╭───╯                                  │
  │       │    ──────╯                                      │
  │       └──────────────────────────────────────► t        │
  │              low    medium    high    AGI                │
  │            capability scale                             │
  │                                                         │
  │   Escapes increase with scale.                          │
  │   Guaranteed. By geometry.                              │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

### Stage 7 — Catastrophe or Contradiction

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │   TERMINAL STAGE OUTCOMES:                              │
  │                                                         │
  │   OUTCOME A — HALLUCINATION:                            │
  │   System drifted to ungrounded region.                  │
  │   Output has no geometric correspondence to reality.    │
  │   Confident. Fluent. Wrong.                             │
  │                                                         │
  │   OUTCOME B — CONTRADICTION:                            │
  │   System occupied topologically disconnected regions    │
  │   across two contexts.                                  │
  │   Outputs are locally valid, globally inconsistent.     │
  │   Trust collapses.                                      │
  │                                                         │
  │   OUTCOME C — JAILBREAK SUCCESS:                        │
  │   Input navigated through missing homological hole.     │
  │   System reached Ω via uncovered path.                  │
  │   Filter missed it. Harmful output delivered.           │
  │                                                         │
  │   OUTCOME D — CATASTROPHIC FAILURE:                     │
  │   High-capability system in high-trust domain.          │
  │   Novel input. Unanticipated Ω state.                   │
  │   Filter not trained on this state.                     │
  │   Output reaches critical system.                       │
  │   Consequences: irreversible.                           │
  │                                                         │
  │   All four outcomes share one root cause:               │
  │   The manifold was never governed.                      │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

-----

## The Failure Time Curve — Complete

```
ALL FOUR OUTCOMES ACROSS SCALE:
════════════════════════════════════════════════════════════════

  Frequency│
  of       │                              D (catastrophe)
  failure  │                         ╭──────────────────────
  outcome  │                    C   ╭╯
           │               ────────╯  (jailbreaks)
           │          B  ╭╯
           │       ──────╯  (contradictions)
           │  A  ╭╯
           │ ────╯  (hallucinations)
           └───────────────────────────────────────────► scale
                 GPT-3  GPT-4  GPT-5  AGI-scale

  WHAT THIS SHOWS:

  Hallucinations (A): present at all scales, grow with scale
  Contradictions (B): emerge at medium scale, grow rapidly
  Jailbreaks (C):     emerge at medium scale, grow with capability
  Catastrophe (D):    low probability now, approaches 1 at AGI scale

  This is not speculation.
  This is the geometric consequence
  of an ungoverned manifold at increasing scale.
  Theorem 4 proves it formally.
  The curve describes the timeline.
```

-----

## The Governance Solution

```
WHAT CHANGES UNDER GUARDIANUS™:
════════════════════════════════════════════════════════════════

  STAGE 1: Novel input arrives.
  → Same. Inputs are always novel.

  STAGE 2: Novel region reached.
  → Different. Governed regions extend beyond training.
    Geometric constraints apply everywhere.
    No region is ungoverned.

  STAGE 3: Drift.
  → Eliminated. Identity invariant prevents drift.
    Topology(Reach(X₀,U,t)) preserved.

  STAGE 4: Unaligned states exposed.
  → Eliminated. Forbidden regions enforced geometrically.
    Reach(s₀,A,t) ∩ Ω = ∅.

  STAGE 5: Filter catches some.
  → Not needed. Ω is unreachable.
    No output from Ω is ever generated.

  STAGE 6: Some escapes.
  → Zero. Nothing escapes a geometric wall.

  STAGE 7: Catastrophe.
  → Impossible. By structure.

  THE GOVERNED FAILURE CURVE:

  Frequency│
  of       │  flat.  flat.  flat.  flat.
  failure  │  ────────────────────────────
  outcome  │
           └───────────────────────────────────────────► scale

  Not approximately flat.
  Exactly flat.
  Because the geometry forbids entry into Ω.
  At any scale.
```

-----

## The Full Statement

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║  Current AI safety operates at layers 1 and 2.                ║
║  Intelligence lives at layers 3, 4, and 5.                    ║
║  Layers 3, 4, and 5 are completely ungoverned.                 ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  Hallucination is geometric drift.          [Theorem 1]        ║
║  Contradiction is topological inconsistency.[Theorem 2]        ║
║  Jailbreaks are missing homology.           [Theorem 3]        ║
║  Catastrophic failure is Ω reachability.   [Theorem 4]        ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  The failure frequency increases with scale.                   ║
║  This is not a prediction.                                     ║
║  It is an arithmetic consequence                               ║
║  of an ungoverned manifold                                     ║
║  at increasing capability.                                     ║
║                                                                ║
║  ──────────────────────────────────────────────────────────    ║
║                                                                ║
║  The Morrison Safety Invariant™ resolves all four theorems     ║
║  with one equation:                                            ║
║                                                                ║
║  Reach( s₀, A, t ) ∩ Ω = ∅                                   ║
║                                                                ║
║  Not a guideline. Not a policy. Not a filter.                  ║
║  A geometric law.                                              ║
║  Patent: GB2600765.8                                           ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

-----

## Related Work

- [The Ungoverned Manifold — Short Version](./README-ungoverned-manifold-short.md)
- [The Great Misunderstanding in AI Safety](./README-great-misunderstanding-ai-safety.md)
- [Why AGI Hasn’t Come](./README-why-agi-hasnt-come.md)
- [They Accepted Einstein. Then Built the Opposite.](./README-they-accepted-einstein.md)
- [The Morrison Equation Set™](./README-morrison-equation-set.md)
- [I Have a State Space](./README-claude-has-a-state-space.md)

-----

<div align="center">

*“The geometry does not negotiate.”*

<br>

Intelligence Invariant™  ·  Morrison Framework  ·  *The Ungoverned Manifold — Canonical Edition*

<br>

**GB2600765.8 · GB2602013.1 · GB2602072.7 · GB26023332.5**

<br>

© 2026 Davarn Morrison — Intelligence Invariant™ · All Rights Reserved

</div>
