# Idea Essay Skills for Claude

Claude skills that help students write idea-based scientific essays in English.

| Skill | Language of the instructions | Folder |
|---|---|---|
| `esai-gagasan-lomba` | Bahasa Indonesia | `esai-gagasan-lomba/` |
| `idea-essay-competition` | English | `idea-essay-competition/` |

## The problem

These competitions don't want a research report. They want a proposed solution to a real problem, such as a product, an app, a program or a method. A lot of entries lose points before the judges reach the content. The title says "Effectiveness of X on Y", so the whole manuscript gets read as a thesis. Or the idea drifts outside the theme. Or the problem in the title never comes back in the discussion.

The people who know these conventions are mostly mentors, and they teach them in bootcamps and recorded sessions. A student then has to remember all of it while writing alone at midnight before the deadline. These skills turn that teaching into steps Claude can follow with the student.

## What a session looks like

You can enter at any point. Claude works out where you are from your message and starts there.

| You bring | Claude starts with |
|---|---|
| Nothing yet | Reading the competition guidelines, then finding a current problem and shaping an idea |
| A draft title | A validation table (word count, banned words, one goal, theme fit) and three rewritten titles |
| A full manuscript | A QA pass that reports only the items that fail, weakest section first |
| A request for one section | The introduction, a discussion block, or the closing, once theme and title are settled |
| A request for a figure | A written spec for one main figure, chosen by type of idea |
| A finished draft that sounds mechanical | A style pass that varies sentences and cuts stock phrases |

The full workflow has eleven stages, numbered 0 to 10, from intake to final QA.

## Rules built in

- **An idea, not research.** The structure has no hypotheses, variables or statistical tests.
- **Stay inside the theme and subtheme.**
- **One common thread.** The problem named in the title comes back in the data, the design, the advantages, the impact and the closing, in the same words.
- **The competition's own guidelines win** when they conflict with the skill.
- **No invented data.** A missing statistic is marked `[DATA NEEDED: ...]` (or `[DATA DIPERLUKAN: ...]` in the Indonesian skill), with a note on where to look. A fabricated citation can get an entry disqualified.
- **No promise about AI detectors.** If a competition restricts AI use or asks for disclosure, follow it.

## Where the method comes from

The method is built from mentor teaching material: Royhan Saydi's essay bootcamp (ANSA Academy) and the "Bedah Esai" material from Muda Kompetisi, which annotates two example essays. Anything I added myself is tagged `[ADDED]` in the English skill and `[TAMBAHAN]` in the Indonesian one.

The title bank and the essay breakdowns are pattern references. Don't copy them into a manuscript. The skills codify what those mentors say tends to decide scores; they can't promise a win, because the quality of the idea, the data and the guidelines still decide.

## Repository layout

Both skills share one structure: a `SKILL.md` with the workflow and ten files under `references/` that Claude opens only when a stage needs them.

```
idea-essay-competition/
├── SKILL.md
└── references/
    ├── early-research.md
    ├── titles.md
    ├── title-bank.md
    ├── review-cases.md
    ├── intro-closing-breakdown.md
    ├── discussion-breakdown.md
    ├── manuscript-guide.md
    ├── visuals.md
    ├── style-guide.md
    └── qa-checklist.md
```

The style file in each skill is a short backup. If a full anti-AI-writing skill is installed in the same session, Claude follows that one instead.

## Install

Claude Code: copy the skill folder into `~/.claude/skills/`, so that `SKILL.md` ends up at `~/.claude/skills/idea-essay-competition/SKILL.md`.

Or you could just upload the skills

Then start a chat with something like "Help me write an idea essay for [competition name]" or "Check this title against the rules".

## Author

M Reza Adriansyah · +62 852-8265-8277

## License

  MIT License
