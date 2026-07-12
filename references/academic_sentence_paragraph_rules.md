# Academic Sentence and Paragraph Rules

Use this reference whenever drafting, rewriting, translating, or polishing academic prose. It is especially important for Chinese-to-English writing, paragraph-level rewriting, Introduction/Related Work/Discussion drafting, and second-language writer support.

## Crisp Sentence Standard

"Crisp" academic sentences are clear, direct, and easy to process.

A crisp sentence should normally have:
- a visible subject;
- a visible predicate verb;
- one main communicative purpose;
- no unnecessary detours before the main verb;
- no comma splice or run-on structure;
- no vague pronoun reference;
- no inflated wording when a precise simple word works.

Preferred pattern:
`Subject + predicate verb + object/complement + necessary modifiers.`

Before finalizing a sentence, ask:
1. Who or what is the grammatical subject?
2. What is the main verb?
3. What is the sentence's one main claim or action?
4. Can the sentence be split without losing meaning?
5. Does any word merely make the sentence sound "academic" without adding precision?

## Clause-Level Checks

Every complete sentence needs at least one independent clause.

Use coordination when two independent clauses have equal weight:
`Independent clause, FANBOYS independent clause.`

Use subordination when one idea supports or frames the main idea:
`Although/Because/When [dependent clause], [independent clause].`

Avoid comma splices:
- Weak: `The method improves runtime, however the memory cost increases.`
- Better: `The method improves runtime; however, the memory cost increases.`
- Better: `The method improves runtime, but the memory cost increases.`
- Better: `The method improves runtime. However, the memory cost increases.`

Use commas after long introductory elements:
- `In the present study, we examine...`
- `When the benchmark size increases, the runtime increases...`

## Word Order and Adverb Placement

Keep the subject and predicate verb close unless the modifier is necessary.

For mid-position adverbs:
- If the verb phrase has an auxiliary, place the adverb after the first auxiliary: `can also improve`.
- If there is one lexical verb, place the adverb before the main verb: `often improves`.
- If the only verb is `be`, place the adverb after `be`: `is often used`.

Avoid:
- `The method also can reduce latency.`
Prefer:
- `The method can also reduce latency.`

## Manuscript Voice: Not Rebuttal Voice

Manuscript prose should present a positive, evidence-based argument. It should not sound like a response to imagined reviewer criticism.

Avoid rebuttal-like patterns in ordinary paper sections:
- leading with limitations before stating the contribution;
- adding defensive phrases such as `we deliberately scope`, `not yet`, or `this does not constitute` when the section should present results;
- repeatedly contrasting with what the paper does not do;
- using caveats as topic sentences;
- over-hedging results that are directly supported by data.

Use limitations only where they serve the genre: experimental setup, metric scope, discussion, conclusion, or an actual rebuttal. Even there, state the positive finding first, then state the boundary precisely.

Preferred pattern:
`[Positive result or contribution]. [Evidence]. [Scope boundary if needed].`

Avoid pattern:
`[Defensive limitation]. [Imagined objection]. [Delayed result].`

## Paragraph Architecture

Each natural paragraph should normally contain one main idea.

Default paragraph structure:
1. Topic sentence: states the topic and controlling idea.
2. Supporting sentences: provide evidence, examples, definitions, comparisons, causes, results, or explanation.
3. Analysis: explains why the support matters.
4. Link sentence: connects to the section purpose, next paragraph, or overall claim when needed.

A strong paragraph does not merely list facts. It tells the reader why the facts are there.

## Topic Sentences

Every natural paragraph should normally begin with a topic sentence.

The topic sentence should contain:
- the topic: what the paragraph is about;
- the controlling idea: what the paragraph will say about the topic.

Weak:
`Several methods have been proposed.`

Better:
`Existing approximation methods reduce hardware cost, but they often sacrifice accuracy under irregular workloads.`

Exceptions are allowed only when the genre or local structure clearly requires them, such as:
- a very short transition paragraph;
- a paragraph following a displayed equation where the equation itself controls the paragraph;
- a theorem/proof environment;
- a caption;
- a venue style that consistently delays the topic sentence for rhetorical reasons.

If the user asks for academic paper writing, default to first-sentence topic sentences.

## PEEL Paragraph Pattern

Use PEEL when the paragraph needs a clear argument:

- Point: the topic sentence states the claim.
- Evidence: data, citation, example, theorem, figure, table, or observation.
- Explanation/Evaluation: explain how the evidence supports the claim.
- Link: connect to the section goal or next idea.

Example skeleton:
`[Point]. [Evidence from method/result/literature]. [Explanation of why the evidence matters]. [Link to contribution or next step].`

