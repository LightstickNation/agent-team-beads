# Project Dashboard

## 📊 Executive Summary

**65** total issues | **34%** complete | **24** ready to work | **19** blocked

## 🎯 Top Priorities

The graph analysis identified these as the highest-impact items to work on:

### 1. Connect workflow executor to main orchestration loop
**ID:** `agent-orchestrator-csf` | **Impact Score:** 0.35 | **Unblocks:** 6 issues

**Why this matters:**
- 🎯 Completing this unblocks 6 downstream issues (agent-orchestrator-1nn, agent-orchestrator-52d, +4 more)
- ✅ Currently unclaimed - available for work
- 🚨 High priority (P1) - prioritize this work

### 2. Implement Discord reaction-based approval system for DANGEROUS tier
**ID:** `agent-orchestrator-8go` | **Impact Score:** 0.22 | **Unblocks:** 3 issues

**Why this matters:**
- 🎯 Completing this unblocks 3 downstream issues (agent-orchestrator-1hd, agent-orchestrator-3dg, agent-orchestrator-avo)
- ✅ Currently unclaimed - available for work
- ⏳ Blocked by agent-orchestrator-isj - complete that first
- 🚨 High priority (P1) - prioritize this work

### 3. Implement risk tier enforcement in workflow executor (CRITICAL/DANGEROUS/SAFE)
**ID:** `agent-orchestrator-1nn` | **Impact Score:** 0.20 | **Unblocks:** 3 issues

**Why this matters:**
- 🎯 Completing this unblocks 3 downstream issues (agent-orchestrator-635, agent-orchestrator-bp5, agent-orchestrator-wl8)
- ✅ Currently unclaimed - available for work
- ⏳ Blocked by agent-orchestrator-csf - complete that first
- 🚨 High priority (P1) - prioritize this work

## 🚧 Critical Bottlenecks

These issues are blocking the most downstream work. Clearing them has outsized impact:

| Issue | Title | Unblocks | Status |
|-------|-------|----------|--------|
| `agent-orchestrator-csf` | Connect workflow executor to main orc... | **6** issues | Ready |
| `agent-orchestrator-8go` | Implement Discord reaction-based appr... | **3** issues | Blocked by 1 |
| `agent-orchestrator-1nn` | Implement risk tier enforcement in wo... | **3** issues | Blocked by 1 |
| `agent-orchestrator-ave` | Morgan: Implement coordination budget... | **2** issues | Ready |
| `agent-orchestrator-isj` | Implement human-in-the-loop approval ... | **2** issues | Blocked by 1 |

## 📈 Graph Analysis

- **Dependency Density:** 0.005 (🟢 Healthy) — Issues are well-isolated and can be parallelized
- **Graph Size:** 65 issues with 22 dependencies
- **Cycles:** None detected ✓

## 🏃 Quick Wins

Low-effort items that clear the path forward:

- **agent-orchestrator-csf**: Connect workflow executor to main orchestration loop (unblocks 6)
  - *Unblocks 6 items, high priority*
- **agent-orchestrator-1lt**: Phase 2 Testing: Validate Memory JSON as canonical source (unblocks 1)
  - *Unblocks 1 items, high priority*
- **agent-orchestrator-1nn**: Implement risk tier enforcement in workflow executor (CRITICAL/DANGEROUS/SAFE) (unblocks 3)
  - *Unblocks 3 items, high priority*
- **agent-orchestrator-8go**: Implement Discord reaction-based approval system for DANGEROUS tier (unblocks 3)
  - *Unblocks 3 items, high priority*
- **agent-orchestrator-ave**: Morgan: Implement coordination budget monitoring (Phase 1) (unblocks 2)
  - *Unblocks 2 items*

## 📋 Status Summary

**By Priority:** P1: 16 | P2: 32 | P3: 17

**By Type:** bug: 1 | task: 64

---

*Generated Dec 21, 2025 at 8:46 PM EST by [bv](https://github.com/Dicklesworthstone/beads_viewer)*

