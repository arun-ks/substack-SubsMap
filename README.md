# Substack Subscriber Map

A small, browser-only page that turns country codes from a Substack subscriber export into a shareable world map.

**Live page:** https://arun-ks.github.io/substack-SubsMap/

## How to use

The instructions are in an expandable panel at the top of the page. Open it to follow the Substack export steps.

### Get country codes from Substack

1. On your laptop or computer, log in to [substack.com](https://substack.com).
2. On the left-hand panel, click **Dashboard**.
3. On the left-hand panel, click **Audience**.
4. Find the subscriber list in the table. Click the **…** at the top-right of the table.
5. In the dropdown menu, click **Export**.
6. In the popup, select **Export all columns** and click **Export**.
7. After a few seconds, the button text will change to **Download last export**. Click it.
8. Open the CSV in Excel and find the column titled **Country** (normally column M).

### Generate the map

1. Select and copy the values in the **Country** column from Excel, with or without its title row, and paste them into the **Subscriber country codes** box.
2. **Malaysia (MY)** is selected as the default home country. Change it if needed, then click **Generate Map**.
3. Open the generated link to view the map on [visitedplaces.com](https://visitedplaces.com/).

The page skips blank and unrecognized rows, removes duplicate country codes, sorts the codes alphabetically, and always includes the selected home country.
## Privacy

All parsing happens in the browser. The page does not save or send the pasted subscriber data. When someone opens the generated link, the selected country codes are included in the URL sent to visitedplaces.com so it can render the map.

## Hosting

This is a static `index.html` page with no build step or backend. GitHub Pages publishes it from the `main` branch root. The live site is at:

https://arun-ks.github.io/substack-SubsMap/

## Created with Codex

This page and README were generated with OpenAI Codex.

## Conversation usage estimate

Approximate cumulative usage for the conversation through this README update, including the response to this request: **about 150,000 tokens** and **roughly $0.01–$0.04 USD in API-equivalent model cost**. This is a rough estimate, not a measured total or an actual Codex charge; the exact per-conversation token and cost totals are not exposed here. The dollar range uses the public GPT-6 Luna standard API rates as a reference and allows for an unknown input/output token mix: https://developers.openai.com/api/docs/pricing
