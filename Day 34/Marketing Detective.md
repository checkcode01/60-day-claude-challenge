# Day 34 – Marketing Detective

## Objective
Built an interactive **Marketing Detective** application using Claude AI to learn how marketers investigate campaign failures, analyze customer behavior, identify root causes, and improve marketing performance through evidence-based decision making.

---

## Features

- 🕵️ Interactive Marketing Detective Game
- 📂 Randomized Marketing Investigation Cases
- 📌 Draggable Evidence Board
- 📊 Campaign Metrics Analysis
- 💬 Customer Feedback Analysis
- 📈 Social Media Performance Review
- 🎯 Marketing Mistake Identification
- ✅ Expert Explanation & Verdict
- 📚 Marketing Learning Report
- 🌙 Premium Dark Detective Theme
- 📱 Responsive Offline HTML Application

---

## Technologies Used

- Claude AI
- HTML5
- CSS3
- JavaScript (or React via CDN if generated)
- GitHub

---

# Screenshots

## Home Screen

![Home](screenshots/home.png)

## Case Assignment

![Case](screenshots/case-assignment.png)

## Investigation Board

![Investigation](screenshots/investigation-board.png)

## Solved Marketing Case

![Solved](screenshots/solved-case.png)

## Marketing Learning Report

![Report](screenshots/learning-report.png)

---

# Key Learnings

- Marketing decisions should be driven by data rather than assumptions.
- Low conversion rates often stem from targeting or messaging issues.
- Customer feedback provides valuable clues for campaign optimization.
- Budget allocation across channels significantly impacts campaign success.
- Interactive case studies improve marketing problem-solving skills.

---

# Challenges Faced

- Generating a large standalone HTML application.
- Testing drag-and-drop interactions.
- Ensuring all JavaScript functionality worked offline.
- Verifying responsive layout across devices.

---

# Outcome

Successfully created an offline interactive **Marketing Detective** application that simulates real-world marketing investigations using fictional business cases and evidence-based learning.

---

# Repository Structure

Day34/

- MarketingDetective.html
- day34.md
- screenshots/
  - home.png
  - case-assignment.png
  - investigation-board.png
  - solved-case.png
  - learning-report.png

---

# Status

✅ Successfully completed **Day 34 – Marketing Detective** as part of the **ABTalks 60-Day Claude Challenge**.

## PROMPT
You are an expert frontend developer, UX designer, instructional designer, and marketing strategist.

Ask the user to choose a color theme from a few presets (including Claude Orange).

Create a beautiful single-file HTML application called 'Marketing Detective'.

Use React via CDN + Babel. However, if React/Babel would prevent the app from running reliably as a standalone local HTML file, automatically switch to an equivalent implementation using pure HTML, CSS and vanilla JavaScript. Do not use Tailwind, npm, backend, APIs, databases, images or external assets.

The application should feel like a polished detective game, not a business dashboard. Every interaction should create curiosity before revealing the next clue.

Generate 10 detailed fictional marketing cases. If output quota allows, expand to 15–20 cases. Store them inside a JavaScript array and randomly load a new case each replay.

Each case must contain:
• Company Name
• Industry
• Campaign Objective
• Target Audience
• Marketing Channels
• Budget Allocation
• Campaign Metrics (Reach, CTR, Engagement, Conversions, Sales)
• Customer Comments
• Social Media Performance
• One Primary Marketing Mistake
• Three Supporting Clues
• Correct Explanation
• Suggested Improvements

User Flow:
1. Case Assignment
2. Investigation Board
3. Interactive Investigation with draggable evidence
4. Solve the Case
5. Case Closed animation
6. Learning Report

Design a premium dark detective aesthetic using corkboards, folders, sticky notes, push pins, paper textures, glowing accents, smooth transitions, hover effects, progress indicators, animated charts, and responsive layout.

Reuse React components wherever possible.

Before returning the final HTML, internally verify there are no syntax or runtime errors and that the application runs correctly as a standalone HTML file.

Return ONLY the complete HTML file.
