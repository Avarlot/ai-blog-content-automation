# Automation Architecture

This automation orchestrates multiple services to generate SEO blog drafts automatically.

## Trigger

The workflow starts from Google Sheets where keywords are stored.

## Pipeline

Google Sheets (keyword input)
↓
SERP retrieval
↓
JSON parsing
↓
AI outline generation
↓
JSON validation
↓
AI section writing
↓
WordPress draft creation
↓
Result logging in Google Sheets

## Components

### Google Sheets
Used as the input source for keywords and as the output log for generated content.

### Make.com
Orchestrates the workflow and connects all services together.

### OpenAI
Generates the outline, article sections, and introduction.

### WordPress
Receives generated content as draft blog posts.

## Design Goals

- automate SEO content generation
- reduce manual writing effort
- maintain structured article outlines
- centralize tracking through Google Sheets
