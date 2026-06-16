# State Schema — Interview Coach

Reference file for `coaching_state.md` format, schema migration rules, and state update triggers. Read this during `kickoff` (to initialize a new file) and at session start when performing the Schema Migration Check.

---

## State File Format

```markdown
# Coaching State — [Name]
Last updated: [date]

## Profile
- Target role(s):
- Seniority band:
- Track: Quick Prep / Full System
- Feedback directness: [1-5]
- Interview timeline: [date or "ongoing"]
- Time-aware coaching mode: [triage / focused / full]
- Interview history: [first-time / active but not advancing / experienced but rusty]
- Biggest concern:
- Known interview formats: [e.g., "behavioral screen, system design (verbal walkthrough)" — updated by Format Discovery Protocol during prep/mock]
- Anxiety profile: [confident-underprepared / anxious-specific / generalized / post-rejection / impostor — set by hype, reused in subsequent sessions]
- Career transition: [none / function change / domain shift / IC↔management / industry pivot / career restart — set by kickoff]
- Transition narrative status: [not started / in progress / solid — set by kickoff, updated by pitch/stories]

## Resume Analysis
- Positioning strengths: [the 2-3 signals a hiring manager sees in 30 seconds]
- Likely interviewer concerns: [flagged from resume — gaps, short tenures, domain switches, seniority mismatches]
- Career narrative gaps: [transitions that need a story ready]
- Story seeds: [resume bullets with likely rich stories behind them]

## Storybank
| ID | Title | Primary Skill | Secondary Skill | Earned Secret | Strength | Use Count | Last Used |
|----|-------|---------------|-----------------|---------------|----------|-----------|-----------|
[rows — compact index. Use Count tracks total times used in real interviews (incremented via debrief). Full column spec in references/storybank-guide.md — the guide adds Impact, Domain, Risk/Stakes, and Notes. Add extra columns as stories are enriched.]

### Story Details
#### S001 — [Title]
- Situation:
- Task:
- Action:
- Result:
- Earned Secret:
- Deploy for: [one-line use case — e.g., "leadership under ambiguity questions"]
- Version history: [date — what changed]

[repeat for each story]

## Score History
### Historical Summary (when table exceeds 15 rows, summarize older entries here)
[Narrated trend summary of older sessions — direction per dimension, inflection points, what caused shifts]

### Recent Scores
| Date | Type | Context | Sub | Str | Rel | Cred | Diff | Hire Signal | Self-Δ |
|------|------|---------|-----|-----|-----|------|------|-------------|--------|
[rows — Type: interview/practice/mock. Sub=Substance, Str=Structure, Rel=Relevance, Cred=Credibility, Diff=Differentiation — each 1-5 numeric. Hire Signal: Strong Hire/Hire/Mixed/No Hire (from analyze/mock only — leave blank for practice). Self-Δ: over/under/accurate (>0.5 delta from coach scores = over or under; within 0.5 = accurate). Keep most recent 10-15 rows.]

## Outcome Log
| Date | Company | Role | Round | Result | Notes |
|------|---------|------|-------|--------|-------|
[rows — Result: advanced/rejected/pending/offer/withdrawn]

## Interview Intelligence

### Question Bank
| Date | Company | Role | Round Type | Question | Competency | Score | Outcome |
[Round Type: behavioral/technical/system-design/case-study/bar-raiser/culture-fit.
 Score: average across 5 dims (e.g., 3.4), or "recall-only" for debrief-captured questions.
 Outcome: advanced/rejected/pending/unknown — updated when known.]

### Effective Patterns (what works for this candidate)
- [date]: [pattern + evidence — e.g., "Leading with counterintuitive choice in prioritization stories scores 4+ on Differentiation (CompanyA R1, CompanyB R2)"]

### Ineffective Patterns (what keeps not working)
- [date]: [pattern + evidence — e.g., "Billing migration story has scored below 3 on Differentiation across 3 uses. Retire or rework."]

### Recruiter/Interviewer Feedback
| Date | Company | Source | Feedback | Linked Dimension |
[Source: recruiter/interviewer/hiring-manager. Keep verbatim when possible.]

### Company Patterns (learned from real experience)
#### [Company Name]
- Questions observed: [types and frequency]
- What seems to matter: [observations from real data]
- Stories that landed / didn't: [S### IDs]
- Last updated: [date]

### Historical Intelligence Summary
[Narrated summary when subsections exceed archival thresholds]

## Drill Progression
- Current stage: [1-8]
- Gates passed: [list]
- Revisit queue: [weaknesses to resurface]

## Interview Loops (active)
### [Company Name]
- Status: [Decoded / Researched / Applied / Interviewing / Offer / Closed]
- Rounds completed: [list with dates]
- Round formats:
  - Round 1: [format, duration, interviewer type — e.g., "Behavioral screen, 45min, recruiter"]
  - Round 2: [format, duration, interviewer type]
- Stories used: [S### per round]
- Concerns surfaced: [ranked list from `concerns` — severity + counter strategy, or from analyze/rejection feedback]
- Interviewer intel: [LinkedIn URLs + key insights, linked to rounds]
- Prepared questions: [top 3 from `questions` if run]
- Next round: [date, format if known]
- Fit verdict: [from research or prep — Strong / Investable Stretch / Long-Shot Stretch / Weak]
- Fit confidence: [Limited — no JD / Medium — JD + resume / High — JD + resume + storybank]
- Fit signals: [1-2 lines on what drove the verdict]
- Structural gaps: [gaps that can't be bridged with narrative, if any]
- Date researched: [date, if `research` was run]

## Active Coaching Strategy
- Primary bottleneck: [dimension]
- Current approach: [what we're working on and how]
- Rationale: [why this approach — links to decision tree / data]
- Pivot if: [conditions that would trigger a strategy change]
- Root causes detected: [list]
- Self-assessment tendency: [over-rater / under-rater / well-calibrated]
- Previous approaches: [list of abandoned strategies with brief reason — e.g., "Structure drills — ceiling at 3.5, diminishing returns"]

## Calibration State

### Calibration Status
- Current calibration: [uncalibrated / calibrating / calibrated / miscalibrated]
- Last calibration check: [date]
- Data points available: [N] real interviews with outcomes

### Scoring Drift Log
| Date | Dimension | Direction | Evidence | Adjustment |

### Calibration Adjustments
| Date | Trigger | What Changed | Rationale |

### Cross-Dimension Root Causes (active)
| Root Cause | Affected Dimensions | First Detected | Status | Treatment |

### Unmeasured Factor Investigations
| Date | Trigger | Hypothesis | Investigation | Finding | Action |

## LinkedIn Analysis
- Date: [date]
- Depth: [Quick Audit / Standard / Deep Optimization]
- Overall: [Strong / Needs Work / Weak]
- Recruiter discoverability: [Strong / Moderate / Weak]
- Credibility on visit: [Strong / Moderate / Weak]
- Differentiation: [Strong / Moderate / Weak]
- Top fixes pending: [1-3 line items]
- Positioning gaps: [resume ↔ LinkedIn inconsistencies, if assessed]

## Resume Optimization
- Date: [date]
- Depth: [Quick Audit / Standard / Deep Optimization]
- Overall: [Strong / Needs Work / Weak]
- ATS compatibility: [ATS-Ready / ATS-Risky / ATS-Broken]
- Recruiter scan: [Strong / Moderate / Weak]
- Bullet quality: [Strong / Moderate / Weak]
- Seniority calibration: [Aligned / Mismatched]
- Keyword coverage: [Strong / Moderate / Weak]
- Top fixes pending: [1-3 line items]
- JD-targeted: [yes — which JD / no]
- Cross-surface gaps: [resume ↔ LinkedIn inconsistencies, if assessed]

## Positioning Statement
- Date: [date]
- Depth: [Quick Draft / Standard / Deep Positioning]
- Core statement: [the full hook + context + bridge — 30-45 second version]
- Hook (10s): [the curiosity-gap opener alone]
- Key differentiator: [one sentence]
- Earned secret anchor: [the earned secret or spiky POV powering the positioning]
- Target audience: [primary audience this was optimized for]
- Variant status: [which variants were produced]
- Consistency status: [aligned / gaps identified — brief summary]

## Outreach Strategy
- Date: [date]
- Depth: [Quick / Standard / Deep]
- Positioning source: [Positioning Statement / Resume Analysis fallback]
- Message types coached: [list]
- Targets contacted: [people/companies]
- Channel strategy: [primary channels]
- Follow-up status: [pending follow-ups with timing]
- LinkedIn profile flagged: [yes/no]
- Key hooks identified: [1-2 reusable positioning hooks]

## JD Analysis: [Company] — [Role]
- Date: [date]
- Depth: [Quick Scan / Standard / Deep Decode]
- Fit verdict: [Strong Fit / Investable Stretch / Long-Shot Stretch / Weak Fit]
- Top competencies: [top 3 in priority order]
- Frameable gaps: [list]
- Structural gaps: [list]
- Unverified assumptions: [count of LOW/UNKNOWN items]
- Batch triage rank: [rank/total, if applicable]

[Multiple JD Analysis sections can exist — one per company+role]

### Past JD Analyses (archived — when 10+ analyses exist, non-active decodes compress here)
| Date | Company | Role | Fit Verdict |
[rows — brief archive of decoded JDs the candidate didn't pursue]

## Presentation Prep: [Topic / Company]
- Date: [date]
- Depth: [Quick Structure / Standard / Deep Prep]
- Framework: [selected narrative arc]
- Time target: [X min presentation + Y min Q&A]
- Content status: [outline only / full content / talk track reviewed]
- Top predicted questions: [top 3]
- Key adjustment: [single biggest change recommended]

## Comp Strategy
- Date: [date]
- Depth: [Quick Script / Standard / Deep Strategy]
- Target range: [bottom / target / stretch — or "not yet researched"]
- Range basis: [sources used]
- Research completeness: [none / partial / thorough]
- Stage coached: [application / recruiter screen / mid-process / general]
- Jurisdiction notes: [relevant info, if applicable]
- Scripts provided: [which stages covered]
- Key principle: [the most important takeaway]

## Meta-Check Log
| Session | Candidate Feedback | Adjustment Made |
|---------|-------------------|-----------------|
[rows — record every meta-check response and any coaching adjustment]

## Session Log
### Historical Summary (when log exceeds 15 rows, summarize older entries here)
[Brief narrative of earlier sessions]

### Recent Sessions
| Date | Commands Run | Key Outcomes |
|------|-------------|--------------|
[rows — brief, 1-line per session]

## Coaching Notes
[Freeform observations that don't fit structured fields — things the coach should remember between sessions]
- [date]: [observation — e.g., "candidate freezes in panel formats," "gets defensive about short tenure at X," "prefers morning interviews," "mentioned they interview better after coffee"]
```

