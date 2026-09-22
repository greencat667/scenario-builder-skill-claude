---
name: scenario-builder
description: >
  Build a set of four plausible, distinct futures using the 2×2 critical-uncertainties method (the "Shell" / intuitive-logics approach), then turn them into early-warning indicators and robust strategic moves. Triggers on: "scenario planning", "build scenarios", "2x2 scenarios", "scenario matrix", "critical uncertainties", "four futures", "alternative futures for", "what are the possible futures of", "scenario workshop", "scenarios for 2035", "explore plausible futures", "signposts", "early warning indicators", "robust strategy", "no-regret moves". Use when someone needs to plan under deep uncertainty — where forecasting a single answer would be false precision — and wants several coherent futures to test decisions against. Works from scratch (it researches the drivers) or from existing material such as a trend report, PESTLE scan, or futures wheel. Different from trend-report (one topic, narrative scenarios as one section), futures-wheel (consequences of one change), and foresight (a single calibrated probability).
---

# Scenario Builder

Scenarios are not predictions. They are a small set of coherent, contrasting stories about how the future *could* unfold, built so that a decision can be tested against all of them. A good set makes people say "I hadn't thought of that" about at least one world, and "we'd be in trouble there" about at least one other.

This skill uses the **2×2 critical-uncertainties method**: find the forces that will shape the future, separate the ones we can count on from the ones we can't, pick the two uncertainties that matter most and are independent of each other, and cross them to get four worlds. Then it does the two things most scenario exercises skip: **early-warning indicators** (so you notice which world is arriving) and **robust moves** (so the scenarios change what you do).

## When to use it — and when not to

Use it when:

- The question is 5–15+ years out and the outcome genuinely depends on things nobody controls
- A team is about to commit to a strategy, a big investment, or a campaign that must survive several possible futures
- People are anchored on one "official future" and need it loosened

Don't use it when:

- The question has a single resolvable answer by a date — use a forecast instead (the `foresight` skill if installed)
- You want the ripple effects of one known change — use a futures wheel
- The horizon is under 2–3 years; most uncertainties won't have played out, so the four worlds collapse into one

## Inputs

Ask for (or infer from the conversation) the following. If something is missing and can't be inferred, ask once, briefly — don't interrogate.

| Input | Why it matters | Default if not given |
|---|---|---|
| **Focal question** | Scenarios need a decision to serve. "The future of transport" is a topic; "Should we build our programme around car-free towns by 2035?" is a focal question. | Draft one from the topic and confirm |
| **Horizon year** | Sets how far drivers can move | 10 years from today |
| **Organisation / user** | Implications and robust moves need an actor | "the organisation" — keep implications generic |
| **Geography** | Drivers differ by place | The user's country |
| **Source material** | Trend reports, PESTLE scans, futures wheels, strategy docs | Research from scratch |
| **Mode** | Interactive (pause at axis choice) or end-to-end | Interactive |

A focal question is good when it names **who decides**, **what is being decided**, and **by when**. Rewrite weak ones before starting and show the user the rewrite:

- ❌ "What's the future of community energy?"
- ✅ "Should our trust commit to community-owned solar as its main local programme for 2026–2036?"

## Process

Work through these steps in order. In interactive mode, pause after Step 4 for the user to choose the axes. In end-to-end mode, choose the axes yourself and say why.

### Step 1 — Driving forces inventory

List **15–25 driving forces** that will shape the answer to the focal question by the horizon year. Cover all of STEEP+ (Social, Technological, Economic, Environmental, Political, plus Legal and Values where relevant) so the list isn't lopsided.

- If source material exists, harvest its drivers first, then research to fill gaps in thin categories.
- If not, research with web search. Prioritise primary sources: statistics offices, legislation, regulators, academic work, the actors themselves.
- Each driver is one line: **name** — what's moving, in which direction, with a linked citation `([Source](https://...))`.
- Phrase drivers as *forces*, not outcomes: "Council budgets for discretionary services" (a force that could go either way), not "Councils cut funding" (one outcome).

