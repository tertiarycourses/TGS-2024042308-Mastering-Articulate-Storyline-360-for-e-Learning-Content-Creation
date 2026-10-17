# Activity 13 — Publish Tin Can xAPI and Validate Release

**Course:** Mastering Articulate Storyline 360 for e-Learning Content Creation (`TGS-2024042308`)
**Version:** v11 · 17 October 2026

## Scenario

HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

## Objective

Prepare an xAPI package without embedded secrets and complete regression evidence.

## Supplied files and checkpoint

- Continue from/save as `HarbourLink-WSH-Checkpoint-13-YourName.story`.
- Shared runnable assets are under `../source/`.
- A completed `.story` solution is not supplied; build and test the project in Storyline 360 on Windows.

## Detailed procedure

1. Open checkpoint 12 and Save As checkpoint 13.
2. Choose Home > Publish > LMS/LRS; open Reporting and Tracking.
3. Select `xAPI (Tin Can API)` and enter the approved stable activity identifier.
4. Track the quiz Results slide and record the selected completion basis.
5. If the target specifically requires cmi5, create and document a separate cmi5 publication; do not describe the generic xAPI package as cmi5.
6. Do not enter or embed endpoint credentials in learner files.
7. Publish locally and create the ZIP from Publish Successful.
8. Inspect the package for accidental tokens, passwords, endpoints or learner data.

![Figure 13.1 — Step 8: AI RECREATED release-trace orientation; choose xAPI (Tin Can API), then verify the target and launch-supplied actor in the current UI. AI RECREATED illustrative orientation; example values may differ, so verify the named control in your own checkpoint.](figures/ai-recreated-reporting-tracking.png)

*Figure 13.1 — Step 8: AI RECREATED release-trace orientation; choose xAPI (Tin Can API), then verify the target and launch-supplied actor in the current UI. AI RECREATED illustrative orientation; example values may differ, so verify the named control in your own checkpoint.*

9. Launch through the approved xAPI-enabled LMS or LRS launch target so actor, endpoint and authentication are supplied at launch.
10. Capture an illustrative Actor/Verb/Object trace only after removing personal data.
11. Inspect statements actually emitted by the current Storyline build and selected tracking.
12. Verify received score and completion; do not promise verbs the runtime did not emit.
13. If a target action requires an extra statement, add an explicit xAPI trigger and document it.
14. If no approved LRS launch exists, complete the blocked-test record without claiming success.
15. Run regression with a clean learner state and record source version, ZIP checksum and actual results.
16. Archive source, ZIP, settings, test log, review approval and provenance together.

## Evidence to retain

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

## Acceptance criteria

- [ ] No credential appears in the package.
- [ ] Activity identifier is stable and recorded.
- [ ] Statement evidence or honest blocker is retained.
- [ ] Release package is reproducible.

## Reflection prompts

- Which storyboard or audience requirement drove your most important decision?
- Which Storyline panel, trigger or setting proves that decision is implemented?
- What accessibility, rights or publishing evidence must accompany the finished project?
