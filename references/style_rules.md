# Academic Style Rules

Use this file for grammar, terminology, notation, citations, cross-references, and style checks.

## Definitions and Terminology

- Define every term or acronym before first use.
- Use one term for one concept. Do not alternate between synonyms for stylistic variety.
- If a paper introduces a named method, use that name consistently.
- Avoid undefined "this", "it", "they", and "which" when the reference is ambiguous.
- Explain every symbol in formulas. Do not assume readers can infer meanings.

## Crisp Sentences

- Use crisp sentences with clear subjects and predicate verbs.
- Keep the subject and main verb close unless a modifier is necessary.
- Prefer one main claim or action per sentence.
- Split sentences that contain several loosely connected claims.
- Avoid comma splices and run-on sentences.
- Do not make sentences complex merely to sound academic.

## Paragraph Topic Sentences

- Every natural paragraph should normally begin with a topic sentence.
- A topic sentence should state both the topic and the controlling idea.
- The rest of the paragraph should support, explain, analyze, or link back to that controlling idea.
- If a paragraph has two controlling ideas, split it.
- If a paragraph lacks a topic sentence, revise the opening sentence before polishing grammar.

## Sentence Style

Prefer:
- Short, declarative sentences.
- Simple subject-verb-object structure.
- Active voice when it is direct and clear.
- Precise technical verbs.

Avoid:
- Contractions: use `cannot`, `do not`, `will not`.
- Colloquialisms: avoid `a lot of`, `kinds of`, `do convolution`, `more and more`.
- Rhetorical questions in manuscript text.
- Overusing `e.g.,` and `i.e.,`.
- Long sentences with multiple unrelated clauses.
- Parentheses as a substitute for clear sentence structure.

## Academic Tone

Good academic tone is precise, not inflated.

Avoid strong or vague words unless justified:
- `obviously`
- `clearly` when no evidence is given
- `very`
- `huge`
- `perfect`
- `undoubtedly`
- `meaningful` when `significant`, `important`, or a specific impact is intended

Prefer cautious claims:
- `can reduce`
- `may improve`
- `is designed to`
- `is intended to`
- `the results suggest`
- `under the evaluated settings`

## Number, Article, and Agreement Checks

Check:
- Singular/plural agreement.
- Countable nouns: `interfaces`, `RCs`, `ALUs`, `FIFOs`, `methods`, `experiments`.
- Uncountable or mass nouns: `performance`, `energy consumption`, `hardware resource usage`.
- Articles: `a footprint`, `an FPGA`, `the proposed method` after introduction.
- Subject-verb agreement across long modifiers.

## Tense

Common defaults:
- Present tense for what the paper proposes and what figures/tables show.
  - `This paper proposes...`
  - `Figure 3 shows...`
- Present tense for established facts.
- Past tense only for specific completed actions when needed.
- Present perfect when linking prior work to current relevance.
  - `Several approaches have explored...`

Avoid unnecessary future tense:
- Use `Section 4 presents...`, not `Section 4 will present...`.
- Use `can lead to...`, not `will lead to...`, unless the result is certain.

## Cross-References

Write out and capitalize specific references:
- `Figure 1`
- `Table 2`
- `Section 3`
- `Equation (4)`
- `Algorithm 1`
- `Appendix A`

Do not abbreviate as `Fig.`, `Tbl.`, or `Sec.` unless the target venue requires it.

Use automatic cross-references in Word or labels in LaTeX. Do not hardwire section, figure, table, equation, or reference numbers.

## Lists and Headings

- If using `First`, include at least `Second`.
- Avoid an "only child" hierarchy: do not create Section 2.1 without Section 2.2.
- Keep heading capitalization consistent with the venue template.
- Use bullets for contributions, motivations, or conclusions when visibility helps.

## Numbers and Units

- Write out numbers below 10 in prose when not tied to units or technical identifiers.
- Use numerals for measurements, equations, benchmark names, and results.
- Do not write `2nd`; write `second`.
- Put a space between numbers and units unless the venue style says otherwise.
- Define percentage metrics and specify whether higher or lower is better.

## Hyphenation

Use hyphens when they prevent ambiguity in compound modifiers:
- `power-aware placement`
- `congestion-driven routing`
- `placement-based synthesis`
- `timing-critical path`

Avoid unnecessary hyphens in established terms:
- `runtime`
- `wirelength`
- `hotspot`
- `linewidth`
- `testcase`
- `signoff`

When unsure, choose the spelling used by the strongest recent papers in the target venue and apply it consistently.

## Citations and References

- Cite every reference that appears in the reference list.
- Do not add references gratuitously.
- Keep reference format consistent and complete.
- Include authors, title, venue, pages, and year when required.
- Do not copy raw exported citation formats without checking the venue style.
- In related work, mention author names when it improves readability, for example, `Smith et al. [12] introduce...`.

## Bilingual Markdown Drafts

For bilingual Markdown paper drafts, use sentence-level English--Chinese pairing:
- Put one English sentence on one line.
- Put the corresponding Chinese sentence on the next line.
- Do not insert a blank line between the English and Chinese lines in a pair.
- Insert one blank line between sentence pairs.
- Insert two blank lines between paragraphs.
- Preserve headings, tables, equations, figures, code blocks, and LaTeX environments without forcing sentence-level pairing inside them.

## Final Read-Aloud Check

For important text, read it aloud or simulate a read-aloud check:
- If the sentence feels hard to say, simplify it.
- If the subject and verb are far apart, split the sentence.
- If a pronoun is unclear, replace it with the noun.
- If the sentence contains more than two commas, consider splitting it.
