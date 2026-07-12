# Public Writing Skill Patterns

Use this file when maintaining this skill, extending it, or explaining how public writing skills tend to be designed.

## Common Skill Design Patterns

Effective Skills usually follow these patterns:

1. Clear trigger description
   - The `description` field should say what the skill does and when to use it.
   - Include trigger words users are likely to write.
   - Keep the scope focused enough that the model selects the skill reliably.

2. Progressive disclosure
   - Keep `SKILL.md` focused on the main workflow.
   - Move long guidelines, examples, style rules, and templates into `references/` or `assets/`.
   - Tell the model exactly when to read each reference file.

3. Concrete workflow
   - Use numbered phases.
   - Prefer imperative instructions.
   - Define output formats.
   - Include quality gates and anti-patterns.

4. Research before writing
   - Writing skills often include a research phase before drafting.
   - For academic writing, research must include recent venue/field papers, not only general web pages.

5. Human-in-the-loop
   - Academic writing skills should help the user define the claim, method, evidence, and limitations.
   - The skill should not fabricate contributions, data, or citations.
   - Use placeholders when the user has not supplied required facts.

6. Iterative drafting
   - Strong writing workflows often follow a sequence such as:
     `Research -> Outline -> Draft -> Evaluate -> Revise -> Compress`.
   - The evaluation pass checks logic, evidence, reader expectations, and style consistency.

7. Reader testing
   - For important documents, review the draft as a fresh reader.
   - Ask whether the paper's problem, gap, contribution, and evidence are understandable without private context.

8. Anti-pattern lists
   - Explicitly name likely failure modes:
     - vague contribution
     - chronological lab-report narrative
     - unsupported claim
     - undefined acronym
     - inconsistent notation
     - overlong sentence
     - copied citation format
     - table or figure with no interpretation

## Patterns Borrowed into This Skill

This skill incorporates the following design ideas:

- Keep the main `SKILL.md` lean and procedural.
- Use references for detailed paper-writing rules.
- Add venue/field research before substantial drafting.
- Preserve user technical meaning and require evidence for claims.
- Use structured output formats that match the task type.
- Include a final quality gate.
- Treat the AI as a writing copilot, not the owner of the research.

## What This Skill Should Not Become

Avoid expanding this skill into:
- A general literature-review automation skill.
- A citation generator that invents references.
- A venue-submission compliance checker for every publisher format.
- A generic grammar checker with no paper-story awareness.
- A style mimicry tool that copies wording from published papers.

If those tasks become important, create separate focused skills.
