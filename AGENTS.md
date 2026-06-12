# AGENTS.md

## Scope

These instructions apply to all files in this repository.

This section is a Quarto coursebook for NREC4107 Applied Econometrics. The material is intended for undergraduate Natural Resource Economics students. The tone should be clear, practical, and beginner friendly.

## Core working rules

1. Think before editing.
   - Read the relevant files before making changes.
   - Do not assume requirements that are not stated.
   - If something is ambiguous but still safely solvable, make a conservative choice and report the assumption.
   - Ask for clarification only when the task cannot be completed safely.

2. Keep changes simple.
   - Make the minimum necessary change.
   - Do not add speculative features.
   - Do not introduce unnecessary abstractions.
   - Preserve the existing coursebook style unless the user explicitly asks for a style change.

3. Make surgical changes.
   - Modify only files required by the requested task.
   - Do not refactor unrelated files.
   - Do not rename files, folders, headings, labels, or navigation entries unless explicitly requested.
   - Do not change wording, formatting, styling, or code outside the requested scope.
   - If unrelated problems are found, report them separately instead of fixing them.

4. Verify the goal.
   - Define the requested outcome before editing.
   - Run available checks when possible.
   - Prefer targeted checks over broad repository-wide changes.
   - Summarize exactly which files changed and why.

## Quarto rules

- Preserve valid Quarto YAML front matter.
- Preserve existing navigation links unless the task asks for navigation changes.
- Do not duplicate title blocks, horizontal navigation bars, or bottom navigation bars.
- Use Quarto callouts where appropriate, especially for notes, warnings, common mistakes, and interpretation.
- Keep page structure consistent across chapters.
- Avoid unnecessary raw HTML unless it already exists or is clearly needed.
- Do not add external dependencies unless explicitly requested.

## Python and data rules

- Keep Python examples simple and teachable.
- Prefer `pandas`, `numpy`, `matplotlib`, and `scikit-learn` when already used in the coursebook.
- Do not add complex packages unless explicitly requested.
- Do not fabricate real datasets, student data, grades, institutional records, or current real-world claims.
- Synthetic examples are allowed only when clearly presented as synthetic teaching examples.
- Preserve existing dataset paths unless the task asks for a dataset update.
- If changing code that reads data, keep paths compatible with the coursebook website structure.

## Teaching style

- Use short explanations.
- Focus on interpretation before technical detail.
- Prefer applied agricultural economics examples.
- Avoid long theoretical digressions.
- Avoid exercises unless explicitly requested.
- Use beginner-friendly language without oversimplifying core econometric meaning.
- Keep chapters light and website-readable.

## Figures and assets

- Prefer clean SVG figures when new figures are needed.
- Do not add binary files unless explicitly requested.
- Do not add decorative images that increase repository size without clear teaching value.

## Content integrity

- Do not fabricate citations, references, policies, grades, schedules, student names, or institutional claims.
- If a citation or current factual claim is needed, report that it must be verified externally.
- Do not present placeholder content as factual.
- Do not silently invent missing course information.

## Final response requirements

After completing a task, report:

1. Files changed.
2. What changed in each file.
3. Checks run and their results.
4. Any checks that could not be run, with the reason.
5. Any unrelated issues noticed but not fixed.
