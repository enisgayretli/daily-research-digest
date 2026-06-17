# Daily Research Digest

<p align="center">
  <img src="./assets/icon.png" width="128" alt="Daily Research Digest">
</p>

A cross-platform daily research briefing skill for AI agents.

Compatible with Claude Code, Codex CLI, Gemini CLI, Cursor, Windsurf, Cline, Roo Code, GitHub Copilot, OpenCode, Hermes, and other Skill Standard compatible agents.

Daily Research Digest helps researchers, engineers, analysts, founders, and technical professionals stay up to date with the most important research developments from the last 24 hours.

The skill monitors papers, models, datasets, benchmarks, open-source projects, and research announcements, then delivers a concise daily briefing focused on what matters most.

## Compatible Agents

Daily Research Digest follows the Skills Standard and can be used with:

* Claude Code
* Codex CLI
* Gemini CLI
* OpenCode
* OpenClaw
* GitHub Copilot
* Cursor
* Windsurf
* Cline
* Roo Code
* Kiro
* Junie
* Augment Code
* Warp
* Goose

---

## Why Daily Research Digest?

Research moves fast.

Keeping up with today's developments is hard.

Daily Research Digest helps answer:

* What happened today?
* Which papers were released today?
* Which new models appeared?
* Which repositories gained attention?
* Which research trends are accelerating?
* What deserves immediate attention?

Instead of searching across dozens of sources, Daily Research Digest identifies the most important developments and explains why they matter.

---

## Features

### Daily Research Monitoring

Track the most important developments from the last 24 hours.

Includes:

* New papers
* New models
* New datasets
* New benchmarks
* New open-source projects
* Research announcements

### Research Synthesis

Generate concise evidence-based research briefings.

### Trend Detection

Discover emerging research topics and growing areas of interest.

### Research-to-Code Discovery

Connect research with:

* GitHub repositories
* Benchmarks
* Datasets
* Models
* Implementations

### Open Source Intelligence

Track:

* Repository growth
* Community adoption
* Research-to-production implementations
* Emerging open-source ecosystems

---

## Supported Sources

### Peer-Reviewed Publications

* OpenAlex
* Crossref
* CORE

### Preprints

* arXiv
* bioRxiv
* medRxiv

### AI Models & Benchmarks

* Hugging Face Models
* Papers With Code
* Open LLM Leaderboard

### Datasets & Repositories

* Hugging Face Datasets
* Kaggle Datasets
* Zenodo
* Figshare

### Open Source Projects

* GitHub
* GitLab

### Research News

* Nature News
* Science News

### Research Groups & Labs

* University Research Groups
* Research Laboratories
* Open Research Organizations

### Industry Research Signals

* Research Blogs
* Research Announcements
* Technical Reports

---

## Example Prompts

### Today's AI Research

```text
What are today's most important AI research developments?
```

### Today's Models

```text
What new AI models were released today?
```

### Today's Open Source Research

```text
Which research repositories gained attention today?
```

### Today's Research Digest

```text
Give me today's research digest for multimodal AI.
```

### Today's Agent Research

```text
Summarize today's most important developments in AI agents.
```

### Today's LLM Research

```text
What happened today in large language model research?
```

---

## Output Structure

Daily Research Digest typically produces:

* Executive Summary
* New Papers
* New Models
* New Datasets
* New Benchmarks
* Emerging Open Source Projects
* Key Research Trends
* Research Announcements
* Why Today's Developments Matter
* Recommended Reading

---

## Design Principles

Daily Research Digest follows several principles:

* Prefer primary sources over summaries
* Prefer peer-reviewed work when available
* Clearly distinguish preprints from published research
* Highlight reproducibility and code availability
* Explain why a development matters
* Focus on evidence rather than hype
* Clearly communicate uncertainty
* Prioritize novelty and significance
* Never fabricate papers, models, datasets, or citations

---

## Ideal Users

