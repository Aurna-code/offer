One-shot run for Codex.

Read `AGENTS.md`, `PLANS.md`, and all files under `inputs/`.

Do this in order:
1. Write a short execution plan to `outputs/_draft_plan.md`
2. Produce:
   - `outputs/competitor-grid.md`
   - `outputs/positioning.md`
   - `outputs/pricing.md`
   - `outputs/offer-spec.md`
   - `outputs/scope-boundaries.md`
   - `outputs/client-requirements.md`
   - `outputs/upwork-project.md`
   - `outputs/faq.md`
   - `outputs/gallery-brief.md`
   - `outputs/acp-job-hidden.json`
   - `outputs/acp-job-public.json`
   - `outputs/acp-sample-request.json`
   - `outputs/acp-sample-deliverable.json`
   - `outputs/sample-report-public.md`
   - `outputs/sample-report-private-template.md`
   - `outputs/pdf-outline.md`
3. Run a red-team pass and write `outputs/redteam.md`
4. Patch earlier outputs if needed
5. Finish with:
   - `outputs/launch-checklist.md`
   - `outputs/publish-sequence.md`

Rules:
- plan first
- keep the product narrower than a full code audit
- do not turn this into implementation or modernization work
- optimize for no-meeting purchase
- if uncertain, choose narrower scope and clearer promises
