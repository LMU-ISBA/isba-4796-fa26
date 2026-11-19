# Capstone kickoff

ISBA 4796 and ISBA 3720 | November 19, 2026 | Hilton 115

You have a project, a team, and a faculty advisor. Between now and Dec 10, your
job is to understand the problem well enough to scope it. You won't build
anything yet.

If your capstone is an internship or your own project, you're a team of one. Do
every step below for your own project, and trade briefs with a partner today.

## What this repository is for

This repository is your team's working record of the project. It holds your
brief, your interview notes, and your research. In the spring it holds what you
build.

Your faculty advisor follows your progress here. At the end of the capstone,
you hand the repository over to your stakeholder. Write and organize it so
someone outside your team can pick it up.

## Keep it private

Set your repository to private. Only your teammates, Prof Lontok, and Prof
Mukherjee get access. If your faculty advisor is someone else, add them too.
Add your stakeholder when they ask for it.

Your stakeholder also has a say in where the work lives. Some organizations
require their own tools. In your first conversation, ask whether a private
GitHub repository is acceptable, and tell them you'll hand it over at the end.
Until they agree, keep only your own notes and made-up data here.

## Set up your repository

One driver per team does steps 1 to 8. Every teammate does steps 9 and 10.

1. Sign in to GitHub.
2. Open the template:
   https://github.com/LMU-ISBA/isba-capstone-starter-template
3. Select "Use this template" at the top right, then "Create a new repository."
4. Choose the driver's account as the owner.
5. Name the repository `isba-capstone-[project]-s27`, like
   `isba-capstone-campus-dining-s27`.
6. Set the visibility to "Private".
7. Select "Create repository."
8. Open "Settings," then "Collaborators," then "Add people." Add every teammate
   by GitHub username. Add both instructors too: `lontok` for Prof Lontok and
   `sam-lmu` for Prof Mukherjee. Every team adds both.
9. Accept the invitation today, before you leave class. It arrives by email
   and at https://github.com/notifications. An invitation expires after seven
   days, and then the driver has to send it again.
10. Copy the repository's URL from its "Code" menu. In a terminal, type
    `git clone`, a space, and the URL. Then run the command.

If you don't see "Use this template," you aren't signed in.

## Team

Fill in this section in your team's own repository, not in the template.

1. Open `README.md` in the repository you cloned. This is the file you're
   reading now.
2. Type your answer after the colon on each line below.
3. Save the file.
4. Commit and push, with a message that starts with `TASK-1`.

Leave "Recorded presentation link" empty until Dec 10.

- Project:
- Team members, full names:
- Faculty advisor:
- Stakeholder, with role and organization:
- Weekly meeting time through Dec 10:
- Spring meeting block:
- How we reach each other:
- Driver today:
- Stakeholder agreed to this repository: not yet asked
- Recorded presentation link:

## What's in this repository

- `PRD.md` is your one-page initial product brief.
- `stakeholder/email.md` asks your stakeholder for a first conversation.
- `stakeholder/interview-guide.md` is how to run that conversation.
- `stakeholder/interview-notes-template.md` is the page you copy and fill in
  after each conversation.
- `stakeholder/confirmation.md` asks your stakeholder to confirm the problem in
  writing.
- `TASKS.md` tracks your tasks, their owners, and their due dates.
- `standups/` holds each teammate's written stand-up. Copy
  `standups/stand-up-template.md` and name your copy
  `YYYY-MM-DD-first-last.md`.
- This README holds your team details.

## Tasks

Your work is tracked in `TASKS.md`. Start with TASK-1 today.

These dates matter:

- Thu Nov 19, in class: TASK-1, TASK-2, and TASK-3.
- Two business days after your advisor says to send: TASK-4.
- Thu Dec 3: TASK-5, your written stand-up.
- Thu Dec 10, 11:59 PM: TASK-6, TASK-7, and TASK-8.

## Working together in this repository

Your advisor reads the `main` branch on GitHub. Work that isn't on `main`
isn't handed in.

- Work on `main` this term. You don't need branches until you build in the
  spring.
- Pull the latest changes before you start.
- Commit and push each time you finish something. Small commits are fine.
- Start each commit message with the task ID, like `TASK-3: Draft the brief`.
- If GitHub rejects your push, pull again and then push.
- Don't edit the same file as a teammate at the same time. Agree on one editor
  for `PRD.md` and `TASKS.md` in each work session.
- If you do use a branch, merge it into `main` before the due date.

You can ask Claude Code to do the Git steps:

```text
Pull the latest changes. Show me what I changed and explain what will be committed.
Wait for my review, then commit with a message that starts with the task ID and push to main.
```

## Due Thu, Dec 10, 11:59 PM

Everything is in this repository. Each student also submits links, so your
instructor knows where your work is.

- ISBA 4796 students submit in Brightspace: the repository link on Thu Nov 19,
  the link to your own stand-up on Thu Dec 3, and the repository and recording
  links on Thu Dec 10.
- ISBA 3720 students follow Prof Mukherjee's instructions.

The repository holds:

- Your preliminary PRD in `PRD.md`, with unconfirmed claims marked.
- Your interview notes in `stakeholder/`, or a note that the conversation moved
  to January.
- Your stakeholder's reply in `stakeholder/`, if you have it.
- `TASKS.md` with every task in the right section and its evidence filled in.
- Each teammate's stand-up in `standups/`.
- The link to your recorded presentation in the Team section above.

## Rules for this repository

- Keep the repository private.
- Don't commit an employer's or client's data, credentials, or internal
  documents.
- Use made-up data in any example.
- Don't give access to anyone outside your team, your instructors, your
  advisor, and your stakeholder.
- Keep every teammate's name in the Team section current.
