# GoHealth — Insurance Plan Comparison Platform

**Role:** UX Designer  
**Timeline:** 2016 – 2020  
**Context:** In-house UX on a Medicare and health insurance marketplace serving 500K+ monthly users  
**Tools:** Figma, Component Library, Usability Testing, User Interviews, Journey Mapping, Persona Development, Responsive Web, Agile

---

## Overview

GoHealth operates a digital health insurance marketplace connecting consumers — primarily Medicare-eligible adults — with health plans through a technology-driven comparison and enrollment experience. I owned UX for the core comparison and enrollment flows, the most high-stakes part of the product, where users make complex financial and healthcare decisions under time pressure.

---

## The Problem

500K+ monthly users were abandoning at the plan selection stage. The comparison experience had grown organically across multiple teams with no unified design language, inconsistent UI patterns, and filtering logic that routinely produced zero results — leaving users with no path forward and no explanation.

Three specific friction points drove the majority of drop-off:

1. **Zero-result filter states** — users filtered themselves into dead ends with no recovery path
2. **Comparison table overload** — 12+ attributes rendered in a flat table with no visual hierarchy or prioritization
3. **Unclear CTA hierarchy** — competing calls-to-action created decision paralysis at the enrollment step

---

## My Process

### 1. User Research & Persona Development
Conducted in-depth user interviews and session recording analysis across a cross-section of Medicare-eligible users. Synthesized findings into a **5-persona framework** representing the primary decision-making patterns — from cost-first to coverage-first to agent-dependent users. This framework was adopted across 4 product teams as the shared language for design decisions.

### 2. Usability Testing
Ran moderated usability sessions that isolated the three critical friction points above. Sessions were designed to test specific hypotheses about filter behavior, comparison table comprehension, and CTA clarity — not general discovery, which allowed faster prioritization.

### 3. Redesign: Filtering
Redesigned the filter architecture with **progressive disclosure** — exposing the most-used filters first and collapsing secondary options. Added explicit zero-result recovery states with plain-language explanations and suggested filter adjustments.

### 4. Redesign: Plan Comparison
Restructured the comparison table around decision priority — surfacing premium, network type, and out-of-pocket maximum above the fold. Collapsed secondary attributes behind an expandable "More details" interaction to reduce cognitive load without hiding information.

### 5. Component Library
Built a shared Figma component library that standardized UI patterns org-wide. This eliminated the design inconsistency that had accumulated across teams and reduced design-to-build time by approximately 40%.

---

## Key Design Decisions

**Zero-result recovery** — Rather than showing an empty state, the redesigned filter experience detects when a filter combination will yield zero results *before* the user applies it, and surfaces a suggestion to modify the most restrictive filter. This keeps users in the flow rather than forcing a reset.

**Persona-driven filter defaults** — Default filter states were tuned per entry point based on persona. Users arriving from Medicare.gov search ads defaulted to Medicare Advantage plans; users from organic search defaulted to all plan types. Reduced irrelevant results without requiring manual filtering.

**CTA consolidation** — Reduced from 3 competing CTAs (Save Plan, Compare, Enroll) to a single primary action per state with contextual secondary actions. Enrollment conversion improved as a result of reduced decision paralysis.

---

## Outcomes

| Metric | Result |
|---|---|
| Critical friction points eliminated | **3 of 3** identified in usability testing |
| Persona framework adoption | **4 product teams** |
| Design-to-build time | **~40% faster** post component library |
| Component library | **Org-wide standard** |
| Monthly users served | **500K+** |

---

## What I Learned

Healthcare insurance UX sits at the intersection of regulatory complexity, high user anxiety, and low domain literacy. The users most likely to make a poor plan selection are also the least likely to use the comparison tools effectively. The biggest design wins came not from adding features but from removing friction — fewer filters shown by default, fewer attributes in the comparison table, fewer CTAs competing for attention. Simplicity in a complex domain is a hard-won design outcome, not a starting point.

---

## Related

- [Live Portfolio](https://richardcarman.github.io) — full case study with process walkthrough
- [GitHub Profile](https://github.com/richardcarman)
