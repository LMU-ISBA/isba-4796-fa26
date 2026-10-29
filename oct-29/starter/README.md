# From discovery to a product brief

ISBA 4796 | October 29, 2026 | 9:55-11:35 AM | Hilton 106

A family-law firm wants help preparing hearing binders containing documents
its attorneys need. Staff need the materials ready by 3 PM the day before a
hearing. Greg will play the office manager.

Interview him to understand how preparation works, where difficulties occur,
and what improvement would mean. Understand the problem before proposing a
solution. The case is anonymous, and any example documents are fictional.

You'll work in four groups, with five or six students per group. Choose one
driver to operate the computer throughout class. Everyone contributes questions,
reviews the proposal, and prepares to answer questions during the defense.

## What you'll produce

- Record evidence, interpretations, and open questions in `interview-notes.md`.
- Develop a one-page initial product brief in `PRD.md`.
- Create `mockup.html` to illustrate your proposal and test an assumption.
- Commit a draft before presenting and a revision after feedback.

Your brief is an early PRD. You won't create a separate project charter,
feature spec, or implementation plan today. This exercise prepares you for
your capstone proposal without adding a new graded assignment.

## 9:55-10:00: Review the internship option

An internship used for your capstone should have been secured by October 22.
Confirm your status with Greg. Be ready to explain the problem you could
address through the internship and who could validate your work.

The internship itself doesn't define the capstone proposal. You'll still need
a stakeholder-confirmed problem, a measure of success, and the course deliverables.
If you didn't secure an internship by the deadline, you'll receive a project
assignment on November 12.

## 10:00-10:10: Set up your group repo

Only the driver needs to clone the repo. Start with this template:
https://github.com/LMU-ISBA/isba-4796-hearing-prep-template

1. Open the template on GitHub.
2. Select "Use this template," then "Create a new repository."
3. Choose the driver's account as the owner.
4. Name the repo `isba-4796-hearing-prep-g1`, replacing `g1` with your group number.
5. Use the visibility Greg specifies.
6. Create the repository from the template.
7. Copy your new repo's URL from its "Code" menu.
8. Open a terminal in your usual project folder.
9. Type `git clone`, a space, and the copied URL.
10. Run the command.
11. Open the cloned folder in your editor.
12. Open a terminal in that folder and start Claude Code.

Check that the folder contains `CLAUDE.md`, `README.md`, `interview-notes.md`,
and `PRD.md`. Ask for help if access fails. Continue with local files if Greg
calls the fallback, so setup doesn't consume the interview.

## 10:10-10:35: Interview and agree on the problem

Use the first three minutes to prepare an opening question and possible
follow-ups. The class interviews Greg for twelve minutes using Example,
Explore, Reflect, and Next. Let his answers guide your next question.

Record brief notes during the interview. Give evidence statements IDs such as
E1 and E2. Use quotation marks only for words you recorded accurately.

After the interview, spend five minutes answering these questions without AI:

- Who is having difficulty, and what are they trying to do?
- What did we hear that supports our interpretation?
- What do we still need to confirm?

The class then has five minutes to agree on one shared problem. Record that
statement in your notes. Groups may propose different solutions to it.

## 10:35-10:55: Develop the product brief

Use this prompt in Claude Code after checking your interview notes together:

```text
/superpowers:brainstorming
Read CLAUDE.md, interview-notes.md, and PRD.md.
Help our group develop the shared problem into an initial product brief.
Keep the six sections in PRD.md and aim for 300-400 words total.

Use our interview evidence, with its E IDs, as the case context.
Separate evidence from interpretation and assumptions.
Ask the questions that would most change our product decision, one at a time.
When we don't know an answer, record how we could validate it.

Compare two or three approaches, including a simpler process change.
Explain trade-offs and let us choose before writing the brief.
Propose a success measure without inventing a baseline or agreed target.
Record our selected approach, scope, and unresolved assumptions in PRD.md.
Ask us to review the brief and correct your interpretation.

This is a classroom adaptation of brainstorming.
Write only PRD.md. Keep the interview record unchanged.
Stop at the initial product brief. Do not create another spec or plan.
Do not implement software, commit, or push.
```

Read the result together before accepting it. Correct claims that go beyond
your evidence, and explain why you chose this approach. The group's agreement
doesn't establish that a real stakeholder has validated the proposal.

## 10:55-11:05: Visualize and commit the draft

After reviewing the brief, use this prompt:

```text
We have reviewed our initial PRD.md for this classroom exercise.
Read it and propose one assumption a visual mockup could help us test.
Wait for our agreement on that assumption before creating the mockup.

Then create one self-contained mockup.html illustrating our proposed approach.
Use a simple screen or workflow with fictional data and inline styles.
It must open directly in a browser without a server or downloaded assets.
Label it "Concept mockup: fictional data, behavior not validated."
State the assumption and one question we would ask a stakeholder.
Use labels for controls that do not actually work.
Do not add capabilities beyond PRD.md without asking us.

This throwaway mockup is the only authorized code artifact.
Do not build the product, connect services, or install dependencies.
Do not create an implementation plan, commit, push, or deploy.
```

Spend at most eight minutes on the mockup. Open `mockup.html` in a browser and
check that it agrees with your brief. Use the remaining time to save a commit.

Run these commands yourself, from the group repo:

If you used a paper sketch, describe it in your notes first. Omit
`mockup.html` from the staging command when that file doesn't exist.

```bash
git status
git diff
git add interview-notes.md PRD.md mockup.html
git diff --cached
```

Review the staged changes with your group. The staged diff includes newly
created files, which may not appear in the earlier diff. If the changes are
correct, run:

```bash
git commit -m "Draft product brief and concept mockup"
git push
```

A commit saves a local checkpoint. Pushing copies it to GitHub. If pushing
fails, keep the local commit and ask for help.

## 11:05-11:25: Present and defend

Each group has two minutes to present and three minutes for questions. Show
the mockup while explaining the choices in your brief. Keep the brief available
for reference, and answer questions in your own words without asking Claude.

Explain the problem, the supporting evidence, and why you chose this approach.
Name an assumption you still need to test. Any group member may receive a
question, even if someone else presents.

## 11:25-11:32: Revise and push

Record feedback in the feedback section of `interview-notes.md`. Explain which
change you accepted or rejected and why. Revise the brief and mockup together
so they still describe the same proposal.

Repeat the review and staging commands above. Then save the revision:

```bash
git commit -m "Revise proposal after class feedback"
git push
git status
```

Check the GitHub repo for the latest commit and revised files. A clean local
status alone doesn't confirm that your push succeeded. Share the repo URL with
Greg through the submission location he announces.

## 11:32-11:35: Reflect individually

Write two or three sentences explaining one choice, the evidence behind it,
and what would change your mind. Submit your own response where Greg directs.

## If the tools fail

Discuss the six PRD questions as a group and write the brief manually. Sketch
the proposal on paper if the mockup can't be generated. Keep your local work
if GitHub is unavailable, and tell Greg which step needs follow-up.

If you couldn't clone the repo, save the files without running the Git commands.
Greg will help you complete that step later.
