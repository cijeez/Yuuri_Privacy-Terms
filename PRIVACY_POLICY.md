---
layout: default
title: Privacy Policy
permalink: /privacy/
---
# Yuuri Bot — Privacy Policy

**Effective date:** 1 November 2026
**Operator:** WTC Boards
**Contact:** https://discord.gg/SkmTArJ3uQ

Yuuri ("the bot", "we") is a Discord bot with an AI chat companion, voice chat,
music and server tools (welcome messages, reaction verify, role announcements).
This policy explains what the bot stores, why, who it is shared with, and how
you can see or delete it.

## 1. What we collect

**When you talk to Yuuri's AI** — you say her name, @mention her, reply in a room
a server admin set up for her, or talk in a voice channel she joined with
`/voicechat` — the bot processes:

| Data | Why | How long |
|---|---|---|
| The message you sent her (text, and images attached to it or to the message you replied to) | To generate her reply | Your last 10 messages with her, per server |
| Short notes about you that the AI picks out of your messages (e.g. your name, likes, dislikes, hobbies, chat style, language) | So she remembers you | Until you or a server admin delete them |
| What you said about other server members (a short summary) | So she understands the people around you | Until deleted |
| A relationship score (0–100) and short reasons for changes | Her personality reacts to how you treat her | Until deleted (last 20 changes kept) |
| First-seen date and message count | Greeting new people, basic stats | Until deleted |
| Voice: what is said in the voice channel while she is in it | Transcribed to text so she can reply; a short summary of the conversation topics is kept per server | Audio is processed in memory and **never saved**. Transcripts are kept only for the live session; the topic summary is kept until a server admin wipes it |

All AI data is stored **separately for each server**: what you say in one server
is never used in another.

**Server-level data:** server and channel IDs and the settings admins choose (AI
rooms, welcome/verify/music settings), "general facts" Yuuri learned in that
server, and daily usage counters (number of AI calls/tokens and voice minutes
per server — no message content).

**What we do not collect:** messages that aren't addressed to Yuuri are not
stored or logged. Music and server-tool commands only store the settings they
need. We don't collect email addresses, IP addresses or payment details.

## 2. Who we share it with

We do not sell your data or use it for advertising. To work, the bot sends data
to these services:

- **OpenRouter** (openrouter.ai), which routes the request to an AI model provider
  (currently OpenAI and Google models): your message, images, recent chat
  history, the notes about you and voice audio, to generate replies and
  transcribe speech. If the operator enables it, requests may instead go
  directly to **OpenAI** or **Anthropic**.
- **DuckDuckGo**: search queries, when Yuuri looks something up for you.
- **MyMemory** (mymemory.translated.net): Thai search queries, translated to English before searching.
- **Microsoft Edge text-to-speech**: the text of Yuuri's own spoken replies in voice chat.
- **Websites** that Yuuri opens when you share a link or she searches the web (only the page address is sent).
- **Discord**, which hosts all messages and voice.

Each provider handles data under its own privacy policy.

## 3. Your choices and rights

You can do all of this yourself, at any time, from any server or in DMs with the bot:

- `/pr info` — a summary of this policy.
- `/pr mydata` — download everything stored about you (JSON file), in every server.
- `/pr forget` — permanently delete everything stored about you in every
  server, including what others said about you.
- `/pr memory off` — Yuuri stops storing anything about you and ignores
  your voice in voice chat (she can still reply to you). Turn it back on with `/pr memory on`.

Server admins (Manage Server permission) can wipe all of Yuuri's AI memory for
their server with `/ai_forget_server`.

If you can't use the commands, contact us (below) and we'll do it for you. Depending on where you live you may have further rights — for example under Thailand's Personal Data Protection Act B.E. 2562 (PDPA) or the EU GDPR — such as asking us to correct your data or to stop processing it; contact us to use them.

## 4. Retention

- Data stays until you, a server admin, or the operator deletes it, with the limits shown in section 1.
- When the bot is removed from a server, that server's data is **automatically
  deleted 30 days later** (unless the bot is added back before then).
- Daily usage counters contain no personal data and are kept for cost tracking.

## 5. Security

Data is stored in a database on the operator's own server, which is not publicly
reachable. API keys are kept out of the code and config files. Only the operator
can access the stored data.

## 6. Children

Discord requires users to be at least 13 (or older where local law requires).
Yuuri is not meant for children under that age and we don't knowingly collect
their data. If you believe a child's data is stored, contact us and we'll delete it.

## 7. Changes

We'll update the date at the top when this policy changes. Big changes will be
announced in the bot's support server.

## 8. Contact

Questions, or a deletion request: https://discord.gg/SkmTArJ3uQ
