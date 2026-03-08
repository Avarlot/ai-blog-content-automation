# AI Blog Generation Automation

Automation pipeline built with Make.com that generates SEO blog drafts from keyword inputs using SERP analysis and AI-generated content.

The system orchestrates multiple tools to transform keywords stored in Google Sheets into structured blog posts that are automatically created as drafts in WordPress.

---

# Overview

Producing SEO content at scale requires multiple repetitive steps:

- keyword research
- SERP analysis
- outline generation
- article writing
- publishing drafts
- tracking production

This automation centralizes the entire workflow into a single automated pipeline.

Starting from a keyword list stored in Google Sheets, the system retrieves search results, generates structured article outlines using AI, writes article sections, and publishes the draft to WordPress.

The result is a scalable system for **automated content production**.

---

# Automation Workflow

The automation follows this pipeline:
Google Sheets (keywords)
↓
Retrieve SERP data
↓
Parse and structure results
↓
Generate SEO outline with AI
↓
Validate JSON structure
↓
Generate article sections
↓
Generate introduction
↓
Create WordPress draft
↓
Log article URL in Google Sheets

---

# Tools Used

This automation integrates several tools:

- **Make.com** – workflow orchestration
- **OpenAI API** – content generation
- **Google Sheets** – keyword input & production tracking
- **WordPress API** – blog draft creation
- **JSON tools** – structured data validation

---

# Example Use Case

1. A list of keywords is added to Google Sheets.
2. The automation is triggered.
3. SERP results are retrieved for the keyword.
4. An SEO outline is generated using AI.
5. Each section of the article is written automatically.
6. The introduction is generated.
7. A draft article is created in WordPress.
8. The result is logged back into Google Sheets.

This allows content teams to generate structured article drafts automatically.

---

# Scenario

Below is the automation scenario built in Make.com.

![Automation Scenario](scenario.png)

---

# Possible Improvements

Potential future improvements include:

- automatic internal linking generation
- SEO scoring before publishing
- automatic image generation
- content quality validation
- publishing scheduling
- integration with CMS editorial workflows