Never invent statistics or sources. If a driver matters but you can't find evidence for it, keep it and mark it `(evidence thin)` — that is useful information in itself.

### Step 2 — Rate impact and uncertainty

Score each driver 1–5 on two scales, with a one-line reason for each score:

- **Impact** on the focal question by the horizon year. 5 = it would change the right answer.
- **Uncertainty** about which way it goes by the horizon year. 5 = genuinely could go either way; 1 = we can be confident of the direction.

Show the result as a table sorted by impact × uncertainty. Then split it:

- **Predetermined elements** — high impact, low uncertainty (impact ≥4, uncertainty ≤2). These will be true in *every* scenario. Name them explicitly; they're some of the most valuable output, because they're the things people often treat as uncertain when they aren't.
- **Critical uncertainties** — high impact, high uncertainty (both ≥4, or the top 5–7 by product).
- Everything else is background colour.

Be honest in the scoring. The commonest failure is rating a driver "uncertain" because the team *dislikes* one direction, not because the evidence is balanced. Ask of each high-uncertainty score: *would a well-informed sceptic agree this could genuinely go either way?*

### Step 3 — Build candidate axes

Turn the top critical uncertainties into **axes**: each has two poles describing opposite, plausible end-states by the horizon year.

Rules for a good axis:

- **Both poles are plausible.** If one pole requires a miracle, it isn't an uncertainty.
- **Neither pole is simply "good" or "bad".** "Strong public support vs weak public support" is value-laden; "Support driven by money-saving vs support driven by identity and belonging" is not. Value-laden axes produce a heaven world, a hell world and two muddles.
- **Poles are described as states of the world, not actions by the user's organisation.** The organisation's choices are what you test *against* the scenarios; they can't be one of the axes.
- **Poles are specific enough to picture.** "High tech" is not; "Most booking, access and payment runs on one national platform" is.

Where two uncertainties are really the same underlying force, merge them.

### Step 4 — Choose the pair (checkpoint)

Offer **2–3 candidate axis pairs**. For each pair, check and report:

1. **Independence.** Does knowing where we sit on axis A tell you much about axis B? If yes, the matrix collapses onto a diagonal and two of the four worlds become implausible. Reject the pair.
2. **Coverage.** Do the two axes together capture most of what matters about the focal question? Name which important uncertainty each pair leaves out.
3. **Surprise.** Does at least one quadrant look unfamiliar or uncomfortable?

Recommend one pair and say why. In interactive mode, **stop here** and let the user choose, swap a pole, or suggest their own axis. In end-to-end mode, proceed with your recommendation.

### Step 5 — Build the four worlds

For each quadrant, write:

- **Name** — two to four memorable words that capture the world's character. Not "Scenario A", not "Best case". Good names get repeated in meetings; that's the point.
- **In one line** — the world as a headline.
- **How we got here** — a causal story from today to the horizon year, 150–250 words, in past tense from the horizon year's viewpoint. Name 2–3 turning points with rough dates. Use the drivers and predetermined elements; every world must contain *all* the predetermined elements.
- **What's true in this world** — 5–8 bullets across STEEP+ describing daily reality, not trends.
- **Winners and losers** — who does well, who is squeezed. Every world has both.
- **A moment in this world** — a vignette of 120–180 words: one named, ordinary person on an ordinary day. Concrete sensory detail, a small tension, no speeches. Use fictional people and places — never real private individuals, and don't hang the vignette on a real small place or organisation in a way that reads as a claim about it.
- **What it means for us** — 3–5 bullets: threats, opportunities, and the capability you'd most wish you'd built.

Use the templates in `references/output-template.md`.

### Step 6 — Critique and rewrite

Before showing the worlds, run the checks in `references/critique-checklist.md` and rewrite whatever fails. The most important:

