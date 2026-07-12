# Paper Structure Reference

Use this file for abstracts, introductions, related work, methods, experiments, conclusions, and whole-paper planning.

## High-Level Paper Story

A strong academic paper should not merely describe what the authors did. It should explain:

1. Why the problem matters.
2. What makes the problem difficult.
3. What existing methods do and where they fall short.
4. What idea, model, algorithm, architecture, or methodology is proposed.
5. Why the proposed approach is technically different.
6. How the approach is validated.
7. What the results show and why the results matter.

Avoid writing the paper as a chronological discovery process. Present the final distilled logic.

## Default Outline

Use or adapt this outline:

1. Title
2. Abstract
3. Introduction
   - Motivation
   - Problem statement or hypothesis
   - Limitations of prior work
   - Proposed solution
   - Summary of contributions
   - Paper organization
4. Related Work / Previous Work
5. Method / Architecture / Algorithm / Theory
   - Definitions and notation
   - Formal problem statement
   - Key idea
   - Detailed method
   - Complexity, proof, or implementation-level reasoning when relevant
6. Experimental Setup and Protocol
   - Platform, benchmarks, datasets, baselines, metrics, parameters
   - Reproducibility details
7. Results and Discussion
   - Main results
   - Ablation, sensitivity, scalability, or case studies
   - Explanation of why results improve
8. Conclusion and Future Work
9. References
10. Appendices, if needed

## Abstract Template

A typical abstract contains four moves:

1. Background and need.
2. Gap or challenge.
3. Proposed method and core contribution.
4. Results and implication.

Template:

`[Problem area] has become important because [motivation]. However, existing [methods/systems] suffer from [gap/challenge], which limits [consequence]. This paper presents [method/name], a [type of contribution] that [key idea]. [Method/name] [technical mechanism]. Experimental results on [benchmarks/datasets/platforms] show that [main quantitative result] compared with [baseline]. These results demonstrate that [main implication].`

Guidelines:
- Keep it concise.
- Include the main quantitative result when available.
- Avoid citations unless the venue allows them.
- Define important acronyms at first use.

## Introduction Flow

A strong Introduction usually follows this order:

1. Broad context.
2. Specific technical problem.
3. Existing solution categories.
4. Remaining limitations.
5. Proposed solution.
6. Main contributions, usually three to four bullets.
7. Key experimental result.
8. Organization of the paper.

Contribution bullets should be concrete:

- `We propose/design/develop [artifact] that [technical novelty].`
- `We introduce [model/algorithm/flow] to [solve specific challenge].`
- `We implement/evaluate [system] on [platform/benchmarks].`
- `Experimental results show [quantified improvement].`

Use "This paper..." if the target style avoids first person.

## Related Work

Related work should not be a list of paper summaries. It should organize prior work into categories and position the proposed work.

For each category:
1. State the category and its relevance.
2. Summarize representative works.
3. Identify the specific limitation relevant to this paper.
4. Transition to how the proposed work differs.

Tone rules:
- Be fair and precise.
- Do not say a prior method is "bad" or "wrong".
- Prefer limited claims, such as `does not address [specific condition]`, `requires [assumption]`, or `is optimized for [scenario]`.
- Mention key references that are later used as baselines.

## Method / Design / Algorithm Section

This section should explain the general idea before implementation details.

Preferred order:
1. Definitions and notation.
2. Problem formulation.
3. Overview of the proposed approach.
4. Detailed components in logical order.
5. Algorithm, pseudocode, flowchart, model, architecture diagram, or theorem.
6. Complexity, correctness, or design rationale.
7. Implementation details only when they affect reproducibility or interpretation.

Avoid:
- Starting with a specific chip, tool, dataset, or parameter unless the paper is explicitly about that object.
- Burying the key contribution inside low-level implementation details.
- Using concrete numbers in principle-level descriptions unless they are examples.

## Experimental Setup

State:
- Hardware/software platform.
- Benchmarks, datasets, workloads, or testcases.
- Baselines and why they are appropriate.
- Metrics and units.
- Parameters and configurations.
- How results are computed, including averages, min/max, variance, or repeated runs when relevant.

Do not present results before readers know what metrics and baselines mean.

## Results and Discussion

Each result should answer a question.

Good pattern:
1. State the question or claim.
2. Point to the figure/table.
3. Explain what is shown.
4. Interpret the result.
5. Connect back to the proposed method.

Example:
`Table 2 reports the runtime of the proposed algorithm and the baselines on all benchmarks. The proposed algorithm reduces runtime by [x]% on average because [mechanism]. The improvement is more significant on [case] because [reason].`

Avoid:
- Dumping tables without explanation.
- Reporting numbers without analysis.
- Claiming superiority without explaining metric direction.
- Using a result that is not tied to a contribution.

## Conclusion

The conclusion should not introduce new evidence. It should:
1. Restate the problem.
2. Summarize the proposed method.
3. Summarize the main result.
4. State the implication or future direction.

Template:
`This paper presented [method], a [type] for [problem]. By [key mechanism], [method] addresses [challenge]. Experiments on [benchmarks/platform] show that [main result]. Future work will explore [limited, realistic extension].`


## Paragraph-Level Discipline

For all sections, write paragraphs before polishing sentences.

Each natural paragraph should normally:
1. begin with a topic sentence;
2. develop one controlling idea;
3. support the idea with evidence, method details, results, examples, citations, or reasoning;
4. explain why the support matters;
5. connect to the section goal or next paragraph when needed.

This rule applies to abstracts, introductions, related work, method overviews, experiment discussion, and conclusions. Paragraphs in theorem/proof environments, captions, and very short transition paragraphs may follow genre-specific conventions.
