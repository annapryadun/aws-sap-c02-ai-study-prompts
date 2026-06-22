
# Round 2: Elimination Technique

## Objective
Develop systematic elimination of incorrect options before selecting the correct answer.

## Why This Matters
With 4 options per question, eliminating even 2 wrong answers improves your odds from 25% to 50%. The SAP-C02 options are architecturally plausible in isolation — the skill is recognizing which option most directly addresses the specific requirements and constraints.

## How to Start

Type `/round2` in Claude Code to begin. The slash command is pre-configured in `.claude/commands/round2.md`.

The prompt Claude Code will use:

---

Let's begin Round 2: Elimination Technique.

Generate a full SAP-C02-style question with 4 answer options (A–D). Each option should be a detailed architectural solution (2–3 sentences each). Make the options plausible but distinguishable through careful analysis.

My task is to eliminate incorrect options before selecting the correct one.

For each question:
1. I will identify which options to eliminate and state my reasoning
2. Then I will select my final answer
3. You confirm which eliminations were correct and explain the elimination category for each:
   - **Service mismatch**: Service doesn't address the stated requirement (e.g., Security Group for a performance problem)
   - **Constraint violation**: Violates an explicit requirement in the question
   - **Over-engineering**: Introduces unnecessary complexity when a simpler solution exists
   - **Scope mismatch**: Solves a different problem than what was asked
   - **Self-contradicting**: Option negates itself based on how the service actually works

After each question, also explain:
- Which elimination was the easiest to spot (and why)
- Which elimination was the trickiest (and what signal to look for)

Track my elimination accuracy separately from my answer accuracy. After 10 questions, identify which elimination patterns I'm missing most frequently.

---

## Elimination Framework

When evaluating each option, ask yourself:

| Check | Question to Ask |
|-------|----------------|
| Service fit | Does this service actually solve the stated problem? |
| Constraint compliance | Does this option violate any explicit requirement? |
| Complexity | Is there a simpler way to achieve the same result? |
| Scope alignment | Does this solve what was actually asked? |
| Technical validity | Does this option make sense given how the service works? |

## Success Criteria
- Correctly eliminating 2+ options per question before answering
- Accurately categorizing elimination reasons
- Identifying the "trap" option (the one designed to look correct but violates a constraint)
