
# Round 4: Note Consolidation

## Objective
Create a concise, exam-focused reference document from all study materials and practice sessions.

## Why This Matters
In the final days before the exam, you need a focused reference — not hundreds of pages of documentation. This round distills everything into decision frameworks and key facts that directly help you answer questions.

## Prompt

Copy everything between the two horizontal lines (---) below and paste it into Kiro after the setup prompt:

---

Let's begin Round 4: Note Consolidation.

Based on our study sessions across Rounds 1–3, generate consolidated study notes organized by exam domain. Structure the notes as follows:

**For each domain, include:**

1. **Key Decision Frameworks** — When to use Service A vs Service B (formatted as decision trees or comparison tables)
2. **Common Exam Traps** — Patterns in wrong answers and how to avoid them
3. **Critical Service Behaviors** — Non-obvious behaviors, limitations, and edge cases that appear in exam questions
4. **Architecture Patterns** — Frequently tested patterns with their use cases and constraints
5. **Quick Reference** — One-line summaries of the most important facts per service

**Domain structure:**

### Domain 1: Design Solutions for Organizational Complexity (26%)
- Multi-account strategies (Organizations, Control Tower, SCPs)
- Cross-account access patterns (IAM roles, resource policies, RAM)
- Governance and compliance at scale
- Networking across accounts (Transit Gateway, VPC sharing, PrivateLink)

### Domain 2: Design for New Solutions (29%)
- Compute selection (Lambda vs Fargate vs ECS vs EKS vs EC2)
- Database selection (RDS vs Aurora vs DynamoDB vs Redshift vs Neptune)
- Storage decision trees (S3 classes, EBS vs EFS vs FSx, Storage Gateway)
- Event-driven architectures (EventBridge, SNS, SQS, Step Functions)
- Analytics pipelines (Kinesis, Glue, Athena, EMR, Lake Formation)

### Domain 3: Continuous Improvement for Existing Solutions (25%)
- Cost optimization strategies (Savings Plans, Reserved Instances, Spot, lifecycle policies)
- Performance optimization (caching, CDN, read replicas, connection pooling)
- Operational excellence (CloudWatch, X-Ray, Systems Manager, Config)
- Security improvements (encryption, rotation, least privilege, detective controls)

### Domain 4: Accelerate Workload Migration and Modernization (20%)
- Migration strategies (6 Rs: Rehost, Replatform, Refactor, Repurchase, Retire, Retain)
- Migration services (DMS, MGN, DataSync, Snow Family, Transfer Family)
- Modernization patterns (monolith to microservices, containers, serverless)
- Hybrid architectures (Direct Connect, VPN, Storage Gateway, Outposts)

**Format requirements:**
- Keep each section concise (bullet points, not paragraphs)
- Include "Exam Tip" callouts for non-obvious facts
- Use comparison tables for service selection decisions
- Highlight constraint keywords that signal specific solutions

---

⚠️ **Everything below this point is for your reference only — do not paste into Kiro.**

## How to Use These Notes

1. **Days 1–3 before exam**: Read through all domains, highlight anything unfamiliar
2. **Day before exam**: Focus only on highlighted items and decision frameworks
3. **Morning of exam**: Quick scan of "Common Exam Traps" section only

## Success Criteria
- Notes fit within 15–20 pages (concise enough to review in 2–3 hours)
- Every bullet point is directly useful for answering exam questions
- Decision frameworks cover the most common "A vs B" choices on the exam