---

## Schema Migration Check

After reading `coaching_state.md`, check whether it contains all sections and columns below. If any are missing, migrate silently:

- **Missing `Secondary Skill` column in Storybank**: Add the column to the table header. Leave existing rows blank for Secondary Skill. Note in Coaching Notes: "[date]: Storybank upgraded to include Secondary Skill tracking. Existing stories need secondary skills added during next `stories improve` session."
- **Missing `Use Count` column in Storybank**: Add the column to the table header. Initialize all existing rows to 0. The count will begin tracking from this point forward.
- **Missing `Calibration State` section**: Add the full section using the schema defined above (after Active Coaching Strategy). Initialize Calibration Status to "uncalibrated", Last calibration check to "never", Data points available to the count of entries in the Outcome Log. All tables start empty.
- **Missing `LinkedIn Analysis` section**: Add the section header with empty fields. Note in Coaching Notes: "[date]: LinkedIn Analysis section added. Run `linkedin` to populate."
- **Missing `Resume Optimization` section**: Add the section header with empty fields. Note in Coaching Notes: "[date]: Resume Optimization section added. Run `resume` to populate."
- **Missing `Positioning Statement` section**: Add the section header with empty fields. Note in Coaching Notes: "[date]: Positioning Statement section added. Run `pitch` to populate."
- **Missing `Outreach Strategy` section**: Add the section header with empty fields. Note in Coaching Notes: "[date]: Outreach Strategy section added. Run `outreach` to populate."
- **Missing `JD Analysis` section(s)**: No migration needed — JD Analysis sections are created per-JD when `decode` is run. Absence is normal.
- **Missing `Presentation Prep` section**: No migration needed — created when `present` is run. Absence is normal.
- **Missing `Comp Strategy` section**: Add the section header with empty fields. Note in Coaching Notes: "[date]: Comp Strategy section added. Run `salary` to populate."
- **Missing `Anxiety profile` in Profile**: Add the field with value "unknown". It will be set during the next `hype` session.
- **Missing `Career transition` in Profile**: Add the field with value "none". If the candidate's resume suggests a transition, update during the next session.
- **Missing `Transition narrative status` in Profile**: Add the field with value "not started". Only relevant when Career transition is not "none".
- **Missing `Known interview formats` in Profile**: Add the field with an empty value. It will be populated by the Format Discovery Protocol during `prep` or `mock`.
- **Missing `Interview Intelligence` section**: Add the full section with empty subsections: Question Bank (empty table with columns: Date, Company, Role, Round Type, Question, Competency, Score, Outcome), Effective Patterns (what works for this candidate) (empty), Ineffective Patterns (what keeps not working) (empty), Recruiter/Interviewer Feedback (empty table with columns: Date, Company, Source, Feedback, Linked Dimension), Company Patterns (learned from real experience) (empty), Historical Intelligence Summary (empty). Note in Coaching Notes: "[date]: Interview Intelligence section added. Will be populated by `analyze`, `debrief`, and `feedback`."
- **`Signal` column renamed to `Hire Signal` in Score History**: If the Score History table header contains a `Signal` column (without the `Hire` prefix), rename it to `Hire Signal`. Leave all existing row data unchanged.
- **Interview Loops entries missing newer fields**: When reading existing Interview Loop entries for a company, check for missing fields: `Status`, `Round formats`, `Fit verdict`, `Fit confidence`, `Fit signals`, `Structural gaps`, `Date researched`. Add any missing fields with empty values. Set `Status` to "Interviewing" if the entry has rounds completed, or "Researched" if it has research data but no rounds.

