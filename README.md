# Analyst Briefing Studio

Use the studio to prepare an analyst conversation about a technical product. Write a briefing objective, connect each anticipated question to a narrative and evidence, and give outstanding follow-up an owner.

## Run locally

Clone the repository or use **Code → Download ZIP** on GitHub. Open `index.html` in a modern browser. There’s no install, build step, or account required.

```sh
git clone https://github.com/johnmir94/analyst-briefing-studio.git
cd analyst-briefing-studio
```

## Sample workflow

1. Start with **How are policy exceptions documented?**, which is marked **Needs evidence** in the sample.
2. Specify the approval-history record to show and assign the teammate who will confirm it.
3. Change the status to **Ready** and check the status summary. Use **Sent** after you have delivered the follow-up.
4. Click **Download Markdown** for a briefing outline with the questions, narrative, evidence, and owners.

## Workspace fields

| Field | What it captures |
| --- | --- |
| Analyst question | Specific question or topic to prepare for |
| Platform narrative | What to communicate about the capability and its scope |
| Evidence to show | Demo step, artifact, or fact to substantiate the answer |
| Follow-up owner | Person or function responsible for closing the evidence gap |
| Status | Needs evidence, Ready, or Sent |

## How it works

The app updates the status summary as topics are edited. Status is selected manually, so the briefing owner can record that evidence is outstanding, mark the answer ready after checking it, and mark a follow-up sent after delivery. The app records the status for planning and export. Delivery happens outside the workspace.

### Worked example

For a question about documenting exceptions, the sample answer calls for showing decision history and checking which exception workflows are covered. An open action can ask the product specialist to confirm exactly what approval history is available before the next analyst discussion.

## Export and data handling

Markdown includes the objective, status counts, and a structured entry for every question, with narrative, evidence, owner, and status.

Processing runs in the browser. The app has no backend and keeps edits in memory. Reloading reopens the fictional sample. Download the Markdown before closing the tab if you need a copy of your work.

## Files and checks

| File | Role |
| --- | --- |
| [`index.html`](index.html) | Workspace and controls |
| [`style.css`](style.css) | Responsive layout |
| [`data.js`](data.js) | Fictional seed data and field labels |
| [`app.js`](app.js) | Editing, validation, summaries, and Markdown export |

Run JavaScript syntax checks with Node.js. Use the sample workflow above for a manual check of editing, summary updates, and the export.

```sh
node --check app.js
node --check data.js
```

## Project context

The workflow draws on analyst relations for the Holistic AI platform, including preparation for Tier 1 briefings and coordination of supporting materials. The sample is fictional and uses no internal employer materials or customer records.
