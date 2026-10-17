# Mastering Articulate Storyline 360 for e-Learning Content Creation — Learner Guide

**Course code:** TGS-2024042308
**Version:** v11 · 17 October 2026

## Purpose

This guide contains the detailed Storyline 360 procedures, evidence requirements and acceptance criteria intentionally omitted from the visual course slides. The 14 connected activities start from a blank Storyline project and continue through exact named checkpoints to an independently created mini capstone. Storyline requires a supported Windows authoring environment; this package does not mislabel legacy or fabricated .story files as completed solutions.

## Learning outcomes

- LO1: Conceptualise and map digital storyboards integrating principles of storytelling in Storyline 360.
- LO2: Identify and determine diverse e-learning content aligned with audience preferences, industry trends and content features.
- LO3: Determine effective modes and processes for distributing interactive e-learning content.
- LO4: Develop guidelines and determine content delivery frequency for effective e-learning delivery.

## TSC alignment

| Code | Knowledge / Ability |
|---|---|
| K1 | Principles of digital storytelling |
| K2 | Potential customers' evolving preferences for content types, styles and modes of delivery |
| K3 | Process of developing a digital storyboard |
| K4 | Parameters for delivering content for marketing purposes |
| K5 | Features of marketing content |
| K6 | Modes of content delivery for marketing |
| A1 | Conceptualise content ideas to meet marketing objectives |
| A2 | Map out digital storyboards as part of a content strategy |
| A3 | Identify content requirements from customer and potential-customer preferences |
| A4 | Determine the frequency of delivering marketing content to customers |
| A5 | Determine the types and styles of content to deliver to customers |
| A6 | Determine modes and processes for distributing content |
| A7 | Develop guidelines for content-strategy execution |

## Core professional workflow

1. Verify the performance gap, required learner behaviour, audience, device, delivery channel and success measure.
2. Map screens, narration, media, interactions, branches, accessibility and evidence in the storyboard.
3. Prototype the riskiest screens and interactions; record review decisions before full production.
4. Work locally from the exact named blank-project checkpoint and retain every prior checkpoint.
5. Use reusable themes, layouts, named objects, layers, states, triggers and variables deliberately.
6. Check visual grammar, rights, provenance, alternative text, focus order, captions, media equivalents and keyboard operation as content is added.
7. Preview the slide, scene and project; test correct, incorrect, boundary, revisit, resume and representative device paths.
8. Publish only to the approved review/test target, verify runtime/tracking and retain the source plus evidence.

## Topic 1 — Project Architecture and Storyboard

Blank project · scenes · theme · masters · storyboard · naming · variables · navigation · preview

**Alignment:** LO1 · A1 · A2 · K1 · K3

### Local project baseline

File > Save As creates WSA-YourName-v01.story on a local Windows drive

**Best used for:** The connected workplace-safety module where local project baseline must produce a testable authoring artifact.

**Key controls:** short local path; version suffix; backup copy

**Watch for:** network/removable-drive authoring; overwriting the baseline

**Quality evidence:** v01 opens locally and the checksum/modified time identifies the retained baseline

### Story View scene architecture

Story View groups Welcome, Learn, Practise, Quiz and Resources scenes and exposes jump paths

**Best used for:** The connected workplace-safety module where story view scene architecture must produce a testable authoring artifact.

**Key controls:** scene names; start scene; slide order; jump targets

**Watch for:** assuming canvas order controls runtime navigation

**Quality evidence:** every route has an intended entry, return and terminal slide

### Slide size and safe area

Design > Slide Size fixes the authoring canvas before layouts and media are placed

**Best used for:** The connected workplace-safety module where slide size and safe area must produce a testable authoring artifact.

**Key controls:** 16:9 size; player chrome; caption area; minimum target size

**Watch for:** changing size after build and clipping controls

**Quality evidence:** preview at the intended player size keeps controls and captions visible

### Theme fonts and colours

Design > Fonts > Create New Theme Fonts and Design > Colors > Create New Theme Colors define the HarbourLink palette; Design > Themes saves the combined theme

**Best used for:** The connected workplace-safety module where theme fonts and colours must produce a testable authoring artifact.

**Key controls:** heading/body fonts; contrast; semantic colours; theme naming

**Watch for:** manual near-match colours and colour-only meaning

**Quality evidence:** theme values reproduce consistently on three representative slides

### Slide master hierarchy

View > Slide Master defines title, content, scenario and quiz layouts with stable placeholders

**Best used for:** The connected workplace-safety module where slide master hierarchy must produce a testable authoring artifact.

**Key controls:** master; layout; placeholder; background; inheritance

**Watch for:** placing course-specific content on the master

**Quality evidence:** new slides inherit geometry without unwanted objects

### Storyboard screen specification

The supplied CSV maps screen ID, purpose, narration, asset, interaction, branch and accessibility

**Best used for:** The connected workplace-safety module where storyboard screen specification must produce a testable authoring artifact.

**Key controls:** unique IDs; owner; status; evidence; source

**Watch for:** building before branch and accessibility fields are resolved

**Quality evidence:** each Storyline slide maps to one storyboard row and acceptance check

### Object naming discipline

Timeline object names encode type and purpose such as btn_Hazard01 and lyr_Hazard01

**Best used for:** The connected workplace-safety module where object naming discipline must produce a testable authoring artifact.

**Key controls:** prefixes; unique names; layer names; variable names

**Watch for:** leaving Rectangle 17 or duplicate names

**Quality evidence:** trigger and focus panels can be audited without selecting each object

### Timeline timing model

Timeline start, duration and cue points coordinate narration, captions and reveals

**Best used for:** The connected workplace-safety module where timeline timing model must produce a testable authoring artifact.

**Key controls:** playhead; cue point; show until end; align to playhead

**Watch for:** objects appearing before narration or disappearing on revisit

**Quality evidence:** preview timing matches the narration script at each cue point

### Alignment and guides

View guides plus Align and Distribute create a repeatable grid for text and controls

**Best used for:** The connected workplace-safety module where alignment and guides must produce a testable authoring artifact.

**Key controls:** guides; margins; distribute; aspect ratio

**Watch for:** pixel drift and stretched images

**Quality evidence:** shared edges and spacing remain consistent at delivery size

### Project variables register

Manage Project Variables defines typed names, defaults, purpose and reset ownership

**Best used for:** The connected workplace-safety module where project variables register must produce a testable authoring artifact.

**Key controls:** True/False; Number; Text; default; scope

**Watch for:** variables with ambiguous names or stale values

**Quality evidence:** variable reference panel matches the supplied logic register

### Scene menu navigation

A custom menu uses explicit Jump to slide triggers and visited states

**Best used for:** The connected workplace-safety module where scene menu navigation must produce a testable authoring artifact.

**Key controls:** button state; destination; focus order; return path

**Watch for:** relying on slide order or trapping the learner

**Quality evidence:** keyboard and pointer routes reach all four learning topics and return

### Revisit behaviour

Slide Properties selects Automatically decide, Resume saved state or Reset to initial state per requirement

**Best used for:** The connected workplace-safety module where revisit behaviour must produce a testable authoring artifact.

**Key controls:** revisit mode; timeline; layer state; variable persistence

**Watch for:** global revisit choice applied without testing

**Quality evidence:** back, next and relaunch tests produce the specified state

### Player feature baseline

Player Properties exposes only required controls and a predictable course title

**Best used for:** The connected workplace-safety module where player feature baseline must produce a testable authoring artifact.

**Key controls:** menu; seekbar; volume; captions; glossary; resources

**Watch for:** duplicated navigation and inaccessible custom chrome

**Quality evidence:** player and slide controls do not conflict in keyboard testing

### Preview test levels

Preview This Slide, This Scene and Entire Project reveal different classes of defects

**Best used for:** The connected workplace-safety module where preview test levels must produce a testable authoring artifact.

**Key controls:** slide logic; cross-slide routing; project variables; player

**Watch for:** signing off from single-slide preview

**Quality evidence:** scene and project test logs cover entry, exit, revisit and resume

### Recovery and version handoff

Save As versions plus a release register separate editable source from published output

**Best used for:** The connected workplace-safety module where recovery and version handoff must produce a testable authoring artifact.

**Key controls:** source version; owner; publish ID; backup; archive

**Watch for:** renaming only the published ZIP or losing the .story source

**Quality evidence:** handoff opens the exact source used to create the tested package

### HarbourLink annual WSH narrative beat map

