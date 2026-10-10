# AI-evals-2026
# Evaluating an AI Support Assistant

## 1. Problem

I built a simple AI assistant for an online course.

The assistant needed to answer student questions using only the
provided course information without inventing policies, benefits,
placement claims, or other unsupported information.

The goal was not just to build the assistant, but to create a
repeatable evaluation system for measuring its quality.

## 2. Golden Dataset

I created test cases covering:

- Factual questions
- Reasoning questions
- Boundary conditions
- Missing information
- Leading questions
- Adversarial instructions
- Multi-part questions
- Hallucination risks

Total eval cases: [YOUR NUMBER]

## 3. Evaluation Metrics

1. Correctness
2. Groundedness
3. Instruction Following

A test passed only when all three criteria passed.

## 4. Evaluation Method

I manually evaluated a sample first.

I then created an LLM-as-a-Judge to evaluate the complete
test set using the same rubric, and manually reviewed a
sample of judge decisions.

## 5. Baseline — V1

Correctness: [ ]%
Groundedness: [ ]%
Instruction Following: [ ]%
Overall Pass Rate: [ ]%

## 6. Key Failure Pattern

The most important failure I found was:

[DESCRIBE THE FAILURE]

Examples:
- [TEST CASE]
- [TEST CASE]

## 7. Improvement

Based on the failure analysis, I changed:

[EXPLAIN YOUR CHANGE]

I expected this to improve:

[EXPECTED BEHAVIOUR]

## 8. V1 vs. V2

| Metric | V1 | V2 | Change |
|---|---:|---:|---:|
| Correctness | | | |
| Groundedness | | | |
| Instruction Following | | | |
| Overall Pass Rate | | | |

## 9. New Edge Cases

After the second evaluation, I tried to break the assistant
and added new cases to the eval suite.

Examples:
- [YOUR EDGE CASE]
- [YOUR EDGE CASE]
- [YOUR EDGE CASE]

## 10. What I Learned

- AI quality needs to be defined before it can be measured.
- A few successful demos do not establish reliability.
- Failure patterns are more useful than isolated bad answers.
- LLM judges are useful, but their outputs also need validation.
- Important new failures should become regression tests.

## Artifacts

- Golden Dataset: [LINK OR FILE]
- Evaluation Results: [LINK OR FILE]
- Prompts: [LINK OR FILE]
