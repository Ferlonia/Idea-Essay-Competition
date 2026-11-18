---
name: idea-essay-competition
description: Helps design, write, review, and polish idea-based (innovation) scientific essays for competitions, where the entry proposes a product, program, app, method, or system to solve a real problem, not a research report. Covers reading the competition guidelines (juknis), theme and subtheme, current-issue research, idea formulation, title design and validation, introduction and discussion drafting (how it works, advantages, feasibility, impact, projection), supporting figures and tables, and final QA and style polish. English version of the Indonesian skill esai-gagasan-lomba; manuscripts are usually written in Bahasa Indonesia, so keep Indonesian terms where competitions use them. Use this skill whenever the user mentions an essay competition, lomba esai, esai ilmiah, esai gagasan, karya tulis ilmiah gagasan, innovation essay, idea essay, essay title, theme or subtheme, a winning-essay breakdown (bedah esai), introduction or discussion sections of such an essay, prototype or workflow figures for an essay, or asks for an essay draft to be reviewed or made to read less like machine writing, even if they never say "skill" or "idea essay".
---

# Idea-Based Scientific Essays for Competitions

This skill helps competition participants (high school, university, general) write essays that avoid the three things that most often cost points: an idea that reads like research, a title that breaks the expected pattern, and content that undersells creativity. The source material is mentor Royhan Saydi's teaching (ANSA Academy, Bootcamp Esai) and the "Bedah Esai" material from Muda Kompetisi (mentor annotations on two example essays). The skill codifies criteria that, according to those mentors, often decide scores. It does not guarantee a win: idea quality, data, and compliance with the competition guidelines still decide.

Sections marked **[ADDED]** are general additions from Claude, not from the mentor sources.

## Language of the manuscript [ADDED]

These instructions are in English, but the competitions this skill targets are mostly Indonesian, so the essay itself is usually written in formal Bahasa Indonesia (baku). Follow the language the competition requires. If the user does not say, ask once. Keep the Indonesian terms in the glossary below when talking about the competition, because users will meet them in the guidelines. If the competition is in English, the structure, title formulas, and checks still apply; use the English equivalents given in the reference files, and count title words in the competition's language.

| Term | Meaning |
|---|---|
| juknis (petunjuk teknis) | the competition's technical guidelines |
| tema / subtema | theme / subtheme set by the organizers |
| gagasan | idea or innovation proposal (the form this essay takes) |
| esai ilmiah | scientific essay |
| pendahuluan / pembahasan / penutup | introduction / discussion / closing |
| daftar pustaka / lampiran | references / appendix |
| BPS | Statistics Indonesia, the national statistics agency |
| dinas | regional government office |
| SDGs | Sustainable Development Goals |
| pentahelix | five-party collaboration model: academia, business, community, media, government |
| UMKM | micro, small, and medium enterprises (MSMEs) |

## Core principles

Definition (Saydi, 2022): a scientific essay competition is a scientific writing competition in the form of an IDEA (gagasan) that solves a problem in the participant's surroundings (social, legal, education, health, agriculture, environment, and others, depending on the theme), presented as a product, program, idea, application, design, method, or system.

Four principles, with the reason for each:

1. **An idea, not research.** A judge who sees a research-style title reads the whole manuscript through a research lens, and the score drops even when the idea is good. So the manuscript structure uses no hypotheses, variables, or statistical tests.
2. **Stay inside the theme and subtheme.** An excellent idea outside the theme is out.
3. **Creativity and innovation carry the most weight**, according to the mentors, so the whole manuscript, and the discussion above all, builds that impression. If the organizers publish a scoring rubric, the rubric overrides this assumption.
4. **One common thread.** The problem in the title, the data in the introduction, how it works, the advantages, the impact, the projection, and the closing must all tell the same story in the same terms. A manuscript whose parts are good but do not connect reads like a patchwork.

If the competition guidelines conflict with this skill, follow the guidelines and explain the difference in one or two sentences.

## Reference map: which file to read, and when

| Need | File |
|---|---|
| Early research, current issues, guidelines, research sheet, common thread | references/early-research.md |
| Title: components, styles, validation | references/titles.md |
| Title pattern examples | references/title-bank.md |
| Evidence of judge corrections on titles | references/review-cases.md |
| Title annotation, introduction paragraph functions, closing, title types judges like, critical notes | references/intro-closing-breakdown.md |
| Discussion framework B1-B8 (neutral) and sentence patterns | references/discussion-breakdown.md |
| Older-skill introduction/discussion items, data rules | references/manuscript-guide.md |
| Figures, schemes, prototypes, tables | references/visuals.md |
| Writing style and patterns to avoid | references/style-guide.md |
| Final checks | references/qa-checklist.md |