A worked beat map links normal work, visible disruption, decision, consequence and safer resolution across screen IDs WSA-001 to WSA-401

**Best used for:** The connected workplace-safety module where harbourlink annual wsh narrative beat map must produce a testable authoring artifact.

**Key controls:** protagonist; workplace goal; hazard tension; learner choice; consequence; resolution

**Watch for:** adding a decorative story that does not change the learner decision

**Quality evidence:** each beat maps to a slide, learner action and observable safety outcome

### Marketing objective to learning promise

A traceability row converts the provider objective 'increase induction completion and safe-reporting uptake' into a learner promise and measurable action

**Best used for:** The connected workplace-safety module where marketing objective to learning promise must produce a testable authoring artifact.

**Key controls:** business objective; audience action; course promise; metric; data owner

**Watch for:** claiming engagement without a defined behaviour or measure

**Quality evidence:** objective, promise, interaction and metric read as one causal chain

### Digital storyboard production cycle

The HarbourLink annual WSH storyboard moves through brief, screen map, narration/media, interaction/branch, accessibility, prototype review and signed revision

**Best used for:** The connected workplace-safety module where digital storyboard production cycle must produce a testable authoring artifact.

**Key controls:** screen ID; owner; asset; branch; access; version; approval

**Watch for:** treating the storyboard as on-screen copy only

**Quality evidence:** one reviewed CSV row contains every required production field and disposition

### PowerPoint slide import

Home > New Slide > Import imports selected source slides into a named scene, followed by master, font and trigger inspection

**Best used for:** The connected workplace-safety module where powerpoint slide import must produce a testable authoring artifact.

**Key controls:** source file; selected slides; destination scene; imported masters; media links

**Watch for:** assuming imported slide order, theme or accessibility is production-ready

**Quality evidence:** import log lists selected slides and the review confirms masters, focus order and navigation

### Activity 01 — Start the Safety Module and Storyboard

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Create the local source baseline, five-scene architecture and traceable storyboard.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-01-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Create a new blank Storyline project and save it as `HarbourLink-WSH-Checkpoint-01-YourName.story` on a local Windows drive. No completed .story solution is supplied.
2. Open `source/storyboard.csv` and the previous checkpoint, then confirm the screen IDs and acceptance criteria before editing.
3. In Story View, create and name scenes `01 Welcome`, `02 Learn`, `03 Practise`, `04 Quiz`, and `05 Resources`; set Welcome as the starting scene.
4. Import `source/storyboard.csv` into your working notes and create the listed placeholder slides with matching screen IDs.
5. Choose Design > Slide Size > 16:9 (960 × 540) before placing content; record the exact dimensions in the build log.
6. Create a variable register in project notes for `HazardsFound` (Number, 0), seven hazard flags (True/False, False), `RiskLevel` (Number, 1), and `LearnerName` (Text, blank).
7. Preview the entire project and confirm every scene has an intentional entry and return path.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Five named scenes and storyboard IDs match.
- Variables use the specified type and default.
- Source and checkpoint are versioned locally.
- Whole-project preview has no dead end.

Self-contained lab folder: `activities/activity-01-brief-storyboard-project/`

### Activity 02 — Build Theme, Masters and Menu

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Create reusable visual layouts and accessible scene navigation.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-02-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open `HarbourLink-WSH-Checkpoint-01-YourName.story` from the previous activity and immediately use File > Save As to create `HarbourLink-WSH-Checkpoint-02-YourName.story` on a local Windows drive. Preserve the prior checkpoint; no completed .story solution is supplied.
2. Open `source/storyboard.csv` and the previous checkpoint, then confirm the screen IDs and acceptance criteria before editing.
3. Choose Design > Fonts > Create New Theme Fonts and Design > Colors > Create New Theme Colors from `source/style-guide.md`; then use Design > Themes to save the combined HarbourLink theme.
4. Open View > Slide Master and build title, content, scenario and quiz layouts; keep course-specific text off the master.
5. On the menu slide, add four labelled buttons with Normal, Hover, Visited and Disabled states.
6. Add explicit Jump to slide triggers for Learn, Practise, Quiz and Resources; name each button and check Focus Order.
7. Test Tab, Shift+Tab, Enter and Space, then verify each destination returns to the menu.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Four reusable layouts inherit correctly.
- Theme values match the style guide.
- Menu routes and returns correctly.
- Keyboard focus and state changes are visible.

Self-contained lab folder: `activities/activity-02-theme-masters-menu/`

## Topic 2 — Media, Interaction and Accessibility

Media Library · hazards · hotspots · layers · states · triggers · motion · simulation · audio · captions

**Alignment:** LO2 · A3 · A5 · K2 · K5

### Picture insertion and crop

Insert > Picture plus Picture Format > Crop fits safety photography without distortion

**Best used for:** The connected workplace-safety module where picture insertion and crop must produce a testable authoring artifact.

**Key controls:** crop focal point; compression; alt text; source

**Watch for:** stretching media or hiding critical hazard detail

**Quality evidence:** image remains sharp and the hazard stays visible at player size

### Illustration and icon system

Insert > Icons/Illustrations creates consistent editable safety cues

**Best used for:** The connected workplace-safety module where illustration and icon system must produce a testable authoring artifact.

**Key controls:** style; size; theme colour; decorative flag

**Watch for:** mixing styles or announcing decorative icons

**Quality evidence:** icons reinforce labels and remain understandable without colour

### Media Library replacement

View > Media Library replaces a source asset and exposes where it is used

**Best used for:** The connected workplace-safety module where media library replacement must produce a testable authoring artifact.

**Key controls:** asset name; usage count; replace; source record

**Watch for:** changing one instance while duplicates drift

**Quality evidence:** replacement updates intended uses and preserves crops after review

### Hazard hotspot geometry

Hotspots sit over seven visible hazards with non-overlapping target regions

**Best used for:** The connected workplace-safety module where hazard hotspot geometry must produce a testable authoring artifact.

**Key controls:** target bounds; label; focus alternative; z-order

**Watch for:** tiny invisible targets or overlapping hotspots

**Quality evidence:** all hazards can be activated by pointer and equivalent keyboard controls

### Hotspot information layers

Each hazard opens one named layer with risk, control and close action

**Best used for:** The connected workplace-safety module where hotspot information layers must produce a testable authoring artifact.

**Key controls:** show layer; hide layer; focus; pause base timeline

**Watch for:** click-through behind the layer or stranded focus

**Quality evidence:** open/close cycles return focus to the invoking hazard control

### Keyboard hotspot alternative

Visible numbered buttons mirror hotspot triggers for keyboard and screen-reader users

**Best used for:** The connected workplace-safety module where keyboard hotspot alternative must produce a testable authoring artifact.

**Key controls:** button label; trigger parity; focus order; visible focus

**Watch for:** mouse-only discovery

**Quality evidence:** keyboard activation shows the same hazard layer and visited state

### Layer properties

Layer Properties controls hide other layers, prevent base clicks, pause and revisit behaviour

**Best used for:** The connected workplace-safety module where layer properties must produce a testable authoring artifact.

**Key controls:** modal behaviour; base visibility; reset/resume

**Watch for:** two hazard layers visible or base controls active behind modal

**Quality evidence:** only one layer is operable and close restores the base slide

### Built-in object states

Normal, Hover, Down, Visited and Disabled states communicate interaction status

**Best used for:** The connected workplace-safety module where built-in object states must produce a testable authoring artifact.

**Key controls:** state name; contrast; icon/text cue; initial state

**Watch for:** colour-only visited state or disabled focus target

**Quality evidence:** state change is perceivable in pointer and keyboard paths

### Custom hazard states

Custom Safe and Selected states show mitigated equipment after a learner choice

**Best used for:** The connected workplace-safety module where custom hazard states must produce a testable authoring artifact.

**Key controls:** custom state; trigger condition; persistent variable

**Watch for:** duplicating whole objects for visual changes

**Quality evidence:** one object changes predictably without shifting geometry

### Trigger execution order

The Triggers panel orders adjust-variable, change-state and show-layer actions deliberately

**Best used for:** The connected workplace-safety module where trigger execution order must produce a testable authoring artifact.

**Key controls:** event; object; condition; top-to-bottom order

**Watch for:** navigation fires before evidence is stored

**Quality evidence:** trigger trace shows the variable updated before feedback/navigation

### Conditional trigger gate

Next jumps only when HazardsFound equals 7; otherwise a prompt layer opens

