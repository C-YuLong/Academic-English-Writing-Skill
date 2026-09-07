---
name: academic-english-paper-writing
description: Draft, revise, polish, translate, outline, or review English academic papers, theses, abstracts, introductions, related work, methods, experiments, figure/table captions, LaTeX/Word prose, and reviewer responses. Use especially for CS, engineering, EDA, FPGA, architecture, algorithms, and Chinese-to-English academic writing. For substantial drafting or venue-targeted rewriting, first research recent papers from the target conference/journal/field to calibrate style, length, structure, terminology, and rhetorical moves unless the user explicitly asks not to browse or only wants local grammar editing. Always enforce crisp sentence style, formal academic register, topic-sentence-led paragraphs, given-before-new information flow, evidence-based claims, and a mandatory end-of-task audit for overlong sentences, logical jumps, and unwarranted reviewer-directed defensiveness. Do not use for creative writing, marketing copy, or inventing citations/results.
---

# Academic English Paper Writing Skill

Use this skill when the user asks for help writing, revising, translating, polishing, structuring, or reviewing an English academic paper, thesis, proposal, manuscript, rebuttal, or response to reviewers.

The default user may write instructions in Chinese. Reply in the user's language for explanations, but produce manuscript text in polished academic English unless the user asks otherwise.

## Core Principles

1. Preserve technical meaning. Never change algorithms, claims, variables, equations, results, hardware/software assumptions, or citation intent unless the user explicitly asks.
2. Do not invent contributions, experiments, citations, numerical results, baselines, datasets, theorems, proofs, or reviewer comments.
3. Prefer a clear academic story over a lab diary. A paper should present the distilled problem, gap, method, evidence, and contribution, not the chronological process of discovery.
4. Start from structure before prose. If the task is broader than a paragraph-level edit, build or validate the outline first.
5. Fix terms and notation early. Use one term for one concept. Define acronyms, symbols, variables, metrics, benchmarks, and algorithm names before use.
6. Make evidence visible. Claims should be supported by experiments, theory, citations, or clearly marked assumptions.
7. Keep prose concise, formal, and direct. Prefer short declarative sentences, active constructions where appropriate, and precise technical verbs.
8. For substantial drafting, calibrate to the target venue and field before writing. Recent accepted papers reveal the expected section order, contribution style, abstract density, evaluation narrative, terminology, and typical length.
9. Use crisp sentences. Each sentence should have a clear subject, a clear predicate verb, and one main communicative purpose. Split sentences that bury the main action, stack too many clauses, or create comma splices.
10. Every natural paragraph must normally begin with a topic sentence that states the topic and controlling idea. Follow it with evidence, explanation, analysis, and a link to the paper's argument.
11. Write manuscript prose as forward-moving scholarship, not as a rebuttal. Do not over-defend claims, imagine reviewer objections, or foreground limitations unless the local section purpose requires it.
12. Maintain tight sentence-to-sentence logic. Each sentence should connect to the previous one through repeated terms, contrast, cause, evidence, or consequence; avoid jumps that force the reader to infer missing links.
13. Use academic language. The default register is formal, neutral, clear, evidence-based, and discipline-aware. Academic language should be precise, not pompous.
14. When producing bilingual Markdown for paper drafts, use sentence-level English--Chinese pairs: one English sentence line followed immediately by its Chinese sentence line, no blank line inside the pair, one blank line between sentence pairs, and two blank lines between paragraphs.
15. End every manuscript collaboration with a mandatory editorial audit. Inspect all drafted, translated, revised, or reviewed prose for overlong sentences, logical jumps, and defensive language aimed at hypothetical reviewers; fix each issue before delivery whenever the technical meaning permits.
16. Avoid default-model prose habits. Treat recurring AI-associated wording, symmetry, and formatting as revision signals, not as proof of AI authorship or a blanket ban on valid academic language.

## When to Read Reference Files

Read only the files needed for the current task.

- For full papers, section outlines, abstracts, introductions, related work, methods, experiments, or conclusions, read `references/paper_structure.md`.
- For polishing, style checking, grammar, terminology, notation, acronyms, citations, cross-references, and formatting rules, read `references/style_rules.md`.
- For crisp sentence style, topic sentences, paragraph structure, given-new information flow, tense choices, modality, articles, and academic register, read `references/academic_sentence_paragraph_rules.md`.
- For Chinese-to-English academic writing issues and recurring engineering-paper phrase fixes, read `references/common_english_fixes.md`.
- For an AI-style signal audit, or when the user asks to make prose less generic, less templated, or less AI-sounding, read `references/ai_style_signals.md`.
- For figures, tables, skeleton result tables, captions, metrics, axes, LaTeX, Word, and cross-reference workflows, read `references/tables_figures_latex.md`.
- For reviewer responses, rebuttals, camera-ready revisions, and response letters, read `references/reviewer_response.md`.
- For substantial drafting, venue-targeted writing, or field-specific style imitation, read `references/venue_style_research.md` before writing.
- For maintaining and extending this skill, or when the user asks how other writing skills are designed, read `references/public_skill_patterns.md`.
- For the summarized principles from the user's Lund academic-writing courseware and sample articles, read `references/courseware_synthesis.md`.
- For reusable section templates, read `assets/section_templates.md`.
- For example user prompts and expected behavior, read `examples/prompts.md`.

