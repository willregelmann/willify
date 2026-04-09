# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This repo is a collection of custom Claude Code skills. Each skill lives in `skills/<name>/SKILL.md` and follows the Claude Code skill format (YAML frontmatter + markdown body).

## Skill Structure

A skill file must have:
- `name` — identifier used to invoke the skill
- `description` — triggers when Claude Code decides which skill to use; be precise so it fires on the right prompts and not others
- `tags` — optional categorization

The body is a markdown prompt that Claude Code executes when the skill is invoked. Skills describe a process for Claude to follow, not code to run.