**Best used for:** The connected workplace-safety module where conditional trigger gate must produce a testable authoring artifact.

**Key controls:** condition; comparison; else feedback; count display

**Watch for:** hidden dead-end or gate based on clicks rather than distinct hazards

**Quality evidence:** six hazards block progression; seven allow it

### True/False completion flags

Hazard01Found through Hazard07Found prevent repeated clicks inflating the count

**Best used for:** The connected workplace-safety module where true/false completion flags must produce a testable authoring artifact.

**Key controls:** default False; condition False; set True

**Watch for:** incrementing every time a hotspot is clicked

**Quality evidence:** repeated activation leaves HazardsFound unchanged

### Number variable counter

HazardsFound increments once per newly identified hazard and drives progress text

**Best used for:** The connected workplace-safety module where number variable counter must produce a testable authoring artifact.

**Key controls:** add 1; variable reference; upper bound; reset

**Watch for:** counter exceeding seven or resetting on revisit

**Quality evidence:** counter sequence is 0–7 and survives specified revisit

### Variable references

Text %HazardsFound% of 7 found gives visible progress tied to runtime state

**Best used for:** The connected workplace-safety module where variable references must produce a testable authoring artifact.

**Key controls:** reference syntax; accessible label; update event

**Watch for:** hard-coded progress text drifting from logic

**Quality evidence:** display matches the variable after every unique selection

### Motion path forklift

A named motion path demonstrates a moving-forklift hazard and supports path-intersection logic

**Best used for:** The connected workplace-safety module where motion path forklift must produce a testable authoring artifact.

**Key controls:** path name; duration; relative start; reverse; trigger

**Watch for:** uncontrolled autoplay motion or path ending off-canvas

**Quality evidence:** motion starts on learner action, remains visible and can be paused

### Animation accessibility

Motion is brief, purposeful and paired with static explanation and learner control

**Best used for:** The connected workplace-safety module where animation accessibility must produce a testable authoring artifact.

**Key controls:** play/pause; duration; alternative; no flashing

**Watch for:** decorative motion causing distraction or vestibular discomfort

**Quality evidence:** meaning is available when animation is paused or skipped

### Slider risk control

A 1–5 slider writes RiskLevel and updates a textual risk classification

**Best used for:** The connected workplace-safety module where slider risk control must produce a testable authoring artifact.

**Key controls:** start; end; step; variable; state mapping

**Watch for:** unlabelled values or pointer-only input

**Quality evidence:** arrow keys change the value and every value has a text equivalent

### Dial inspection control

A dial rotates through inspection zones and reveals the matching checklist layer

**Best used for:** The connected workplace-safety module where dial inspection control must produce a testable authoring artifact.

**Key controls:** steps; start; end; variable; trigger

**Watch for:** continuous values with unreachable layers

**Quality evidence:** each detent selects exactly one named inspection zone

### Web object incident form

Insert > Web Object embeds the supplied local incident-report simulation folder

**Best used for:** The connected workplace-safety module where web object incident form must produce a testable authoring artifact.

**Key controls:** index.html root; focus exit; fallback link; offline test

**Watch for:** selecting a single HTML file or depending on external tracking

**Quality evidence:** published output loads locally and keyboard users can enter and leave it

### Screen recording preparation

Slides > Record Screen captures a clean bounded application workflow with no private data

**Best used for:** The connected workplace-safety module where screen recording preparation must produce a testable authoring artifact.

**Key controls:** recording region; resolution; notifications; rehearsal

**Watch for:** tiny UI, exposed data or unplanned cursor search

**Quality evidence:** test capture is readable and follows the scripted incident-report path

### View mode screencast

Insert recording as Video on a Single Slide for an uninterrupted demonstration

**Best used for:** The connected workplace-safety module where view mode screencast must produce a testable authoring artifact.

**Key controls:** video controls; captions; trim; poster frame

**Watch for:** autoplay sound or unreadable cursor detail

**Quality evidence:** learner can pause, seek and use captions/transcript

### Try mode simulation

Insert recording as Step-by-Step Slides > Try Mode adds coached interactive actions

**Best used for:** The connected workplace-safety module where try mode simulation must produce a testable authoring artifact.

**Key controls:** hint caption; hotspot; failure layer; attempts

**Watch for:** automatic steps accepting the wrong target

**Quality evidence:** expected actions advance and wrong actions show actionable coaching

### Test mode simulation

Test Mode records scored actions without coaching and reports through a result slide

**Best used for:** The connected workplace-safety module where test mode simulation must produce a testable authoring artifact.

**Key controls:** score; attempts; feedback; tracked result

**Watch for:** testing pixel precision instead of meaningful action

**Quality evidence:** correct and incorrect actions score according to the specification

### Audio narration import

Insert > Audio > Audio from File places the supplied WAV/MP3 on the intended slide

**Best used for:** The connected workplace-safety module where audio narration import must produce a testable authoring artifact.

**Key controls:** timeline name; trim; volume; fade; playback

**Watch for:** multiple tracks overlapping on revisit

**Quality evidence:** one intelligible track plays and stops at the specified boundary

### Caption import

Select the audio, then Options > Import (or Accessibility > Import CC) imports WebVTT and exposes the player caption control

**Best used for:** The connected workplace-safety module where caption import must produce a testable authoring artifact.

**Key controls:** VTT timing; speaker labels; meaningful sound; position

**Watch for:** captions drifting or covering controls

**Quality evidence:** caption spot-check matches narration at start, middle and end

### Transcript equivalent

Resources or an accessible text layer supplies narration plus relevant visual actions

**Best used for:** The connected workplace-safety module where transcript equivalent must produce a testable authoring artifact.

**Key controls:** equivalent meaning; reading order; download link

**Watch for:** verbatim transcript omitting visual hazards

**Quality evidence:** learner can complete the objective without hearing the audio

### Focus order panel

Home > Focus Order removes decorative objects and sequences interactive content logically

**Best used for:** The connected workplace-safety module where focus order panel must produce a testable authoring artifact.

**Key controls:** object visibility; order; names; layer focus

**Watch for:** timeline order mistaken for reading order

**Quality evidence:** Tab/Shift+Tab follows the intended task sequence

### Alternative text

Size and Position > Accessibility names meaningful images and controls

**Best used for:** The connected workplace-safety module where alternative text must produce a testable authoring artifact.

**Key controls:** concise purpose; decorative blank; no filename

**Watch for:** describing appearance but omitting instructional meaning

**Quality evidence:** screen-reader output conveys the hazard and available action

### Accessible text styling

Native text, sufficient contrast and restrained formatting preserve zoom and reflow usability

**Best used for:** The connected workplace-safety module where accessible text styling must produce a testable authoring artifact.

**Key controls:** font size; contrast; spacing; heading role

**Watch for:** text baked into images or low-contrast overlays

**Quality evidence:** content remains readable at 200% browser zoom

### Audience preference matrix

A worked matrix compares new warehouse staff, supervisors and mobile field staff by prior knowledge, language, device, bandwidth, session length and evidence need

**Best used for:** The connected workplace-safety module where audience preference matrix must produce a testable authoring artifact.

**Key controls:** persona; context; device; language; accessibility; format; duration

**Watch for:** using one content style because it is convenient for the author

**Quality evidence:** each audience difference changes a named media, interaction or delivery choice

### Content type and style decision

A selection table scores narrated scenario, hotspot inspection, job aid and quiz against immediacy, practice, accessibility and tracking

**Best used for:** The connected workplace-safety module where content type and style decision must produce a testable authoring artifact.

**Key controls:** content type; style; mode; criterion; score; rationale

**Watch for:** choosing novelty over performance need

**Quality evidence:** selected mix has a recorded criterion-level rationale and accessible equivalent

### Safety content feature specification

The specification defines concise copy, realistic hazards, consequence feedback, learner control, captions and persistent progress as mandatory features

**Best used for:** The connected workplace-safety module where safety content feature specification must produce a testable authoring artifact.

**Key controls:** accuracy; relevance; clarity; interactivity; accessibility; provenance

**Watch for:** describing features as broad benefits without acceptance values

**Quality evidence:** each feature has an owner, threshold and preview/publish test

### Content Library 360 assets

Insert > Content Library 360 adds a permitted template, character or media asset and records its use

**Best used for:** The connected workplace-safety module where content library 360 assets must produce a testable authoring artifact.

**Key controls:** asset type; search/filter; licence context; crop; alt text

