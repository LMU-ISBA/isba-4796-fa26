# ISBA 4796-01, Fall 2026

Capstone Proposal Development
Loyola Marymount University, College of Business Administration

Start with the [syllabus](syllabus.md), also available as a
[PDF](isba-4796-syllabus-fa26.pdf).

You leave this course with an approved capstone proposal, a development
environment and project repository you built yourself, and enough Scrum to run
the first sprint of ISBA 4797.

## When we meet

The course holds the Tuesday/Thursday 9:55 to 11:35 AM slot, and uses eight
Thursdays. Keep the time free and come on these dates.

| Date | What | Room |
|---|---|---|
| Thu Sep 3 | What the capstone expects of you, then this syllabus. Joint with ISBA 3720 | Hilton 106 |
| Thu Sep 24 | Framing a problem worth solving, and the interview it exposes | Hilton 106 |
| Thu Oct 1 | Discovery and stakeholder engagement | Hilton 106 |
| Thu Oct 29 | Writing the PRD | Hilton 106 |
| Thu Nov 12 | Agile and Scrum in practice. Project briefs go out and teams form. Joint with ISBA 3720 | Hilton 106 |
| Thu Nov 19 | Sprint planning | Hilton 106 |
| Thu Dec 3 | Stand-up | Hilton 106 |
| Thu Dec 10 | Sprint review and the retrospective | Hilton 106 |

Plus one 15-minute individual meeting on Zoom in week 2, which you book.

Both joint sessions put you in Hilton 106 with ISBA 3720 on Zoom. Come to the
room.

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
| Thu Oct 29 | Practice wiki |
| Thu Nov 12 | Projects assigned and teams form |
| Fri Nov 13 | Last day to withdraw |
| Thu Nov 19 | Stakeholder confirmation |
| Thu Dec 10 | Capstone wiki and final PRD |

This repository is read-only for students. Your work lives in your own capstone
project repository.

## Regenerating the syllabus PDF

After editing `syllabus.md`, rebuild the PDF with the shared script:

```bash
uv run ~/.claude/skills/pdf-generation/generate_pdf.py syllabus.md -o isba-4796-syllabus-fa26.pdf
```
