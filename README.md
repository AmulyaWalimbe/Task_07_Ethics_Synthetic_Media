# Task 7: The Ethics of Synthetic Representation

## Description

This repo contains the ethical analysis and governance policy required for Task 7, reasoning
outward from the synthetic voice and video artifacts I built in
[Task 6](https://github.com/AmulyaWalimbe/Task_06_Deep_Fake) into a concrete policy question:
what would responsible use of this capability actually look like inside a real organization.

## Organizational context chosen: University Communications & Marketing Office

I chose this setting because it's a natural extension of my own Task 6 artifact - a coach
advisory narrative built from athletics data - into the office that would realistically be asked
to produce something like it for external use. It also has concrete, describable constraints
(named stakeholders like coaches, student-athletes, and prospective students; a mix of
low-stakes promotional use and high-stakes crisis/admissions communications; a mix of staff and
student workers) that made it possible to write specific permitted/prohibited boundaries rather
than generic principles.

## Repository contents

| File | Contents |
|---|---|
| `PHASE A_Analysis.pdf` | Ethical analysis: return to the Task 6 artifact, reasoning across the truth, consent, context, and scale axes with original hypotheticals, and a survey of the mitigation landscape (disclosure, provenance, detection, legal/regulatory, platform policy, professional norms) |
| `PHASE B_Policy.pdf` | The governance artifact itself — a synthetic media policy for the University Communications & Marketing Office, including a limitations section |

## Relationship to Task 6

This task's analysis is grounded directly in the artifacts, process log, and evaluation from
[Task_06_Deep_Fake](https://github.com/AmulyaWalimbe/Task_06_Deep_Fake). That repo is not
duplicated here — see it directly for the source artifacts, the full process log, and the
detection/provenance evaluation this analysis builds on.

## Reflection: what surprised me

The biggest surprise carrying into this task wasn't anything about how convincing my artifacts
looked - it was what happened when I ran the ElevenLabs narration through a purpose-built
detector and it came back 95% "Likely Authentic." I went into Task 6 assuming detection was the
backstop: if a disclosure ever got lost, at least a good detector could catch the artifact later
and set the record straight. That assumption didn't survive contact with my own data. A tool
built for exactly one job - telling synthetic speech from real speech - got it backwards, and
explained itself with confident, detailed-sounding language that on inspection was partly
generic template text rather than a real per-file analysis.

That result reshaped how I approached Phase B more than anything else. Writing the policy, I
kept reaching for "verify with a detection tool" as a safeguard to slot into the review or
incident-response sections, and had to stop myself each time, because my own Task 6 evidence
says that safeguard doesn't hold. It's one thing to know abstractly that "detectors lag
generators" - it's another to have generated the exact audio clip that fooled one. That gap
between what I assumed going in and what I actually found is, I think, the whole point of doing
Task 6 before Task 7: it's a lot harder to write a policy that leans on detection as a solution
once you've watched detection fail on something you made yourself.
