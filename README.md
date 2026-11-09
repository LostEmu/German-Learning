# German Learning Journey — A0 → C1

A structured, long-term programme for learning German, from absolute beginner (A0) to advanced (C1).

- **Target variety:** Standard German (*Hochdeutsch*) first. Swiss German (*Schweizerdeutsch*) is introduced gradually from about B1/B2.
- **Long-term goal:** to live, study and work in Zurich, including a possible MSc in Computational Science and Engineering at ETH Zurich.
- **Learner background:** Australian undergraduate (BEng (Hons) Electrical & Electronic Engineering + BSc Physics). Studied French at school.

This repository is the **permanent source of truth** for the programme: textbook, curriculum, exercise bank, assessment record and progress tracker. Teaching happens in conversation with my tutor (Claude). Everything taught, practised and assessed is recorded here.

---

## Current status

| | |
|---|---|
| **Current CEFR level** | A0 (absolute beginner) |
| **Working towards** | A1 |
| **Lessons completed** | 0 |
| **In progress** | Lesson 0 (Alphabet & Pronunciation) and Lesson 1 (Greetings & Introductions). Guided exercises set, waiting for answers |
| **Assessments taken** | None yet |
| **Next milestone** | Cumulative Assessment 1 (after Lesson 5) |
| **Recommended next step** | Complete the [Lesson 0](exercises/A1/lesson-00-exercises.md) and [Lesson 1](exercises/A1/lesson-01-exercises.md) guided exercises |

_Last updated: 2026-11-09._ Full detail: [progress/progress-tracker.md](progress/progress-tracker.md)

---

## How the programme works

### The lesson cycle
Every lesson follows the same nine steps:

1. **Learning objectives**: what you will learn and why it matters
2. **Concept explanation**: thorough, in English at first, with more German as you improve
3. **Examples**: German sentences with English translations
4. **Grammar breakdown**: *why* each sentence is built the way it is
5. **Vocabulary**: every noun with its article and plural; every verb with its conjugation
6. **Guided exercises**: getting gradually harder
7. **Independent assessment**: applying the material without help
8. **Corrections**: every mistake explained, with the correct reasoning
9. **Revision**: spaced review of earlier material

A lesson counts as **completed** only after step 8. Moving on depends on demonstrated competence, not on the number of lessons done.

### Assessment schedule

| Frequency | Assessment | Stored in |
|---|---|---|
| Every lesson | Independent assessment (lesson test) | [`assessments/lesson-tests/`](assessments/lesson-tests/) |
| Every 5 lessons | Cumulative assessment | [`assessments/cumulative-tests/`](assessments/cumulative-tests/) |
| Every 10 lessons | Major exam: grammar, vocabulary, reading, writing | [`assessments/cumulative-tests/`](assessments/cumulative-tests/) |
| End of each level | CEFR checkpoint (exam-style) | [`assessments/CEFR-assessments/`](assessments/CEFR-assessments/) |

Marking is strict. Pass marks, the mastery scale and the writing rubric are set out in [assessments/README.md](assessments/README.md).

### Mastery scale
`Not started → Introduced → Practising → Secure → Mastered`

A topic is **Mastered** only when it has been applied correctly in *free production* on at least two separate occasions, at least one of them a cumulative test taken a week or more after the lesson.

---

## Repository map

```
├── README.md                  ← you are here (current status + overview)
├── curriculum/                ← level-by-level syllabus (A1, A2, B1, B2, C1), revised as weaknesses appear
├── lessons/<level>/           ← complete lesson notes, one file per lesson
├── grammar/                   ← growing grammar reference, updated as topics are taught
├── vocabulary/                ← vocabulary database (gender, plural, conjugation, translation)
├── exercises/<level>/         ← exercise sheets (no answers)
│   └── solutions/             ← model answers, added only AFTER you submit your attempt
├── assessments/               ← lesson tests, cumulative tests, CEFR checkpoints + results
├── progress/                  ← progress tracker, completed lessons, mistakes log, vocab review
└── resources/                 ← listening, reading and external resources
```

## How to study with this repository

1. **Before each lesson:** review the vocabulary that is due in [progress/vocabulary-review.md](progress/vocabulary-review.md).
2. **During a lesson:** attempt every exercise *before* looking anything up. Answers go in the chat.
3. **After a lesson:** re-read the lesson's *Summary and revision notes*, add the new words to your flashcards (Anki is recommended), and read your entries in the [mistakes log](progress/mistakes-log.md).
4. **Solutions** are committed only after you have submitted an attempt, so you can never accidentally see the answers first.

## Quick links

- Pronunciation reference: [Lesson 0: Alphabet & Pronunciation](lessons/A1/lesson-00-alphabet-and-pronunciation.md)
- Current lesson: [Lesson 1: Greetings & Introductions](lessons/A1/lesson-01-greetings-and-introductions.md)
- Syllabus: [A1](curriculum/A1.md) · [A2](curriculum/A2.md) · [B1](curriculum/B1.md) · [B2](curriculum/B2.md) · [C1](curriculum/C1.md)
- Tracking: [Progress](progress/progress-tracker.md) · [Completed lessons](progress/completed-lessons.md) · [Mistakes](progress/mistakes-log.md) · [Vocabulary review](progress/vocabulary-review.md)
