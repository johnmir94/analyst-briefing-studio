# Analyst Briefing Studio

**Holistic AI · Analyst relations**

Analyst Briefing Studio helps an analyst relations lead plan what to say, what to show, and who will follow up. Use it to turn a broad briefing objective into a focused agenda with specific evidence for each analyst question.

## Why I built it

I built this around my work leading analyst relations for the Holistic AI platform and preparing materials for Tier 1 analyst engagements. It demonstrates how I would connect a product narrative to a proof point and track questions that need a follow-up.

## Try the sample

1. Start with **How are policy exceptions documented?**, which is marked **Needs evidence** in the sample.
2. Specify the approval-history record to show and assign the teammate who will confirm it.
3. Change the status to **Ready** and check the status summary. Use **Sent** after you have delivered the follow-up.
4. Click **Download Markdown** for a briefing outline with the questions, narrative, evidence, and owners.

The status is set by the briefing owner. The app tracks it for planning and export.

## Run locally

Download the repository ZIP or clone it, then open `index.html` in a modern browser.

```sh
git clone https://github.com/johnmir94/analyst-briefing-studio.git
cd analyst-briefing-studio
```

The app uses HTML, CSS, and JavaScript and runs entirely in the browser without an account or backend. Sample data is fictional. Edits stay in the current tab, so download the Markdown before reloading or closing it.

## Source files

| File | Role |
| --- | --- |
| `index.html` | Workspace layout and controls |
| `style.css` | Responsive styling |
| `data.js` | Fictional sample workspace |
| `app.js` | Editing, validation, summaries, and Markdown export |
