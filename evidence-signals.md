# Evidence Signals

Version: `v0.1`

This page is a compact guide to evidence maturity in health AI.

It is not a rigid hierarchy.
But it helps distinguish between:

- visible evidence
- partial evidence
- confidence theater

## Quick evidence ladder

| Evidence type | What it tells you | Common limit |
| --- | --- | --- |
| Demo or concept video | the product can be shown | tells you almost nothing about clinical reliability |
| Internal benchmark | the model performs under selected test conditions | may not reflect real workflow or real users |
| Retrospective study | the system can be analyzed on existing data | often weak on prospective workflow reality |
| External validation | the system holds up outside the original build environment | still may not show downstream outcome impact |
| Prospective study | the system was evaluated closer to real use | may still be narrow in setting or population |
| Real-world deployment report | the system has encountered operational reality | may still underreport failure modes |
| Post-market or ongoing monitoring signal | someone is tracking drift, harms, and operational change | quality depends on transparency and scope |

## Questions worth asking

1. Is the evidence about model performance, workflow performance, or patient outcome impact?
2. Is the evidence internal only, or externally tested?
3. Was the system evaluated in the same context in which it is being promoted?
4. Is the company showing best-case evidence, or decision-relevant evidence?
5. Is there any signal of prospective validation, monitoring, or failure analysis?

## Stronger signals

These do not guarantee safety, but they are better signs than a polished demo:

- prospective evaluation
- external validation
- subgroup analysis
- workflow-specific analysis
- explicit limitations
- post-deployment monitoring plans

## Weak or incomplete signals

These are not meaningless, but they should not carry too much rhetorical weight on their own:

- benchmark headlines without deployment context
- "clinically proven" language without linked methods
- pilot language without sample details
- broad safety claims without failure cases
- governance language without product-specific evidence

## Editorial use

This page is useful when a launch feels impressive but underspecified.

It helps shift the discussion from:

- "Does the demo look compelling?"

to:

- "What type of evidence is actually visible here?"
