# Awesome-Customer-Satisfaction-Feedback-Surveys

# Awesome-Customer-Satisfaction-Feedback-Surveys

**Top Customer Satisfaction Feedback Surveys (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on NPS/CSAT Collection, In-Product Micro-Surveys, Research Questionnaires & Self-Hosted Feedback Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Satisfaction & Feedback Surveys**. These tools enable teams to measure Net Promoter Score, Customer Satisfaction, and Customer Effort Score, collect feedback at every touchpoint, and turn responses into action—from fully managed platforms with AI analysis to self-hosted survey engines that give organizations complete ownership of response data and GDPR compliance.



**Examples** include Qualtrics, SurveyMonkey, Typeform, Delighted, Survicate, AskNicely, CustomerGauge, InMoment, Nicereply, and HubSpot Surveys (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted NPS, in-app surveys, and open feedback infrastructure. **Critical note**: The open-source landscape is genuinely viable—**Formbricks** is the modern choice for in-product NPS and micro-surveys with behavior-based targeting , while **LimeSurvey** remains the veteran for research-grade questionnaires with 30+ question types and deep logic . **HeyForm** and **OhMyForm** offer lighter form-builder alternatives. No single open-source project matches Qualtrics's research depth or Delighted's NPS automation, but for core satisfaction measurement, Formbricks and LimeSurvey are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Qualtrics](https://www.qualtrics.com/)**

  **Enterprise experience management platform** with NPS, CSAT, CES, and advanced analytics. **Pricing**: **Free Account** with **500 lifetime responses and 3 active surveys**; paid tiers quote-only. **Free tier**: Yes, lifetime limits. **Best for**: individuals and teams wanting to explore Qualtrics capabilities before enterprise commitment—**trade-off**: 500 lifetime responses exhaust quickly; no email distribution on free tier .



- **[SurveyMonkey](https://www.surveymonkey.com/)**

  **Survey platform** with NPS templates and basic analytics. **Pricing**: **Basic (free)** with **1 user, unlimited surveys, 10 questions per survey, limited responses**; paid plans from ~$25/month. **Free tier**: Yes, 10 questions/limited responses. **Best for**: simple surveys and quick feedback collection—**trade-off**: response limits on free tier; advanced logic requires paid plans .



- **[Typeform](https://www.typeform.com/)**

  **Conversational form builder** with NPS and logic branching. **Pricing**: **Free plan** with **10 responses/month and unlimited forms**; Typeform branding on every form; no custom domain. **Free tier**: Yes, 10 responses/month. **Best for**: engaging, conversational survey experiences—**trade-off**: 10 responses/month is a sandbox, not production .



- **[Delighted](https://delighted.com/)** (Qualtrics)

  **NPS-focused feedback platform** with automated email/SMS collection and AI text analysis. **Pricing**: Quote-only; third-party listings show starting prices but no public free tier details. **Free tier**: Not specified in results. **Best for**: teams wanting turnkey NPS automation with Slack/Salesforce integrations—**trade-off**: quote-based pricing .



- **[Survicate](https://survicate.com/)**

  **Customer feedback platform** with in-product, website, and email surveys. **Pricing**: **Free account** with **up to 3 teammates, 25 survey responses/month, unlimited active surveys (300 collective response limit)**, branch logic, and 400+ templates. **Free tier**: Yes, permanent free plan. **Best for**: small teams wanting a genuine free tier with in-product survey capability—**trade-off**: 25 responses/month; 300 collective cap across active surveys .



- **[AskNicely](https://www.asknicely.com/)**

  **NPS and customer experience platform** for frontline teams. **Pricing**: Starting at **$399/month** per third-party listings; free trial available. **Free tier**: Trial only. **Best for**: service teams wanting NPS tied to frontline coaching—**trade-off**: premium entry price .



- **[CustomerGauge](https://customergauge.com/)**

  **B2B NPS and account experience platform**. **Pricing**: **Pricing available upon request**; no public tiers. **Free tier**: Not specified. **Best for**: B2B organizations wanting account-level NPS and revenue impact analysis—**trade-off**: quote-only; enterprise focus .



- **[InMoment](https://inmoment.com/)**

  **Experience improvement platform** with NPS and text analytics. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting AI-powered feedback analysis at scale.



- **[Nicereply](https://www.nicereply.com/)**

  **CSAT, NPS, and CES** for support teams with helpdesk integrations. **Pricing**: Starting at **$59/month** per third-party listings; free trial available. **Free tier**: Trial only. **Best for**: support teams wanting feedback tied to tickets—**trade-off**: per-agent pricing .



- **[HubSpot Surveys](https://www.hubspot.com/)**

  **NPS, CSAT, and CES surveys** within HubSpot Service Hub. **Pricing**: Included with Service Hub Professional ($100/seat/month) and Enterprise. **Free tier**: Limited. **Best for**: HubSpot users wanting feedback integrated with CRM and tickets.



## Open-Source GitHub Projects



- **[Formbricks](https://github.com/formbricks/formbricks)**

  **Open-source survey and experience management platform** (AGPLv3, ~10,000+ stars) — **the best open-source choice for in-product NPS and behavior-triggered micro-surveys** . **Features**: **In-app, website, link, and email surveys**; no-code editor with multiple question types; **target specific user groups without changing application code**; shareable link surveys; team collaboration; integrations with Slack, Notion, Zapier, and n8n; **privacy-first and self-hostable**; built on Next.js, TypeScript, and PostgreSQL . **Tech stack**: TypeScript (Next.js), PostgreSQL. **Deploy**: Self-hosted (Docker) or Formbricks Cloud . **Trade-off**: **In-product focus**—less suited for long-form research questionnaires than LimeSurvey; enterprise features may be gated in paid tier. **Best for**: SaaS and product teams wanting contextual NPS that fires while users are in the app—with full data ownership and GDPR compliance.



- **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)**

  **The world's #1 open-source survey platform** (GPL v2) — **the veteran research-grade survey engine**, active since 2006 and trusted by businesses, universities, and governments in 80+ countries . **Features**: **Unlimited surveys and questions**; **30+ question types**; **900+ survey templates**; **multilingual surveys (80+ languages)**; skip logic and question branching; **GDPR compliance**; two-factor authentication; SAML/LDAP integration; **NPS question type supported**; data export to SPSS/R/STATA; WCAG 2.0 compliance . **Tech stack**: PHP, MySQL/MariaDB/PostgreSQL. **Deploy**: Self-hosted (Docker, manual) or LimeSurvey Cloud . **Trade-off**: **Utilitarian interface** compared to Formbricks; heavier for simple in-app NPS. **Best for**: research teams, academics, and organizations running long-form questionnaires where question logic and statistical exports matter.



- **[HeyForm](https://github.com/heyform/heyform)**

  **Open-source conversational form builder** (AGPL-3.0) — **the most accessible open-source Typeform alternative** for surveys, quizzes, and polls . **Features**: **Versatile inputs** (text, email, phone, picture choices, date pickers, file uploads); **conditional logic and URL redirections**; **integrations** with webhooks, Zapier, and Make.com; **visual themes** with custom CSS; **analytics** including drop-off and completion rates; CSV export; self-hosting with one-click deployment options; OpenID Connect support for self-hosted identity providers . **Tech stack**: Node.js, React. **Deploy**: Self-hosted or HeyForm Cloud . **Trade-off**: **Form builder, not a dedicated NPS/CSAT platform**—no built-in scoring or feedback analytics specific to satisfaction metrics. **Best for**: teams wanting conversational, branded surveys with logic branching—especially those migrating from Typeform.



- **[OhMyForm](https://github.com/ohmyform/ohmyform)**

  **Open-source TypeForm alternative** (license per repo) — **the lightweight form builder for mobile-ready surveys** . **Features**: Multi-language support; 11 question types; editable start/end pages; **export submissions to XLS, JSON, or CSV**; native analytics and Google Analytics support; embeddable forms; **Forms-as-a-Service API**; customizable notifications; **webhooks on submission**; deployable with Heroku and DockerHub; PostgreSQL and SQLite support. **Tech stack**: Per repository. **Deploy**: Self-hosted (Docker, Heroku) . **Trade-off**: **Fewer question types (11)** than HeyForm or LimeSurvey; roadmap features (file upload, payment field, encryption) not yet implemented . **Best for**: developers wanting a simple, API-friendly form builder with webhooks—not a full survey platform.



### Additional Strong Open-Source Options



- **SurveySensum (HubSpot app)** — Free plan with **25 responses/month, 500 emails/month, unlimited surveys and users** . **Note**: **HubSpot marketplace app**, not standalone open source—requires HubSpot. **Best for**: HubSpot users wanting free survey capability within their CRM.



**Frameworks for building custom systems**: Combine **Formbricks** for in-product NPS and micro-surveys with **LimeSurvey** for research-grade questionnaires and **HeyForm** for conversational forms—creating a feedback stack matched to different collection contexts. **None of these match Qualtrics's research depth or Delighted's NPS automation**, but for core satisfaction measurement, Formbricks and LimeSurvey cover most needs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer feedback platforms handling respondent data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for survey responses and satisfaction scores.

- **The "in-product NPS" vs. "research-grade survey" vs. "conversational form builder" distinction is critical.** **Formbricks** is **in-product NPS**—it targets users by behavior and triggers surveys inside the app . **LimeSurvey** is **research-grade**—it handles long questionnaires with deep logic and statistical exports . **HeyForm and OhMyForm** are **form builders**—they collect responses but lack NPS-specific scoring and analytics . **Choose based on whether you need contextual in-app NPS, deep research surveys, or conversational forms.**

- **Formbricks is the best open-source choice for in-product NPS.** With 10,000+ stars, in-app/website/link/email surveys, behavior-based targeting, and Docker self-hosting, it is the modern alternative for product teams . **The trade-off**: less suited for long-form research than LimeSurvey.

- **LimeSurvey is the veteran for research.** Since 2006, with 30+ question types, SPSS/R exports, and GDPR compliance, it is hard to beat for academic and market research . **The trade-off**: utilitarian interface; heavier for simple in-app NPS.

- **Qualtrics offers a free account with 500 lifetime responses and 3 active surveys**—useful for exploration but exhausted quickly . **SurveyMonkey's free tier is 10 questions per survey with limited responses** . **Typeform's free tier is 10 responses/month**—a sandbox, not production . **Survicate's free tier is the most generous at 25 responses/month with in-product capability** .

- **Pricing opacity varies.** Qualtrics, SurveyMonkey, Typeform, Survicate, AskNicely, Nicereply, CustomerGauge, Delighted, InMoment, and HubSpot all have published or partially published pricing, but enterprise tiers require sales contact. **Validate with direct vendor conversations against your response volume and feature needs.**

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL for Formbricks, PHP/MySQL for LimeSurvey, Node.js for HeyForm), security hardening, and ongoing maintenance. **Survey data includes respondent PII and sentiment**—ensure your deployment meets your organization's privacy and GDPR requirements before collecting responses.



---



**Made for product teams, CX researchers, and organizations building transparent feedback solutions.**

Let's make Customer Satisfaction & Feedback Surveys more open, data-driven, and respondent-friendly.
