# Phone Ordering with an AI Voice Assistant for an Auto Parts Store

Portfolio project by Pavlo Holnyk, based on the Dnipro Auto store scenario.

## Overview

Kristina, a Ukrainian-speaking ElevenLabs voice agent, helps customers find auto parts and place confirmed phone orders through n8n and Zoho CRM.

## Workflow

Incoming call -> ElevenLabs voice agent -> product lookup by exact article -> quantity, delivery and payment details -> customer confirmation -> n8n payload validation -> Zoho CRM customer and Deal with product rows, amount and order number.

A separate post-call flow analyzes conversation outcomes, saves the call log in Google Sheets and links CRM call records to the relevant customer or order. Store knowledge-base documents cover delivery, payment, returns and exchanges.

## Stack

ElevenLabs Conversational AI, n8n, Zoho CRM API, OpenAI API, Google Sheets API, JavaScript, webhooks, REST APIs, JSON and prompt design.

## Demo and case study

- [Case study in Notion](https://tangy-whitefish-6d0.notion.site/a5fc12839d068374b6ed01c3035ce41f)
- [Video demo](https://youtu.be/WncJT7-GrnQ)

## Repository contents

Project documentation only. Workflow exports, voice-agent configuration, catalog data and source files have not been added. Revenue and time-saving examples are potential scenarios, not verified production results.
