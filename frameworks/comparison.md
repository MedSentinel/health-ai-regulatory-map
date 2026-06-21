# Framework Comparison

Version: `v0.1`

This page is a compact comparison aid.

It does not tell you which framework definitively governs a product.
It helps you understand what kinds of questions each lens tends to foreground.

## Quick comparison

| Lens | Best for asking | Typical focus | Common mistake |
| --- | --- | --- | --- |
| FDA | What is the intended medical use and how much does the software affect care? | claims, user type, evidence, oversight, decision consequence | treating AI as the issue instead of intended use |
| MHRA | How is innovation being framed in the UK and what evidence is actually behind that framing? | pilots, sandboxes, UK-facing oversight, real-world deployment language | confusing innovation support with proven clinical readiness |
| EU MDR / SaMD | Is the software behaving like a medical device in practice? | medical function, clinical influence, user context, software role | assuming support language automatically avoids device-like scrutiny |
| Clinical Decision Support boundary | How much does the system shape the path to a clinical decision? | support vs influence, prioritization, nudging, action-shaping | focusing only on whether the system gives the final answer |
| Medical Advice boundary | Will a user experience this as advice rather than information? | patient-facing guidance, reassurance, urgency, actionability | relying on disclaimers as if they solve the safety problem |

## How to use this page

Start here when you have a product, launch, paper, or public claim and need a first-pass orientation.

Then move to the more specific note that matches the question you are trying to answer.

## Example usage

### Example 1: Patient-facing symptom assistant

Start with:

- [../boundaries/medical-advice-boundary.md](../boundaries/medical-advice-boundary.md)
- [fda.md](./fda.md)

Why:

The main issue is whether the system is behaving like general information support or drifting toward individualized medical guidance.

### Example 2: Clinician-facing workflow copilot

Start with:

- [../boundaries/clinical-decision-support.md](../boundaries/clinical-decision-support.md)
- [fda.md](./fda.md)
- [eu-mdr-samd.md](./eu-mdr-samd.md)

Why:

The key issue is whether workflow support remains support, or begins to shape clinical action in a meaningful way.

### Example 3: UK sandbox announcement

Start with:

- [mhra.md](./mhra.md)

Why:

The key issue is often whether the public announcement is describing experimental innovation infrastructure, real deployment readiness, or something in between.
