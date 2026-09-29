# Reddit value-first launch draft

## Suggested communities

- r/SideProject — founder story and feedback request
- r/indiehackers — product, positioning, and pricing discussion
- r/devops — only after checking the community's current self-promotion rules; lead with the cost-analysis problem, not the sale

## Title

I built a local-first tool that turns GitHub Actions and Copilot billing exports into prioritized cost actions

## Body

GitHub billing exports are detailed, but I kept running into a practical gap: they show rows, minutes, SKUs, and credits without clearly answering what is driving the bill or what is worth changing first.

I built MeterMind around that workflow. You import a GitHub billing CSV or usage API JSON file and it produces:

- a month-end spend projection;
- a Copilot vs. Actions split;
- ranked cost drivers; and
- three prioritized saving opportunities.

The analysis runs locally in the browser. There is no account, API key, upload server, or recurring data connection.

I priced it at $19 once rather than adding another subscription. I am looking for honest feedback from people who manage GitHub usage: is visibility enough, or would workflow-level recommendations be the deciding feature for you?

Product page: https://get-metermind.yuqih019.chatgpt.site/
