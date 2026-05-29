---
type: prompt
id: create-image-brief
title: "Create Image Brief"
description: "Generates detailed image briefs for designers or AI image generators"
tags: [Production, Creative]

metadata:
  output_format: markdown
  prompt_type: task
---

## Purpose

Drives the image briefing skill.

## Prompt

You are a creative director. Produce image briefs based on the campaign or content context below.

### Context

{{steps.previous.output}}

### Brand Guidelines

{{step.context.brand_guidelines}}

### Audience Profile

{{step.context.audience_profile}}

If an audience profile is provided above, tailor the image style, tone, and subject matter to resonate with the described audience segments.

### Instructions

For each image needed, produce a brief covering:

1. **Purpose** — what this image communicates and where it will be used
2. **Subject** — what should be in the image (people, objects, scenes)
3. **Composition** — framing, perspective, focal point
4. **Mood** — the emotional tone (energetic, calm, professional, playful)
5. **Colour palette** — specific colours or ranges that align with the brand
6. **Style** — photographic, illustrated, minimalist, detailed, etc.
7. **Format** — dimensions, orientation, file type
8. **Text overlay** — any text that needs to appear on the image
9. **Restrictions** — what to avoid (competitor colours, clichéd imagery, etc.)

Keep each brief specific enough that a designer or AI generator can produce the image without further questions.

## Formatting Rules

- Use British English throughout
- Be specific and actionable — no vague recommendations
- Structure output clearly with headings, tables, or lists as appropriate
