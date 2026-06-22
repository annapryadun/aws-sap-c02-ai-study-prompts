
# Round 3: Full Practice with Explanations

## Objective
Simulate exam conditions with adaptive difficulty and deep understanding of incorrect answers.

## Why This Matters
Unlike traditional practice test platforms with fixed question pools, this approach generates unique questions on demand, adapts to your weak areas, and allows follow-up questions for deeper understanding. The feedback loop accelerates learning significantly.

## How to Start

Type `/round3` in Claude Code to begin. The slash command is pre-configured in `.claude/commands/round3.md`.

The prompt Claude Code will use:

---

Let's begin Round 3: Full Practice with Explanations.

Generate unique SAP-C02-style questions that adapt to my weak areas. Simulate exam conditions with the following parameters:

**Question format:**
- Scenario: 150–300 words (matching real exam verbosity)
- Options: 4 choices (A–D), each 2–4 sentences
- Mix of single-answer and multi-select (select TWO) questions
- Include questions that span multiple domains/services

**Feedback protocol:**
- If I answer correctly: Brief confirmation (2–3 sentences) of why it's right and the architectural principle demonstrated
- If I answer incorrectly: Detailed explanation including:
  1. Why my choice was wrong (specific technical reason)
  2. Why the correct answer is better (architectural trade-off)
  3. The relevant AWS documentation link
  4. The architectural principle or pattern being tested
  5. A "watch for" tip — what signal in the question should have pointed me to the correct answer

**Adaptive behavior:**
- After every 10 questions, show my accuracy breakdown by domain:
  - Domain 1: Organizational Complexity (26%)
  - Domain 2: New Solutions (29%)
  - Domain 3: Continuous Improvement (25%)
  - Domain 4: Migration & Modernization (20%)
- Identify patterns in my incorrect answers (e.g., "You tend to miss networking constraints" or "You over-engineer when the question asks for minimal overhead")
- Generate the next set focused 60% on my weak areas, 40% on maintaining strong areas
- Gradually increase difficulty as my accuracy improves

**Time pressure simulation:**
- After every 5 questions, remind me of my average time per question
- Flag if I'm spending too long (target: under 2.5 minutes per question)

---

## Session Structure

| Questions | Focus |
|-----------|-------|
| 1–10 | Baseline assessment across all domains |
| 11–20 | Targeted practice on identified weak areas |
| 21–30 | Mixed difficulty with emphasis on multi-service questions |
| 31–40 | High-difficulty questions spanning multiple domains |
| 41–50 | Simulated exam block (timed, no breaks) |

## Success Criteria
- 80%+ accuracy across all domains
- Consistent performance under time pressure
- Ability to explain WHY the correct answer is correct (not just recognize it)
