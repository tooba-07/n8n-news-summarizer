# n8n News Summarizer → Discord

An n8n automation that monitors a news RSS feed, summarizes new articles using Google Gemini AI, and posts the summaries to a Discord channel via webhook.

## How it works
1. **Trigger**: An RSS Feed Trigger node monitors the BBC World News feed for new articles.
2. **Processing**: When a new article is detected, its content is sent to Google Gemini AI, which generates a concise 2-sentence summary.
3. **Delivery**: The summary is automatically posted to a Discord channel using a webhook integration.

## Problem it solves
Staying updated on current events usually means reading full-length articles, which is time-consuming. This automation delivers short, digestible summaries directly to Discord without any manual effort.

## Nodes used
RSS Feed Trigger → Google Gemini (Message a Model) → Discord (Send a Message via Webhook)

## Files
- `workflow.json` — exported n8n workflow
- `screenshot.png` — workflow canvas screenshot

## Full documentation
Full write-up with execution proof: [Google Doc link](https://docs.google.com/document/d/1OCWUXv2tdLwB8vZ5uZTS9tvTtwYLGfW8vQsHWHQpudg/edit?usp=sharing)# n8n-news-summarizer
n8n workflow that monitors an RSS news feed, summarizes new articles with Google Gemini AI, and posts the summaries to Discord via webhook.
