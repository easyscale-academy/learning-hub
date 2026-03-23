# Learn Systematic Job Search

## Overview

The best tech students from top schools (MIT, CMU, etc.) typically job hunt like this: create an Excel spreadsheet, search job boards daily, review postings one by one, and manually log them. This is already better than most—at least there's tracking.

**But it's still incredibly inefficient.**

Our module is an **AI-powered systematic job search toolkit**. With a well-defined resume, experience narrative, and specific requirements, we leverage AI capabilities:

- **AI Research Tools**: Generate personalized search strategies, research target companies' career pages and H1B sponsorship history
- **AI Browser Automation**: Automatically scrape the latest job postings from job boards
- **AI Contact Discovery**: Find the hiring managers, recruiters, and alumni behind job postings
- **AI-Assisted Outreach**: Proactively reach out with your killer projects to dramatically increase response rates

This is a **systematic application workflow** built on our Job Hunting AI tools:

| Traditional Approach | Our Approach |
|---------------------|--------------|
| Manual daily searching | AI auto-scrapes, filters, and ranks |
| Mass applying and waiting | Precisely locate contacts, proactive outreach |
| No idea if company sponsors visa | AI researches H1B history |
| Projects go unseen | Projects sent directly to the right people |

**This is the most reliable job search method for students without career track records in the AI era.**

---

## Prerequisites

This module assumes you have completed the following prerequisite modules and prepared the relevant materials:

| File | Description | Source Module |
|------|-------------|---------------|
| `profile/resume.md` | Your complete resume | Resume Module |
| `profile/narrative.md` | Expanded descriptions of each resume experience | Narrative Module |
| `profile/objective.md` | Job search objectives (full-time/intern, remote/onsite, H1B needs, big tech/startup, etc.) | Objective Module |

---

## Module Index

