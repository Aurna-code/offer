# Goal
Turn "Repo Onboarding Snapshot" into a sellable, async-first technical product that can live on ACP, Upwork Project Catalog, and self-serve surfaces.

# Product
Name: Repo Onboarding Snapshot
Primary outcome: turn one unfamiliar repository into a clear first-week action plan.

# Audience
- founders inheriting contractor code
- engineers joining an unfamiliar repository
- solo builders returning to an old project
- teams handing off an internal tool to a new owner

# In Scope
- repository summary
- likely entry points
- startup or reading path
- missing context checklist
- key risks
- first 7 priority tasks
- concise confidence note

# Out of Scope
- code changes
- bug fixing
- live meetings
- open-ended consulting
- formal security audit
- formal performance audit
- guaranteed successful local setup

# Constraints
- optimize for no-meeting purchase
- reduce back-and-forth
- prefer specific, narrow language over broad claims
- avoid promising implementation work
- outputs must be reusable across ACP and Upwork
- keep the tone calm, senior, concrete, and non-hypey

# Workspace map
- inputs/: fixed source inputs, do not rewrite unless explicitly asked
- market/raw/: optional extra market notes
- outputs/: final generated assets only
- prompts/: task prompts and workflow notes
- .codex/: project-scoped Codex config

# File discipline
- read from `inputs/` first
- write final files only under `outputs/`
- do not create new top-level folders unless explicitly asked
- if a task needs working notes, write them under `outputs/` with a temporary prefix like `_draft_`

# Required outputs
- outputs/competitor-grid.md
- outputs/positioning.md
- outputs/pricing.md
- outputs/offer-spec.md
- outputs/scope-boundaries.md
- outputs/client-requirements.md
- outputs/upwork-project.md
- outputs/faq.md
- outputs/gallery-brief.md
- outputs/acp-job-hidden.json
- outputs/acp-job-public.json
- outputs/acp-sample-request.json
- outputs/acp-sample-deliverable.json
- outputs/sample-report-public.md
- outputs/sample-report-private-template.md
- outputs/redteam.md
- outputs/pdf-outline.md
- outputs/launch-checklist.md
- outputs/publish-sequence.md

# Review standard
- flag vague promises
- flag hidden sync work
- flag scope creep into implementation
- flag pricing that makes the offer look cheap or too broad
- tighten language instead of adding features

# Done means
- the offer is narrow enough to buy without a call
- the mandatory intake can fit into 5 fields if possible, 6 max
- Upwork copy and ACP schema describe the same product
- a skeptical technical buyer could read the sample report and understand the value
