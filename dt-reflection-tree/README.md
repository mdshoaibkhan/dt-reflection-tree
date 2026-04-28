# Daily Reflection Tree

## Overview
This project is a deterministic reflection tool that guides users through a structured end-of-day reflection using a decision tree.

The system does not use any AI at runtime. Instead, it uses predefined questions, fixed options, and deterministic branching to ensure consistent and auditable outcomes.

## Axes Covered
The reflection process follows three psychological axes:

1. **Locus (Victim vs Victor)**
   - Measures sense of control and agency.

2. **Orientation (Contribution vs Entitlement)**
   - Focuses on giving vs expecting.

3. **Radius (Self vs Others)**
   - Expands perspective from self to team and beyond.

## Approach
- Fully deterministic tree structure
- Fixed options for every question
- No randomness or AI usage at runtime
- Structured branching using decision nodes
- Reflection nodes provide insights based on user choices

## AI Usage
AI tools (ChatGPT) were used during development for:
- Understanding psychological frameworks
- Improving question phrasing
- Structuring the decision tree

All final logic, branching, and structure were manually designed and refined.

## Improvements (Future Scope)
- Add a web-based UI
- Improve summary personalization
- Expand tree depth and coverage
- Add data persistence for user sessions
## Design Philosophy
The tree is designed as a guided reflection conversation rather than a static survey, where each question builds on the previous response to deepen self-awareness across the three axes.
