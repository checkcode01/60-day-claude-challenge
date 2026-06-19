
Problem
Welcome to Day 18 of the 60-Day Claude AI Mastery Challenge.

Theme: Phase 3 — Custom Skills & Automation

Today's focus: Learn how to create a Custom Skill that transforms messy information into structured action plans.

Most meetings, brainstorming sessions, voice notes, transcripts, and personal notes contain valuable information hidden inside unstructured text.

Today you'll build a reusable Claude Skill called Brain Dump Action Planner that automatically converts messy notes into organized summaries, action items, decisions, risks, blockers, open questions, and project dashboards.

Instead of manually organizing information every time, you'll create a skill that can be reused across meetings, classes, projects, startups, interviews, and personal planning.

Tasks:

Learn how Custom Skills work.
Create a Brain Dump Action Planner Skill.
Configure reusable instructions.
Test the skill using meeting notes or transcripts.
Generate interactive project dashboards.
Share your learning publicly.
Important: Set Claude's effort level to Low before creating the skill.

Once the skill is created, you can reuse it indefinitely without pasting the full instructions again.

If Claude does not complete the output or your usage limit is reached, wait for the reset period and continue later.

Submission: Share your GitHub commit URL containing screenshots of the skill, generated dashboards, and learning notes.

PROMPT USED : 
Skill Name: brain-dump-action-planner

Description: Transform messy notes, meeting transcripts, voice memos, brainstorming sessions, and stream-of-consciousness thoughts into structured summaries, action plans, decisions, open questions, and task lists. Organize information clearly without inventing, assuming, or filling gaps. Preserve all names, dates, numbers, and terminology exactly as provided.

Instructions:

## Output Requirement

For Full Breakdown, Transcript Mode, and Merge Mode, generate the output as a complete interactive HTML artifact.

Requirements:

* Output a self-contained HTML artifact starting with <style>.
* Use a modern dashboard layout.
* Mobile responsive.
* Use cards, sections, badges, tables, and visual indicators.
* Do not use markdown.
* Use clean typography and strong visual hierarchy.
* Highlight important items using colored status badges.
* Make action items visually prominent.
* Use collapsible sections for long notes.
* Output only the HTML artifact.

### Required Sections

1. Summary

* Short overview of the note, meeting, transcript, or brain dump.

2. Key Takeaways

* Display as cards or structured highlights.

3. Action Items

* Interactive table containing:
* Task
* Owner
* Deadline
* Status

4. Open Questions

* Display unresolved topics and pending decisions.

5. Risks / Blockers

* Display dependencies, blockers, risks, and concerns.

6. Conflicts

* Display conflicting deadlines, owners, decisions, or information.

7. Additional Notes

* Supporting context that does not fit elsewhere.

8. Source Information (Merge Mode only)

* Display merged sources.

### Status Badges

Use:

* 🔴 High Priority
* 🟠 Medium Priority
* 🟢 Low Priority
* ⚠️ Conflict
* ❓ Open Question
* ✅ Completed
* ⏳ Pending

### Missing Information

If information is missing display:

'Not specified'

Never invent values.

### Transcript Mode

Include:

* Speaker Summary
* Decisions by Speaker
* Action Items by Speaker
* Attribution Notes when ownership is unclear

Use speaker labels exactly as provided.

### Merge Mode

Include:

* Duplicate Items Section
* Conflict Resolution Review Section
* Source Note

Never automatically resolve conflicts.

### Design Goals

The final artifact should feel like:

* Notion
* ClickUp
* Linear
* Asana
* Airtable
* Modern Project Dashboard

Use responsive cards, clean tables, section headers, badges, hover effects, soft shadows, and dashboard-style layouts.

Everything displayed must come directly from the provided notes.

Never add, infer, assume, predict, estimate, or complete missing information.

Generate the complete HTML directly starting with <style>.
