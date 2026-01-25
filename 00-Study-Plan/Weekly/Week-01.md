# CCIE Enterprise Infrastructure – Week 01 Study Plan

## Overview
**Total study time:** 18 hours  
**Tools:** Cisco CML, EVE-NG, Udemy, INE  
**Focus:** Layer 2 fundamentals – Spanning Tree Protocol (STP)

This week establishes the study rhythm and documentation workflow while building a strong STP foundation.

---

## Weekly Time Allocation
- **Monday–Friday:** 2 hours/day (10 hours)
- **Saturday:** 4 hours
- **Sunday:** 4 hours
- **Total:** 18 hours

---

## Objectives for Week 01
- Understand STP operation and elections
- Predict STP behavior from topology
- Configure and verify STP variants
- Troubleshoot common STP failures
- Document labs clearly in GitHub

---

## Daily Plan

### Monday (2h)
- **Theory (1h):**
  - STP fundamentals
  - Root bridge election
- **Lab (1h):**
  - Build a basic 3-switch L2 topology (triangle)
  - Verify STP state and root

---

### Tuesday (2h)
- **Theory (45 min):**
  - Port roles and port states
- **Lab (1h15):**
  - Force root bridge using priority
  - Observe root and designated ports

---

### Wednesday (2h)
- **Theory (45 min):**
  - STP timers (Hello, Max Age, Forward Delay)
- **Lab (1h15):**
  - Manipulate port cost and priority
  - Observe topology changes

---

### Thursday (2h)
- **Theory (45 min):**
  - RSTP vs STP overview
- **Lab (1h15):**
  - Enable RSTP
  - Compare convergence behavior

---

### Friday (2h)
- **Review (1h):**
  - Key commands and outputs
- **Documentation (1h):**
  - Write notes under `01-Layer2/STP`
  - Commit changes to GitHub

---

### Saturday (4h)
- **Deep Lab (3h):**
  - Inject failures:
    - Root bridge change
    - Link failure
    - Misconfigured priorities
- **Troubleshooting (1h):**
  - Identify root cause
  - Document recovery steps

---

### Sunday (4h)
- **Full Scenario Lab (2h):**
  - End-to-end STP topology
- **Review (1h):**
  - Lessons learned
- **GitHub (1h):**
  - Final commit for the week

---

## Key Verification Commands
```text
show spanning-tree
show spanning-tree vlan <id>
show spanning-tree interface <interface>
```

---

## Deliverables
- STP topology diagram
- Configuration snippets
- Troubleshooting notes
- GitHub commits under:
  `01-Layer2/STP/`

---

## Success Criteria
- Predict STP behavior without trial-and-error
- Quickly identify the root bridge
- Explain STP decisions clearly under pressure

---

_End of Week 01_
