# CareCoach: Patient Engagement Feedback App
CoE Growth Project, Batch C28 (about 75% complete draft)

A prototype that explains a patient's progress in simple language (home blood-pressure scenario), with consent, privacy and role-based views (Patient / Clinician / Admin) built into the UI.

## Run
Open `index.html` in any browser. No install needed. Tabs: Prototype, Experiment, Edge cases, Documentation.

## What is included
- Baseline: same generic clinical sentence every week
- Prototype: rule-based plain-language feedback + safety ladder (consent, critical, implausible, missing, normal)
- Experiment: 200 synthetic patients x 8 weeks (see `docs/results.md`)
- 6 edge/failure tests (run live in the Edge cases tab)
- Docs: scenario, baseline, solution, usability walkthrough, clinical failure modes, ethics note, deployment checklist

## Limits
All data is synthetic. Simulated behaviour follows rules set by the author, so results show the design is measurable, not real-world effect. Not a medical device.

## Remaining work
- Stakeholder validation with 3-5 real people
- Screenshots of each role's view
- More random seeds
- Low-literacy support (icons/audio)
