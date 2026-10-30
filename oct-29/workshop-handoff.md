# Workshop handoff prompt

This prompt incorporates the October 29, 2026 Granola meeting notes titled
"Capstone project requirements and interview practice with family law firm."
It distinguishes the planned activity from what the notes document.

---

Help me adapt a stakeholder-discovery workshop for another university class.
Act as an instructional designer and product-management coach. Keep the
activity practical, simple, and discussion-centered.

Start by asking which course this is for, how long the session lasts, and
what students already know about GitHub and Claude Code. Then help me make
one planning decision at a time. Don't generate an entire teaching package
immediately.

## Context

The original ISBA 4796 workshop used this GitHub template:
https://r.isba.co/hearing-prep

Students practiced moving from an ambiguous stakeholder request to an
evidence-based product proposal. The instructor played an anonymous
family-law office manager. Four groups participated in one shared interview,
then developed separate proposals.

The central lesson: a stakeholder's requested solution may differ from the
underlying problem. Students must investigate before recommending what to build.

## Case background

The initial request was help preparing printed hearing binders. These contain
documents attorneys need in court and must be ready by 3 PM the previous day.

Reveal the following through student questions, rather than giving everything
away upfront:

- Staff search across Google Drive, Gmail, Box, and PracticePanther.
- Box-to-Drive transfers are manual, and documents may never reach Drive.
- Filenames and folder structures vary across attorney teams.
- Staff struggle to identify the correct document version.
- Binder contents depend partly on staff experience and attorney judgment.
- A preparation checklist exists but isn't consistently followed.
- Previous naming standards failed to stick after one-time training.
- PracticePanther adoption and training are incomplete.
- Confidentiality, approved tools, and restricted device access constrain possible solutions.

These are findings recorded during the classroom role-play, informed by a
real project. They aren't independently verified requirements for a new
implementation.

Keep the firm anonymous. Use fictional documents and names. A messy example
folder can be revealed midway through the interview.

## Original activity

1. Each group chooses one computer driver, creates a public repository from
   the template, and clones its own repository.
2. The class interviews the instructor using EXAMPLE → EXPLORE → REFLECT → NEXT.
   Designated interviewers lead questions while teammates take notes.
   Everyone may contribute follow-ups.
3. Groups interpret their notes without AI, distinguishing evidence,
   assumptions, and unanswered questions. The class agrees on a provisional
   shared problem.
4. Groups paste their notes into Claude Code and use Superpowers brainstorming
   to explore approaches and draft PRD.md.
5. Groups review every claim and explain their decisions.
6. If time permits, groups create one mockup.html screen or workflow using
   fictional data.
7. Students ask Claude Code to review changes, then commit and push after
   group approval.
8. Groups defend their proposals in their own words. Any member may receive
   a question.

The intended outputs were a one-page product brief, a simple mockup, and a
public repository listing all members. Private reflections weren't submitted.

## What the class notes document

The notes confirm the interview, AI-assisted PRD drafting, and comparison of
group proposals. They don't confirm that every group completed a mockup or
formal defense.

Groups identified document retrieval and organization as major contributors
to late preparation. Proposed approaches included a hearing tracker, a linked
document index, cross-platform search, and automatic file transfer. Treat
these as alternatives to investigate.

Baselines and targets remained unknown. Don't invent search-time savings or
on-time completion rates. File modification timestamps were suggested as a
possible measurement proxy, but they don't necessarily prove a binder was ready.

## Lessons to preserve

Question quality and note quality shape the proposal. Include a recent-example
question and a workflow walkthrough.

Distinguish who performs the work from who approves the result. Check existing
tools and adoption problems before proposing custom software.

Keep the PRD to six sections: problem and users, evidence, desired outcome,
proposed solution, scope, and open questions.

Use AI to question and draft. Students remain responsible for the reasoning.
Don't add a charter, detailed feature specification, implementation plan, or
working application to this introductory exercise.

Help me adapt this activity to the new class while preserving its focus on
evidence and defensible decisions.
