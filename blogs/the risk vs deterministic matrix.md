---
name: Where to look for an anti-hype AI startup
description: We can make a risk vs. determinism matrix
---

## Start with a simple quadrant chart

Let's make a 2x2 matrix. The x-axis represents determinism: given a specific input, how strictly can we constrain the output? The y-axis represents risk: if something goes wrong, how bad are the consequences?

Here are two examples.

Surgery: Unlike mass-produced objects, every patient is different, which makes surgery inherently nondeterministic. If something goes wrong, the consequences can be severe.

Another example is financial tracking. You can write code to parse specific formats, but the real challenge lies in handling the unpredictable, inconsistent, and highly fragmented ways different financial institutions export data. As a result, purely programmatic approaches have not solved the problem—RIP Intuit Mint, and less RIP Chase Blueprint—and the remaining products continue to struggle.

```mermaid
quadrantChart
    title Risk vs. Determinism in Complex Domains and AI
    x-axis Non-deterministic --> Deterministic
    y-axis Low Risk --> High Risk
    quadrant-1 Strict and Critical
    quadrant-2 Complex and Critical
    quadrant-3 Flexible and Low Stakes
    quadrant-4 Rigid and Low Stakes
    Surgery Healthcare: [0.15, 0.95]
    Autonomous Driving: [0.30, 0.88]
    Biotech Drug Discovery: [0.20, 0.80]
    Quant Trading Execution: [0.85, 0.90]
    Financial Data Tracking: [0.25, 0.55]
    Recruiting AI Screening: [0.35, 0.40]
    Customer Service: [0.40, 0.25]
    Software Development Assist: [0.65, 0.30]
    Architectural Design: [0.80, 0.15]
    Architectural Rendering: [0.48, 0.15]
```

## My take

I don't see an AGI coming up any time sooner. My current bet is AI is best suited to low-risk, nondeterministic work.
