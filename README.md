# 🤖 AI Engineer Technical Assignment: Vulnerability Remediation Challenge


## 📋 Overview

**🎯 Objective:** Design an AI-powered vulnerability remediation system and implement a smart package bumping agent that can automatically upgrade vulnerable dependencies.

---

## 🚀 The Challenge

### Part 1: System Architecture Design

Design an **AI-powered CVE remediation system** that handles the complete vulnerability lifecycle.

**System Flow:**

1. Takes a container image as input
2. Scans it for vulnerabilities
3. Collects security advisory information for each CVE:
   - Fixed versions available
   - Patches available
   - Severity and exploitability data
   - Dependency impact
4. Decides on remediation strategy for each vulnerability:
   - **Bump**: Upgrade to a fixed version
   - **Backport**: Apply security patch without major version change
   - **Patch**: Apply a specific security fix
5. Generates an actionable remediation plan

**Your Task:**

Create an **architecture document (PDF)** that includes:

- **System Design**
  - High-level architecture diagram showing:
    - Image scanning pipeline
    - CVE detection and advisory collection
    - AI decision-making components
    - Remediation plan generation

- **Technology Choices**
  - What AI techniques would you use? (LLMs, RAG, reasoning agents, etc.)
  - How would you integrate with scanners and advisory databases?
  - Key services and frameworks

---

### Part 2: AI Bumper Agent Implementation

Implement a working **AI-powered version bumping agent** that can automatically upgrade vulnerable package dependencies.

**Requirements:**

Build an agent that:

1. Analyzes a package's dependencies
2. Identifies vulnerable packages
3. Uses AI to:
   - Understand what each dependency does
   - Assess the risk of upgrading
   - Recommend specific version bumps
   - Explain the reasoning
4. Outputs a structured upgrade plan

**Test Projects:**

Choose one of these real-world projects to test your agent:
- [Thanos](https://github.com/thanos-io/thanos)
- [Terraform](https://github.com/hashicorp/terraform)
- Or any other **open-source package** you prefer

**Implementation Notes:**

- **Language**: Use any language you're comfortable with (Python, Go, TypeScript, etc.)
- **AI Integration**: You can use:
  - LLM APIs (OpenAI, Anthropic, etc.)
  - Mocked AI responses if you prefer
  - Local models
- **Keep it simple**: Focus on demonstrating the AI reasoning, not building a production tool

---

## 📝 Deliverables

- **Part 1**: Architecture document (PDF) with clear diagrams and explanations
- **Part 2**: Implementation code in forked repository
	- 	README with:
  		- How to run your agent
  		- Example output from testing
  		- Your design decisions and trade-offs
		- Any test results or sample outputs

You'll walk us through your work in your technical interview.

---

## 💡 Reminders

- Focus on quality of reasoning over volume.
- Don't make this production-grade; you can do things that don't scale.
- AI tools are welcome. Tell us what you used them for and where they helped or hurt.
- If you hit a wall, write down what you tried and move on.

---

## 🚢 Submission

- Create a fork of this repository and give access to your fork
- Email us your architecture PDF and link to your forked repository

---

## ❓ Questions

Have fun! For any question or clarification, reach out without a second thought 🙂

**Echo Team**
