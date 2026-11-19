# ISBA 4796-01, Fall 2026

Capstone Proposal Development
Loyola Marymount University, College of Business Administration

Start with the [syllabus](syllabus.md), also available as a
[PDF](isba-4796-syllabus-fa26.pdf).

You leave this course with an approved capstone proposal, a development
environment and project repository you built yourself, and enough Scrum to run
the first sprint of ISBA 4797.

## When we meet

The course holds the Tuesday/Thursday 9:55 to 11:35 AM slot, and uses six
Thursdays. Keep the time free and come on these dates. The Thu Nov 12 session
is canceled, and the Thu Dec 3 stand-up is written.

| Date | What | Room |
|---|---|---|
| Thu Sep 3 | What the capstone expects of you, then this syllabus. Joint with ISBA 3720 | Hilton 106 |
| Thu Sep 24 | Framing a problem worth solving, and the interview it exposes | Hilton 106 |
| Thu Oct 1 | Discovery and stakeholder engagement | Hilton 106 |
| Thu Oct 29 | Writing the PRD | Hilton 106 |
| Thu Nov 12 | Canceled. Project briefs and team formation move to Thu Nov 19 | none |
| Thu Nov 19 | Projects are assigned, teams form, and each project gets a faculty advisor. You start scoping. Joint with ISBA 3720 | Hilton 115 |
| Thu Dec 3 | No meeting. Commit your written stand-up to your capstone repository | none |
| Thu Dec 10 | Questions on your project, the retrospective, and handoff to ISBA 4797 | Hilton 106 |

Plus one 15-minute individual meeting on Zoom in week 2, which you book.

The second joint session with ISBA 3720 moved from Thu Nov 12 to Thu Nov 19, in
Hilton 115.

## November 19: Capstone kickoff

You get your project, your team, and your faculty advisor. One driver per team
creates a private repository from this template:
https://github.com/LMU-ISBA/isba-capstone-starter-template

Start with TASK-1 in `TASKS.md`. The template's README explains what the
repository is for and what you hand in on Thu Dec 10.

## October 29: From discovery to a product brief

Start with the [session instructions](oct-29/README.md). We'll announce next
week's project and internship survey, interview a stakeholder, and develop an initial
product brief with an HTML mockup. Each group will defend its proposal, followed by individual reflections.

One driver per group will create and clone a repository during class using
this template:
https://github.com/LMU-ISBA/isba-4796-hearing-prep-template

## October 1: Discovery and stakeholder engagement

Use these worksheets on your computer; no printouts are needed.

- [Student workbook](oct-1/student-workbook.html): conversation guide,
  interview notes, feedback, and reflection. Each student completes their own.
- [Group recap](oct-1/group-recap.html): one recorder captures the group's
  findings after everyone checks the account.

Open each file on GitHub and click **Download raw file**, then open the downloaded
HTML file in your browser. After your interview and at the end of class, use
**Save editable copy** to keep your answers. Reopen that saved copy to continue.
Use **Download text for submission** and submit the text file through the
location announced in class. Downloading does not submit your work.

## Dates that decide things

| | |
|---|---|
| Tue Sep 8 | [Self-discovery interview](self-discovery-interview.md) |
| Tue Sep 22 | AI Dev Workflow Tutorial |
| Thu Oct 22 | Internship secured |
| Fri Nov 13 | Last day to withdraw |
| Thu Nov 19 | Projects assigned, teams form, and capstone repository created |
| Thu Dec 3 | Written stand-up |
| Thu Dec 10, 11:59 PM | Stakeholder confirmation, preliminary PRD, and recorded presentation |

This repository is read-only for students. Your work lives in your own capstone
project repository.

## Regenerating the syllabus PDF

After editing `syllabus.md`, rebuild the PDF with the shared script:

```bash
uv run ~/.claude/skills/pdf-generation/generate_pdf.py syllabus.md -o isba-4796-syllabus-fa26.pdf
```
