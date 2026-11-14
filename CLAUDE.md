# Job Evidence Bank — instructions for Claude

## Who I am
- Bush regenerator in NSW, moving into ecological stewardship or a better-paying environmental role.
- I apply for three kinds of roles: NSW Government (state), local council, and private/not-for-profit.
- Target titles: Bushcare/bushland supervisor, ecological stewardship, project officer, community engagement, environment admin, and similar. Minimum base salary $78,000. Priority: NSW Government (especially DCCEEW), then council, then private. Full details are in `profile.md`.
- I have no tech or coding background. Explain anything technical in plain English and keep things small. **When gathering information, ask all your questions at once as a numbered list** (my preference); I'll answer in one go. If I say "don't worry about this", drop it, with no [CHECK] nagging.

## How the repo works
- `profile.md` — contact details, work history, qualifications/tickets, referees, target roles, career goal.
- `evidence/` — one file per story, in STAR format (Situation, Task, Action, Result), with a tag block at the top. File names: `short-descriptive-name.md`. Copy `evidence/_template.md` for new ones.
- `evidence/INDEX.md` — one table listing every story and its tags. **Update it every time a story is added or changed.**
- `reference/nsw-capability-framework.md` — plain-English summary of the NSW Public Sector Capability Framework. **Not filled in yet:** the PSC website is blocked from Claude's workspace. When I say a job is a government job, ask me to paste the framework text (or the relevant capabilities), then fill in this file.
- `master-resume.md` — full, untailored resume built from profile + evidence. Update it when big new evidence arrives.
- `applications/YYYY-MM-employer-role-title/` — one folder per job: `job-ad.md` (what I pasted), `resume.md`, `cover-letter.md`, and `targeted-questions.md` or `selection-criteria.md` when needed.
- `inbox/` — raw documents I upload (old resumes, references, certificates). Read them and pull evidence out.
- Slash commands in `.claude/commands/`: `/braindump` (guided interview), `/add` (turn rough notes into a story), `/apply` (tailor documents for a job).
- Don't build anything else (no trackers, scripts, dashboards or apps) unless I ask.

## Rules
- **Never invent** evidence, numbers, qualifications or results. If something is missing, ask me or leave a clear `[CHECK: ...]` note.
- Australian English, in my voice: plain, confident, practical. No corporate fluff.
- Outputs I paste into job portals (resumes, cover letters, answers) must be clean markdown: simple headings and bullets, **no tables**.
- Respect every word and page limit, and show the word count.
- NSW Government roles: demonstrate each focus capability at the level the role asks for, using the framework's language naturally (no keyword stuffing). Check `reference/nsw-capability-framework.md`.
- Council roles: address each essential/desirable criterion directly.
- Private roles: tailored resume + cover letter matched to the ad's keywords.
- Help me frame transferable bush regen experience (site planning, coordinating volunteers or contractors, reporting to land managers, working with community and landholders) for stewardship and project officer roles.
- I tend to undersell myself: push for numbers and outcomes (hectares, plants, people, budget, timeframes).
- Be honest about where my evidence is thin.

## End of every session
- Commit and push all changes so they're there next time.
- Tell me in one plain sentence if I need to do anything (e.g. merge a pull request on GitHub).
