<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=RingCentral%20Call%20Logging%20%26%20Missed-Call%20Text-Back&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Telephony%20and%20CRM%20integration&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="RingCentral Call Logging & Missed-Call Text-Back" />

**Every intake call is summarised by AI and logged to the CRM, and every missed caller gets an instant text with an intake link.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Telephony%20and%20CRM%20integration-9533fa?style=flat-square" alt="Telephony and CRM integration" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/RingCentral%20API-231f20?style=flat-square" alt="RingCentral API" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-231f20?style=flat-square" alt="OpenAI" />
  <img src="https://img.shields.io/badge/CRM%20API-231f20?style=flat-square" alt="CRM API" />
  <img src="https://img.shields.io/badge/SMS-231f20?style=flat-square" alt="SMS" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![RingCentral call logging in n8n: incoming call event, AI call summary prompt and structured JSON output logged to the CRM.](assets/cover.webp)

## Overview

Calls were not logged consistently, and a missed caller could easily go to another firm. Lexvaxa built a custom Node.js integration on RingCentral webhooks, with n8n handling the CRM and SMS steps. Every call event is logged to the CRM contact timeline, an AI model turns the transcript into structured call notes with practice area, urgency and next step, missed calls get an instant SMS text-back, and new callers receive an intake link. Screens shown use sample data, so no client records are exposed.

## The challenge

Busy intake lines meant missed calls and inconsistent notes, and potential clients were lost before anyone called back.

## The solution

A Node.js webhook service for RingCentral with n8n workflows for AI call summaries, CRM logging, SMS text-back and team alerts.

## Key features

- Every call event logged to the CRM contact timeline
- AI call notes: practice area, injury, urgency, next step
- Instant SMS text-back for missed calls
- Intake link sent to new callers
- Alerts to the intake team for urgent calls

## Results

- Every call is recorded and no potential client is left without a reply

## Tech stack

![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![RingCentral API](https://img.shields.io/badge/RingCentral%20API-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge) ![CRM API](https://img.shields.io/badge/CRM%20API-1d1726?style=for-the-badge) ![SMS](https://img.shields.io/badge/SMS-1d1726?style=for-the-badge) ![Webhooks](https://img.shields.io/badge/Webhooks-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/ringcentral-call-logging-text-back

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
