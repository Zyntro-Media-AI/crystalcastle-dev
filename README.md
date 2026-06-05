✦ Crystal Castle

AI-Powered Social Commerce Automation Platform

Transform product assets into high-converting marketing content through AI-driven video generation, caption creation, affiliate tracking, and automated publishing workflows.

Built for modern creators and affiliate marketers across:

TikTok · Shopee · Reels · Threads · X



🎯 What is Crystal Castle?

Crystal Castle is an AI-powered content automation platform designed for creators, affiliate marketers, and social commerce teams.

The platform automates the content lifecycle from raw product assets to publish-ready marketing materials.

Automated Workflow

Product Image

↓

AI Video Generation

↓

AI Caption Creation

↓

Affiliate Link Injection

↓

Publishing Workflow

↓

Monitoring & Alerts

↓

Performance Tracking

⚡ Core Capabilities

Module

Description

🎬 AI Video Engine

Generate short-form product videos

✍️ Caption Generator

Create platform-optimized captions

🔗 Affiliate Monitoring

Validate affiliate links automatically

📊 State Tracking

Store pipeline state in Supabase

🚨 Alert System

Notify failures and link issues

🚀 CI/CD Automation

GitHub Actions orchestration

🌐 Landing Hub

GitHub Pages / Vercel deployment

📚 Knowledge Base

AI documentation and workflow guidance

🏗️ Architecture

flowchart TD

A[Product Assets]
--> B[AI Content Pipeline]

B --> C[Video Generation]
B --> D[Caption Generation]

C --> E[Content Package]
D --> E

E --> F[Affiliate Link Injection]

F --> G[Publishing Workflow]

G --> H[TikTok]
G --> I[Shopee]
G --> J[Threads]
G --> K[X]

E --> L[Supabase]

L --> M[Monitoring]
M --> N[Line Alerts]

✅ Feature Matrix

Feature

Status

AI Video Generation

✅

AI Caption Generation

✅

Affiliate Validation

✅

Supabase Tracking

✅

GitHub Actions Automation

✅

Alert System

✅

Link-in-Bio Landing Page

✅

Analytics Dashboard

🚧

Content Performance Tracking

🚧

Publishing API

📅 Planned

Autonomous AI Agent

📅 Planned

🔧 Technology Stack

Automation

GitHub Actions

Backend

Python 3.11+

Database

Supabase PostgreSQL

AI

Groq API

Meta Llama Models

Notifications

Line Notify

Hosting

GitHub Pages

Vercel

Security

GitHub Secrets

Environment Variables

Secret Scanning

📁 Project Structure

crystalcastle/

├── .github/
│   └── workflows/
│       ├── ci.yml
│       ├── ai_pipeline.yml
│       ├── monitor.yml
│       └── docs.yml
│
├── src/
│   ├── ai_pipeline.py
│   ├── monitor.py
│   ├── notify.py
│   ├── supabase_store.py
│   └── utils.py
│
├── scripts/
│   └── check_env.py
│
├── docs/
│   ├── architecture/
│   ├── knowledge/
│   ├── workflows/
│   └── prompts/
│
├── tests/
│
├── main_script.py
├── requirements.txt
├── .env.example
└── README.md

📋 Requirements

Required

Python 3.11+

GitHub Account

Supabase Project

Groq API Key

Optional

Node.js 18+

Vercel CLI

Self-hosted Runner

🚀 Quick Start

Clone Repository

git clone https://github.com/1napz/crystalcastle.git

cd crystalcastle

Install Dependencies

pip install -r requirements.txt

Configure Environment

Create:

.env.local

Example:

# Supabase
SUPABASE_URL=https://project.supabase.co
SUPABASE_SERVICE_ROLE_KEY=your-key

# AI
GROQ_API_KEY=your-key

# Notifications
LINE_NOTIFY_TOKEN=your-token

# Optional
VERCEL_TOKEN=your-token

Validate Environment

python scripts/check_env.py

Run

python main_script.py

🟢 Supabase Setup

Install CLI

npm install -g supabase

Login

supabase login

Initialize

supabase init

Link Project

supabase link --project-ref YOUR_PROJECT_ID

Deploy Schema

supabase db push

🔺 Vercel Deployment

Install

npm install -g vercel

Login

vercel login

Deploy

vercel --prod

🔐 Security

Crystal Castle follows secure-by-default practices.

Security Principles

No secrets committed to source control

Environment validation before execution

GitHub Secrets for credentials

Least-privilege access

Automated dependency scanning

Branch protection support

Reporting Security Issues

Please do not create public issues for sensitive vulnerabilities.

Contact project maintainers privately with:

Vulnerability description

Reproduction steps

Impact assessment

📈 Monitoring & Observability

Crystal Castle tracks:

Workflow executions

AI generation failures

Affiliate link health

Notification delivery

Publishing success rate

Pipeline latency

All events are persisted in Supabase for auditing and analytics.

📚 Knowledge Base

docs/

└── knowledge/
    ├── ai/
    ├── platform/
    ├── architecture/
    ├── workflows/
    └── prompts/

Suggested Knowledge Documents

AI

ai-prompt-engineering.md

ai-model-selection.md

ai-content-guidelines.md

Platform

github-actions.md

supabase.md

vercel.md

openai.md

stripe.md

Architecture

system-overview.md

database-design.md

deployment-strategy.md

Workflows

ci-cd.md

monitoring.md

content-pipeline.md

🤖 GitHub Actions

Current workflows:

Workflow

Purpose

ci.yml

Testing and validation

ai_pipeline.yml

Content generation

monitor.yml

Affiliate monitoring

docs.yml

Documentation validation

🌿 Branch Strategy

Branch

Purpose

main

Production

develop

Integration

feature/*

New features

fix/*

Bug fixes

🤝 Contributing

Contributions are welcome.

Development Flow

Fork repository

Create feature branch

git checkout -b feature/my-feature

Commit using Conventional Commits

git commit -m "feat: add monitoring dashboard"

Push branch

Open Pull Request

Requirements

Follow coding standards

Update documentation

Add tests when applicable

Pass CI checks

Sign commits if required

Developer Certificate of Origin

By contributing to this project, you agree to the Developer Certificate of Origin (DCO).

💬 Feedback & Support

Feedback helps improve Crystal Castle.

Report a Bug

Open a GitHub Issue including:

Expected behavior

Actual behavior

Logs

Screenshots

Request a Feature

Include:

Problem statement

Proposed solution

Expected benefits

Community Channels

GitHub Discussions

X (Twitter)

Threads

Project feedback is typically reviewed within 48 hours.

🗺️ Roadmap

Q3 2026

Analytics Dashboard

Publishing Metrics

Workflow Insights

Q4 2026

Content Recommendation Engine

AI A/B Testing

Multi-account Publishing

2027

Autonomous Content Agent

Marketplace Integrations

Enterprise Workspace Features

📄 License

MIT License

Copyright (c) 2026 1napz

Crystal Castle

Where AI transforms commerce into scalable content systems.

Built with automation, AI, and creator-first workflows.