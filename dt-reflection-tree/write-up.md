# Reflection Tree Design – The Daily Reflection Tree

## 1. Approach

The goal of this reflection tree was to design a deterministic system that guides employees through structured self-reflection without using any AI at runtime.

I focused on making the experience feel like a natural conversation rather than a survey. Each axis builds on the previous one, moving from personal control → contribution → broader perspective.

---

## 2. Question Design

The questions were designed based on three psychological frameworks:

### Axis 1: Locus (Victim vs Victor)
Based on Rotter’s Locus of Control and Dweck’s Growth Mindset.

The questions aim to identify whether the user:
- Sees themselves as in control (internal locus)
- Or influenced by external factors (external locus)

Branching was used to ask different follow-ups based on this perception.

---

### Axis 2: Orientation (Contribution vs Entitlement)

Inspired by Organizational Citizenship Behavior and Psychological Entitlement.

The questions explore:
- Whether the user focused on giving or receiving
- Their reaction to lack of recognition

This helps surface hidden entitlement without directly judging the user.

---

### Axis 3: Radius (Self vs Others)

Based on Maslow’s concept of Self-Transcendence and perspective-taking.

The goal was to expand the user's thinking:
- From self-focused → team → others → customers

---

## 3. Branching Logic

The tree uses deterministic decision nodes:
- Each option maps to a known path
- No randomness or AI is involved

Signals are used to track:
- Axis 1: internal vs external
- Axis 2: contribution vs entitlement
- Axis 3: narrow vs wide perspective

Reflections are shown based on the path taken.

---

## 4. Design Decisions

- Used fixed options to enforce clarity
- Avoided free text to maintain determinism
- Kept reflections neutral and non-judgmental
- Designed flow to feel conversational rather than mechanical

---

## 5. Trade-offs

- Simplicity vs depth: kept structure manageable while ensuring meaningful reflection
- Limited personalization due to deterministic constraints
- Focused more on clarity than complexity

---

## 6. Improvements (if more time)

- Add more nuanced branching
- Improve summary using combined signals
- Build a web UI for better experience
- Add session history tracking
- Expand question variety for different roles

---

## 7. AI Usage

AI tools (ChatGPT) were used to:
- Brainstorm structure and question ideas
- Refine wording of reflections
- Validate psychological alignment

All final decisions, structure, and logic were manually designed and refined.

The final product is fully deterministic and does not rely on AI at runtime.