- **No good/bad/muddle pattern.** If one world is obviously the one everyone wants, reframe until each has real upsides and real costs.
- **Internal consistency.** Nothing in a world contradicts its own axis poles or a predetermined element.
- **Distinctiveness.** Each pair of worlds differs in ways that would change a decision, not just in tone.
- **Plausibility, not probability.** Don't assign likelihoods to the worlds. The moment one is labelled "most likely", people stop thinking about the others.

Add a short "Critique notes" section at the end of the working file recording what failed and what you changed — the user will want to see the reasoning, and it goes in the appendix of the final output.

### Step 7 — Early-warning indicators

For each world, write **3–5 indicators** that would tell you it's arriving. Each indicator must be:

- **Observable** — something that will be published, measured or announced
- **Specific** — with a threshold or direction, not "more interest in X"
- **Discriminating** — more likely in this world than in the others. An indicator that fires in all four worlds is useless.
- **Sourced** — name where you'd look (a statistics series, a register, a budget document, a regulator's announcements), with a link where one exists

Format as a table: Indicator · Points towards · Where to watch · Check by (year).

Then add two bridges, so the indicators get used rather than filed:

- **Signal-monitor topics** — 3–6 search-ready topics and queries a weekly signal scan could track (compatible with a trend-signal-monitor style scheduled task).
- **Forecastable questions** — 2–4 indicators rewritten as resolvable yes/no questions with a date, e.g. "Will [named register] show more than [N] [things] by 31 December 2029?" These can be handed to a forecasting skill to put a probability on them and track it.

### Step 8 — Implications and robust moves

Finish with the section that makes the scenarios matter:

- **Predetermined elements** — restated, because these are safe to plan on.
- **No-regret moves** — actions that pay off in all four worlds. Aim for 3–5. Test each honestly: does it really help in the worst world for it?
- **Hedges** — cheap actions that protect against a specific bad world.
- **Options to keep open** — decisions to delay until an indicator fires.
- **Big bets** — moves that only pay off in one or two worlds. Name which, and which indicators would justify making the bet.
- **Strategy stress test (optional)** — if the user has current strategy or options, score each against each world (✅ works / ⚠️ strained / ❌ fails) in a table and name the weakest point.

## Output

Produce two files in the user's working folder (or wherever they ask):

1. **`scenarios-[slug].md`** — the full scenario report, following `references/output-template.md`:
   focal question → summary matrix → predetermined elements → the four worlds → early-warning indicators → implications and robust moves → appendix (driver inventory with scores, rejected axis pairs, critique notes, sources).
2. **`scenarios-[slug].html`** — a one-page visual 2×2, made by copying `assets/scenario-matrix.html` and replacing only the `SCENARIOS` data object near the bottom of the file. Open it in a browser (or the built-in browser) to check it renders before handing over.

If the user wants Word, convert the markdown with pandoc (`pandoc scenarios-[slug].md -o scenarios-[slug].docx`, adding `--reference-doc` if they have a branded template).

## Style

- Plain English, short sentences. Write as a colleague thinking out loud, not as a consultant.
- Every factual claim about the present has a linked citation. Claims about the future don't need citations — they need to be traceable to a driver.
- Keep the whole report readable in 20 minutes: roughly 2,500–4,000 words excluding the appendix.
- No meta-text in the output (no word counts, no "as an AI").

## Handoffs

If these skills are installed, offer the natural next step at the end:

- **strategic-wargame** — play out the most threatening world with adversaries and allies
- **options-paper** — turn the robust moves into a decision paper
- **experiment-card** — test the riskiest assumption behind a no-regret move
- **foresight** — put probabilities on the forecastable questions and track them
- **trend-signal-monitor** — schedule a weekly scan of the signal-monitor topics

## Files

| File | Purpose |
|---|---|
| `SKILL.md` | This process |
| `references/output-template.md` | Section-by-section template for the report |
| `references/critique-checklist.md` | Checks to run in Step 6 |
| `assets/scenario-matrix.html` | Self-contained 2×2 visual; replace the `SCENARIOS` object |
| `examples/community-tool-libraries-scenarios.md` | A complete worked example |
| `examples/community-tool-libraries-scenarios.html` | Its visual matrix |
