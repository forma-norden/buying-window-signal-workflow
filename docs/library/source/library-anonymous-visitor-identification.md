# Anonymous Visitor Identification

> **What it targets:** Named target accounts revisiting pricing, product, case-study, or integration pages without filling a form.

## The logic

This is one of the strongest first-party signals because the behavior happened on your property.

Most SaaS sites still lose the majority of that demand by default. Median SaaS landing-page conversion sits around **3.8%** (MarketingProfs summarizing Unbounce 2024), which means most qualified visitors leave without a hand raise. Visitor identification closes part of that gap.

## Tool options

| Tool | Purpose | Alternative |
| --- | --- | --- |
| Albacross [visitor ID] | Identify named visiting accounts | Warmly [visitor ID] |
| Clay [enrichment / automation] | Enrich account and contacts | Apollo.io [enrichment / prospecting] |
| HubSpot [CRM] | Score and assign the account | Salesforce [CRM] |
| Instantly.ai [sequencing] | Trigger fast follow-up | Smartlead [sequencing] |

## SOP

> **Step 1: install the signal source**
>
> - Add the visitor-ID script
> - Pass company name, page URL, and visit time into the CRM
> - Filter for high-intent pages only
>
> **Step 2: score the visit**
>
> - Pricing / demo / integrations -> high priority
> - Case study -> medium priority
> - Generic blog only -> monitor unless account tier is high
>
> **Step 3: enrich before contact**
>
> - Confirm company domain
> - Find 1-2 buying-committee contacts
> - Verify email
> - Add page visited as the opener variable

## Route rules

| Page behavior | Route |
| --- | --- |
| Pricing or demo revisit | Triggered outbound same day |
| Case-study depth | Outbound or ABM depending on account tier |
| Single low-intent page view | Monitor |

## Short template

> Subject: {{company}} pricing question
>
> {{first_name}} - looks like your team has been back on the {{page_topic}} side of the site.
>
> Usually that means one of two things: active evaluation, or internal research before a process change.
>
> If it is useful, I can send over the framework we use to map where signal, routing, and outbound ops usually break before teams scale headcount.

## Common mistake

Treating every visit the same.

A repeat pricing-page visit from a target account is not the same as a single homepage session from a random company.