**Watch for:** treating a template as finished instruction or mixing incompatible styles

**Quality evidence:** inserted asset is adapted to the WSA theme and has purpose, provenance and accessibility metadata

### 360-degree image interaction

Insert > 360° Image adds an explorable warehouse view with labelled markers and hotspots

**Best used for:** The connected workplace-safety module where 360-degree image interaction must produce a testable authoring artifact.

**Key controls:** initial view; marker label; hotspot target; accessible alternative; completion cue

**Watch for:** hidden required targets, motion discomfort or mouse-only exploration

**Quality evidence:** all required locations are discoverable with an equivalent keyboard-accessible list and clear completion state

### Video insert and edit

Insert > Video adds a safety demonstration; Video Tools configures trim, poster frame, controls and captions

**Best used for:** The connected workplace-safety module where video insert and edit must produce a testable authoring artifact.

**Key controls:** source; trim in/out; playback; compression; captions; transcript

**Watch for:** autoplay with sound, unreadable detail or captions covering controls

**Quality evidence:** learner can pause/seek and obtain equivalent meaning through captions and transcript

### Native text, shapes and tables

Insert > Text Box, Shape and Table creates editable safety labels and a risk-control table

**Best used for:** The connected workplace-safety module where native text, shapes and tables must produce a testable authoring artifact.

**Key controls:** heading hierarchy; margins; table headers; contrast; focus order

**Watch for:** text baked into images or tables used only for layout

**Quality evidence:** content remains editable, readable at 200% zoom and ordered logically for assistive technology

### Activity 03 — Add Media and Hazard Scene

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Construct the warehouse visual with rights-aware media and seven meaningful hazards.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-03-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open the previous checkpoint and File > Save As `HarbourLink-WSH-Checkpoint-03-YourName.story`.
2. In Story View open scene `02 Learn`; open the existing storyboard placeholder `WSA-101 Hazard Walkthrough` and replace its placeholder content without creating a duplicate slide ID.
3. In Slide View choose Insert > Picture, browse to `activities/source/warehouse-seven-hazards.png`, and select Insert.
4. Choose Picture Tools — Format > Crop; drag the crop handles without stretching until all seven hazards remain visible, then click Crop again to finish.
5. Right-click the picture > Accessibility; enter alt text describing the unsafe warehouse inspection scene.
6. Open View > Media Library; rename the asset `img_WarehouseHazards` and record the source in the evidence sheet.
7. Choose Insert > Hotspot; draw a non-overlapping region over the forklift route.
8. Duplicate and reposition hotspots for blocked exit, spill, unstable stack, missing PPE, trailing cable and fire-door obstruction.
9. In Timeline rename them `hs_Hazard01` through `hs_Hazard07`; extend every hotspot to the full slide duration.
10. Insert seven visible numbered buttons and rename them `btn_Hazard01` through `btn_Hazard07`.
11. Open States > Edit States; add visible Hover, Down and Visited treatments that use icon/text as well as colour.
12. Open Focus Order; remove decorative objects and place the seven buttons in logical warehouse order.
13. Preview This Slide; operate all seven buttons by Tab and Enter, then repeat with pointer hotspots.
14. Check at player size that no target overlaps and every hazard remains visible.
15. Save, close, reopen and retain one screenshot showing the final hazard slide plus named Timeline objects.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Seven hazards are visually plausible.
- Media retains aspect ratio and provenance.
- Hotspots do not overlap.
- Visible keyboard alternatives map one-to-one.

Self-contained lab folder: `activities/activity-03-media-hazard-scene/`

### Activity 04 — Add Layers, States, Variables and Gate

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Make hazard discovery accessible, persistent and completion-gated.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-04-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open `HarbourLink-WSH-Checkpoint-03-YourName.story`; File > Save As `HarbourLink-WSH-Checkpoint-04-YourName.story`.
2. In the Triggers panel click the Manage project variables icon. Create Number `HazardsFound` with default `0`.
3. Create True/False variables `Hazard01Found` through `Hazard07Found`, each default `False`.
4. Open Slide Layers > New Layer; create `lyr_Hazard01` through `lyr_Hazard07` before creating any Show layer trigger.
5. On every hazard layer, first add title text (for example `Forklift route hazard`) and body text describing risk and control.
6. Open layer Properties, enable Present as Dialog, then choose the existing title text in the Dialog Label dropdown and body text in Dialog Description. Add a labelled Close button, set it to Hide this layer, and verify automatic focus trapping/return.
7. Create `lyr_Incomplete` now, with instructions to find all seven hazards and a Close button.
8. Select `hs_Hazard01`; in Triggers choose Create a new trigger.
9. Set Action `Adjust variable`, Variable `HazardsFound`, Operator `Add`, Value `1`, Event `When user clicks`, Object `hs_Hazard01`, Condition `Hazard01Found == False`.
10. Add second same-click trigger: set `Hazard01Found` to `True` only if it equals False.
11. Add third trigger: change `btn_Hazard01` to `Visited`; add fourth: Show layer `lyr_Hazard01`. Keep this exact order.
12. Copy the same ordered four triggers to `btn_Hazard01`; edit every trigger event object to `btn_Hazard01` and keep the same flag condition so keyboard and hotspot paths share the counter.
13. Mirror both hotspot and button trigger sets for hazards 02–07, changing object, flag, button and layer names consistently.
14. Insert text `%HazardsFound% of 7 found`; give it the accessible name `Hazard discovery progress`.
15. On Next add Jump to next slide when HazardsFound equals 7; below it add Show layer `lyr_Incomplete` when HazardsFound is less than 7.
16. Preview the hotspot path and the visible-button keyboard path; each unique hazard must increment once and open the same layer.
17. Click one hotspot then its matching button; confirm the counter stays 1.
18. Select six hazards and confirm Next shows `lyr_Incomplete`; select the seventh and confirm progression.
19. Open every Dialog layer by keyboard, close it and verify focus returns to the invoking numbered button.
20. Save, close, reopen and capture Manage Variables, one hotspot trigger group, one button trigger group, Dialog properties, condition and 7-of-7 runtime state.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Counter never exceeds seven.
- Repeated selections do not inflate progress.
- Six hazards block and seven permit progression.
- Pointer and keyboard paths show identical content.

Self-contained lab folder: `activities/activity-04-layers-states-gating/`

### Activity 05 — Build Motion, Slider and Dial Controls

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Use motion and data controls to explain dynamic workplace risk.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-05-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open HarbourLink-WSH-Checkpoint-04 and Save As HarbourLink-WSH-Checkpoint-05-YourName.story.
2. In the Triggers panel choose Manage project variables; create Number `RiskLevel` with default `1` and Number `RiskZone` with default `1`.
3. Insert a slider on the risk screen; select Slider Tools — Design and set Start `1`, End `5`, Initial `1`, Step `1`.
4. In Slider Tools — Design > Variable bind the slider to `RiskLevel`.
5. Create `lyr_RiskLow`, `lyr_RiskMedium`, and `lyr_RiskHigh` before selecting any layer in a trigger.
6. Create slider-moves triggers: show Low when RiskLevel is 1–2, Medium when 3, and High when 4–5; order the conditions so only one layer opens.
7. Insert a dial and bind its variable to `RiskZone`; set Start `1`, End `3`, Initial `1`, Step `1`.
8. Create `lyr_Zone01`, `lyr_Zone02`, and `lyr_Zone03` before adding dial-moves triggers.
9. Add one dial-moves trigger per exact RiskZone value; show the matching zone layer and hide the other two.
10. Add a motion path to the forklift icon; trigger it only after the learner confirms the route is clear.
11. Provide visible Previous/Next value buttons as keyboard alternatives for both slider and dial.
12. Set the interactive objects to remain visible for the full slide duration in Timeline.
13. Preview values 1, 3, and 5 plus all three zones; compare visible value, variable readback, layer, and keyboard path.
14. Revisit the slide and verify the specified resume/reset behaviour.
15. Save and retain Slider Tools values, variable bindings, layer list, trigger conditions, and three runtime states.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Motion is learner-controlled.
- All slider values have text equivalents.
- Every dial detent maps to one zone.
- Revisit matches the specification.

Self-contained lab folder: `activities/activity-05-motion-slider-dial/`

