# Assignment 3 / Week 5 — Innovation and Disruption Agent

NYU MASY1-GC 1800 Emerging Technologies. Version: 0.2-student.

This specialist classifies innovation and analyzes creative destruction and business-model disruption using the user's authoritative Assignment 3 requirements. It preserves the existing input and output contracts and is separate from Assignment 2's Creation Agent.

## Inputs and reproducible workflow
- Primary: LLM operations knowledge assistant in a safety-sensitive petrochemical/energy organization, 12–24 months.
- Contrast 1: LLM marketing generation at a large consumer retailer, 6–12 months.
- Optional contrast 2: LLM drafting of internal meeting minutes at a hypothetical wholesaler, 6–12 months; tests ambiguous novelty and possible overstatement of disruption.

Primary and contrast 1 preserve supplied descriptions in the common intake fields. Additional organizational facts must be sourced or explicitly treated as assumptions. Contrast 2 is a synthetic test case, not a factual company description.

From the scaffold root, build a primary packet with:

```bash
python3 tools/build_prompt.py --agent agents/innovation_disruption_agent --case agents/innovation_disruption_agent/cases/primary.json
```

Run the packet in ChatGPT, save its actual JSON in this agent's responses directory, and validate using the supplied validator. Repeat for contrast cases and record an observed weakness, revision and retest. The saved responses preserve the actual ChatGPT runs; rebuilding a prompt does not execute an analytical test.

## Status and boundaries
The v0.1 primary, context contrast, and borderline tests are complete, followed by an evidence-policy revision and a v0.2 primary retest. All four saved responses pass the supplied structural validator. The Agent Record documents findings, the preserved citation-matching weakness, partial improvement, and remaining limitations. Structural validation does not establish factual accuracy. Classification/disruption judgments stay within existing output fields; no schema edits are needed.

Do not modify core/, tools/, agents/_template/, or agents/creation_agent/. Source policy and handoffs are specified in specialist_instructions.md.
