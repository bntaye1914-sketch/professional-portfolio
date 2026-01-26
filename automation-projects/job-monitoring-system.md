# GitHub Actions Job Monitoring System

> **Project Type:** Process Automation | Career Development Tool  
> **Technologies:** GitHub Actions, Python, USAJobs API, LinkedIn  
> **Date:** December 2024 - January 2025

---

## Problem Statement

Job searching for specialized federal positions (grants management, capital infrastructure) is:
- **Time-intensive:** Manual daily checks across multiple platforms
- **Inefficient:** Same positions resurface without status tracking
- **Reactive:** Missing new postings in narrow search windows

**Goal:** Build automated system to monitor federal and private sector job boards, track new positions, and eliminate manual repetitive work.

---

## Solution Design

### Architecture

```
GitHub Actions (Scheduled)
→ Python Script (API calls + web scraping)
→ USAJobs API (federal positions)
→ LinkedIn Jobs (private sector)
→ Deduplicate & Filter
→ Markdown Report Generation
```

### Key Features

1. **Automated Scanning:** Runs daily via GitHub Actions cron schedule
2. **Multi-Platform Coverage:** USAJobs (federal) + LinkedIn (private sector)
3. **Intelligent Filtering:** Keywords: grants, capital, infrastructure, program management
4. **Deduplication:** Tracks previously seen positions to surface only new opportunities
5. **Structured Output:** Markdown reports with position details, links, deadlines

---

## Results

### First Run (January 2025)

- **52 grants-related positions identified**
- **15 capital infrastructure roles** matching target criteria
- **Zero manual effort** post-deployment

### Time Savings

- **Before:** 45-60 minutes daily across multiple job boards
- **After:** 5 minutes reviewing automated report
- **Annual savings:** ~250+ hours

### Secondary Benefits

- Complete historical tracking of target positions
- Pattern analysis: which agencies hire when
- Reduced job search fatigue and decision paralysis

---

## Skills Demonstrated

| Skill | Application |
| ------- | ------------- |
| **Process Automation** | Eliminated repetitive manual tasks through systematic workflow |
| **API Integration** | USAJobs API authentication, rate limiting, error handling |
| **Data Engineering** | Deduplication logic, historical tracking, structured output |
| **GitHub Actions / CI-CD** | Scheduled workflows, secrets management, artifact storage |
| **Python Development** | Web scraping, API clients, data transformation |

---

## Related Artifacts

- **[AI-Enabled Process Improvement Case Study](../case-studies/ai-process-improvement-higher-ed.md)**
- **[Lean Six Sigma Green Belt](../certifications/lean-six-sigma-green-belt.md)**

---

**Author:** Ta'ye Bailey, MBA, MSHE  
**Date:** January 2025
