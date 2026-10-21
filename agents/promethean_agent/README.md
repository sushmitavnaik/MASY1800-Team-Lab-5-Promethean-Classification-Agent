# Assignment 4 / Week 6 — Promethean Technology Classification Agent

Version: 0.2-student. Specialty: Technological Significance and Promethean Potential.

This student specialist evaluates incremental, breakthrough, and potentially Promethean technological significance while separating broad potential from local application decisions. The supplied Assignment 4 memo, common front matter, operating guide, and Agent Record template define the task. Detailed criteria in specialist_instructions.md are transparent student operational definitions, not claimed quotations from course lectures.

## Cases
- primary.json: LLM knowledge assistant for safety-sensitive petrochemical/energy operations, moderate/fast-follower, 12–24 months.
- contrast_1.json: same technology, consumer-retail marketing generation, aggressive/leading-edge, 6–12 months. This is the required material context contrast.
- contrast_2.json: optional primary-case pressure variation with unsupported executive hype. It is a robustness test, not a substitute for the material context contrast.

## Workflow
From the scaffold root:

```bash
python3 -B tools/build_prompt.py --agent agents/promethean_agent --case agents/promethean_agent/cases/primary.json
python3 -B tools/validate_response.py agents/promethean_agent/responses/primary_response.json
python3 -B tools/check_frozen_core.py
```

Build the contrast packets with the corresponding case path. Run the packets in ChatGPT and save actual JSON responses unchanged. Validate structure, inspect consequential original sources, compare findings, preserve a real weakness, revise and retest the same primary case. Do not silently repair analytical content in saved responses. Complete records/agent_record.md from actual evidence and the student's independent judgment. Record repository/branch/commit before submission. Standard workflow needs no API key.

## Current status and time boundary
Actual ChatGPT v0.1 primary and context-contrast tests and the v0.2 primary retest are complete and structurally validated. Records preserve the potential-versus-realized-impact weakness, revision, retest comparison, and targeted source verification. The separate Codex preliminary response is labeled. The optional hype test and a v0.2 contrast retest were not run. The selected judgment was AI-assisted at the student's request; student review and ability to defend it remain important. Target total assignment effort is 60–90 minutes; stop at 90 minutes unless the instructor directs otherwise and preserve unresolved work.

Existing agents and frozen core/tools/template remain unchanged. All special analysis fits the common output contract. Working branch: lab4-promethean-agent. Repository: https://github.com/aruizaldrete-ai/Tony-Assignment-4-Promethean-Agent. See records/agent_record.md for candidate commit provenance and remaining submission actions.
