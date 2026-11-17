# AI Voice Assistant for Auto Parts Phone Orders

**ElevenLabs · n8n · Zoho CRM · OpenAI · Google Sheets**

A Ukrainian-speaking voice assistant helps customers find parts, confirms their order and transfers the details to CRM.

Portfolio project based on the Dnipro Auto online-store scenario.

## Problem

Managers could not always answer calls while serving other customers. Enquiries outside working hours also went unanswered, creating missed opportunities to answer product questions and collect orders.

## Solution

Incoming call → ElevenLabs voice agent Kristina → exact-article product lookup → quantity / delivery / payment → customer confirmation → n8n validation → Zoho CRM customer and Deal → order number.

- Use returned product names and prices from the lookup tool.
- Confirm unclear article numbers and collect the required order details.
- Summarize the order and create it after explicit customer confirmation.
- Store product rows, total amount, delivery method and payment method in Zoho CRM.
- Analyze completed calls and save outcomes in Google Sheets and CRM conversation records.

## Results

- **Fewer missed enquiries:** the voice agent can handle calls while managers are busy and outside working hours, provided the connected services are available.
- **Less manual work:** consultation, order-detail collection and transfer to CRM reduce routine data entry.
- **Clearer follow-up:** customers receive an order number, while the team has customer details, order information and conversation history in the same process.

### Potential Monthly Business Impact

The Notion case includes an illustrative scenario, not measured production results:

| Assumption / outcome | Scenario value |
| --- | --- |
| Previously missed calls handled | 100 per month |
| Assumed call-to-order conversion | 25% |
| Average order value | UAH 1,500 |
| Potential additional orders | 25 per month |
| Potential additional revenue | UAH 37,500 per month, before returns and operating costs |
| Estimated avoided manager workload | Approximately 4–7 hours per month |

These outcomes depend on call volume, conversion, service availability and average order value.

## Tech Stack

ElevenLabs Conversational AI, n8n, Zoho CRM API, OpenAI API, Google Sheets API, JavaScript Code nodes, webhooks, REST APIs, JSON and store knowledge-base documents.

## Demo & Case Study

- [Watch the demo](https://youtu.be/WncJT7-GrnQ)
- [Read the full Notion case](https://tangy-whitefish-6d0.notion.site/a5fc12839d068374b6ed01c3035ce41f)

## Author

**Pavlo Holnyk — AI Automation & AI Agents**

[Portfolio](https://tangy-whitefish-6d0.notion.site/408c12839d06816f9e61ff1aa7392587) · [LinkedIn](https://www.linkedin.com/in/pavlo-holnyk/) · [Upwork](https://www.upwork.com/freelancers/~011ee82fd5725aa92e)