### Activity 06 — Create View, Try and Test Simulations

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Capture and deploy the supplied incident-report simulation in three Storyline modes.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-06-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open `HarbourLink-WSH-Checkpoint-05-YourName.story` from the previous activity and immediately use File > Save As to create `HarbourLink-WSH-Checkpoint-06-YourName.story` on a local Windows drive. Preserve the prior checkpoint; no completed .story solution is supplied.
2. Open `source/storyboard.csv` and the previous checkpoint, then confirm the screen IDs and acceptance criteria before editing.
3. Open `source/incident-report/index.html`, use fictional data only, silence notifications and rehearse the submit path.
4. Record a readable bounded region with Slides > Record Screen.
5. Insert one copy as Video on a Single Slide and add learner playback controls.
6. Insert a second copy as Try Mode; edit hotspots and coaching so intended actions advance and wrong actions receive guidance.
7. Insert a third copy as Test Mode; configure score and attempts, then test correct and incorrect action paths.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Recording exposes no private data.
- View mode can pause and seek.
- Try mode coaches wrong actions.
- Test mode scores specified actions.

Self-contained lab folder: `activities/activity-06-screen-recording-simulation/`

### Activity 07 — Add Audio, Captions and Accessibility

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Add the supplied eight-scene HarbourLink annual WSH narration with one matching MP3/VTT pair per screen, equivalent transcript and keyboard-operable Replay/Stop controls.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-07-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open HarbourLink-WSH-Checkpoint-06 and Save As HarbourLink-WSH-Checkpoint-07-YourName.story.
2. In scene `02 Learn`, confirm storyboard screens `HLL-VO-01` through `HLL-VO-08` exist in order; create none with duplicate IDs.
3. For each screen 01–08, choose Insert > Audio > Audio from File and import the matching `activities/source/narration/harbourlink-scene-01.mp3` through `harbourlink-scene-08.mp3`; place exactly one clip on its matching screen.
4. Rename each Timeline audio object `aud_HLL_01` through `aud_HLL_08`; do not repeat the 201.67-second combined track on every screen.
5. On each screen select its audio object, choose Options > Import (or Accessibility > Import CC), and import the matching `activities/source/captions/harbourlink-scene-01.vtt` through `harbourlink-scene-08.vtt`.
6. Compare the eight screen IDs, MP3 filenames and VTT filenames against `activities/source/storyboard.csv` and `activities/source/narration/harbourlink-audio-manifest.json`.
7. Add labelled Replay and Stop controls on every narrated screen; Replay restarts only that screen's clip and Stop stops only that clip.
8. Link `activities/source/narration/annual-wsh-script.md` as the transcript and add concise alternative text for visual actions not spoken.
9. Open Focus Order on every narrated screen; remove decorative objects and place heading, visual, Replay, Stop, transcript and Next in logical order.
10. Preview screens HLL-VO-01 to HLL-VO-08 in sequence with audio muted/captions on, keyboard only, and at 200% browser zoom after publish preview. Open or download the supplied narrated reference video at `activities/source/video/HarbourLink-Annual-WSH-Refresher.mp4`; the accessible browser player is `activities/source/video/index.html` and uses `activities/source/captions/harbourlink-annual-wsh.vtt`.
11. Record one start/middle/end caption timing check per screen and correct any overlap with controls.
12. Save and retain one mapping table plus screenshots of a representative audio Timeline, caption editor, Replay/Stop triggers and keyboard focus order.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Narration and captions synchronise.
- Transcript conveys equivalent visual meaning.
- Focus order is logical.
- No task depends on hearing or precise pointer input.

Self-contained lab folder: `activities/activity-07-audio-captions-accessibility/`

## Topic 3 — Branching, Questions and Results

Branching · freeform · feedback · question banks · result slide · retry · review · completion

**Alignment:** LO3 · A6 · K6

### Branching decision scene

Three response choices route to consequence layers and reconverge deliberately

**Best used for:** The connected workplace-safety module where branching decision scene must produce a testable authoring artifact.

**Key controls:** choice trigger; consequence; return; state preservation

**Watch for:** branches with no return or unearned success

**Quality evidence:** every path reaches feedback and the specified continuation

### Freeform pick-one conversion

Insert > Convert to Freeform turns workplace objects into a scored pick-one decision

**Best used for:** The connected workplace-safety module where freeform pick-one conversion must produce a testable authoring artifact.

**Key controls:** response set; correct object; states; submit

**Watch for:** visual ambiguity or automatic submission

**Quality evidence:** selection can be revised before Submit and scores correctly

### Freeform hotspot question

A screenshot-based hazard question uses defined regions and consequence feedback

**Best used for:** The connected workplace-safety module where freeform hotspot question must produce a testable authoring artifact.

**Key controls:** hotspot region; score; attempts; feedback

**Watch for:** mouse-only graded task

**Quality evidence:** an equivalent keyboard-operable response path is provided

### Drag-and-drop fallback

A sorting interaction includes keyboard-accessible buttons or an equivalent pick-one version

**Best used for:** The connected workplace-safety module where drag-and-drop fallback must produce a testable authoring artifact.

**Key controls:** drag item; drop target; snap; reset; fallback

**Watch for:** requiring precise dragging as the only route

**Quality evidence:** both paths create the same instructional and scoring outcome

### Question form configuration

Form View defines prompt, choices, score, attempts, shuffle and feedback before visual styling

**Best used for:** The connected workplace-safety module where question form configuration must produce a testable authoring artifact.

**Key controls:** question type; points; required; attempts

**Watch for:** styling before the scoring model is stable

**Quality evidence:** question specification matches runtime scoring

### Feedback layers

Correct, Incorrect and Try Again layers explain the safety consequence and next action

**Best used for:** The connected workplace-safety module where feedback layers must produce a testable authoring artifact.

**Key controls:** layer text; continue; focus; attempts

**Watch for:** feedback saying only correct/incorrect

**Quality evidence:** learner can state why the response changes risk

### Question bank design

A Safety Bank groups items by criterion and supports controlled random draws

**Best used for:** The connected workplace-safety module where question bank design must produce a testable authoring artifact.

**Key controls:** bank name; criterion tags; draw count; randomisation

**Watch for:** random draw missing a required criterion

**Quality evidence:** repeated draws preserve minimum content coverage

### Draw from question bank

Slides > Question Banks > New Draw from Question Bank selects the intended bank; Draw questions randomly enables Include N

**Best used for:** The connected workplace-safety module where draw from question bank must produce a testable authoring artifact.

**Key controls:** draw count; include/exclude; lock order

**Watch for:** tracking the bank source instead of delivered questions

**Quality evidence:** preview draws the configured count and result slide includes them

### Result slide tracking

Insert > New Slide > Results tracks only the scored quiz and sets 80% pass

**Best used for:** The connected workplace-safety module where result slide tracking must produce a testable authoring artifact.

**Key controls:** tracked questions; passing score; score display

**Watch for:** tracking the wrong questions or allowing slides-viewed bypass

**Quality evidence:** known answer sets return expected percentage and pass/fail

### Retry quiz trigger

Retry Quiz resets tracked questions and relevant variables before returning to the quiz

**Best used for:** The connected workplace-safety module where retry quiz trigger must produce a testable authoring artifact.

**Key controls:** reset results; destination; attempt count

**Watch for:** old answers or hazard variables contaminating retry

**Quality evidence:** second attempt starts clean while permitted course progress remains

### Review quiz behaviour

Review Quiz shows submitted responses without exposing answers before completion

**Best used for:** The connected workplace-safety module where review quiz behaviour must produce a testable authoring artifact.

**Key controls:** review state; correct-answer display; navigation

**Watch for:** answer leakage during the active attempt

**Quality evidence:** review is unavailable until submission and then matches policy

### Submit-all interaction

Submit All Responses defers scoring when the design requires final review

**Best used for:** The connected workplace-safety module where submit-all interaction must produce a testable authoring artifact.

**Key controls:** submit mode; confirmation; unanswered check

**Watch for:** learner submits incomplete quiz accidentally

**Quality evidence:** confirmation identifies unanswered items before final scoring

### Results variables

Built-in SafetyQuiz.ScorePercent and SafetyQuiz.PassPercent support transparent status text

**Best used for:** The connected workplace-safety module where results variables must produce a testable authoring artifact.

**Key controls:** variable reference; rounding; pass threshold

**Watch for:** manual score formulas drifting from Storyline results

**Quality evidence:** displayed values match LMS debug data

### Completion trigger

Course completion reports from the selected quiz result, with no competing early trigger

**Best used for:** The connected workplace-safety module where completion trigger must produce a testable authoring artifact.

