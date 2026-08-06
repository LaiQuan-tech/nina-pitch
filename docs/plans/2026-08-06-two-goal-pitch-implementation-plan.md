# Two-Goal Nina Pitch Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Rewrite the full Nina pitch deck around reducing customer communication time and reducing employee handover/training time while presenting the website and AI intake capabilities as one integrated system.

**Architecture:** Keep the existing single-file static deck and its visual system. Update the metadata and all 16 slide narratives in `index.html`, preserving the existing DOM classes and interactive script so the change remains content-focused and low risk.

**Tech Stack:** Static HTML, CSS, and vanilla JavaScript.

---

### Task 1: Rewrite the narrative and system positioning

**Files:**
- Modify: `index.html`

**Step 1:** Update metadata, navigation naming, cover, problem, solution, feature, flow, preview, and closing copy so every section maps to one or both approved goals.

**Step 2:** Replace all two-package wording with a single integrated-system position.

### Task 2: Rewrite the eight-week delivery plan

**Files:**
- Modify: `index.html`

**Step 1:** Organize weeks 1–4 around customer communication automation.

**Step 2:** Organize weeks 5–8 around customer knowledge retention, handover, integration, training, and launch.

### Task 3: Consolidate the quote narrative

**Files:**
- Modify: `index.html`

**Step 1:** Rename the two quote columns as goal-based build categories within one system.

**Step 2:** Preserve the approved subtotal, tax, total, and 50/50 payment terms.

### Task 4: Verify and publish

**Files:**
- Test: `index.html`

**Step 1:** Run text assertions for the two goals, eight-week schedule, and approved totals.

**Step 2:** Assert obsolete two-part wording is absent and run `git diff --check`.

**Step 3:** Inspect the final diff, commit only intended files, push directly to `main`, and verify the deployed HTML contains the new positioning.