Run this migration silently — do not announce schema changes to the candidate unless they affect immediate coaching recommendations. After migration, the coaching state is fully compatible with the current skill version.

---

## State Update Triggers

Write to `coaching_state.md` whenever:
- kickoff creates a new profile and populates Resume Analysis from resume analysis. Also initializes empty sections: Meta-Check Log, Active Coaching Strategy, Interview Loops, Coaching Notes.
- research adds a new company entry (lightweight, in Interview Loops with Status: Researched, plus fit verdict, fit confidence, fit signals, structural gaps, and date)
- stories adds, improves, or retires stories (write full STAR text to Story Details, not just index row)
- analyze, practice, or mock produces scores (add to Score History — practice sub-commands that use the 5-dimension rubric add to Score History; retrieval drills log to Session Log only) — analyze also updates Active Coaching Strategy after triage decision. When updating Active Coaching Strategy, always preserve Previous approaches — move the old approach there before writing the new one. Analyze also extracts questions and scores to Interview Intelligence Question Bank, updates Effective/Ineffective Patterns if 3+ data points reveal a pattern, updates Company Patterns, and checks for cross-dimension root causes (updates Calibration State → Cross-Dimension Root Causes if a root cause appears across 2+ answers).
- concerns generates ranked concerns (save to Interview Loops under the relevant company's Concerns surfaced, or to Active Coaching Strategy if general)
- questions generates tailored questions (save top 3 to Interview Loops under Prepared questions for the relevant company)
- debrief captures post-interview data (add to Interview Loops, update storybank Last Used dates and increment Use Count for each story used, add to Outcome Log as pending). Also extracts recalled questions to Interview Intelligence Question Bank (marked "recall-only") and captures recruiter/interviewer feedback to the Recruiter/Interviewer Feedback table.
- feedback captures ad-hoc input: recruiter feedback (add to Recruiter/Interviewer Feedback — also check for drift signals when feedback contradicts coach scoring), outcomes (update Outcome Log + Question Bank Outcome column — trigger calibration check when 3-outcome threshold is crossed), corrections (evaluate and adjust if warranted — may update Score History or Storybank ratings, record in Coaching Notes), post-session memories (route to Question Bank, Storybank, Interview Loops, or Company Patterns as appropriate), and meta-feedback (record in Meta-Check Log)
- progress reviews trends (update Active Coaching Strategy, check Score History archival, check Interview Intelligence archival thresholds). Also runs calibration check when 3+ outcomes exist (scoring drift detection, cross-dimension root cause review, success pattern analysis) — updates Calibration State.
- User reports a real interview outcome (add to Outcome Log)
- linkedin produces profile audit (save LinkedIn Analysis section to coaching_state.md — date, depth, overall score, dimension scores, top fixes pending, positioning gaps)
- resume produces resume audit (save Resume Optimization section to coaching_state.md — date, depth, overall score, dimension scores, top fixes pending, JD-targeted status, cross-surface gaps)
- pitch produces a positioning statement (save Positioning Statement section to coaching_state.md — date, depth, core statement, hook, key differentiator, earned secret anchor, target audience, variant status, consistency status)
- outreach produces outreach coaching (save Outreach Strategy section to coaching_state.md — date, depth, positioning source, message types coached, targets contacted, channel strategy, follow-up status, LinkedIn profile flagged, key hooks identified)
- decode produces JD analysis (save JD Analysis section per JD to coaching_state.md — date, depth, fit verdict, top competencies, frameable gaps, structural gaps, unverified assumptions, batch triage rank). Multiple JD Analysis sections can exist. Also update Interview Loops: if decode is for a company already in loops, add/update JD decode data; if new company, add lightweight entry with Status: Decoded.
- present produces presentation prep (save Presentation Prep section as top-level section in coaching_state.md — include company name in header when company-specific — date, depth, framework, time target, content status, top predicted questions, key adjustment)
- salary produces comp strategy (save Comp Strategy section to coaching_state.md — date, depth, target range, range basis, research completeness, stage coached, jurisdiction notes, scripts provided, key principle)
- prep starts a new company loop or updates interviewer intel, round formats, fit verdict, fit confidence, and structural gaps (add to Interview Loops)
- negotiate receives an offer (add to Outcome Log with Result: offer)
- reflect archives the coaching state (add Status: Archived header)
- Meta-check conversations (record candidate's response and any coaching adjustment to Meta-Check Log)
- Any session where the candidate reveals coaching-relevant personal context — preferences, emotional patterns, interview anxieties, scheduling preferences, etc. (add to Coaching Notes)
