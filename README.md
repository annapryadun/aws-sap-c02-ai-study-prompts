<div align="center">
<h1>AWS Certified Solutions Architect Professional</h1>

<img src="AWS-Certified-Solutions-Architect-Professional_badge.png">
</div>

## 📖 About

This repository contains the exact prompts I used to prepare for and pass the **AWS Certified Solutions Architect — Professional (SAP-C02)** exam in 21 days using [Kiro](https://kiro.dev/) (an agentic AI-powered IDE) with Claude Sonnet 4.6.

Instead of traditional video courses and practice test platforms, I structured my preparation into four distinct rounds — each designed to build a specific skill needed for the exam. These prompts turn AI into an adaptive study partner that generates unique questions, tracks your weak areas, and provides immediate feedback with documentation links.

**Read the full article:** [How I cleared the AWS Solutions Architect Professional exam in 21 days using AI](https://www.rogernem.com)

## 🎯 Who Is This For?

- AWS professionals preparing for the SAP-C02 exam
- Anyone looking for an adaptive, AI-driven study approach
- Candidates who want to maximize study efficiency while managing career and family responsibilities
- People who learn better through active practice than passive video consumption

## 📁 Repository Structure

| File | Purpose |
|------|---------|
| `README.md` | You are here |
| `00-setup-prompt.md` | Initial Kiro configuration |
| `01-round1-keyword-identification.md` | Train rapid info extraction |
| `02-round2-elimination-technique.md` | Systematic option elimination |
| `03-round3-full-practice.md` | Adaptive exam simulation |
| `04-round4-note-consolidation.md` | Focused reference creation |

## 🚀 Quick Start

### Prerequisites

1. Install [Kiro](https://kiro.dev/) IDE
2. Configure the following MCP servers in your Kiro settings:
   - [AWS Documentation MCP Server](https://awslabs.github.io/mcp/)
   - [AWS Knowledge MCP Server](https://awslabs.github.io/mcp/)
3. Download the [SAP-C02 Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-pro/AWS-Certified-Solutions-Architect-Professional_Exam-Guide.pdf)

### Usage

1. **Clone this repo:**

   git clone https://github.com/rnem/aws-sap-c02-ai-study-prompts.git

2. **Start with the setup prompt:**
   Open `00-setup-prompt.md` and paste the configuration prompt into Kiro. This establishes the AI's role, context, and behavior for your study sessions.

3. **Progress through the rounds:**
   Follow the rounds in order — each builds on skills developed in the previous round.

## 📋 The Four Rounds

### Round 1: Keyword Identification (`01-round1-keyword-identification.md`)
**Objective:** Train rapid extraction of relevant information from verbose scenarios.

SAP-C02 questions are intentionally verbose — packed with realistic but irrelevant details. This round trains you to cut through the noise and identify only what drives the correct answer in under 30 seconds.

### Round 2: Elimination Technique (`02-round2-elimination-technique.md`)
**Objective:** Develop systematic elimination of incorrect options.

With 4 options per question, eliminating even 2 wrong answers improves your odds from 25% to 50%. This round teaches you to categorize eliminations: service mismatch, constraint violation, over-engineering, scope mismatch, and self-contradicting options.

### Round 3: Full Practice with Explanations (`03-round3-full-practice.md`)
**Objective:** Simulate exam conditions with adaptive difficulty.

Unlike fixed practice test platforms, this approach generates unique questions on demand, adapts to your weak areas, and provides detailed explanations with AWS documentation links for every incorrect answer.

### Round 4: Note Consolidation (`04-round4-note-consolidation.md`)
**Objective:** Create a concise, exam-focused reference document.

Distills everything from Rounds 1–3 into decision frameworks, common exam traps, and key facts organized by exam domain — designed to be reviewed in the final days before the exam.

## 📊 Exam Overview

| Detail | Value |
|--------|-------|
| **Exam Code** | SAP-C02 |
| **Questions** | 75 (65 scored, 10 unscored) |
| **Duration** | 180 minutes |
| **Time per Question** | ~2 min 24 sec |
| **Passing Score** | 750/1000 |
| **Validity** | 3 years |

### Domain Weightings

| Domain | Weight |
|--------|--------|
| Design Solutions for Organizational Complexity | 26% |
| Design for New Solutions | 29% |
| Continuous Improvement for Existing Solutions | 25% |
| Accelerate Workload Migration and Modernization | 20% |

## 🛠️ Key Services to Know Deeply

- **Organizations & Governance:** AWS Organizations, SCPs, Control Tower, RAM
- **Networking:** VPC peering, Transit Gateway, Direct Connect, PrivateLink, VPN CloudHub
- **Storage:** S3 (classes & lifecycle), EBS vs EFS vs FSx, Storage Gateway
- **Databases:** RDS vs Aurora vs DynamoDB vs Redshift vs Neptune
- **Migration:** DMS, MGN, DataSync, Snow Family, Transfer Family
- **Compute:** Lambda vs Fargate vs ECS vs EKS vs Batch
- **Analytics:** Kinesis (Streams vs Firehose), Glue, Athena, EMR, Lake Formation
- **Security:** IAM Identity Center, Cognito, KMS, Secrets Manager, WAF, Shield, GuardDuty
- **Cost Optimization:** Savings Plans, Reserved Instances, Spot, S3 lifecycle policies

## 💡 Tips for Success

- **Start with Round 1** — keyword identification was the highest-ROI activity
- **Spend the most time on Round 3** — full practice with explanations provides the most learning per hour
- **Customize the prompts** — adjust service focus areas based on your background
- **Maintain conversation continuity** — Kiro tracks performance across the session
- **Practice with time pressure** — target under 2.5 minutes per question
- **Take the exam at a testing center** — fewer technical issues than online proctoring
- **Practice with ambient noise** — testing centers are never completely silent

## 📝 License

This project is licensed under the MIT License — feel free to use, modify, and share these prompts.

---

*If you found this helpful, please ⭐ star this repository and share it with others preparing for the SAP-C02 exam!*

## Contact

Feel free to reach out to me! 👨‍💻 <br />

<a href="https://www.linkedin.com/in/rogertn">LinkedIn</a>
