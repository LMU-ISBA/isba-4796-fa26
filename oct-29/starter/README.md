# From discovery to a product brief

ISBA 4796 | October 29, 2026 | 9:55-11:35 AM | Hilton 106

A family-law firm wants help preparing hearing binders containing documents
its attorneys need. Staff need the materials ready by 3 PM the day before a
hearing. The instructor will play the office manager.

Interview the instructor to understand how preparation works, where difficulties occur,
and what improvement would mean. Understand the problem before proposing a
solution. The case is anonymous, and any example documents are fictional.

You'll work in four groups, with five or six students per group. Choose one
driver to operate the computer throughout class. Everyone contributes questions,
reviews the proposal, and prepares to answer questions during the defense.

## Group members

Replace this line with your group number and every group member's full name.

## What you'll produce

- Develop a one-page initial product brief in `PRD.md`.
- Create `mockup.html` to illustrate your proposal and test an assumption.
- Commit and push your draft before presenting.
- Write an individual reflection after the discussion.

Your brief is an early PRD. You won't create a separate project charter,
feature spec, or implementation plan today. This exercise prepares you for
your capstone proposal without adding a new graded assignment.

## 10:00-10:10: Set up your group repo

Only the driver needs to clone the repo. Start with this template:
https://github.com/LMU-ISBA/isba-4796-hearing-prep-template

1. Open the template on GitHub.
2. Select "Use this template," then "Create a new repository."
3. Choose the driver's account as the owner.
4. Name the repo `isba-4796-hearing-prep-g1`, replacing `g1` with your group number.
5. Set the repository visibility to "Public".
6. Create the repository from the template.
7. Copy your new repo's URL from its "Code" menu.
8. Open a terminal in your usual project folder.
9. Type `git clone`, a space, and the copied URL.
10. Run the command.
11. Open the cloned folder in your editor.
12. Open a terminal in that folder and start Claude Code.

Add every group member's full name to the "Group members" section of this README.

Check that the folder contains `CLAUDE.md`, `README.md`, and `PRD.md`.
Ask for help if access fails. Continue with local files if the instructor
calls the fallback, so setup doesn't consume the interview.

## 10:10-10:35: Interview and agree on the problem

Use the first three minutes to prepare an opening question and possible
follow-ups. There is one twelve-minute interview for the whole class, using
Example, Explore, Reflect, and Next.

One group asks the opening question. All four groups contribute follow-up
questions and take their own notes. The instructor calls on different groups
as the conversation develops. Let the answers guide your next question.

Take brief notes in any app you prefer during the interview.
Use quotation marks only for words you recorded accurately.

After the interview, spend five minutes answering these questions without AI:

- Who is having difficulty, and what are they trying to do?
- What did we hear that supports our interpretation?
- What do we still need to confirm?

The class then has five minutes to agree on one shared problem. Record that
statement in your notes. Groups may propose different solutions to it.

## 10:35-10:55: Develop the product brief

Review your notes together, then paste them at the end of this prompt in
Claude Code:

```text
/superpowers:brainstorming
Read our interview notes below and help us understand the problem.
Ask us one question at a time to explore possible approaches and what we still need to learn.
Once we agree on an approach, draft PRD.md for our review.

[Paste your group's interview notes here]
```

Read the result together before accepting it. Correct claims that go beyond
your evidence, and explain why you chose this approach. The group's agreement
doesn't establish that a real stakeholder has validated the proposal.

## 10:55-11:05: Visualize and commit the draft

After reviewing the brief, use this prompt:

```text
Read PRD.md and suggest a simple visual that would help us explain our proposal.
Ask us what we want to show before creating a single mockup.html file with fictional data.
```

Spend at most eight minutes on the mockup. Open `mockup.html` in a browser and
check that it agrees with your brief. Use the remaining time to save a commit.

Ask Claude Code to help save your draft:

```text
Show us the changes in README.md, PRD.md, and mockup.html and explain what will be committed.
Wait for our review, then commit with the message "Draft product brief and concept mockup" and push to GitHub.
If mockup.html doesn't exist, commit only README.md and PRD.md.
```

Review the changes together before telling Claude Code to proceed.

A commit saves a local checkpoint. Pushing copies it to GitHub. If pushing
fails, keep the local commit and ask for help.

Check the public GitHub repo for the latest commit and draft files. Confirm
that the README lists every group member's full name.

One person per group posts the public repo link in the class Teams channel:
https://teams.microsoft.com/l/channel/19%3AHOfl44oya2Y6zy3jfQOg03qdCjWxwXusvxTkwHqaHkY1%40thread.tacv2/General?groupId=03a3e50e-3b80-4675-904e-11651fc51b6d&tenantId=0376eb4b-c206-4056-9061-e342dc2ecda8

## 11:05-11:25: Present and defend

Each group has two minutes to present and three minutes for questions. Show
the mockup while explaining the choices in your brief. Keep the brief available
for reference, and answer questions in your own words without asking Claude.

Explain the problem, the supporting evidence, and why you chose this approach.
Name an assumption you still need to test. Any group member may receive a
question, even if someone else presents.

## 11:25-11:32: Continue presentations and questions

This time is reserved for presentation overflow and additional questions.
Capture useful feedback in your notes for the reflection.

## 11:32-11:35: Reflect individually

Write two or three sentences without AI:

> What's one decision your group made, and what did you hear in the interview
> that supports it? After the discussion, what would you change or investigate
> next, and why?

Submit your own response where the instructor directs.

## If the tools fail

Discuss the six PRD questions as a group and write the brief manually. Sketch
the proposal on paper if the mockup can't be generated. Keep your local work
if GitHub is unavailable, and tell the instructor which step needs follow-up.

If you couldn't clone the repo, save the files and ask the instructor for help with Git.
The instructor will help you complete that step later.
