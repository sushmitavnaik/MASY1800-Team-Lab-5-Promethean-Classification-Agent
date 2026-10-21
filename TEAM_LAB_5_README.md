# Team Lab 5 — Promethean Classification Agent starter

**Status: team-testing starter; not yet team-approved.**

Base: Tony’s uploaded Assignment 4 repository ZIP. Original agent instructions, original test outputs, and frozen scaffold have been preserved. Added two unrun Team Lab 5 cases under `agents/promethean_agent/cases/`. No test outputs or consensus decisions have been invented.

## Run common test
```powershell
python tools/check_frozen_core.py
python tools/build_prompt.py --agent agents/promethean_agent --case agents/promethean_agent/cases/team_lab5_common_case.json
```
Open the generated prompt under `work/` and run it in a new ChatGPT conversation. Save the JSON response to `agents/promethean_agent/responses/team_lab5_common_response.json` and validate with:
```powershell
python tools/validate_response.py agents/promethean_agent/responses/team_lab5_common_response.json
```

## Run hype test
```powershell
python tools/build_prompt.py --agent agents/promethean_agent --case agents/promethean_agent/cases/team_lab5_hype_case.json
```
Run in a separate ChatGPT conversation; save JSON as `agents/promethean_agent/responses/team_lab5_hype_response.json`; validate it.

## Team decision still required
Compare the same cases using the second candidate agent without changing either specialist’s instructions. The five-person team should document candidate comparison, sources, contrary evidence, actual common/hype test findings, dissent, whether to incorporate additional rival-classification checks, and its approved version/commit. Do not present this starter as a completed team artifact.
