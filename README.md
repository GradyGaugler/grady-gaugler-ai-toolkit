# Grady's AI Prompt Library

Welcome to Grady's collection of reusable AI resources—concise prompts and flexible document templates designed to speed up and standardize everyday AI-assisted workflows.

## Purpose
This repository serves as a central, version-controlled library for:

• **Prompts** – carefully crafted instructions that drive consistent results across different AI tools.
• **Templates** – markdown scaffolds that help the AI produce long-form content (reports, articles, etc.) with minimal setup.

Together, these resources make it easy to plug high-quality, pre-vetted building blocks into any AI project.

## Directory Overview

• `prompts/`   Single-purpose prompt files, each containing exactly one prompt.
• `templates/` Reusable document skeletons that guide content generation.

## Governance – Cursor Rules
A lightweight “constitution” (see `prompts/cursor-plan-mode` for an example) defines conventions for naming, placement, and metadata. In short:

1. All new filenames use **kebab-case**.
2. New markdown files inside `prompts/` or `templates/` begin with a YAML front-matter block containing required metadata (`title`, `type`, `tags`, `status`, `created`).
3. File modifications must keep the front-matter accurate and up to date.

> **Note:** This root-level README is the sole exception to those rules—no front-matter is required here.

## Getting Started
Clone the repo, explore the `prompts/` and `templates/` directories, and copy any file you need into your workflow. When adding new material, follow the Cursor Rules to keep the library consistent and searchable.

---

Made with ☕ and keen attention to prompt engineering best practices. 