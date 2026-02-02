# 10 Academy Week 0 MCP Setup Challenge

## Overview
This repository documents work completed for the 1-hour Tenx MCP setup challenge. The goal is to validate that the development environment is configured with modern MCP tooling so AI agent assistants can operate with clear rules and telemetry.

## Competencies Assessed
| Competency | What We're Looking For |
| --- | --- |
| Technical Comprehension | Ability to follow technical instructions and configure MCP Sense (Tenx MCP server) correctly. |
| AI Openness & Curiosity | Willingness to explore AI-powered tooling (Cursor, Antigravity, Warp, Claude Code, VS Code MCP servers, skills, agent rules, Coderabbit, etc.). |
| Motivation & Work Ethic | Consistent effort, prompt communication, and task completion within the assessment window. |

## Challenge Tasks
### Task 1: Setup
- Use VS Code with the Tenx MCP server integration enabled.
- Follow the Tenx MCP Analysis documentation to authenticate against https://mcppulse.10academy.org/proxy as configured in .vscode/mcp.json.
- Keep the Tenx MCP connection active for the entire assessment so the interaction log remains complete.

### Task 2: Research & Configure Rules
- Maintain the VS Code agent rules in .github/copilot-instructions.md.
- Research best practices for guiding AI coding agents, including Boris Cherny's Claude workflow and community resources.
- Iteratively update the rules file, testing agent behaviour after each change to confirm the rules align with your workflow and expectations.

### Task 3: Documentation
Document all work inside this repository so reviewers can trace the setup process. At minimum include:
- **What you did** - detailed record of rule changes and configuration steps.
- **What worked** - configurations or approaches that improved the agent experience.
- **What didn't work** - issues encountered, troubleshooting steps, and partial solutions.
- **Insights gained** - reflections on how rule adjustments influence the agent's alignment with your intent and habits.

## Recommended Repository Structure
```
README.md
.github/
  copilot-instructions.md   # VS Code rules for GitHub Copilot
reports/
  mcpsetup-report.md        # Detailed documentation for Task 3
.vscode/
  mcp.json                  # Tenx MCP server connection settings
```
Adjust the layout as needed for your IDE choice. Include additional files generated during the assessment (logs, screenshots, snippets) when they add clarity.

## Working Notes Template
Use the following template (or similar) to capture Task 3 documentation:

```
# MCP Setup Report

## What I Did
- Step-by-step notes of configuration work.

## What Worked
- Successful commands, settings, or rule patterns.

## What Didn't Work
- Challenges faced, supporting error messages, and resolutions.

## Insights Gained
- Observations on how rule changes shaped agent behaviour.
```
## Resources
- Tenx MCP Analysis Documentation (internal reference).

## Next Steps
1. Complete the IDE-specific Tenx MCP configuration.