| Module | Core Function | Tool |
|--------|--------------|------|
| [Module 1](#module-1-search-strategy--target-companies) | Generate search queries, filter recommendations, target company list | AI Research Tools |
| [Module 2](#module-2-linkedin-job-auto-scraping) | Auto-scrape LinkedIn jobs, rank by fit | AI Controls Your Browser |
| [Module 3](#module-3-identify-key-contacts) | Identify Recruiters, Hiring Managers, Alumni | AI Controls Your Browser |
| [Module 4](#module-4-send-cold-messages) | Proactive outreach with project links, request referrals/interviews | AI Tools |

---

## Module 1: Search Strategy & Target Companies

### Problem

> "What positions should I search for? What filters should I use? Which companies should I target?"

### Solution

**AI Research Tools**—Analyze your profile and generate:

**1. Search Query Strategy**
- **L1 Precise Match**: Direct match to target job titles
- **L2 Skill Combination**: Core skills + job type
- **L3 Broad Search**: Maximum coverage, don't miss opportunities

**2. Filter Recommendations**
- Specific filter settings for LinkedIn, Indeed, Glassdoor, etc.
- Customized based on your experience level, visa requirements, location preferences

**3. Target Company List**
- AI web search for matching companies
- Obtain official Career Page links
- Research H1B sponsorship history

### Sample Output

```
job/query.tsv   - Search query list
job/filter.tsv  - Filter recommendations
job/company.tsv - Target company list (with Career Page and H1B friendliness)
```

---

## Module 2: LinkedIn Job Auto-Scraping

### Problem

> "Browsing job boards daily is exhausting, and it's hard to judge which ones are worth applying to."

### Solution

**AI Controls Your Browser**—Based on your personal background and specific requirements, automatically:

1. **Open LinkedIn Jobs** with your personalized search queries
2. **Click into each posting** and read the full JD
3. **Compare against your background** and evaluate fit (based on your resume, skills, objectives)
4. **Research H1B support** (if visa is required)
5. **Rank by fit** and output TSV file

### Personalization

- Search queries derived from your profile, not generic templates
- Fit evaluation based on your specific skills and experience
- Ranking considers your specific requirements (location, remote, company type, etc.)

### Sample Output

```tsv
title	company	location	posting_date	short_description	reasoning	job_link
Data Scientist	Stripe	Remote	2 days ago	Build ML models for fraud detection	High skill match, sponsors H1B, excellent eng culture	https://linkedin.com/jobs/view/123
ML Engineer	Notion	SF (Hybrid)	1 week ago	Optimize recommendation systems	Matches ML background, unicorn company, strong growth	https://linkedin.com/jobs/view/456
```

### Core Value

- **5 minutes daily** replaces 2 hours of manual searching
- **Never miss** qualified new postings
- **Prioritized** so you know what to apply to first

---

## Module 3: Identify Key Contacts

### Problem

> "Applied and heard nothing back. No idea who's reviewing my resume or how to follow up."

### Solution

**AI Controls Your Browser**—For your specific target positions and companies, identify key contacts:

| Role | Value |
|------|-------|
| **Recruiter** | Screens resumes, can help you enter the interview pipeline |
| **Hiring Manager** | Final decision maker, knows the role requirements best |
| **Future Peers** | Potential colleagues, can refer you and provide insider info |
| **Alumni** | **Your** school alumni, more willing to help, higher response rates |

### Personalization

- Find alumni working at target companies based on **your school**
- Identify corresponding Recruiters and Hiring Managers for **your specific applied positions**
- Match contacts most likely to help based on **your background**

### Sample Output

```tsv
name	role	company	title	contact	reason
Jane Doe	Recruiter	Stripe	Technical Recruiter	LinkedIn: /in/janedoe	Handles Data Science recruiting
John Smith	Alumni	Stripe	Senior Data Scientist	LinkedIn: /in/johnsmith	CMU alumni, same role, can refer
```

---

## Module 4: Send Cold Messages

### Problem

> "Found the contacts, but don't know how to reach out. Messages get no replies."

### Solution

**AI Tools**—With a **killer project targeting the specific role** already built, assist in sending cold messages:

**Core Formula:**

```
You're hiring for [Position]
I built [Matching Project]
Here's the link: [Live Demo]
It's directly relevant—could you refer me or offer an interview?
```

### Why It Works

1. **Project demonstrates capability**: Not empty talk—they can click and see it
2. **Precisely relevant**: Project content highly matches job requirements
3. **Lowers their effort**: No need to guess if you can do it—the project shows it
4. **Differentiation**: 99% of people only send resumes

### Response Rate Comparison

| Approach | Expected Response Rate |
|----------|----------------------|
| Mass applying | < 5% |
| Cold Message (no project) | 10-15% |
| **Cold Message (with killer project)** | **30-50%** |

---

## Systematic Workflow Summary

```
┌──────────────────────────────────────────────────────────┐
│  Prerequisites: Complete Profile Preparation             │
│  (Resume + Narrative + Objective)                        │
│  (Completed by Resume / Narrative / Objective Modules)   │
└─────────────────────────┬────────────────────────────────┘
                          ▼
┌──────────────────────────────────────────────────────────┐
│  Module 1: AI Research Tools generate search strategy    │
│            and target company list                       │
│            → Queries + Filters + Companies + Career Pages│
└─────────────────────────┬────────────────────────────────┘
                          ▼
┌──────────────────────────────────────────────────────────┐
│  Module 2: AI Controls Your Browser to scrape jobs       │
│            Based on your background and requirements     │
│            Daily scrape of latest postings               │
│            Ranked by personalized fit                    │
└─────────────────────────┬────────────────────────────────┘
                          ▼
┌──────────────────────────────────────────────────────────┐
│  Module 3: AI Controls Your Browser to find contacts     │
│            Based on your school, applied positions,      │
│            target companies                              │
│            Find Recruiters / HMs / Alumni                │
└─────────────────────────┬────────────────────────────────┘
                          ▼
┌──────────────────────────────────────────────────────────┐
│  Module 4: AI-Assisted Cold Message Outreach             │
│            Proactive outreach with killer project links  │
│            "I built XX project, directly relevant,       │
│             could you refer me?"                         │
└──────────────────────────────────────────────────────────┘
```

---

## Why This Workflow Works

### Pain Points of Traditional Job Hunting

| Pain Point | Consequence |
|------------|-------------|
| Mass applying | Apply to 100, hear back from < 5 |
| Don't know which companies | Miss opportunities or apply to mismatches |
| Can't find contacts | Can only wait for ATS screening, completely passive |
| No project portfolio | No differentiation from other fresh grads |

### Our Solution

| Module | Problem Solved |
|--------|----------------|
| Module 1 | **Don't know what to apply to** → AI Research Tools generate search strategy and company list |
| Module 2 | **Daily job browsing is exhausting** → AI Controls Your Browser to scrape, filter, and rank |
| Module 3 | **Can't find contacts** → AI Controls Your Browser to find Recruiters, HMs, Alumni |
| Module 4 | **No differentiation** → AI-assisted proactive outreach with killer projects |

### Core Advantage

> **Modules 2 + 3 are traditionally the most tedious, time-consuming steps (especially Module 3, which is nearly impossible manually), but with AI controlling your browser, they become trivially easy.**

> **Combined with killer projects (equivalent to or exceeding the qualifications the target role seeks) and Module 4's proactive outreach, response rates dramatically increase.**
