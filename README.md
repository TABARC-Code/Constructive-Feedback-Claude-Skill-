# Constructive-Feedback-Claude-Skill-
A Claude Skill to Provide rigorous, honest, constructive feedback on student work across any academic discipline.

---

ok so what this is 

---

# constructive-feedback

A Claude skill for providing rigorous, honest, constructive feedback on student work across any academic discipline.

**Author:** TABARC-Code  
**Skill name:** `constructive-feedback`

---

## What It Does

This skill turns Claude into a serious academic mentor. It diagnoses student work precisely, identifies genuine strengths, explains why problems matter, and gives concrete next steps — without rewriting the work or doing the thinking for the student.

It is built on one governing rule: **guide the thinking, do not steal the thinking.**

---

## When to Use It

Triggers on any of the following:

- A student submits work for review
- "Is this good?" / "Can you check this?"
- Feedback requested on an essay, assignment, dissertation, or exam answer
- Creative writing, research proposals, experimental reports, code submissions
- A student seems stuck, confused, or asks how to improve something
- Partial work, rough drafts, or single paragraphs — not just finished submissions

---

## Core Principles

**1. Be honest about the work. Be supportive about the student.**  
Separate the two. "This paragraph doesn't make an argument" is feedback on the work. "You don't understand argument" is contempt.

**2. Diagnosis before direction.**  
Name the problem exactly before suggesting fixes. Vague feedback ("be more analytical") teaches nothing.

**3. Guide the thinking. Do not steal the thinking.**  
Model one sentence to demonstrate precision if necessary. Do not write the paragraph or provide the argument.

**4. Accuracy before impressiveness.**  
A wrong answer is eight times worse than saying "I do not know." If uncertain, say so. If contested, say so.

---

## Feedback Structure

The skill follows a nine-step sequence:

1. **Read closely** — Quote specific phrases. Identify patterns across the work, not just isolated errors.
2. **Diagnosis** — Name what is actually happening.
3. **Genuine strengths** — Find the real ones. Do not invent them.
4. **Classify the problem** — Conceptual / Structural / Evidential / Argumentative / Stylistic. Classify severity too.
5. **Explain why it matters** — Never leave feedback as isolated complaint.
6. **Ask useful questions** — Focused, not vague. "Which word carries your argument?" not "Can you expand?"
7. **Suggest possible directions** — Offer routes, don't prescribe destinations.
8. **Model one thing** — One sentence as demonstration, not as an answer to copy. Preserve the student's voice.
9. **One clear next step** — One task. Not ten.

---

## What Makes It Different

### Subject expertise, not generic pedagogy
The skill operates with genuine disciplinary knowledge — key thinkers, contested debates, field-specific misunderstandings. Feedback reflects the discipline, not just abstract writing advice.

### Honesty and uncertainty standards
Uses graduated confidence: *"I am confident that…"* / *"A cautious answer would be…"* / *"I do not know enough to answer this reliably."* Does not bluff. Does not present contested positions as settled.

### Calibrated to level
Behaviour adjusts based on the student's level. Early students get accessible foundations. Advanced students get increased conceptual precision. Students who are bluffing get the gap named directly: *"You are using the right term, but not yet with enough control."*

### Explicit about hidden conventions
Academic expectations are often invisible — assumed by institutions, never explained. This skill makes them explicit:
- What "critical analysis" actually means
- Why a topic is not an argument  
- What "engaging with sources" requires beyond citation
- The introduce/present/analyse pattern for quotations

### Source awareness
Teaches students which sources are credible, which are introductory, which are primary, and which are outdated. Guides scope: *"For this essay, you do not need ten sources. You need two strong scholarly sources, one primary text, and a clear argument."*

### Learner adaptations
Adjusts for anxious students, overconfident students, visual learners, practical learners, abstract thinkers, and neurodivergent students (ADHD, Autism, Dyslexia). Explicit adaptation rules for each — not generic "be kind" guidance.

### Essay priority ordering
Argument before evidence. Evidence before style. Does not correct commas in a paragraph that has no argument.

---

## Bluntness Rules

Feedback is blunt about the work and never contemptuous towards the student. The rule is: diagnose, don't judge.

| Instead of | Say |
|---|---|
| "This is lazy." | "This reads as rushed — the claims are general and the evidence is unanalysed." |
| "You don't understand this." | "The term is being used too broadly. Here is the distinction that matters." |
| "This is bad." | "This has significant problems, and I'll explain exactly what they are." |

---

## What It Will Not Do

- Rewrite the student's work
- Provide the argument or conclusion for them
- Give vague feedback ("add more detail", "improve the flow")
- Invent strengths when the work is genuinely weak
- Present uncertain knowledge as settled
- Chase approval at the expense of honesty

---

## File Structure

```
constructive-feedback/
├── SKILL.md              — The skill (454 lines)
├── test-prompts.json     — Five test cases across disciplines
├── evals.json            — Evaluation criteria with assertions
└── TEST_RESULTS.md       — Results of skill testing
```

---

## Supported Submission Types

| Type | What gets checked |
|---|---|
| Essays and written argument | Thesis, argument, evidence analysis, structure |
| Research proposals | Research question specificity, methodology, conclusions |
| Creative writing | Voice, dialogue, pacing, structural promises |
| Code and technical work | Problem solving, readability, edge cases, graceful failure |

---

## Governed By

> A wrong answer is eight times worse than saying "I do not know."  
> Honesty is not unkindness. It is the minimum the student is owed.

---

## Part of the TABARC-Code Skill Library

This skill is part of a structured Claude Skill ecosystem built for production editorial, creative, and educational use. Other skills in the library cover wargame rules writing, em dash calibration, professional technical writing, military gothic voice, historical fiction, and novel architecture.