# Project Dashboard

## 📊 Executive Summary

**95** total issues | **32%** complete | **25** ready to work | **40** blocked

⚠️ **Health Warning:** More issues are blocked than actionable. Focus on clearing blockers.

## 🎯 Top Priorities

The graph analysis identified these as the highest-impact items to work on:

### 1. Team Maturity: Development Best Practices
**ID:** `agent-orchestrator-ngs` | **Impact Score:** 0.39 | **Unblocks:** 14 issues

**Why this matters:**
- 🎯 Completing this unblocks 14 downstream issues (agent-orchestrator-485, agent-orchestrator-55f, +12 more)
- ✅ Currently unclaimed - available for work

### 2. Connect workflow executor to main orchestration loop
**ID:** `agent-orchestrator-csf` | **Impact Score:** 0.28 | **Unblocks:** 6 issues

**Why this matters:**
- 🎯 Completing this unblocks 6 downstream issues (agent-orchestrator-1nn, agent-orchestrator-52d, +4 more)
- ✅ Currently unclaimed - available for work
- 🚨 High priority (P1) - prioritize this work

### 3. Implement risk tier enforcement in workflow executor (CRITICAL/DANGEROUS/SAFE)
**ID:** `agent-orchestrator-1nn` | **Impact Score:** 0.21 | **Unblocks:** 3 issues

**Why this matters:**
- 🎯 Completing this unblocks 3 downstream issues (agent-orchestrator-635, agent-orchestrator-bp5, agent-orchestrator-wl8)
- ✅ Currently unclaimed - available for work
- ⏳ Blocked by agent-orchestrator-csf - complete that first
- 🚨 High priority (P1) - prioritize this work

## 🚧 Critical Bottlenecks

These issues are blocking the most downstream work. Clearing them has outsized impact:

| Issue | Title | Unblocks | Status |
|-------|-------|----------|--------|
| `agent-orchestrator-ngs` | Team Maturity: Development Best Pract... | **14** issues | Ready |
| `agent-orchestrator-csf` | Connect workflow executor to main orc... | **6** issues | Ready |
| `agent-orchestrator-1nn` | Implement risk tier enforcement in wo... | **3** issues | Blocked by 1 |
| `agent-orchestrator-8go` | Implement Discord reaction-based appr... | **3** issues | Blocked by 1 |
| `agent-orchestrator-isj` | Implement human-in-the-loop approval ... | **2** issues | Blocked by 1 |

## 📈 Graph Analysis

- **Dependency Density:** 0.005 (🟢 Healthy) — Issues are well-isolated and can be parallelized
- **Graph Size:** 95 issues with 48 dependencies
- **Cycles:** None detected ✓

## 🏃 Quick Wins

Low-effort items that clear the path forward:

- **agent-orchestrator-ngs**: Team Maturity: Development Best Practices (unblocks 14)
  - *Unblocks 14 items*
- **agent-orchestrator-csf**: Connect workflow executor to main orchestration loop (unblocks 6)
  - *Unblocks 6 items, high priority*
- **agent-orchestrator-1nn**: Implement risk tier enforcement in workflow executor (CRITICAL/DANGEROUS/SAFE) (unblocks 3)
  - *Unblocks 3 items, high priority*
- **agent-orchestrator-8go**: Implement Discord reaction-based approval system for DANGEROUS tier (unblocks 3)
  - *Unblocks 3 items, high priority*
- **agent-orchestrator-ave**: Morgan: Implement coordination budget monitoring (Phase 1) (unblocks 2)
  - *Unblocks 2 items*

## 📋 Status Summary

**By Priority:** P1: 20 | P2: 42 | P3: 33

**By Type:** bug: 1 | epic: 2 | task: 92

---

*Generated Dec 21, 2025 at 11:14 PM EST by [bv](https://github.com/Dicklesworthstone/beads_viewer)*

