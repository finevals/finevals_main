---
title: "What testing can and cannot evidence"
description: "Behavioural testing can evidence some AI obligations and not others. Here is where the line falls, and why we put it in writing before showing a single result."
author: "FinEvals.ai"
---

Every eval vendor will tell you what their tests cover. Fewer will tell you what
no test can cover — and if you are the one signing off on an AI system, that
second list is the one that decides whether your file holds.

## Where the line falls

Obligations for high-risk AI split into two kinds, and only one of them is
reachable by a test harness.

The first kind is about **how the system behaves**. Does it produce accurate
outputs. Does it discriminate. Does it stay inside its stated purpose. Does it
hold up on inputs it was not designed for. Behaviour can be observed: you build
a scenario with a known correct answer, run the system against it, and count how
often it is right. That is what an eval pack does, and for these obligations it
produces evidence that stands on its own.

The second kind is about **how the organisation works**. How training data was
sourced, governed and documented. Whether technical documentation is complete
and current. Whether records are retained and retrievable. Whether human
oversight is genuinely designed into the workflow rather than asserted on a
slide. These are process and organisational controls. No behavioural test can
see them. You could run every eval ever written and learn nothing about whether
your record-keeping is adequate.

Take the EU AI Act's requirements for high-risk AI in lending. Only a minority
of the relevant articles can be evidenced by testing how the model behaves. The
rest — training-data governance, technical documentation, record-keeping,
human-oversight design — sit outside what any test harness can reach, no matter
how good the tests are.

## Why we say it before showing results

A validator's job is to find the gap between what the evidence shows and what
the sign-off claims. If a pack implies coverage it does not have, that gap is
the first thing they will find. And once they find one, everything else you
handed them gets read differently — including the parts that were sound.

So every pack states, in writing and before it shows a single result, which
obligations it evidences behaviourally, which it evidences only partially, and
which it does not touch at all. That last list is not a disclaimer buried at the
back. It is part of the deliverable, and it is the part that makes the rest
credible.

## What this means in practice

A pack that covers the behavioural obligations well is genuinely useful. It
closes the part of the file that is hardest to close with process evidence
alone, and it closes it with results a validator can re-check rather than
take on trust.

But it closes part of the file, not the file. The organisational controls still
need their own evidence, produced by people and processes rather than by a test
harness. Anyone who tells you a testing product covers all of it is describing
something testing cannot do.