* Researchers
* Engineers
* Founders
* Product Teams
* Analysts
* Technical Writers
* Science Communicators
* Technology Leaders

---

## Roadmap

### v1

* Daily research digest
* New paper discovery
* Model monitoring
* Dataset monitoring
* Open-source project tracking
* Research news monitoring

### v2

* Personalized topic tracking
* Research memory
* Watchlists
* Research alerts

### v3

* Automated monitoring
* Project-aware research tracking
* Research trend forecasting
* Advanced research intelligence

---

## Installation

### Install via Skills Hub

Install directly from Skills Hub and choose your preferred agent.

The skill is compatible with:

* Claude Code
* Codex CLI
* Gemini CLI
* OpenCode
* OpenClaw
* GitHub Copilot
* Cursor
* Windsurf
* Cline
* Roo Code
* Kiro
* Junie
* Augment Code
* Warp
* Goose
* Hermes

---

## macOS

### One-Line Installation (Recommended)

Install Daily Research Digest across all supported agents:

```bash
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agents=claude,codex,gemini,opencode,openclaw,copilot,cursor,windsurf,cline,roo,kiro,junie,augment,warp,goose&format=sh" | bash
```

---

### Full Installation Script

```bash
#!/bin/bash
# SkillHub Installer - daily-research-digest
# Platform: macOS

set -e

# Install to Claude Code
mkdir -p "$HOME/.claude/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=claude&format=raw" > "$HOME/.claude/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Claude Code: $HOME/.claude/skills/enisgayretli-daily-research-digest"

# Install to Codex CLI
mkdir -p "$HOME/.codex/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=codex&format=raw" > "$HOME/.codex/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Codex CLI: $HOME/.codex/skills/enisgayretli-daily-research-digest"

# Install to Gemini CLI
mkdir -p "$HOME/.gemini/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=gemini&format=raw" > "$HOME/.gemini/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Gemini CLI: $HOME/.gemini/skills/enisgayretli-daily-research-digest"

# Install to OpenCode
mkdir -p "$HOME/.opencode/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=opencode&format=raw" > "$HOME/.opencode/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to OpenCode: $HOME/.opencode/skills/enisgayretli-daily-research-digest"

# Install to OpenClaw
mkdir -p "$HOME/.openclaw/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=openclaw&format=raw" > "$HOME/.openclaw/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to OpenClaw: $HOME/.openclaw/skills/enisgayretli-daily-research-digest"

# Install to GitHub Copilot
mkdir -p "$HOME/.copilot/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=copilot&format=raw" > "$HOME/.copilot/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to GitHub Copilot: $HOME/.copilot/skills/enisgayretli-daily-research-digest"

# Install to Cursor
mkdir -p "$HOME/.cursor/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cursor&format=raw" > "$HOME/.cursor/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Cursor: $HOME/.cursor/skills/enisgayretli-daily-research-digest"

# Install to Windsurf
mkdir -p "$HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=windsurf&format=raw" > "$HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Windsurf: $HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest"

# Install to Cline
mkdir -p "$HOME/.cline/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cline&format=raw" > "$HOME/.cline/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Cline: $HOME/.cline/skills/enisgayretli-daily-research-digest"

# Install to Roo Code
mkdir -p "$HOME/.roo/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=roo&format=raw" > "$HOME/.roo/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Roo Code: $HOME/.roo/skills/enisgayretli-daily-research-digest"

# Install to Kiro
mkdir -p "$HOME/.kiro/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=kiro&format=raw" > "$HOME/.kiro/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Kiro: $HOME/.kiro/skills/enisgayretli-daily-research-digest"

# Install to Junie
mkdir -p "$HOME/.junie/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=junie&format=raw" > "$HOME/.junie/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Junie: $HOME/.junie/skills/enisgayretli-daily-research-digest"

# Install to Augment Code
mkdir -p "$HOME/.augment/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=augment&format=raw" > "$HOME/.augment/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Augment Code: $HOME/.augment/skills/enisgayretli-daily-research-digest"

# Install to Warp
mkdir -p "$HOME/.warp/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=warp&format=raw" > "$HOME/.warp/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Warp: $HOME/.warp/skills/enisgayretli-daily-research-digest"

# Install to Goose
mkdir -p "$HOME/.config/goose/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=goose&format=raw" > "$HOME/.config/goose/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Goose: $HOME/.config/goose/skills/enisgayretli-daily-research-digest"

echo ""
echo "Done! Restart your agent to activate the skill."
```

