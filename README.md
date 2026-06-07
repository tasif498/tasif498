# Hi, I'm Talha

Software Engineer at **CountyData** (remote, US) building data-extraction and lead-management systems that run in production every day.

## What I work on

- **Automation at scale** — a fleet of 60+ scrapers and integrations (~80% built by me) running unattended in production against constantly-changing targets: anti-bot evasion (undetected-chromedriver), LLM-assisted data extraction (Gemini) inside the pipelines, and CRM delivery integrations (GoHighLevel, Zoho, HubSpot) — Python, Selenium, Playwright, AWS Lambda & serverless
- **Multi-tenant data platform** — designed and built the lead-delivery platform the entire fleet runs on: subscription-based routing with wildcards, atomic-claim delivery daemons safe under concurrent workers, guaranteed delivery tracking, and cross-source deduplication (FastAPI + MongoDB). Client onboarding went from days of custom integration code to configuration-only
- **AI in production** — an AI medical scribe that turns doctor-patient audio into structured, SNOMED-coded clinical notes pushed directly into the EHR (speech-to-text via AssemblyAI/Azure Speech → OpenAI → schema-validated output → athenahealth FHIR R4 integration), plus LLM chatbots and Gemini-powered extraction inside scraping pipelines. The hard problem: making LLM output trustworthy enough for clinical use
- **Backend & infra** — FastAPI and Django/DRF services on AWS Fargate/ECS and App Runner, deployed with Terraform and GitHub Actions CI/CD; MongoDB + Redis caching that cuts third-party API costs 60–80%; monitoring with Sentry, Prometheus, CloudWatch
- **Full-stack delivery** — React 19 + TypeScript frontends (Vite, TanStack Query, Tailwind), payments (Stripe), enterprise auth (Microsoft SSO, OAuth, JWT)

## Background

- 5+ years freelancing on Fiverr (Python automation, scraping, desktop apps)
- BS Computer Science, FAST NUCES · former AI Lab Teaching Assistant
- 2,400+ contributions in the last year — most of my work lives in private client and company repos

## Currently building

- LLM agents that orchestrate research and data-collection workflows
- A self-recovering scraper fleet (60+ bots) and the multi-tenant data platform behind it

## Core stack

`Python` `FastAPI` `Django/DRF` `TypeScript/React` `Selenium/Playwright` `AWS (Fargate · Lambda · SQS)` `Azure` `Terraform` `Docker` `MongoDB` `PostgreSQL` `Redis` `OpenAI & Gemini LLM pipelines` `FHIR/EHR integration`

## Reach me

tasif498@gmail.com · [LinkedIn](https://www.linkedin.com/in/tasif498/)
