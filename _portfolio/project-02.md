---
title: "Formal Verification of AGV Emergency Stop"
excerpt: "Formal verification of safety-critical control logic for an AGV emergency stop function using a FRET → NuSMV → UPPAAL pipeline."
collection: portfolio
---

**Type:** Research project
**Tools:** FRET, NuSMV, UPPAAL, EN ISO 13849-1

Applied a formal verification pipeline to safety-critical control logic for an automated guided vehicle (AGV) emergency stop function. Requirements were specified in FRET, translated to NuSMV for model checking, and verified in UPPAAL for timed behavior.

The verification process revealed a one-cycle timing hazard that was not visible through consistency analysis alone - demonstrating the value of formal methods for safety-critical PLC logic beyond what standard safety standards currently require.

**Key aspects:**
- Requirements formalization using NASA FRET
- Model checking with NuSMV
- Timed automata verification with UPPAAL
- Discovery of timing hazard invisible to consistency analysis
- Context: AGV emergency stop per EN ISO 13849-1
