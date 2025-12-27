Product-Requirements: AI-Generated Product Requirements Documents

Comprehensive PRD generation optimized for AI-assisted development workflows

Author: Ankit Kushwaha
Email: ankitkushwha7787@gmail.com

GitHub: https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents

License: MIT
Status: Beta

What is This?

A Claude Code skill that generates detailed, engineer-focused Product Requirements Documents (PRDs) designed to work seamlessly with AI task breakdown tools like Taskmaster.

Think of it as your AI product manager that asks the right questions, writes comprehensive specs, and sets you up for successful implementation.

Why You Might Want This
The Problem

You have an idea for a feature or product, but:

Writing comprehensive PRDs takes hours

You’re not sure what details to include

You want to use AI task breakdown tools (like Taskmaster) but they need detailed requirements

Vague specs lead to vague tasks, which lead to poor implementations

The Solution

This skill:

Asks 12+ detailed questions to extract all context

Generates a comprehensive PRD with all the sections engineers need

Sets up Taskmaster integration with proper directory structure

Validates quality with 13 automated checks

Suggests task breakdowns with complexity estimates and dependencies

Result: You go from “I have an idea” to “I have a complete, validated PRD ready for AI task generation” in minutes.

Installation
Option A: Claude Code CLI (Recommended)

Prerequisites:

Claude Code CLI installed

Git

Install the skill:

cd ~/.claude/skills
git clone https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents.git Product-Requirements


Verify installation:

claude
# In the chat, type:
# "I want a PRD for adding dark mode"


Troubleshooting:

Ensure skill is in ~/.claude/skills/Product-Requirements/

SKILL.md should exist in that directory

Restart Claude Code if needed

Check skill is enabled: type /help and look for the description

Option B: Codex (Untested)

Prerequisites:

Codex installed

Git

Install the skill:

cd ~/desired-directory
git clone https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents.git Product-Requirements
cd Product-Requirements


Configure Codex to find the skill:

Run Codex in the Product-Requirements directory

Initialize Codex: /init

Confirm Codex reads SKILL.md

Verify installation:
Ask Codex to generate a PRD and check workflow output.

Quick Start Guide

Basic Usage:

"I want a PRD for [your feature/product]"


Activation phrases:

"I want a PRD for adding two-factor authentication"

"Create product requirements for a user dashboard"

"Write a PRD for integrating with Stripe payments"

"Generate requirements for building a dark mode feature"

What Happens Next:

Skill asks 12+ detailed questions (problem, target user, metrics, tech stack, constraints, etc.)

Analyzes codebase (if applicable)

Generates a comprehensive PRD with all sections

Sets up taskmaster/ directory

Runs 13 automated quality checks

Suggests task breakdowns with dependencies and complexity

Shows summary and next steps

First-Time Tips

Be detailed in your answers! More context = better PRD

Example good answer:

"We need 2FA because we're seeing 150 security incidents per month from compromised accounts. Target users are enterprise customers who require SOC2 compliance. Success = reduce incidents to <10/month and meet SOC2 requirements."

Example too-vague answer:

"We need 2FA for security."

What You Get

📄 Comprehensive PRD

Executive Summary

Problem Statement

Goals & Metrics

User Stories

Functional Requirements

Technical Considerations

Task Breakdown Hints

Dependencies

Out of Scope

🗂️ Taskmaster Integration

taskmaster/
├── docs/
│   ├── prd.md
│   └── architecture.md
├── tasks/
│   └── .gitkeep
├── notes/
│   └── .gitkeep
└── .gitignore


🤖 CLAUDE.md / codex.md – TDD Workflow Guide

Quality Validation

13 automated checks ensure:

All sections present

Requirements are testable

Success metrics are SMART

Technical considerations addressed

Task breakdown hints included

Dependencies mapped

Example Output

PRD Created: taskmaster/docs/prd.md
CLAUDE.md Generated: Project root
codex.md Generated: If using Codex

Feature: Two-Factor Authentication
Complexity: Medium
Estimated Effort: 26 tasks, ~119 hours
Key Goal: Reduce security incidents from 150/month to <10/month

Who Is This For?

Perfect if:

You use AI-assisted development workflows

You want Taskmaster or similar task breakdown tools

You prefer detailed planning before coding

Maybe not if:

You prefer writing PRDs yourself

You do not use AI development tools

Advanced Usage & Customization

Automatic MCP detection for seamless integration

Templates in templates/ folder:

taskmaster-prd-comprehensive.md

taskmaster-prd-minimal.md

Manual validation checklist in reference/validation-checklist.md

Development Approach

Iterative “vibe-coding” approach

Tested with web/API projects

Status: Beta

Your Feedback Matters

Found a bug? Open an issue

Want new templates or validation rules? Contribute!

Contributing

Fork the repo

Make changes

Test with real projects

Submit PR with:

What you changed

Why you changed it

How you tested it

License

MIT License – Use freely, modify, share improvements.

Contact: Ankit Kushwaha – ankitkushwha7787@gmail.com

GitHub: https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents.


