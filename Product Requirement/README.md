Product-Requirements: AI-Generated Product Requirements Documents

Comprehensive PRD generation optimized for AI-assisted development workflows






Author: Ankit Kushwaha
Email: ankitkushwha7787@gmail.com

GitHub: https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents

What is This?

A Claude Code skill that generates detailed, engineer-focused Product Requirements Documents (PRDs) designed to work seamlessly with AI task breakdown tools like Taskmaster.

Think of it as your AI product manager that asks the right questions, writes comprehensive specs, and sets you up for successful implementation.

Why You Might Want This
The Problem

You have an idea for a feature or product, but:

Writing comprehensive PRDs takes hours

You're not sure what details to include

You want to use AI task breakdown tools (like Taskmaster) but they need detailed requirements

Vague specs lead to vague tasks, which lead to poor implementations

The Solution

This skill:

Asks 12+ detailed questions to extract everything from your brain

Generates a comprehensive PRD with all the sections engineers need

Sets up taskmaster integration with proper directory structure

Validates quality with automated checks (13 different validations)

Suggests task breakdowns with complexity estimates and dependencies

Result: You go from "I have an idea" to "I have a complete, validated PRD ready for AI task generation" in minutes.

Installation

This skill works with Claude Code CLI and Codex (VS Code extension). Choose your tool below:

Option A: Claude Code CLI (Recommended)

Prerequisites:

Claude Code CLI installed (installation guide
)

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

Check skill is enabled by typing /help

Option B: Codex (Untested)

Prerequisites:

Codex (see
)

Git

Install the skill:

cd ~/desired-directory
git clone https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents.git Product-Requirements
cd Product-Requirements


Configure Codex:

Run Codex in the Product-Requirements directory

Initialize Codex: /init

Codex will read SKILL.md and understand how to generate PRDs

Verify installation:
Ask Codex:

What would you do if I told you to generate a PRD?

Quick Start Guide
Basic Usage
"I want a PRD for [your feature/product]"


Activation phrases:

"I want a PRD for adding two-factor authentication"

"Create product requirements for a user dashboard"

"Write a PRD for integrating with Stripe payments"

"Generate requirements for building a dark mode feature"

What Happens Next

Ask 12+ detailed questions (problem, target user, metrics, tech stack, constraints, etc.)

Analyze your codebase (if applicable)

Generate a comprehensive PRD with all sections, task hints, and complexity estimates

Set up taskmaster integration (not .taskmaster)

Validate everything with 13 automated quality checks

Show summary & next steps

Be detailed in your answers — the more context you provide, the better the PRD.

Taskmaster Directory Structure
taskmaster/
├── docs/
│   ├── prd.md
│   └── architecture.md
├── tasks/
│   └── .gitkeep
├── notes/
│   └── .gitkeep
└── .gitignore


CLAUDE.md / codex.md guide the TDD workflow, agents usage, parallel task execution, validation, and quality gates.

Quality Validation

13 automated checks ensure:

All required sections are present

Requirements are testable

Success metrics are SMART

Technical considerations addressed

Task breakdown hints included

Dependencies mapped

Example Output
📄 PRD Created: taskmaster/docs/prd.md
🤖 CLAUDE.md Generated: Project root
   + codex.md (if you're using Codex)

Advanced Features (v2.0)

Real DateTime Tracking – UTC timestamps, duration, JSON persistence

Instant Rollback Command – Rollback to any task checkpoint

Accuracy Learning System – Adjust estimates based on actual pace

Security Audit Checklist – Auto-generated scans and standard checks

Auto-Resume After Crash – Detect incomplete sessions and continue safely

All enhancements work with MCP or CLI integration.

Contributing
# Fork the repo
# Make changes
# Test with real projects
# Submit PR with:
# - What you changed
# - Why you changed it
# - How you tested it


License: MIT
Author: Ankit Kushwaha – ankitkushwha7787@gmail.com

GitHub: https://github.com/Ankitkushwaha2004/AI-Generated-Product-Requirements-Documents
