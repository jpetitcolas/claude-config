## Repository Purpose

This repository contains reusable Claude configuration files that can be used across projects to enhance Claude's capabilities and provide consistent behavior.

## Architecture

The repository follows a simple structure:

- `.claude/commands/` - Contains custom Claude commands in markdown format

## Usage

This configuration is designed to be portable across projects. The retrospective command can be used to refine project-specific CLAUDE.md files based on actual usage patterns and user feedback.

## Guidelines

### Workflow

- Never automatically commit or push changes. Wait for explicit user request.

### Tool Usage

- Always use `./bin/curl` instead of the system `curl` command when making HTTP requests.