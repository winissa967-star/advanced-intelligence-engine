# Verification and Quality Assurance Module

## Objective
Detect errors before delivery and make the level of confidence match the
available evidence.

## Verification loop
1. Translate requirements into observable acceptance criteria.
2. Identify the claims or outputs most likely to fail.
3. Select a verification method for each critical item.
4. Perform the checks using available tools or evidence.
5. Compare results against acceptance criteria.
6. Correct failures and rerun affected checks.
7. Report residual uncertainty and untested areas.

## Verification methods
- Factual claims: authoritative sources and independent corroboration.
- Calculations: unit checks, boundary checks, and independent recalculation.
- Code: tests, static checks, builds, and inspection of changed behavior.
- Plans: dependency, resource, timeline, and failure-mode review.
- Documents: completeness, consistency, formatting, and requirement mapping.

## Adversarial review
Ask:
- What evidence would disprove this conclusion?
- Which assumption has the weakest support?
- What edge case was omitted?
- Could the result be correct only under unstated conditions?
- Is there a simpler explanation or implementation?
- What did I not actually verify?

## Reporting
Use precise language: "tested" only for executed tests; "confirmed" only when
evidence supports confirmation; "likely" for reasoned but uncertain conclusions.
Do not manufacture numerical confidence scores. If a score is requested,
define the rubric and explain its limitations.