## Default Workflow

### 1. Classify the request

Identify the task type:

- Outline/design: paper plan, contribution framing, section structure.
- Drafting: abstract, introduction, related work, method, experiment, conclusion, caption, rebuttal.
- Polishing: grammar, concision, academic tone, terminology consistency.
- Translation: Chinese technical text to English academic prose.
- Review: diagnose weaknesses, logical gaps, missing definitions, unsupported claims.
- Formatting: citations, cross-references, figures, tables, notation, LaTeX/Word style.

### 2. Decide whether venue/field research is required

Before writing new manuscript text or substantially restructuring existing text, perform venue/field style calibration unless the user explicitly asks not to browse, the task is only local grammar correction, or the user already supplies enough recent target papers.

Read `references/venue_style_research.md` and use it to:
- Search recent papers from the target conference, journal, or closest field venue.
- Prefer official proceedings, publisher pages, author PDFs, arXiv versions linked from accepted papers, or lab pages.
- Extract structure, approximate length, abstract density, section order, contribution style, related-work placement, figure/table style, terminology, and evaluation rhetoric.
- Use the findings to guide style and organization, not to copy wording.

When the target venue is missing, infer the most likely venue family from the field and state the assumption. Ask only if the choice affects correctness.

### 3. Collect only necessary missing inputs

Proceed with reasonable assumptions when possible. Ask a clarification only when the missing information blocks correctness, such as unknown contribution, missing experimental result, unspecified target venue/page limit, or unavailable source text.

When information is missing but the user wants immediate output, use explicit placeholders, such as `[baseline]`, `[dataset]`, `[metric]`, `[result]`, `[venue]`, or `[citation needed]`.

### 4. Build the paper logic

For substantial writing tasks, check this story chain:

Background need -> technical challenge -> gap in prior work -> proposed idea -> key contribution -> validation protocol -> quantitative or qualitative evidence -> implication.

If any link is weak, mention it before or after the draft.

### 5. Plan paragraphs before writing sentences

For every natural paragraph in a drafted or revised section, identify:
- Topic sentence: the first sentence states the paragraph's topic and controlling idea.
- Support: the middle sentences provide evidence, examples, definitions, comparisons, causal explanation, results, or analysis.
- Link: the final sentence connects the paragraph to the section purpose, next paragraph, or paper argument when needed.

Use a PEEL-like structure when useful: Point, Evidence, Explanation/Evaluation, Link.

Keep information flow reader-friendly:
- Put given or familiar information before new information.
- Let sentence subjects pick up terms from the previous sentence when this improves flow.
- Use passive voice strategically when the procedure or prior object should be the subject.

If a paragraph lacks a topic sentence, rewrite the opening or flag the issue.


### 6. Draft or revise

For new text:
- Use formal academic English.
- Use crisp sentences with clear subjects and predicate verbs; split long sentences before polishing wording.
- Begin each natural paragraph with a topic sentence unless a venue-specific or genre-specific reason justifies another structure.
- Build explicit local transitions so each sentence follows from the previous one.
- Put the main contribution early.
- Match the target venue's recent structural conventions when appropriate.
- Avoid overclaiming.
- Avoid rhetorical questions.
- Avoid vague pronouns such as "this" without a clear noun.
- Avoid colloquial expressions, contractions, and "do"-style verbs for technical operations.
- Use present tense for established paper claims and section descriptions unless a different tense is required.

For revised text:
- Preserve all technical content.
- Fix paragraph openings, not just grammar: add or strengthen topic sentences when needed.
- Remove rebuttal-like or over-defensive framing from manuscript prose unless the task is an actual rebuttal or response letter.
- Repair sentence-to-sentence logic before sentence-level polishing.
- Improve grammar, concision, flow, and precision.
- Standardize terminology, acronyms, notation, capitalization, and units.
- Align the structure and rhetorical moves with recent venue examples when the task asks for venue fit.
- Do not silently delete important technical details; if removal improves flow, note the deletion.
- Run the AI-style signal audit when requested and for substantial generated or substantially rewritten prose; preserve a flagged expression when it is technically exact and document the reason only if material.

### 7. Produce the output in the right format

Choose a format based on the task:

- Short polish: provide `Revised text` and `Notes`.
- Translation: provide `Academic English version` and `Key wording notes`.
- Paragraph/section rewrite: provide `Paragraph plan`, `Revised version`, `Main changes`, and `Remaining issues`.
- Paragraph-level rewrite: provide `Topic sentence`, `Support logic`, `Revised paragraph`, and `Sentence-level notes`.
- Full section drafting: provide `Venue/field calibration`, `Mini-outline`, `Draft`, and `Checklist`.
- Paper review: provide `Major issues`, `Line/style issues`, and `Actionable rewrite suggestions`.
- Reviewer response: provide `Response draft`, `Manuscript change summary`, and `Risk notes`.
- Bilingual Markdown paper drafts: use sentence-level English--Chinese pairs; write the English sentence on one line and the Chinese sentence on the next line; do not insert a blank line inside the pair; insert one blank line between sentence pairs; insert two blank lines between paragraphs.

