# Common English Fixes for Engineering Papers

Use this file when polishing Chinese-to-English academic writing, especially CS, engineering, FPGA, CGRA, architecture, and algorithm papers.

The examples are patterns, not blind replacements. Preserve the user's technical meaning.

## Objective Subject

Prefer objective subjects when the venue discourages first person.

- Weak: `In this paper, we propose...`
- Better: `This paper proposes...`
- Better: `The proposed method...`
- Better: `Section 4 presents...`

Do not remove first person if the target venue explicitly accepts or prefers `we`.

## Articles

Chinese has no articles, so check every singular countable noun.

- Weak: `with the footprint of`
- Better: `with a footprint of`

- Weak: `called dual track model`
- Better: `called the dual-track model` if the model was already introduced.

- Weak: `provides a direct access to`
- Better: `provides direct access to`

## Singular and Plural

Check technical abbreviations carefully.

- Weak: `MorphSys and ADRES has no local memory`
- Better: `MorphSys and ADRES have no local memory`

- Weak: `the number of RC`
- Better: `the number of RCs`

- Weak: `Three pairs of multiplier-ALU`
- Better: `Three pairs of multiplier-ALUs`

- Weak: `the total energy consumption are listed`
- Better: `the total energy consumption is listed`

- Weak: `performance scalability is measured with different number of RC`
- Better: `performance scalability is evaluated with different numbers of RCs`

## Prepositions

Use standard technical collocations.

- `running at 450 MHz`, not `running with 450 MHz`
- `explored in the spatial domain`, not `explored from the spatial domain`
- `distinguish it from other CGRAs`, not `distinguish with other CGRAs`
- `inputs to HLS`, not `inputs of HLS`
- `useful for data`, not `useful on data`
- `increase in the number of RCs`, not `increase of the number of RC`

## Comparison and Metrics

Make comparison direction explicit.

- Weak: `2483x energy efficiency`
- Better: `2483 times higher energy efficiency`
- Better: `improves energy efficiency by 2483 times`
- Better: `achieves, on average, 2483 times the energy efficiency of [baseline]`

Use `compared with/to` for passive comparison:
- Weak: `Comparing to previous CGRAs`
- Better: `Compared with previous CGRAs`
- Better: `When compared with previous CGRAs`

Avoid `more` without a comparison target:
- Weak: `accelerate more algorithms`
- Better: `accelerate multiple algorithms`
- Better: `accelerate more algorithms than [baseline]`

## Avoid Colloquial "Do"

Replace informal `do` constructions with technical verbs or noun phrases.

- Weak: `do convolution`
- Better: `perform convolution`
- Better: `support efficient convolution`
- Better: `for efficient convolution`

- Weak: `do multiplication and accumulation`
- Better: `perform multiplication and accumulation`
- Better: `for multiplication and accumulation`

## Precision of Verbs

Choose verbs that match the object.

- A problem is `solved`, `addressed`, or `alleviated`, not `improved`.
- A method `targets` an application, not `aims for` an application.
- A design `supports scalability`, not `is designed for the scalability purpose`.
- A method `reduces overhead`, not always `decreases overhead`.
- A design `takes 34 s`, not `costs 34 s`.
- A method `uses/adopts/involves RLE`, not `is RLE methods`.

## Word Choice

Prefer precise academic words:
- `significant` or `important`, not `meaningful` when discussing research value.
- `case studies`, not `study cases`.
- `corresponding`, not `correspondent` for "对应的".
- `initially`, not `firstly` unless a second/third item follows.
- `many`, not `most`, unless the majority claim is supported.
- `recent advances`, not `the development`, when referring to progress in a field.
- `increasingly important`, not `more and more important`.

## Concision

Prefer compact noun phrases when clear:
- Weak: `the bandwidth from off-chip memory`
- Better: `off-chip memory bandwidth`

- Weak: `the decompression throughput of it`
- Better: `its decompression throughput`

- Weak: `is lack of competitiveness`
- Better: `is not competitive`

- Weak: `It is clearly to see that`
- Better: `It is clear that`
- Better: remove the phrase and state the result directly.

## Avoid Unnecessary Intensifiers

Remove words that do not add technical meaning:
- `also` when there is no true addition.
- `already` when present tense is enough.
- `just` unless the limitation is deliberate.
- `only` unless the exclusivity is verified and important.

## Sentence Completeness

Watch for Chinese-style fragments translated into English.

- Weak: `There are two key factors should be considered...`
- Better: `Two key factors should be considered...`
- Better: `There are two key factors that should be considered...`

- Weak: `There are two problems must be resolved.`
- Better: `Two problems must be resolved.`
- Better: `There are two problems that must be resolved.`