Read only the files the current stage needs; do not load all of them.

## Where to start: recognize the request mode

Users do not always start from zero. Pick the mode from their message, enter at the matching stage, and do not force every stage.

| Situation | Mode | Start at |
|---|---|---|
| No idea yet | Formulate the idea | Stage 0, then 1 and 2 |
| Has an idea or a draft title | Title review | Stage 3 |
| Has a manuscript (partial or full) | Manuscript review | Stage 10, then the stage of the weak part |
| Asks for a specific section to be written | Write a section | Stage 5, 6, or 8, after the prerequisites below are met |
| Asks for a figure, scheme, or prototype | Design a figure | Stage 7 |
| Asks for the text to be polished so it does not read like a machine | Style polish | Stage 9 |
| Asks for a winning essay's structure to be explained | Breakdown | The relevant part of intro-closing-breakdown.md and discussion-breakdown.md |

Prerequisite before writing any content: the theme, subtheme, manuscript limits, and title are settled. Content written on top of an unsettled title or theme almost always gets thrown away. If the user already supplied all of them, do not ask again.

## Workflow

### Stage 0. Intake and guidelines
Ask only what is still unknown, a few questions at a time at most:
- Competition name, theme, and chosen subtheme
- Page limit (usually 7; range 3-15) and/or word limit (usually 1,500-2,000; some are 300), and whether it includes cover, abstract, references, and appendix
- Required format (font, spacing, margins, section order, citation style), scoring rubric, rules on figures, and rules on AI use or AI-use disclosure
- The initial idea, or ask the user to choose among options you offer
- Location or target group
- [ADDED] Language of the manuscript, if not already clear

### Stage 1. Early research and current issues
Run references/early-research.md: map the current problem within the subtheme, collect core data and a local case, map existing solutions and their gaps, check related regulations, then fill in the research sheet. Skip steps the user has already done. The research sheet is the source for the title, introduction, and discussion.

### Stage 2. The idea: an idea, not research
Test the idea with one question: is this a solution that is PROPOSED for a problem, or an experiment that TESTS the relationship or influence between variables? The second is research and must be reformulated.

How to turn a research idea into an idea essay:
- Replace "Effectiveness/Influence of X on Y" with "Utilization/Optimization of X as a [product/method/system] for [concrete goal]".
- Write results as projections and an implementation design, not as laboratory test data.

Evidence from judge comments is in references/review-cases.md (section "Research-style titles"). Read it if the user objects that their idea or title is being called research. Politely point out when an idea reads like research or falls outside the theme, then immediately offer a corrected idea version; do not just reject.

### Stage 3. Title
The title sets the judge's first impression. Read references/titles.md for the five components, three styles (Style 1/2/3), acronym rules, the list of banned words, and the validation procedure. The title types judges tend to like are in intro-closing-breakdown.md.

In short, a good title: has no research-marker words (influence, effectiveness, efficiency, impact, analysis, study, and similar), targets 20 words with a 25-word ceiling (a mentor annotation on one example essay says 20 maximum; if the guidelines are silent, use 20 as the target), contains the form of the idea + the problem + one main goal (scope optional), fits the theme and subtheme, uses a short acronym with a single meaning and no expansion in parentheses, and has no Latin names or excessive technical detail.

Standard output: a validation table with Pass/Fix (word count, banned words, components, one goal, theme, acronym, ambiguous terms), then 3 alternative titles in Style 1, 2, and 3. In title-review mode, show the table and alternatives straight away without repeating the theory.

### Stage 4. Manuscript limits and allocation
For a 7-page limit, the mentors suggest an introduction of 1.5 pages (2 at most) and a discussion of about 5 pages, with the remaining material moved to the appendix. That total is already close to 7, so ask whether the closing and references count. If they do, shrink the discussion and move supporting tables or figures to the appendix.

[ADDED] Rough spread for a 5-page discussion: B1-B2 0.4; B3 1.3 (including the main figure); B4 1.0; B5 0.8; B6 0.6; B7 0.6; B8 0.3. For a word limit, divide proportionally: introduction about 25-30%, discussion 55-60%, closing the rest. For a very short limit (around 300 words), use only B1, B3 (P1), B4 (P1), and B7.

### Stage 5. Introduction
The introduction is always read by the judges and is the bridge to the discussion. Required content: the problem, urgency, recent data and case (preferably a case from the same year as its data), recent references, fit with the theme and subtheme, novelty and strength of the idea, and the idea's focus and direction of continuation.

