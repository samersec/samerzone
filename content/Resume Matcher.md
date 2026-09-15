---
title: Resume Matcher — Solo-Built Freemium SaaS
date: 2025-04-15
tags:
  - project
  - ai
  - nlp
  - python
  - react
  - fastapi
---

## Resume Matcher — Solo-Built Freemium SaaS

A live, freemium SaaS that scores resumes against job descriptions, identifies missing keywords, and provides AI-powered improvement tips — designed, built, and shipped solo.

### Project Overview

Resume Matcher helps job seekers understand how well their CV matches a target role. Instead of guessing, users paste their resume and a job description, and the app returns a match score, missing-keyword insights, and tailored improvement suggestions.

### Business Problem

Most candidates do not know whether their resume genuinely matches the language used by hiring teams or ATS systems. This creates a gap between application quality and actual hiring signal. Resume Matcher closes that gap by making the match evaluation fast, actionable, and easy to understand.

### Key Features

- Resume-to-job-description scoring
- Missing-keyword detection
- AI-generated improvement suggestions via LLM
- Freemium usage model with IP-based rate limiting
- Premium subscription flow for unlimited use

### Tech Stack

- **Frontend:** React / Vite
- **Backend:** FastAPI (Python)
- **AI:** Groq API — Llama 3.3-70B-Versatile
- **Database:** SQLite
- **Hosting / Infra:** Vercel, Render, OVH

### How It Works

1. User submits a resume and a target job description
2. The backend analyzes the alignment between both texts using an LLM
3. The app returns a match score, key missing skills, and improvement recommendations
4. Free users are limited by IP-based daily quotas; premium users get unlimited access

### Freemium Model

- **Free tier:** 3 analyses per day
- **Premium:** $9.99/month for unlimited access

### What I learned

- Building a full-stack SaaS from scratch without a team
- Combining AI tooling with practical product UX and business logic
- Designing rate limits and user flows for a freemium product
- Shipping and maintaining a live product with real users

### Resources

- **Live:** [resumematcher.tn](https://resumematcher.tn)
- **GitHub Repository:** [samersec/resume-matcher](https://github.com/samersec/resume-matcher.git)