# Venue and Field Style Research

Use this file before substantial drafting, venue-targeted rewriting, or field-specific paper planning.

The goal is not to imitate any single paper. The goal is to calibrate to current expectations in the target venue and research community: structure, length, density, terminology, evidence style, and rhetorical moves.

## When to Run This Step

Run this step before:
- Writing a new abstract, introduction, related work, method, experiment, conclusion, or full paper section.
- Reorganizing a manuscript for a target conference or journal.
- Translating a Chinese draft into English for a known venue.
- Advising on paper structure, contribution framing, or expected page/section balance.

Skip or shorten this step when:
- The user only asks for local grammar correction.
- The user explicitly asks not to browse.
- The user supplies 3-8 recent target papers and asks you to use them.
- The task is a tiny sentence-level fix where venue conventions will not change the answer.

## Search Strategy

If the user gives a venue:
1. Search the official conference or journal page for recent accepted papers, proceedings, or program pages.
2. Search publisher/proceedings pages: ACM Digital Library, IEEE Xplore, USENIX, ACL Anthology, Springer, Elsevier, Nature, Science, arXiv links from accepted papers, or the venue website.
3. Prefer papers from the last 2-3 years. For fast-moving fields, prefer the last 1-2 years.
4. Pick 3-8 papers closest to the user's topic, method type, and evaluation style.

If the user gives only a field:
1. Identify likely target venues in that field.
2. Search recent papers from 2-3 representative venues.
3. State the assumed venue family before applying the calibration.

If the user gives a specific paper style to emulate:
1. Use that paper as one exemplar.
2. Add 2-4 recent papers from the same venue to avoid overfitting to one author's style.

## What to Extract

For each exemplar, capture:

- Venue, year, title, and source.
- Paper type: empirical, systems, theoretical, architecture, algorithm, dataset, survey, tool, case study.
- Approximate length if available: page count, abstract word count, section count.
- Section order and section names.
- Introduction pattern:
  - background opening
  - problem/gap framing
  - method preview
  - contribution bullets
  - result preview
  - organization paragraph
- Related work placement:
  - separate section early
  - near end
  - integrated into introduction/method
- Method section style:
  - formal notation first
  - architecture overview first
  - algorithm first
  - design principles first
- Experiment section style:
  - benchmarks/datasets
  - baselines
  - metrics
  - ablation/scalability/sensitivity
  - discussion depth
- Figure and table patterns:
  - architecture overview figure
  - algorithm pseudocode
  - result tables
  - ablation plots
  - captions with standalone explanations
- Citation style and density.
- Terminology and naming conventions.
- Claim strength:
  - cautious wording
  - direct contribution claims
  - quantified claims
  - limitations/scope statements.

## Calibration Summary Format

Before drafting a substantial section, prepare a concise summary for internal use and optionally show it to the user.

Use this format when useful:

`Venue/field calibration`
- `Target`: [venue/field/year range]
- `Sources checked`: [3-8 papers or proceedings pages]
- `Observed structure`: [common section order]
- `Typical length/density`: [page/abstract/intro length if available]
- `Contribution style`: [bullets, paragraph, named system, theorem-first, etc.]
- `Experiment style`: [benchmarks, baselines, ablations, result explanation]
- `Writing implications`: [how the draft should be shaped]
- `Uncertainties`: [missing venue, paywalled papers, incomplete page-count data]

## How to Use the Findings

Use calibration to decide:
- Whether to use contribution bullets.
- Whether related work should be Section 2 or later.
- Whether to open with application motivation or technical bottleneck.
- Whether to introduce notation before method details.
- How much experimental setup detail to include before results.
- How assertive the contribution language should be.
- Whether to mention limitations, artifacts, reproducibility, or ethics.

Do not:
- Copy sentences or paragraph structure too closely from any paper.
- Invent citation details.
- Treat arXiv formatting as identical to final proceedings formatting unless it is clearly the accepted version.
- Overfit to a single exemplar.
- Use old papers to define current style if recent papers are available.

## If Web Access Is Unavailable

Ask the user to provide:
- Target venue or journal.
- 3-5 recent accepted papers or PDFs.
- Page limit and template.
- Their target section.

If immediate help is required, proceed with general academic conventions and mark the missing venue calibration as a limitation.
