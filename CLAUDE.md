# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a collection of specialized AI prompt templates designed for different domains and use cases. The repository contains three main prompt templates:

1. **SAP_3_fpga_analysis.txt** - Technical analysis prompt for Verilog-based CPU implementations
2. **meta_prompt.txt** - Meta-prompt generator using the C.R.A.F.T. framework
3. **personal_brand_coach.txt** - LinkedIn personal branding strategy prompt

## Architecture

Each prompt follows a structured format with these key sections:
- **Context**: Situational background and purpose
- **Role**: Expertise definition and experience level
- **Action**: Sequential numbered steps to follow
- **Format**: Output structure and presentation requirements
- **Target Audience**: Intended users and their characteristics

## Working with Prompts

When modifying or creating new prompts:
- Maintain the established sectional structure (Context, Role, Action, Format, Target Audience)
- Ensure roles specify "industry-leading expert with 20+ years experience"
- Use numbered action lists for clear sequential execution
- Specify concrete output formats (markdown, tables, code blocks, etc.)
- Define target audience demographics and expertise levels
- Keep technical language appropriate for the specified audience

## File Naming Convention

Use descriptive names with underscores for prompt files:
- Domain-specific: `[domain]_[use_case]_[type].txt`
- Meta-prompts: `meta_[purpose].txt`
- Coaching/advisory: `[subject]_coach.txt`