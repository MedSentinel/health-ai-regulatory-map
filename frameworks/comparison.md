# Framework Comparison

Version: `v0.2`

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

## Decision table

| If the public claim sounds like this | Start with | Why |
| --- | --- | --- |
| "Helps detect, screen, diagnose, or predict" | FDA, EU MDR / SaMD | medical-use language is already close to device-style scrutiny |
| "Supports clinicians without replacing them" | Clinical Decision Support boundary, FDA | support language often hides meaningful clinical influence |
| "Patient-centered guidance" or "personalized health support" | Medical Advice boundary, FDA | personalization can drift into advice even without explicit diagnosis claims |
| "Safer, more accurate, clinically proven" | Evidence Signals, ISO 14971, FDA | safety and accuracy claims need evidence and risk context |
| "Governed, responsible, enterprise-ready AI" | ISO/IEC 42001, Evidence Signals | governance language may be strong while product evidence remains weak |
| "Sandbox, pilot, innovation program, real-world testing" | MHRA, Evidence Signals | innovation framing is not the same thing as readiness |

## Lens selection by question

| Your question | Primary lens | Secondary lens |
| --- | --- | --- |
| Is this product making a medical claim? | FDA | EU MDR / SaMD |
| Is this still support, or is it shaping care? | Clinical Decision Support boundary | FDA |
| Will a patient experience this as advice? | Medical Advice boundary | FDA |
| Is this company using regulation language too loosely? | FDA or EU MDR / SaMD | Claim Language |
| Is this launch evidence-light but rhetorically strong? | Evidence Signals | Review Questions |
| Is this UK innovation framing ahead of actual evidence? | MHRA | Evidence Signals |

## What each lens tends to miss

| Lens | What it tends to miss if used alone |
| --- | --- |
| FDA | workflow burden, organizational readiness, subtle user over-reliance |
| MHRA | product-specific maturity hidden beneath innovation language |
| EU MDR / SaMD | patient-perception issues in consumer-facing tools |
| Clinical Decision Support boundary | broader governance claims and evidence maturity |
| Medical Advice boundary | clinician-side workflow consequences |

## Public-language triggers

These phrases are not conclusions, but they are good reasons to slow down:

- patient-centered
- clinically proven
- FDA-cleared
- real-world validated
- decision support only
- not intended to diagnose
- responsible AI
- enterprise-grade governance
- breakthrough
- whole-body imaging

Use those phrases as prompts to ask:

- what exactly is being claimed
- for whom
- under what evidence conditions
- with what remaining uncertainty

## How to use this page

Start here when you have a product, launch, paper, or public claim and need a first-pass orientation.

Then move to the more specific note that matches the question you are trying to answer.

If the product language itself feels slippery, read:

- [../claim-language.md](../claim-language.md)

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

### Example 4: "Patient-centered" ambient scribe claim

Start with:

- [../claim-language.md](../claim-language.md)
- [../boundaries/clinical-decision-support.md](../boundaries/clinical-decision-support.md)
- [../review-questions.md](../review-questions.md)

Why:

The main issue may not be pure model performance.
It may be whether efficiency language is being quietly reframed as patient benefit.