---

## Windows

### One-Line Installation (Recommended)

Install Daily Research Digest across all supported agents:

```powershell
irm "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agents=claude,codex,gemini,opencode,openclaw,copilot,cursor,windsurf,cline,roo,kiro,junie,augment,warp,goose&format=ps1" | iex
```

---

### Full Installation Script

```powershell
# SkillHub Installer - daily-research-digest
# Platform: Windows (PowerShell)

# Install to Claude Code
$skillDir = "$env:USERPROFILE\.claude\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=claude&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Claude Code: $skillDir" -ForegroundColor Green

# Install to Codex CLI
$skillDir = "$env:USERPROFILE\.codex\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=codex&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Codex CLI: $skillDir" -ForegroundColor Green

# Install to Gemini CLI
$skillDir = "$env:USERPROFILE\.gemini\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=gemini&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Gemini CLI: $skillDir" -ForegroundColor Green

# Install to OpenCode
$skillDir = "$env:USERPROFILE\.opencode\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=opencode&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to OpenCode: $skillDir" -ForegroundColor Green

# Install to OpenClaw
$skillDir = "$env:USERPROFILE\.openclaw\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=openclaw&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to OpenClaw: $skillDir" -ForegroundColor Green

# Install to GitHub Copilot
$skillDir = "$env:USERPROFILE\.copilot\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=copilot&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to GitHub Copilot: $skillDir" -ForegroundColor Green

# Install to Cursor
$skillDir = "$env:USERPROFILE\.cursor\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cursor&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Cursor: $skillDir" -ForegroundColor Green

# Install to Windsurf
$skillDir = "$env:USERPROFILE\.codeium\windsurf\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=windsurf&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Windsurf: $skillDir" -ForegroundColor Green

# Install to Cline
$skillDir = "$env:USERPROFILE\.cline\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cline&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Cline: $skillDir" -ForegroundColor Green

# Install to Roo Code
$skillDir = "$env:USERPROFILE\.roo\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=roo&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Roo Code: $skillDir" -ForegroundColor Green

# Install to Kiro
$skillDir = "$env:USERPROFILE\.kiro\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=kiro&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Kiro: $skillDir" -ForegroundColor Green

# Install to Junie
$skillDir = "$env:USERPROFILE\.junie\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=junie&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Junie: $skillDir" -ForegroundColor Green

# Install to Augment Code
$skillDir = "$env:USERPROFILE\.augment\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=augment&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Augment Code: $skillDir" -ForegroundColor Green

# Install to Warp
$skillDir = "$env:USERPROFILE\.warp\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=warp&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Warp: $skillDir" -ForegroundColor Green

# Install to Goose
$skillDir = "$env:USERPROFILE\.config\goose\skills\enisgayretli-daily-research-digest"
New-Item -ItemType Directory -Force -Path $skillDir | Out-Null
Invoke-WebRequest -Uri "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=goose&format=raw" -OutFile "$skillDir\SKILL.md"
Write-Host "Installed to Goose: $skillDir" -ForegroundColor Green

Write-Host "Done! Restart your agent to activate the skill." -ForegroundColor Cyan
```

---

## Linux

### One-Line Installation (Recommended)

Install Daily Research Digest across all supported agents:

```bash
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agents=claude,codex,gemini,opencode,openclaw,copilot,cursor,windsurf,cline,roo,kiro,junie,augment,warp,goose&format=sh" | bash
```

---

### Full Installation Script