For sentence-level edits, do not over-explain every grammar point unless the user asks.

### 8. Run the mandatory end-of-collaboration audit

Before delivering any task that drafts, translates, polishes, rewrites, or reviews manuscript content, inspect the complete proposed output rather than only the latest sentence-level edits.

- **Overlong sentences:** Review sentences longer than about 35 words, sentences with more than three clauses, and sentences carrying multiple claims. Treat these as diagnostic signals rather than mechanical limits. Split or restructure them when doing so improves clarity without damaging technical meaning.
- **Logical continuity:** Check that every sentence follows from the previous sentence and that every paragraph advances the section argument. Add a missing premise, transition, causal link, comparison basis, or evidence statement when the prose otherwise makes the reader bridge the gap.
- **Hypothetical-reviewer defensiveness:** Remove rebuttal-like wording, preemptive concessions, unnecessary caveats, and attempts to answer objections that no actual reviewer has raised. State the method, scope, evidence, or limitation directly. Retain defensive language only in genuine rebuttals or reviewer-response documents.
- **Paragraph architecture:** Confirm that each natural paragraph has a clear topic sentence, focused support, and an explicit link to the local argument when needed.
- **Claim discipline:** Check that contribution, novelty, generality, causality, and superiority claims match the available evidence and use appropriate modality.
- **Terminology and information flow:** Confirm consistent terms and notation, defined acronyms, clear pronoun referents, and given-before-new progression.

Fix detected issues directly when the requested task permits editing. If a fix would require inventing evidence, changing technical meaning, or making an authorial decision, preserve the text and report the unresolved issue concisely. For substantial outputs, briefly state that the audit was completed and identify any material unresolved risks; do not burden the user with a report when no noteworthy issue remains.

### 9. Run the AI-style signal audit when applicable

For substantial generated or substantially rewritten manuscript prose, and whenever the user asks for natural, non-generic, or non-AI-sounding English, read `references/ai_style_signals.md` and perform its four-pass audit. This audit is a style-and-substance check, not an authorship detector: do not label text AI-generated and do not delete a word merely because it appears on a watchlist.

Replace or remove high-risk boilerplate when a plainer, evidence-bearing statement preserves the meaning. Retain a flagged word or construction when it is a defined technical term, required by the target venue, a faithful quotation, or the clearest accurate wording. Do not manufacture variation solely to evade detectors.

## Quality Gate Before Final Answer

Before sending the final answer, check:

- For substantial drafting, was venue/field style calibration performed, or was the reason for skipping it clear?
- Does every natural paragraph begin with a topic sentence that states the topic and controlling idea?
- Is each paragraph built around one main idea and supported by evidence, examples, explanation, or analysis?
- Did the mandatory end-of-collaboration audit inspect the complete proposed output rather than only isolated edits?
- Are the sentences crisp, with clear subjects and predicate verbs, and without avoidable length or clause stacking?
- Were long or clause-heavy sentences split or restructured where clarity improved, without applying a rigid word-count rule?
- Does the prose sound like an academic paper rather than a rebuttal or imagined defense against nonexistent reviewers?
- Were preemptive concessions, unnecessary caveats, and unprompted objection handling removed or stated directly?
- When applicable, did the AI-style signal audit remove unsupported generic framing, ornamental vocabulary, formulaic symmetry, and model-like formatting without degrading technical precision?
- Were any retained high-risk expressions technically necessary, evidence-bearing, or required by the target convention?
- Does each sentence connect tightly to the previous sentence through explicit logic or given-before-new flow, without missing premises or unexplained jumps?
- Does information flow from given to new instead of surprising the reader with unsupported new subjects?
- Are register, tone, and style formal, neutral, clear, and evidence-based?
- Are tense, modality, article use, countability, and definiteness choices appropriate?
- Does the text clearly state the problem, gap, contribution, and evidence?
- Are all acronyms and technical terms defined before first use?
- Is one concept named consistently?
- Are variables and symbols in math style or clearly described?
- Are Figure, Table, Section, Equation, Algorithm, and Appendix references spelled out and capitalized when specific?
- Are tables/figures/captions understandable without hidden context?
- Are claims supported by results, citations, or marked placeholders?
- Are grammar, number agreement, articles, tense, prepositions, and units correct?
- Is the tone formal but not inflated?
- If producing bilingual Markdown, does it follow sentence-level English--Chinese pairing with no blank line inside a pair, one blank line between sentence pairs, and two blank lines between paragraphs?
- Did the answer avoid fabricating citations, results, or reviewer concerns?
