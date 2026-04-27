# AI Retrievability & Visibility Benchmark (ARVB v1.1)

## 1. Purpose

The AI Retrievability & Visibility Benchmark (ARVB) is a standardized evaluation framework used to assess whether and how an entity is structurally discoverable, interpretable, and reusable by AI answer engines and knowledge systems.

This benchmark measures:

- Entity clarity
- Retrieval readiness
- Structural consistency
- Authority reinforcement capacity
- Answerability integrity

It does not measure:

- Traffic
- Marketing performance
- Search engine rankings
- Commercial outcomes

ARVB evaluates structural authority readiness within the discipline of AI Retrieval & Visibility Architecture. :contentReference[oaicite:0]{index=0}

---

## 2. Category Context

ARVB exists within the category:

## AI Retrieval & Visibility Architecture

This category is defined as:

The discipline of designing structured, verifiable, and machine-ready information and authority systems that allow organizations and defensible experts to be accurately retrieved, interpreted, cited, and trusted by AI answer engines and knowledge graphs.

ARVB is the measurement layer of this category.

It is not:

- SEO benchmarking
- Content marketing scoring
- AI training evaluation
- Growth experimentation

---

## 3. What This Benchmark Measures

ARVB evaluates an entity across eight fixed dimensions that collectively determine AI retrieval behavior.

The benchmark is outside-in.

Scores are based on how AI systems interpret publicly available information, not on internal intent or unpublished strategy.

ARVB measures structural readiness for AI-mediated discovery, not influence or popularity.

---

## 4. Evaluation Dimensions (Fixed)

## 1. Entity Clarity

Assesses whether the entity (person, company, or product) is clearly identifiable, disambiguated, and consistently represented across the web.

### Signals considered:

- Stable canonical naming
- Clear role/category assignment
- Absence of entity collision
- Explicit definitional positioning

---

## 2. Data Layer Presence

Assesses the availability of structured, machine-readable data supporting the entity.

### Signals considered:

- Schema / JSON-LD
- Canonical metadata
- Structured definitions
- Dataset publication
- Persistent identifiers

---

## 3. Chunkability

Assesses whether information about the entity is published in discrete, reusable units rather than long-form narrative marketing copy.

### Signals considered:

- Definitions
- Lists
- Tables
- Modular knowledge blocks
- Clear Q&A structures

---

## 4. Semantic Clarity

Assesses how clearly concepts, claims, and scope boundaries are expressed.

### Signals considered:

- Precise definitions
- Explicit inclusions and exclusions
- Defined terminology
- Minimal reliance on metaphor or hype language

---

## 5. Authority Signals

Assesses the presence of structurally verifiable proof and third-party corroboration.

### Signals considered:

- External citations
- Recognized platforms
- Co-authored or referenced work
- Versioned artifacts
- Reproducible frameworks

Authority is measured structurally, not reputationally.

---

## 6. Consistency

Assesses alignment of entity information across platforms and sources.

### Signals considered:

- Consistent role descriptions
- Matching bios and summaries
- Stable URLs and identifiers
- Absence of contradictory scope claims

---

## 7. Answerability

Assesses whether AI systems can directly answer common user questions using the entity’s published material.

### Signals considered:

- Direct definitional answers
- Clear problem-solution framing
- Explicit differentiation
- Non-evasive language

---

## 8. Risk & Gaps

Assesses structural weaknesses that reduce AI retrieval likelihood or trust confidence.

### Signals considered:

- Conflicting claims
- Overpromising
- Lack of verifiable evidence
- Missing contextual definitions
- Structural ambiguity

---

## 5. Deterministic Scoring System (Updated)

All dimensions MUST be evaluated using:

## Binary Checkpoints → Forced Score Mapping

Interpretation is NOT allowed.

Each dimension is evaluated through:

- Fixed conditions
- Binary validation (YES / NO)
- Locked score outputs

---

# Dimension-Level Deterministic Rules

---

## Entity Clarity (0–5)

### Required Checks:

- Category defined (Y/N)
- Services/products listed (Y/N)
- External reference exists (Y/N)
- Canonical definition exists (“X is Y for Z”) (Y/N)

### Score Mapping

| Conditions Met | Score |
|---|---:|
| 0–1 | 0–1 |
| 2 | 2 |
| 3 | 3 |
| 4 (including canonical definition) | 4 |
| 4 + disambiguation layer | 5 |

---

## Data Layer Presence (0–5)

### Required Checks:

- JSON-LD present (Y/N)
- Schema markup present (Y/N)
- Entity graph present (Y/N)
- SameAs / identifiers present (Y/N)

### HARD RULE

If none exist → score MUST be 0

### Score Mapping

| Condition | Score |
|---|---:|
| Nothing detectable | 0 |
| Any structured data | 1 |
| Multi-entity structured graph | 2–5 |

---