## Given-Before-New Information Flow

Academic readers expect sentences to move from familiar information to new information. This rule also prevents sentence-to-sentence logic jumps.

Guidelines:
- Start a sentence with information already mentioned or inferable.
- Put new, important, or complex information later in the sentence.
- Let the subject of a sentence often pick up an object, term, or idea from the previous sentence.
- Make relations explicit when moving between claim, mechanism, evidence, and implication.
- Use cause, contrast, example, continuation, or consequence markers only when they reflect the real logic.
- Avoid introducing a new technical subject without a bridge.

Weak flow:
`The biological clock controls circadian rhythm. The suprachiasmatic nucleus was identified as the location of the clock...`

Better flow:
`The biological clock controls circadian rhythm. The clock was identified in a part of the brain called the suprachiasmatic nucleus...`

## Active and Passive Voice

Use active voice when the agent matters or when active voice is clearer:
- `This paper proposes...`
- `Figure 3 shows...`
- `The algorithm computes...`

Use passive voice when:
- the procedure matters more than the actor;
- the actor is obvious or irrelevant;
- passive voice helps place given information in subject position;
- the method section describes experimental steps.

Good passive use:
`The coarse representation is filtered to remove objects below the capture-rate threshold.`

Avoid vague passive when the agent matters:
- Weak: `A solution was proposed.`
- Better: `Smith et al. proposed a solution.`
- Better: `This paper proposes a solution.`

## Academic Register

Default to formal academic register:
- clear and straightforward;
- neutral and respectful;
- evidence-based rather than opinion-based;
- discipline-aware;
- precise without being pompous.

Avoid:
- slang and colloquialisms;
- contractions;
- rhetorical questions in manuscript prose;
- biased or loaded wording;
- unnecessary jargon;
- inflated words used only to sound academic;
- clichés and empty intensifiers.

Good academic style is not complicated style. Prefer exact, economical wording.

## Tense and Aspect

Common academic choices:
- Present tense for established knowledge, theory, interpretation, and what figures/tables show.
  - `Figure 2 shows...`
  - `These results suggest...`
- Past tense for completed methods, experiments, and specific past findings.
  - `We evaluated the method on...`
  - `The baseline achieved...`
- Present perfect for prior work connected to the current research space.
  - `Several studies have explored...`
- Present tense for the paper's purpose and contribution.
  - `This paper presents...`

In introductions, a useful pattern is:
- present tense to establish territory;
- present perfect to summarize prior work and open a niche;
- present tense to occupy the niche and state the paper's contribution.

In conclusions:
- present perfect can summarize what the paper has done;
- present tense can state implications.

## Modality and Qualification

Match claim strength to evidence.

Strong evidence:
- `show`
- `demonstrate`
- `establish`
- `reduce`
- `improve`

Moderate or indirect evidence:
- `indicate`
- `suggest`
- `provide evidence that`
- `are consistent with`

Uncertain or limited evidence:
- `may`
- `might`
- `could`
- `tend to`
- `under the evaluated settings`

Do not over-hedge clear findings.
Weak:
`Based on limited data, the results seem to possibly indicate a marginal improvement.`

Better:
`The proposed method improves accuracy by [x]% on the evaluated benchmarks. Because the dataset is limited, future work should test whether this improvement generalizes to [setting].`

Separate clear findings from limitations whenever possible.

## Articles, Countability, and Definiteness

Use `a/an` for new singular countable information:
- `a method`
- `an algorithm`
- `a unique architecture`

Use `the` for known, specific, or previously mentioned information:
- `the method`
- `the proposed algorithm`
- `the results of this study`

Use no article for general plural count nouns or general uncountable nouns:
- `Algorithms often require...`
- `Research has shown...`
- `Evidence suggests...`

Watch uncountable nouns:
- `evidence` not `evidences`
- `advice` not `advices`
- `research` not `researches` when used as a mass noun
- `information` not `informations`

Check count nouns:
- `one phenomenon`, `several phenomena`
- `one method`, `several methods`
- `one figure`, `several figures`

## Paragraph-Level Revision Procedure

When revising a paragraph:
1. Identify the topic sentence.
2. Identify the controlling idea.
3. Delete or move sentences that do not support the controlling idea.
4. Reorder sentences so familiar information precedes new information.
5. Add transition phrases only where logic requires them.
6. Split the paragraph if it contains two controlling ideas.
7. Rewrite long sentences into crisp sentences.
8. Remove over-defensive or rebuttal-like wording unless the text is an actual reviewer response.
9. Check that every adjacent sentence pair has an explicit logical relation.
10. Check tense, modality, articles, and technical terms.