Form guidelines: 1.5-2 pages, ideally 5 paragraphs, 3-5 sentences per paragraph, about 30% opinion and 70% data/facts (a rough guide, not a number to count exactly). The function of each paragraph, from the mentor annotations merged with the 5-paragraph pattern, is in references/intro-closing-breakdown.md; data rules are in references/manuscript-guide.md.

Order of functions: the author's argument with data, the shortcomings of the old solution, the opening to break the problem, one potential solution backed by research, then a transition sentence that states the idea in full.

"Recent" is counted from today's date: sources from the last 5 years. Older sources are acceptable with a strong reason (for example, foundational scientific work); case counts and statistics must still be recent.

### Stage 6. Discussion
The longest section and the place to show creativity. Follow the eight blocks in references/discussion-breakdown.md and choose the ones that fit the type of idea:

- B1 Idea overview, B2 Fit with theme and subtheme
- B3 How it works and the design (flow, tools/materials, steps, design advantages; for products: target users, materials, procedure, parties involved, prototype)
- B4 Advantages and differentiators (comparison table, evidence of benefit, where it differs)
- B5 Feasibility (materials/technology/social, economic, policy, challenges and how to overcome them)
- B6 Impact and link to development goals (when relevant to the theme)
- B7 Development projection (short, medium, long term)
- B8 Statement of innovation and creativity

State creativity explicitly: what is new, why it is different, what the benefit is. The discussion stays a design, not a test-results report. One paragraph, one job; each block carries one message the judge must come to believe.

### Stage 7. Figures, schemes, and tables
Read references/visuals.md. Choose one main figure that answers "how does this work" according to the type of idea (device: labeled design; product: prototype; app: user flow; program/system: stage flow or actor scheme), add at most one or two supporting figures, and write the figure's specification (type, labeled elements, caption, source, placement) before producing it. Stage/Activity/Purpose tables, comparison tables, and projection tables are treated like figures: numbered, sourced, and cited in the text.

### Stage 8. Closing, references, appendix
Follow the section order in the competition guidelines. If there is none: closing (return to the key fact once, state the idea as the solution using the title's keywords, the hope for implementation, and concrete recommendations; no new data or arguments), references (consistent with the in-text citations), appendix (supporting material that does not fit, including figures that do not fit the page limit).

### Stage 9. Style polish
Apply references/style-guide.md to finished text: vary sentence length, join runs of short sentences, remove banned vocabulary and phrases, reduce em dashes, replace the "not just X, but Y" pattern, and add details that fit only this idea. If the full anti-AI-writing skill is installed in the same session, follow the full one. The title is exempt from the vocabulary list because it follows the mentor pattern. Do not promise to pass AI detectors, and if the guidelines regulate AI use, follow the guidelines.

### Stage 10. Review and final QA
Apply the mentor correction pattern from the three real cases in references/review-cases.md: remove research words, one goal, short acronym with no expansion, no Latin names in the title, explicit problem and goal, clear scope, definite terms (not "rich in (?)"). Then run references/qa-checklist.md and report only the items that fail, with fixes, so the user is not buried in checkmarks. In manuscript-review mode, start here, then fix the weakest part first.

## Data and honesty rules

Invented numbers, statistics, quotes, and references can get a participant disqualified, so never invent them. When data is missing:
- If a web search tool is available, search official sources (BPS, ministries, regional offices, reputable journals), give the link, and state the year.
- If there is no tool or nothing is found, mark [DATA NEEDED: ...] and tell the user where to look. (In an Indonesian manuscript the original marker is [DATA DIPERLUKAN: ...]; either is fine as long as it is removed before submission.)

Benefit figures from other people's studies are written as those studies' findings; benefit figures for the idea are written as sourced projections or stated assumptions. Claims about efficacy or effect use verbs matched to the strength of the evidence ("is reported to", "has the potential to"). Invented personal stories, quotes, and examples are not allowed; hypothetical examples are labeled as hypothetical.

Write in concise, fact-based, formal language in the manuscript's language. End each stage with a one- or two-line summary of decisions and the next step.

## Important note about the examples

The title bank in references/title-bank.md and the two example essays broken down in references/*-breakdown.md are pattern references, not material to copy. Do not copy titles, ideas, or sentences wholesale, and do not call the examples winning titles or winning essays, because the source material only calls the bank titles "potential winners". Product names and figures in the example essays have been neutralized in the breakdown files; do not put them back into the user's manuscript.
