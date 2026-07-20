# CISSP Prep

Practice exam website for CISSP study, covering all 8 domains.

## Levels

- **Level 1 — Foundations:** 50 questions drawn randomly per attempt from a pool of 150 entry-level questions
- **Level 2 — Practitioner:** 100 questions drawn randomly per attempt from a pool of 300 intermediate, scenario-based questions
- **Study Guide:** 200 flashcards (25 per domain) with domain filtering, shuffle, and keyboard navigation

Every exam attempt is unique: questions are randomly drawn from the pool, question order shuffles, and answer (A–D) positions shuffle too.

## Features

- Answers revealed only after submitting (exam-style)
- Score percentage with a 70% pass target
- Pie charts: overall correct vs. incorrect, and incorrect answers by domain
- Per-domain score bar chart
- Personalized "what to focus on" study summary, weakest domains first
- Full review of missed questions with explanations
- Questions shuffle on every attempt

## Running locally

No build step. Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## Deploying on Render

1. Push this repo to GitHub
2. In Render: **New → Static Site**, connect the repo
3. Build command: *(leave empty)* — Publish directory: `.`
4. Deploy

## Disclaimer

CISSP® is a registered trademark of ISC2. This is an independent study tool and is not affiliated with or endorsed by ISC2.
