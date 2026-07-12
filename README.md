# Academic English Paper Writing Skill

This folder is an Agent Skill for English academic paper writing and revision.

## Contents

- `SKILL.md` — main trigger description and workflow.
- `references/` — detailed writing rules loaded only when needed.
- `assets/section_templates.md` — reusable manuscript and rebuttal templates.
- `examples/prompts.md` — example user requests and expected behavior.
- `manifest.txt` — file list for packaging/review.

## Intended Use

Use this skill to draft, revise, translate, polish, outline, or review English academic papers, especially CS/engineering papers written by Chinese-speaking authors.

## Install

Upload the zip file or folder to a Skills-compatible environment. The zip contains one top-level folder.


## Version 1.1 additions

- Adds a pre-drafting venue/field style calibration workflow.
- Instructs the skill to search recent target-conference or target-field papers before substantial drafting.
- Adds `references/venue_style_research.md`.
- Adds `references/public_skill_patterns.md`, summarizing design patterns from public writing and skill-creation skills.


## Version 1.2 additions

- Adds explicit crisp-sentence rules.
- Adds a hard default rule that every natural paragraph should begin with a topic sentence.
- Adds paragraph architecture rules: topic sentence, support, explanation/evaluation, link.
- Adds given-before-new information flow and active/passive voice guidance.
- Adds tense, modality, article, definiteness, register, and countability rules from the uploaded Lund courseware.
- Adds `references/academic_sentence_paragraph_rules.md`.
- Adds `references/courseware_synthesis.md`.


## Version 1.3 additions

- Adds a mandatory end-of-collaboration editorial audit for every manuscript drafting, translation, polishing, rewriting, or review task.
- Requires explicit checks for overlong or clause-heavy sentences, logical jumps, and defensive language aimed at hypothetical reviewers.
- Requires direct repair when technical meaning permits and concise reporting when an issue needs evidence or an authorial decision.
- Extends the final quality gate to verify full-output coverage, paragraph architecture, claim discipline, terminology, and information flow.
