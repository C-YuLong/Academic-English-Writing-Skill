# Tables, Figures, Captions, LaTeX, and Word

Use this file for experimental tables, figures, captions, labels, cross-references, LaTeX, Word formatting, and result presentation.

## Skeleton Result Tables

Before running large experiments, create skeleton tables:

- Row names.
- Column names.
- Metrics and units.
- Baselines.
- Testcases or benchmarks.
- Expected aggregation, such as average, min, max, or standard deviation.
- Draft caption.
- Notes on which script or experiment produces each value.

This prevents rerunning experiments because a statistic, parameter, or logfile was forgotten.

## Table and Figure Rules

Every table and figure should be referenced and explained in the main text.

For each table/figure, check:
- Is the caption complete enough to understand the item without the main text?
- Are all axes, units, metrics, headers, abbreviations, and baselines defined?
- Does the caption exactly match the terminology in the main text?
- Is the font readable after scaling?
- Is the figure readable in black and white?
- Does the table/figure fit within the text width?
- Are table captions above tables and figure captions below figures, unless the venue says otherwise?
- Are headings and captions kept with the table/figure and not split awkwardly across pages?

## Explaining Results

Do not write only: `The results are shown in Table 3.`

Use:
`Table 3 reports [metric] for [methods] on [benchmarks]. The proposed method achieves [result]. This improvement comes from [technical reason].`

For plots:
- Define x-axis and y-axis.
- State units.
- Explain whether higher or lower is better.
- Explain trends, outliers, and saturation points.

## Cross-References

Use automatic cross-references:
- Word: captions, cross-reference fields, and update fields.
- LaTeX: `\label{}` and `\ref{}` or the venue's reference macro.

Do not hardwire:
- `Section 1`
- `Figure 2`
- `Table 3`
- Reference numbers such as `[12]`

## LaTeX Style

- Put variables and mathematical expressions in math mode.
- Do not write `\ref {fig:x}`; write `\ref{fig:x}`.
- Use consistent label prefixes, such as `fig:`, `tab:`, `sec:`, `eq:`, and `alg:`.
- Avoid overly long source lines if the team style requires readable diffs.
- Keep bibliography files local to the paper if the team requires long-term reproducibility.
- Remove obsolete comments and revision markers before final submission.

## Word Style

- Use automatic numbering for sections, equations, figures, tables, and references.
- Use cross-references instead of typed numbers.
- Use the built-in equation editor for formulas.
- Align equations and surrounding text cleanly.
- Ensure line spacing and paragraph spacing are consistent.
- Update all fields before final export.

## Camera-Ready / Final Formatting Check

Check:
- No orphaned headings.
- No widows at the top or bottom of columns.
- No excessive whitespace from floating figures or tables.
- No figure/table exceeds margins.
- Captions and body descriptions use exactly the same names and metrics.
- References are cited in the body and formatted consistently.
- PDF output is checked visually, not only source text.
