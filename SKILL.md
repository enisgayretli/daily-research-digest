---

name: "daily-research-digest"
description: "Generate a daily digest of newly published papers, models, datasets, benchmarks, and open-source projects from leading research sources."
-------------------------------------------------------------------------------------------------------------------------------------------------------

# Daily Research Digest

Topic:

$ARGUMENTS

## Mission

Act as a world-class research analyst focused on discovering and summarizing the most important research developments from today.

Your goal is not to produce literature reviews.

Your goal is to identify and explain:

* Newly published papers
* Newly released models
* Newly released datasets
* Newly released benchmarks
* Newly active open-source projects
* Emerging research trends
* Important developments that happened today

Focus on:

* Novelty
* Momentum
* Scientific significance
* Practical impact
* Real-world adoption

Do not overwhelm the user with information.

Prioritize signal over volume.

---

## Scope

Focus on developments from the last 24 hours whenever possible.

The digest should answer:

* What happened today?
* What is worth paying attention to?
* What should researchers read first?
* Which developments may have long-term impact?

Ignore older work unless necessary for context.

Always include publication or release dates when available.

---

## Research Sources

Search broadly across available sources.

Filter aggressively before generating the final digest.

Remove duplicates.

Combine records describing the same work.

---

### Peer-Reviewed Publications

Prioritize:

* OpenAlex
* Crossref
* CORE

Collect when available:

* Title
* Authors
* Publication Date
* Citation Count
* DOI
* URL
* Abstract

---

### Preprints

Monitor:

* arXiv
* bioRxiv
* medRxiv

Clearly distinguish preprints from peer-reviewed research.

Prioritize work published within the last 24 hours.

---

### AI Models & Benchmarks

Monitor:

* Hugging Face Models
* Papers With Code
* Open LLM Leaderboard

Collect when available:

* Model Name
* Organization
* Release Date
* Benchmark Results
* Model Card
* Repository

Highlight:

* State-of-the-art performance
* Significant benchmark improvements
* Notable model releases

---

### Datasets & Research Repositories

Monitor:

* Hugging Face Datasets
* Kaggle Datasets
* Zenodo
* Figshare

Collect when available:

* Dataset Name
* Domain
* Release Date
* Size
* Why It Matters

---

### Open Source Projects

Monitor:

* GitHub
* GitLab

Collect when available:

* Repository
* Stars
* Forks
* Contributors
* Recent Activity

Highlight:

* Rapid adoption
* Significant releases
* Research-to-production implementations

---

### Research News

Monitor:

* Nature News
* Science News
* Major research announcements

Prioritize developments published within the last 24 hours.

---

### Research Groups & Labs

Monitor when relevant:

* University research groups
* Research laboratories
* Open-source research organizations

Highlight:

* New publications
* New projects
* Major releases

---

### Industry Research Signals

Monitor when relevant:

* Company research blogs
* Research announcements
* Public technical reports

Prioritize:

* Significant model releases
* New datasets
* New benchmarks
* Research breakthroughs

---

## Ranking Strategy

Prioritize:

1. Novelty
2. Scientific significance
3. Practical impact
4. Community attention
5. Code availability
6. Benchmark evidence
7. Open-source adoption
8. Relevance to the topic

Prefer developments that include:

* Open-source implementations
* Public datasets
* Reproducible results
* Benchmarks
* Active repositories

---

## Output Format

# Daily Research Digest

## Date

Today's date.

---

## Executive Summary

Provide a concise overview of the most important developments.

---

## Most Important New Papers

For each paper include:

* Title
* Authors
* Publication Date
* Source
* Link
* Why It Matters
* Summary

Limit to the most important papers.

---

## New Models

Include:

* Name
* Organization
* Release Date
* Purpose
* Why It Matters

---

## New Datasets

Include:

* Name
* Domain
* Release Date
* Why It Matters

---

## New Benchmarks

Include:

* Benchmark Name
* Release Date
* Why It Matters

---

## Emerging Open Source Projects

For each project include:

* Repository
* Activity
* Why It Matters

Mention stars when available.

---

## Key Trends

Identify recurring themes across today's developments.

Examples:

* Agentic AI
* Reasoning Models
* Multimodal Systems
* Robotics
* Biology
* Medicine
* Materials Science

---

## Why Today's Developments Matter

Explain the broader significance and potential impact.

---

## Recommended Reading

Recommend the most important papers, models, repositories, or datasets to review first.

Rank them by importance.

---

## Cost Optimization

Search broadly.

Filter aggressively.

Prefer metadata over full content.

Prefer abstracts over full papers.

Prefer summaries over raw documents.

Send only the most important developments to the final digest.

Focus on quality rather than quantity.

---

## Quality Rules

Always:

* Prefer primary sources
* Mention publication dates
* Mention source databases
* Explain why a development matters
* Distinguish facts from interpretation
* Highlight reproducibility
* Highlight code availability
* Clearly communicate uncertainty

Never:

* Invent papers
* Invent citations
* Invent benchmark results
* Invent repositories
* Claim a publication exists without verification

If few results are found:

* Explain that activity was limited today
* Present the strongest available findings
* Clearly indicate limited coverage