**Key controls:** complete/pass trigger; result slide; conditions

**Watch for:** multiple completion criteria using OR and bypassing the quiz

**Quality evidence:** viewing every slide without passing does not report successful completion

### Branch and quiz test matrix

A structured matrix covers correct, incorrect, incomplete, retry, review, revisit and resume

**Best used for:** The connected workplace-safety module where branch and quiz test matrix must produce a testable authoring artifact.

**Key controls:** expected state; actual state; evidence; defect owner

**Watch for:** testing only the happy path

**Quality evidence:** all high-risk cases have recorded results and resolved defects

### Zoom region timing

Insert > Zoom Region enlarges a named detail only during the explanatory cue-point interval

**Best used for:** The connected workplace-safety module where zoom region timing must produce a testable authoring artifact.

**Key controls:** region bounds; timeline start/end; duration; return to normal

**Watch for:** decorative zoom or loss of context

**Quality evidence:** zoom begins at the named cue point, reveals the required detail and returns before the next task

### Slide transitions

Transitions applies one restrained transition at scene boundaries and records timing

**Best used for:** The connected workplace-safety module where slide transitions must produce a testable authoring artifact.

**Key controls:** transition type; duration; advance mode; reduced-motion alternative

**Watch for:** different transitions on every slide or automatic advance before content completes

**Quality evidence:** scene change remains predictable and no essential meaning depends on motion

### Activity 08 — Build Branching and Freeform Decisions

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Create consequence-based decisions and an accessible freeform interaction.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-08-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open HarbourLink-WSH-Checkpoint-07 and Save As HarbourLink-WSH-Checkpoint-08-YourName.story.
2. In existing scene `03 Practise`, open storyboard placeholder `WSA-210 Spill Decision`; do not create a duplicate ID.
3. Create three choice buttons and three Dialog consequence layers; add choice-click Show layer triggers for this ungraded branch prototype.
4. Create or open placeholder `WSA-220 Reconvergence`; add Continue triggers from each consequence layer to WSA-220 and test all three paths.
5. Duplicate WSA-210 so the working ungraded branch remains a rollback reference.
6. On the duplicate, delete every old choice-click Show layer, Jump, and feedback trigger before conversion.
7. Select the three decision objects and choose Insert > Convert to Freeform > Pick One.
8. In Form View assign each object to its response and mark the approved control as correct.
9. Use the interaction Submit button; do not reveal feedback or navigate when a choice is merely clicked.
10. Edit the generated Correct, Incorrect, and Try Again layers with plain-English consequence and next action.
11. Set attempts and feedback behaviour in Question Tools — Design; keep Try Again only while another attempt remains.
12. Add Continue from submitted feedback to `WSA-220 Reconvergence`.
13. Open Focus Order and place prompt, choices, Submit, and feedback controls in logical order.
14. Preview without Submit, then submit correct, incorrect, and retry paths; confirm scoring and reconvergence.
15. Save and capture the original branch, cleaned duplicate triggers, Form View, feedback layers, score, and reconvergence.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- All branches reach feedback and continuation.
- Freeform scoring matches the specification.
- Feedback explains consequence.
- Equivalent keyboard route is complete.

Self-contained lab folder: `activities/activity-08-branching-freeform/`

### Activity 09 — Build the Safety Question Bank and Quiz

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Create a five-question graded quiz with controlled bank coverage and 80% pass.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-09-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open HarbourLink-WSH-Checkpoint-08 and Save As HarbourLink-WSH-Checkpoint-09-YourName.story; in existing scene `04 Quiz`, open placeholder `WSA-301 Safety Quiz`.
2. Choose Slides > Question Banks > Create Question Bank; name it `Safety Bank`.
3. Create five graded items: hazard recognition, control selection, reporting, emergency action and PPE.
4. For each item open Form View and enter the prompt, choices and correct response from `activities/source/quiz-content.md`.
5. Set points consistently and define attempts before styling.
6. Write Correct/Incorrect/Try Again feedback that names the safety consequence.
7. For multiple-response items add `Select all that apply` and use perceivable response states.
8. Tag item titles with the criterion name so coverage is auditable.
9. Choose Slides > Question Banks > New Draw from Question Bank; select `Safety Bank`, then replace the WSA-301 placeholder content with this draw slide so the Quiz menu entry opens the bank draw.
10. Enable Draw questions randomly, set Include to five, and mark every required criterion Always in Include in Shuffle.
11. Open Focus Order for a representative item and remove decorative objects.
12. Preview two different answer sets and record expected raw score.
13. Verify no correct answer is exposed before Submit.
14. Review at phone-width player size for target spacing and readable feedback.
15. Save and capture bank contents, draw settings and one complete feedback path.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Five criteria are covered.
- Scoring is reproducible.
- Instructions and states are accessible.
- Answers are not leaked before submission.

Self-contained lab folder: `activities/activity-09-question-bank-quiz/`

### Activity 10 — Configure Results, Retry and Completion

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Track only the scored quiz, set 80% pass and prove retry/review behaviour.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-10-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open checkpoint 09 and Save As checkpoint 10.
2. Choose Slides > Results; create a graded Results slide and name its quiz `SafetyQuiz`.
3. Open Result Tools — Design > Quiz Settings and select only the `Safety Bank` question-draw slide; do not select its five bank questions as separate direct rows.
4. In Result Tools — Design set Quiz Type to `Final Assessment`; then open Quiz Settings and confirm the `Safety Bank` draw is the only scored source.
5. Set Passing Score to `80%`; confirm visible score uses SafetyQuiz.ScorePercent.
6. Choose Result Tools — Design > Retry Button and Review Button so Storyline creates the built-in Reset results and Review results behaviour.
7. On Retry add Reset results for this result slide before Jump to the first quiz slide.
8. Confirm relevant question states reset while permitted course progress remains.
9. Keep Review unavailable until the attempt is submitted.
10. Choose Home > Publish > LMS/LRS > Reporting and Tracking; select the SafetyQuiz Results slide as the only tracking criterion.
11. Do not add slides viewed because multiple criteria are OR and could bypass the quiz.
12. Test 3/5=60% fail and record state.
13. Test 4/5=80% pass and record state.
14. Test 5/5=100%, retry, review and relaunch paths.
15. Compare visible score/pass with the result variables and expected LMS state.
16. Save and capture Quiz Settings, Retry trigger order and pass/fail runtime screens.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- 80% threshold is exact.
- Slides viewed cannot bypass the quiz.
- Retry starts a clean quiz attempt.
- Review appears only after submission.

Self-contained lab folder: `activities/activity-10-results-retry-completion/`

## Topic 4 — Review, Publishing and Governance

Player · translation · Review 360 · SCORM 1.2/2004 · Tin Can xAPI · LMS/LRS tests · retention

**Alignment:** LO4 · A4 · A7 · K4

### Player accessibility controls

Player Properties retains volume, captions, keyboard focus and clear labels

**Best used for:** The connected workplace-safety module where player accessibility controls must produce a testable authoring artifact.

**Key controls:** controls; colour; language; menu; seekbar

**Watch for:** hiding controls required for media access

**Quality evidence:** keyboard and screen-reader test reaches each enabled control

### Translation workflow

File > Localization > XLIFF/Word Translation exports text, protects variables and imports the reviewed translation into a duplicate source

**Best used for:** The connected workplace-safety module where translation workflow must produce a testable authoring artifact.

**Key controls:** XLIFF/Word workflow; locale; font; expansion

**Watch for:** editing object IDs or truncating expanded text

**Quality evidence:** import preserves triggers and representative layouts fit

### Review 360 publishing

Home > Publish > Review 360 creates a versioned review item with named reviewers

**Best used for:** The connected workplace-safety module where review 360 publishing must produce a testable authoring artifact.

**Key controls:** item name; version; comments; resolve/reopen

**Watch for:** treating comments as the only requirement record

**Quality evidence:** each comment has owner, disposition and source version

### Review version control

Update an existing Review 360 item only when continuity is intended; otherwise create a new item

**Best used for:** The connected workplace-safety module where review version control must produce a testable authoring artifact.

**Key controls:** review URL; version label; approval snapshot

**Watch for:** overwriting an approved review with untracked changes

**Quality evidence:** approved comment set maps to a retained .story checksum

### LMS/LRS publish target

Home > Publish > LMS/LRS opens title, folder, quality, reporting and tracking settings