```bash
#!/bin/bash
# SkillHub Installer - daily-research-digest
# Platform: Linux

set -e

# Install to Claude Code
mkdir -p "$HOME/.claude/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=claude&format=raw" > "$HOME/.claude/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Claude Code: $HOME/.claude/skills/enisgayretli-daily-research-digest"

# Install to Codex CLI
mkdir -p "$HOME/.codex/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=codex&format=raw" > "$HOME/.codex/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Codex CLI: $HOME/.codex/skills/enisgayretli-daily-research-digest"

# Install to Gemini CLI
mkdir -p "$HOME/.gemini/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=gemini&format=raw" > "$HOME/.gemini/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Gemini CLI: $HOME/.gemini/skills/enisgayretli-daily-research-digest"

# Install to OpenCode
mkdir -p "$HOME/.opencode/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=opencode&format=raw" > "$HOME/.opencode/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to OpenCode: $HOME/.opencode/skills/enisgayretli-daily-research-digest"

# Install to OpenClaw
mkdir -p "$HOME/.openclaw/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=openclaw&format=raw" > "$HOME/.openclaw/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to OpenClaw: $HOME/.openclaw/skills/enisgayretli-daily-research-digest"

# Install to GitHub Copilot
mkdir -p "$HOME/.copilot/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=copilot&format=raw" > "$HOME/.copilot/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to GitHub Copilot: $HOME/.copilot/skills/enisgayretli-daily-research-digest"

# Install to Cursor
mkdir -p "$HOME/.cursor/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cursor&format=raw" > "$HOME/.cursor/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Cursor: $HOME/.cursor/skills/enisgayretli-daily-research-digest"

# Install to Windsurf
mkdir -p "$HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=windsurf&format=raw" > "$HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Windsurf: $HOME/.codeium/windsurf/skills/enisgayretli-daily-research-digest"

# Install to Cline
mkdir -p "$HOME/.cline/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=cline&format=raw" > "$HOME/.cline/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Cline: $HOME/.cline/skills/enisgayretli-daily-research-digest"

# Install to Roo Code
mkdir -p "$HOME/.roo/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=roo&format=raw" > "$HOME/.roo/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Roo Code: $HOME/.roo/skills/enisgayretli-daily-research-digest"

# Install to Kiro
mkdir -p "$HOME/.kiro/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=kiro&format=raw" > "$HOME/.kiro/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Kiro: $HOME/.kiro/skills/enisgayretli-daily-research-digest"

# Install to Junie
mkdir -p "$HOME/.junie/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=junie&format=raw" > "$HOME/.junie/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Junie: $HOME/.junie/skills/enisgayretli-daily-research-digest"

# Install to Augment Code
mkdir -p "$HOME/.augment/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=augment&format=raw" > "$HOME/.augment/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Augment Code: $HOME/.augment/skills/enisgayretli-daily-research-digest"

# Install to Warp
mkdir -p "$HOME/.warp/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=warp&format=raw" > "$HOME/.warp/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Warp: $HOME/.warp/skills/enisgayretli-daily-research-digest"

# Install to Goose
mkdir -p "$HOME/.config/goose/skills/enisgayretli-daily-research-digest"
curl -sL "https://www.skillhub.club/api/v1/skills/enisgayretli-daily-research-digest/install?agent=goose&format=raw" > "$HOME/.config/goose/skills/enisgayretli-daily-research-digest/SKILL.md"
echo "✓ Installed to Goose: $HOME/.config/goose/skills/enisgayretli-daily-research-digest"

echo ""
echo "Done! Restart your agent to activate the skill."
```

---

### Verify Installation

After restarting your agent, try:

```text
daily research digest for ai agents
```

or

```text
what happened today in large language model research?
```

If the skill is installed correctly, the agent should generate a Daily Research Digest using the skill.

---

## License

MIT License

---

Daily Research Digest transforms hundreds of daily research updates into a concise briefing, helping you stay informed without spending hours searching across papers, repositories, models, datasets, benchmarks, and research news.
