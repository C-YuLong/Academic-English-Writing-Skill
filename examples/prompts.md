# Example Prompts

## Polish a Paragraph

User:
`请把下面这段改成 IEEE 风格的英文论文表达，保持技术含义不变，并指出主要问题。`

Expected behavior:
- Provide revised academic English.
- List only the most important change notes.
- Preserve variables, citations, and quantitative results.

## Draft an Abstract

User:
`根据这些贡献和实验结果写一个 180 词左右的 abstract。`

Expected behavior:
- Ask for missing key results only if necessary.
- Otherwise use placeholders.
- Include problem, gap, method, result, implication.

## Review an Introduction

User:
`帮我看这个 Introduction 逻辑有没有问题。`

Expected behavior:
- Diagnose background -> gap -> method -> contribution -> result chain.
- Identify missing definitions, overclaims, unsupported claims.
- Suggest a revised outline or paragraph order.

## Related Work

User:
`帮我写 Related Work，不要把别人说得太差。`

Expected behavior:
- Group references by method category.
- Use fair, precise limitations.
- Connect limitations to the proposed work.

## Reviewer Response

User:
`审稿人说实验规模太小，帮我写回复。`

Expected behavior:
- Avoid defensive tone.
- Clarify scope.
- Mention added experiments only if the user provides them.
- Use placeholders for unknown manuscript locations or results.


## Venue-Targeted Introduction

User:
`我要投 DAC，帮我写 Introduction。先看看最近 DAC 类似方向论文怎么写。`

Expected behavior:
- Search recent DAC papers and close topic papers.
- Summarize venue/field structure and contribution style.
- Draft an Introduction using the user's contribution and results.
- Use placeholders for missing results or citations.

## Field-Only Drafting

User:
`我的方向是 FPGA 加速大模型推理，还没有定会议，帮我写 abstract。`

Expected behavior:
- Infer likely venue families such as FPGA/architecture/EDA/system venues.
- State the assumption.
- Search recent representative papers.
- Draft the abstract with venue-style calibration and placeholders for missing numbers.

## Local Grammar Only

User:
`只改语法，不要查资料。`

Expected behavior:
- Do not browse.
- Preserve meaning.
- Return revised text and concise notes.


## Crisp Paragraph Rewrite

User:
`这段太啰嗦了，帮我改成 crispy sentence，每个自然段开头要有 topic sentence。`

Expected behavior:
- Identify the paragraph's controlling idea.
- Rewrite the first sentence as a clear topic sentence.
- Split long sentences.
- Preserve technical meaning.
- Return paragraph plan, revised paragraph, and concise notes.

## Academic Register Check

User:
`帮我检查这段是不是太口语化，改成学术语言。`

Expected behavior:
- Remove colloquialisms, contractions, rhetorical questions, and vague claims.
- Keep the language formal but not pompous.
- Use precise verbs and evidence-based modality.
- Check articles, tense, and countability.

## Given-New Flow

User:
`这段读起来不顺，帮我增强逻辑衔接。`

Expected behavior:
- Reorder sentences so given information comes before new information.
- Use sentence subjects to pick up previously introduced terms.
- Use passive voice if it improves information flow.
- Add transitions only where the logic requires them.