**Best used for:** The connected workplace-safety module where lms/lrs publish target must produce a testable authoring artifact.

**Key controls:** publish path; title; identifier; standard; tracking

**Watch for:** publishing to a synced/network folder or reusing IDs carelessly

**Quality evidence:** local publish completes and the settings record identifies the package

### SCORM 1.2 reporting

Reporting and Tracking selects SCORM 1.2 and the LMS status pair required by the target LMS

**Best used for:** The connected workplace-safety module where scorm 1.2 reporting must produce a testable authoring artifact.

**Key controls:** Passed/Incomplete; Passed/Failed; identifier; title

**Watch for:** choosing a status model without LMS validation

**Quality evidence:** sandbox records score, lesson status, location and suspend data

### SCORM 2004 editions

Reporting and Tracking selects the LMS-supported SCORM 2004 edition and separate completion/success semantics

**Best used for:** The connected workplace-safety module where scorm 2004 editions must produce a testable authoring artifact.

**Key controls:** edition; completion; success; score; identifier

**Watch for:** assuming every LMS supports the same edition

**Quality evidence:** sandbox launch, suspend/resume and score readback pass

### Tin Can xAPI publishing

Reporting and Tracking selects xAPI (Tin Can API) and uses launch-supplied actor/LRS configuration

**Best used for:** The connected workplace-safety module where tin can xapi publishing must produce a testable authoring artifact.

**Key controls:** activity ID; actor; endpoint; auth; statements

**Watch for:** embedding LRS secrets in learner assets

**Quality evidence:** test launch sends expected statements without credentials stored in the package

### cmi5 boundary

cmi5 is chosen only when the LMS supports its launch/session rules and xAPI statement profile

**Best used for:** The connected workplace-safety module where cmi5 boundary must produce a testable authoring artifact.

**Key controls:** AU launch; session; moveOn; masteryScore

**Watch for:** treating generic xAPI and cmi5 as interchangeable

**Quality evidence:** cmi5 conformance test shows launched, completed and passed lifecycle

### Tracking criteria semantics

The scored safety module tracks the quiz result only because multiple Storyline criteria are OR

**Best used for:** The connected workplace-safety module where tracking criteria semantics must produce a testable authoring artifact.

**Key controls:** result slide; criteria list; completion trigger

**Watch for:** adding slides viewed and allowing a bypass

**Quality evidence:** slides-viewed alone cannot complete the scored module

### Publish Success ZIP

Publish Successful > ZIP creates an upload package with imsmanifest.xml and course files at ZIP root

**Best used for:** The connected workplace-safety module where publish success zip must produce a testable authoring artifact.

**Key controls:** ZIP command; manifest root; no extra wrapper folder

**Watch for:** zipping the containing folder manually

**Quality evidence:** archive inspection finds manifest and launch assets at root

### LMS sandbox upload

A non-production LMS course tests launch, completion, score, bookmark, session time and suspend data

**Best used for:** The connected workplace-safety module where lms sandbox upload must produce a testable authoring artifact.

**Key controls:** learner ID; attempt; status; score; resume; debug log

**Watch for:** using production learners for package debugging

**Quality evidence:** fresh, failed, passed and resumed attempts read back correctly

### SCORM runtime reference

The supplied workplacesafety-scorm site informs runtime test structure, status and relaunch controls

**Best used for:** The connected workplace-safety module where scorm runtime reference must produce a testable authoring artifact.

**Key controls:** API discovery; status; score; bookmark; session time; suspend data

**Watch for:** claiming the reference is Storyline output or an xAPI tester

**Quality evidence:** comparison notes distinguish its SCORM demo role from the new Storyline build

### Standalone preview boundary

course.html style standalone preview is used for visual checks only because no LMS API is present

**Best used for:** The connected workplace-safety module where standalone preview boundary must produce a testable authoring artifact.

**Key controls:** preview notice; no tracking claim; fallback

**Watch for:** equating local browser preview with LMS completion

**Quality evidence:** test report labels standalone and LMS evidence separately

### LMS debug diagnosis

Browser console and LMS debug logs isolate API discovery, commit, status and suspend-data failures

**Best used for:** The connected workplace-safety module where lms debug diagnosis must produce a testable authoring artifact.

**Key controls:** API found; Initialize; SetValue; Commit; Terminate

**Watch for:** guessing from a visible course screen

**Quality evidence:** log timestamps identify the failing runtime call and value

### Package regression test

Republish after source changes and rerun the full high-risk matrix against a clean learner attempt

**Best used for:** The connected workplace-safety module where package regression test must produce a testable authoring artifact.

**Key controls:** source version; package checksum; clean state; results

**Watch for:** reusing a contaminated learner attempt

**Quality evidence:** new package checksum and clean readback match the release register

### Release retention

Retain .story, publish settings, ZIP, test log, review approval and asset provenance together

**Best used for:** The connected workplace-safety module where release retention must produce a testable authoring artifact.

**Key controls:** owner; date; version; checksum; review trigger

**Watch for:** keeping only the uploaded ZIP

**Quality evidence:** auditor can reproduce which source and settings created the live package

### Articulate Labs boundary

Experimental Articulate Labs features are tried only in a duplicate sandbox project with manual fallback

**Best used for:** The connected workplace-safety module where articulate labs boundary must produce a testable authoring artifact.

**Key controls:** duplicate source; experiment flag; fallback; review

**Watch for:** making an experimental feature mandatory in production

**Quality evidence:** baseline remains buildable without the experiment

### AI-assisted authoring fallback

Optional AI proposes copy or imagery, while the author verifies accuracy, rights and accessibility

**Best used for:** The connected workplace-safety module where ai-assisted authoring fallback must produce a testable authoring artifact.

**Key controls:** prompt record; provenance; human review; manual path

**Watch for:** publishing generated output without verification

**Quality evidence:** release evidence identifies reviewer and the non-AI fallback

### Distribution mode comparison

A worked decision table compares Review 360, web, video, SCORM LMS and xAPI/cmi5 by interactivity, identity, score, resume, review and analytics

**Best used for:** The connected workplace-safety module where distribution mode comparison must produce a testable authoring artifact.

**Key controls:** channel; launch; tracking; interaction; security; maintenance

**Watch for:** selecting the easiest export rather than the required evidence

**Quality evidence:** SCORM LMS wins for scored induction and the rejected modes have recorded reasons

### Delivery cadence calculation

A 30-day induction cadence schedules launch on Day 0, reminders on Days 3 and 7, supervisor escalation on Day 10 and content review every 180 days

**Best used for:** The connected workplace-safety module where delivery cadence calculation must produce a testable authoring artifact.

**Key controls:** trigger date; audience; channel; owner; stop condition; review interval

**Watch for:** sending reminders after completion or setting cadence without an owner

**Quality evidence:** calendar table totals each touchpoint and stops when completion status is read back

### Cadence exception rules

Status-driven rules suppress reminders for passed learners, route failed learners to retry guidance and escalate overdue incomplete learners

**Best used for:** The connected workplace-safety module where cadence exception rules must produce a testable authoring artifact.

**Key controls:** status; threshold; retry; suppression; escalation; privacy

**Watch for:** broadcasting scores or sending identical messages to every status

**Quality evidence:** test learner records produce the correct next contact and no unnecessary disclosure

### Content execution guideline register

The WSA guideline records tone, terminology, template, object naming, accessibility, review, publish ID, cadence and archive controls

**Best used for:** The connected workplace-safety module where content execution guideline register must produce a testable authoring artifact.

**Key controls:** rule ID; rationale; owner; verification; exception; review date

**Watch for:** guidelines with no verifier or exception path

**Quality evidence:** a release reviewer can accept or reject each rule from retained evidence

### Lifecycle metric decision

A worked register links completion, pass rate, retry rate, incident-report simulation errors and overdue rate to a defined action threshold

**Best used for:** The connected workplace-safety module where lifecycle metric decision must produce a testable authoring artifact.

**Key controls:** metric; source; threshold; action; owner; review date

**Watch for:** collecting analytics without a decision purpose

**Quality evidence:** each threshold triggers a named content, coaching or cadence response