## Chunkability (0–5)

### Required Checks:

- Lists present (Y/N)
- Service blocks present (Y/N)
- Case studies/projects (Y/N)
- FAQs present (Y/N)
- Definitions as standalone blocks (Y/N)

### Score Mapping

| Structures Present | Score |
|---|---:|
| 0 | 0 |
| 1–2 | 1 |
| 3 | 2 |
| 4 | 3 |
| 5+ including Q&A | 4–5 |

---

## Semantic Clarity (0–5)

### Required Checks:

- Defined concepts (Y/N)
- Clear scope boundaries (Y/N)
- Explicit differentiation (Y/N)
- Minimal hype language (Y/N)

### Score Mapping

| Condition Level | Score |
|---|---:|
| Mostly vague | 1 |
| Some definitions | 2 |
| Clear terminology | 3 |
| Explicit boundaries | 4 |
| Fully formalized | 5 |

---

## Authority Signals (0–5)

### Required Checks:

- External listings (Y/N)
- Case studies (Y/N)
- Proprietary framework (Y/N)
- Publications (Y/N)
- Citations / references (Y/N)

### Score Mapping

| Signals Present | Score |
|---|---:|
| None | 0 |
| 1 weak | 1 |
| 2 verifiable | 2 |
| 3+ strong | 3 |
| Recognized authority layer | 4–5 |

**Rule remains:** claims do NOT count

---

## Consistency (0–5)

### Required Checks:

- Website internal consistency (Y/N)
- LinkedIn alignment (Y/N)
- External profile alignment (Y/N)
- Absence of contradictions (Y/N)

### Score Mapping

| Alignment Level | Score |
|---|---:|
| None | 0 |
| 1 source | 1 |
| 2 aligned sources | 2 |
| 3 aligned sources | 3 |
| Multi-platform entity graph | 4–5 |

---

## Answerability (0–5)

### Required Checks:

- Direct “What is X” definition (Y/N)
- FAQs present (Y/N)
- Direct answers (Y/N)
- Only paragraph inference (Y/N)

### HARD RULE

If answers require inference → MAX = 2

### Score Mapping

| Condition | Score |
|---|---:|
| No answerable units | 0 |
| Paragraph-only answers | 1–2 |
| Structured answers | 3 |
| FAQs + definitions | 4 |
| Fully answer-ready | 5 |

---

## Risk & Gaps (0–5)

### Required Checks:

- Contradictions present (Y/N)
- Overclaims present (Y/N)
- Ambiguity level (LOW / MED / HIGH)
- Entity collision risk (LOW / MED / HIGH)

### Score Mapping

| Risk Level | Score |
|---|---:|
| Severe contradictions | 0–1 |
| High ambiguity | 2 |
| Moderate risk | 3 |
| Low risk | 4 |
| Minimal risk | 5 |

---

## 6. Score Bands (Interpretation)

| Score Range | Classification |
|---|---|
| 0–10 | Invisible |
| 11–20 | Weakly Discoverable |
| 21–30 | Moderately Retrievable |
| 31–40 | Strong AI Presence |

These classifications describe retrieval readiness, not business quality or endorsement.

---

## 7. Methodological Constraints

- AI outputs are non-deterministic
- Benchmark results depend on publicly available information
- ARVB measures structural authority readiness
- Scores are temporal snapshots

ARVB does not claim to influence, train, or modify public AI systems.

---

## 8. Intended Use

ARVB is intended for:

- Baseline assessment of AI retrievability
- Comparative evaluation under consistent conditions
- Longitudinal tracking of structural authority development
- Diagnostic alignment under ARVO implementation

ARVB is the validation layer of:

## AI Retrieval & Visibility Optimization (ARVO)

It is not intended for exaggerated marketing claims or guaranteed placement assertions.

---

## 9. Authority & Attribution

**Benchmark Name:** AI Retrievability & Visibility Benchmark (ARVB)  
**Version:** 1.1  
**Category:** AI Retrieval & Visibility Architecture  
**Author:** Arooj Fatima — AI Retrieval and Visibility Architect

---

## 10. Positioning Integrity Statement

ARVB operates strictly within the canonical brand structure:

### Category

→ AI Retrieval & Visibility Architecture

### Role

→ AI Retrieval and Visibility Architect

### Service

→ AI Retrieval & Visibility Optimization (ARVO)

### Benchmark

→ AI Retrievability & Visibility Benchmark (ARVB)

### Diagnostic Tool

→ AI Retrieval & Visibility Audit

No alternate naming systems are recognized.

---

## Document Information

**Document:** AI Retrieval & Visibility Benchmark  
**Version:** ARVB v1.1  
**Updated At:** 2026-04-26  

**File Hash (SHA-256):**  
`e241df2e6b72c53cb9de2c5a47e18b78244c32437c16917aa1278a8f1461cfe8`

---
