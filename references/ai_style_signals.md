# AI-Style Signals and Review Protocol

Use this reference for substantial generated or substantially rewritten manuscript prose, or when the user asks for text that is less generic, less templated, or less AI-sounding.

## Purpose and Limits

This is an editorial quality check, not an authorship detector. No word, punctuation mark, or construction proves that a text was written by AI. Many flagged expressions are legitimate in a specific technical context, and non-native writers must not be penalized for using standard English.

Apply this reference to remove empty, ornamental, or repetitive prose. Do not alter a defined technical term, a direct quotation, a venue-mandated form, or an accurate statement merely to create superficial variation. Do not claim that the resulting text is undetectable or human-written.

## High-Risk Phrase Families

Community discussion repeatedly identifies the following clusters as default-model habits. A single occurrence is normally harmless; repeated, unsupported, or stacked occurrences require revision.

| Signal family | Review signals | Preferred action |
| --- | --- | --- |
| Empty signposting | `It is worth noting that`, `It is important to note that`, `It should be noted that`, `Needless to say` | Delete the lead-in and state the fact, or supply the missing reason why it matters. |
| Inflated generic vocabulary | `delve`, `leverage` (verb), `utilize`, `harness`, `foster`, `underscore`, `pivotal`, `groundbreaking`, `seamless`, `robust`, `comprehensive` | Use a specific verb or measurable property. Retain `robust` only with a stated robustness condition, perturbation, or definition. |
| Grand metaphors and abstractions | `rich tapestry`, `ever-evolving landscape`, `beacon`, `testament`, `cornerstone`, `paradigm shift`, `synergy` | Name the actual system, research area, relation, or evidence. `landscape` may remain when mapping a field is the literal subject. |
| Formulaic emphasis | `not only ... but also ...`, `not merely ... but ...`, `serves as a testament to`, `plays a crucial role in`, `holds immense potential` | Keep only when the parallel contrast adds real analytical content; otherwise state the two claims separately and support them. |
| Generic progress narrative | `In today's rapidly evolving ...`, `As technology continues to evolve`, `the future of ...`, `a new era` | Replace with the relevant constraint, date, trend, or empirical observation. |
| Stock conclusion or transition | `In conclusion`, `Ultimately`, `Moreover`, `Furthermore`, `Additionally` used as a sequence of fillers | Make the logical relation explicit (contrast, cause, evidence, consequence), or remove the transition. |
| Polished but content-free evaluation | `This highlights the importance of`, `This demonstrates the potential of`, `a significant step forward`, `transformative` | State the observed result, scope, and limitation. Avoid importance claims without a consequence or measurement. |
| Symmetry and list inflation | Repeated three-part adjective lists; repeated `X, Y, and Z`; stacked synonymous claims | Retain only distinct, necessary dimensions. Collapse synonyms and attach each remaining claim to evidence. |
| Model-like presentation | Excessive em dashes, title-cased generic headings, bold-first micro-headings, or a flood of short bullets | Follow the venue style and use the format only where it improves manuscript navigation. Do not ban em dashes categorically. |

## Four-Pass Audit

### Pass 1: Surface scan

Search for the phrase families above and inspect clusters rather than isolated tokens. Flag a sentence when it contains two or more signals, when the same signal recurs in a paragraph, or when the wording could be removed without changing the technical claim.

### Pass 2: Meaning and exception test

For each flag, ask:

1. Does the phrase name a defined technical concept or an exact relation?
2. Does it add information that cannot be expressed more directly?
3. Is the claim backed by a result, derivation, citation, or stated assumption?
4. Is the construction required by a quotation, target venue, or genre?

Keep the expression if the answer supports its use. Otherwise, delete it or replace it with a concrete subject, action, condition, result, and scope.

### Pass 3: Structure and evidence scan

Check the full paragraph, not only flagged sentences:

- Replace generic introductions with the problem, constraint, or prior result that motivates the paragraph.
- Replace a rhetorical contrast with a real comparison basis.
- Break decorative three-part lists into distinct, supported claims.
- Ensure transition words express the actual relation between adjacent sentences.
- Check that each contribution or superiority claim states the evaluated setting and evidence.

### Pass 4: Read-through and disposition

Read the revised text once as a domain reviewer. Confirm that the prose has a clear local purpose, technical nouns and verbs, evidence-bearing claims, and natural variation driven by meaning rather than random synonym substitution.

Before delivery, report one of the following when the audit was applicable:

- `AI-style audit: completed; no material violations remain.`
- `AI-style audit: completed; retained [expression] because [technical/quotation/venue reason].`
- `AI-style audit: [issue] remains because resolving it requires evidence or an authorial decision.`

## Examples

Avoid: `It is worth noting that the proposed framework leverages a robust strategy to significantly enhance performance.`

Prefer: `Under the evaluated congestion levels, the method reduces routed wirelength by 8.2% relative to [baseline].`

Avoid: `Not only does the method improve efficiency, but it also paves the way for a new era of scalable design.`

Prefer: `The method reduces runtime on the evaluated designs. Its memory cost grows linearly with the number of nets.`

Avoid: `Navigating the ever-evolving landscape of EDA requires a comprehensive and seamless solution.`

Prefer: `Recent process-node scaling increases routing congestion and timing closure cost; the method targets these two constraints.`

## Community Evidence Informing This Reference

- Hacker News discussions repeatedly mention default-model vocabulary (`delve` and related inflated verbs), em-dash-heavy presentation, bullet-list verbosity, and formulaic contrasts. They also caution that these signals are weak evidence of authorship and can occur in human writing.
- The community-maintained catalogue at `https://tropes.fyi/` groups recurrent complaints into empty signposting, `delve`-like vocabulary, ornamental `tapestry`/`landscape` metaphors, formulaic emphasis, and formatting habits.

These sources motivate the review categories only. They are not authorities on academic style and must not override discipline-specific conventions or evidence-based writing.