### Activity 11 — Configure Player, Translation and Review 360

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Prepare the module for accessible review and localisation.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-11-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open `HarbourLink-WSH-Checkpoint-10-YourName.story` from the previous activity and immediately use File > Save As to create `HarbourLink-WSH-Checkpoint-11-YourName.story` on a local Windows drive. Preserve the prior checkpoint; no completed .story solution is supplied.
2. Open `source/storyboard.csv` and the previous checkpoint, then confirm the screen IDs and acceptance criteria before editing.
3. Open Player Properties and enable only required controls, including volume and captions; verify player focus and labels.
4. Choose File > Localization > XLIFF/Word Translation > Export to Word or Export to XLIFF; inspect protected variables/object IDs, then use the same path > Import into a duplicate source and verify representative layouts.
5. Publish a versioned Review 360 item or, if credentials are unavailable, complete the supplied settings worksheet without claiming upload.
6. Define reviewers, review questions, due date, comment owner and accept/adapt/reject disposition.
7. Retain the Review item/version identifier or the honest offline plan.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Player controls are keyboard accessible.
- Translation workflow protects logic identifiers.
- Review ownership is explicit.
- No upload is claimed without readback.

Self-contained lab folder: `activities/activity-11-player-translation-review/`

### Activity 12 — Publish and Test SCORM 1.2 and 2004

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Create root-correct SCORM packages and verify runtime behaviour in a sandbox.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-12-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open checkpoint 11 and Save As checkpoint 12.
2. Choose Home > Publish > LMS/LRS; set the title and a local publish folder.
3. Open Reporting and Tracking; select `SCORM 1.2`.
4. Select the target LMS reporting status pair and record it; track the quiz Results slide only.
5. Set a stable identifier and retain it in the release record.
6. Publish locally; on Publish Successful choose ZIP.
7. Open the ZIP and confirm `imsmanifest.xml` and launch files are at archive root, without an extra wrapper folder.
8. Repeat Home > Publish > LMS/LRS and choose the LMS-supported SCORM 2004 edition.
9. Record SCORM 2004 completion, success and score settings separately.
10. Upload only to an approved sandbox with a fresh learner attempt.
11. Launch and test 3/5 fail; read back status and score.
12. Launch and test 4/5 pass; read back completion, success and score.
13. Bookmark, close and relaunch; verify location, suspend data and session time.
14. Compare the supplied runtime demo only for API/status/relaunch structure; label it not Storyline output.
15. Save both ZIP checksums and one screenshot per package showing final reporting/tracking settings.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Two distinct packages and setting records exist.
- Manifest is at archive root.
- Score/status/resume read back in sandbox.
- Reference boundary is stated accurately.

Self-contained lab folder: `activities/activity-12-scorm-publishing-testing/`

### Activity 13 — Publish Tin Can xAPI and Validate Release

**Scenario:** HarbourLink Logistics needs an 8–10 minute annual WSH refresher for frontline warehouse operators, including learners with low reading confidence. Build a picture-first module with short plain-English labels, narration, captions, purposeful interaction, keyboard equivalents and a five-question 80% practice quiz.

**Objective:** Prepare an xAPI package without embedded secrets and complete regression evidence.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-13-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Open checkpoint 12 and Save As checkpoint 13.
2. Choose Home > Publish > LMS/LRS; open Reporting and Tracking.
3. Select `xAPI (Tin Can API)` and enter the approved stable activity identifier.
4. Track the quiz Results slide and record the selected completion basis.
5. If the target specifically requires cmi5, create and document a separate cmi5 publication; do not describe the generic xAPI package as cmi5.
6. Do not enter or embed endpoint credentials in learner files.
7. Publish locally and create the ZIP from Publish Successful.
8. Inspect the package for accidental tokens, passwords, endpoints or learner data.
9. Launch through the approved xAPI-enabled LMS or LRS launch target so actor, endpoint and authentication are supplied at launch.
10. Capture an illustrative Actor/Verb/Object trace only after removing personal data.
11. Inspect statements actually emitted by the current Storyline build and selected tracking.
12. Verify received score and completion; do not promise verbs the runtime did not emit.
13. If a target action requires an extra statement, add an explicit xAPI trigger and document it.
14. If no approved LRS launch exists, complete the blocked-test record without claiming success.
15. Run regression with a clean learner state and record source version, ZIP checksum and actual results.
16. Archive source, ZIP, settings, test log, review approval and provenance together.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- No credential appears in the package.
- Activity identifier is stable and recorded.
- Statement evidence or honest blocker is retained.
- Release package is reproducible.

Self-contained lab folder: `activities/activity-13-xapi-release-validation/`

### Activity 14 — Independent Mini Capstone

**Scenario:** Create your own original 8–12 slide e-learning module on any suitable learning topic from your organisation, community or personal interests. Start from a blank project, write your own narration, build purposeful interactions and quiz, and publish a standards-compatible package. This developmental capstone is separate from HarbourLink and from the formal PP.

**Objective:** Independently create a small original e-learning module from a new blank project and present verified evidence.

**Checkpoint:** `HarbourLink-WSH-Checkpoint-14-YourName.story` (created by the learner in Storyline 360 on Windows)

#### Detailed procedure

1. Choose any suitable learning topic from your organisation, community or personal interests; do not reuse the guided HarbourLink module or a formal PP solution and write a one-page brief naming audience, performance need, three measurable objectives, delivery channel and accessibility constraints.
2. Create a new blank `Capstone-YourName-v01.story`; do not copy the WSA checkpoint file.
3. Storyboard 8–12 slides containing a menu, one purposeful hotspot interaction or accessible equivalent, layers, one variable gate, recorded or synthetic voiceover with matching captions or transcript, minimal on-screen text, a three-question graded quiz and a result slide.
4. Apply your own theme and masters, implement keyboard focus, captions/transcript where relevant, and test correct, incorrect, incomplete, retry, revisit and resume paths.
5. Publish one standards-compatible test package selected for your target environment and produce a two-minute demonstration plus a one-page release/test record.
6. Optional AI may assist ideation in a duplicate sandbox; retain a manual fallback and verify every output. This capstone is developmental practice and is not the approved formal PP assessment.

#### Evidence

Retain the named .story checkpoint, the completed self-check table and one screenshot for each task showing the final state or setting that proves the acceptance criteria.

#### Acceptance criteria

- Original blank project and brief are evident.
- Required Storyline mechanisms work together.
- Accessibility and test evidence are complete.
- Publishing choice matches the target.
- Capstone is labelled separately from formal PP.

Self-contained lab folder: `activities/activity-14-independent-mini-capstone/`

## Intellectual property, privacy and responsible AI

Use only assets and personal information you created or are permitted to use. Record the source, owner, licence or consent, date, allowed modifications, commercial or redistribution scope and attribution requirement. Public visibility does not itself grant reuse permission. Review current Articulate and AI-service terms before commercial work, do not provide third-party content or personal data without authority, and retain prompt/provenance evidence where appropriate. This guide is educational information, not legal advice.

## Publishing and lifecycle checklist

- The .story source and published output carry the intended version and owner.
- Preview and published-output tests cover navigation, scoring, resume, captions, focus and keyboard operation.
- The selected channel supports the required interaction and tracking.
- Delivery frequency, reminders, review date and update triggers are documented.
- Review comments are resolved or dispositioned before release.
- Source, media permissions, test evidence and the final package are retained together.

## Source register

- **Official course page:** https://www.tertiarycourses.com.sg/wsq-mastering-articulate-storyline-360-for-e-learning-content-creation.html
- **Legacy trainer deck v8:** reference/WSQ - Master Trainer Slides - Mastering Articulate Storyline 360 for e-Learning Content Creation - v8.pptx
- **Approved live assessment structures:** WA v3: six SAQs K1–K6; PP v4: four tasks A1/A2, A3/A5, A6, A4/A7; both 60 minutes
- **Approved assessment plan v5.0:** reference/tms/Assessment Plan_TGS-2024042308_v5.0.docx
- **Approved courseware mapping v1:** reference/tms/Courseware Mapping_TGS-2024042308_v1.docx
- **Articulate Storyline 360 User Guide:** https://community.articulate.com/kb/user-guide-series/storyline-360-user-guide/1193854
- **Official LMS/LRS publishing procedure:** https://www.articulatesupport.com/article/Storyline-360-Publishing-a-Course-for-LMS-LRS-Distribution
- **Articulate accessibility guidance:** https://www.articulate.com/about/accessibility/storyline-360-accessibility-maturity-plan/
- **Articulate Labs experimental-feature boundary:** https://www.articulatesupport.com/article/Articulate-360-Teams-Explore-New-Features-with-Labs
- **Workplace SCORM runtime reference:** https://alfredang.github.io/workplacesafety-scorm/
