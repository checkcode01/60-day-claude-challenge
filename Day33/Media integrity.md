Day33/
│── day33.md
│── MediaIntegrityAnalyzer.html
│── screenshots/
│     ├── home.png
│     ├── headline-detective.png
│     ├── emotion-detector.png
│     ├── dashboard.png


# Day 33 – Media Integrity Analyzer

## Objective
Built an interactive Media Integrity Analyzer using Claude that teaches users how to identify misleading headlines, emotional manipulation, and media bias through guided learning.

## Features
- Interactive Headline Detective
- Emotion Detector
- Live Media Integrity Metrics
- Media Integrity Dashboard
- Theme Selection
- Responsive UI
- Offline Single HTML Application

## Technologies Used
- HTML
- CSS
- JavaScript
- Claude AI

## Screenshots : https://claude.ai/public/artifacts/6a06334f-3f09-40b1-a3f9-feafef0cac65

### Home Screen
![Home] <img width="2560" height="1600" alt="1000038287" src="https://github.com/user-attachments/assets/87a7c19f-bc8e-4f68-9429-1a786ba1a400" />


### Headline Detective
![Headline](screenshots)

<img width="2560" height="1600" alt="1000038289" src="https://github.com/user-attachments/assets/d1864ae1-e6a7-48aa-8099-0f6051d6db16" />


### Emotion Detector
![Emotion](screenshots/emotion-detector)
<img width="2560" height="1600" alt="1000038293" src="https://github.com/user-attachments/assets/c9cf95a4-7c04-4664-9f28-939e5c85d5d8" />


### Final Dashboard
![Dashboard](screenshots/dashboard)

<img width="2560" height="1600" alt="1000038299" src="https://github.com/user-attachments/assets/bdeaddac-5616-40f8-a1d9-094f074d3592" />


## Key Learnings

- Headlines can influence perception before reading the article.
- Emotional language is often used to drive engagement.
- Separating facts from opinions improves critical thinking.
- Media should be evaluated using evidence rather than emotions.
- Interactive learning makes media literacy easier to understand.

## Challenges Faced

- Generating a large HTML file.
- Testing responsiveness.
- Verifying all interactions worked correctly.

## Outcome

Successfully created a single-file offline Media Integrity Analyzer with an interactive educational experience.

## Repository Structure

Day33/
- MediaIntegrityAnalyzer.html
- day33.md
- screenshots/

## Status

✅ Completed Day 33 of the ABTalks 60-Day Claude Challenge.

## PROMPT USED
You are an expert frontend developer, UX designer, instructional designer, and media literacy analyst.

Ask the user to choose a color theme from a few options (including Claude Orange).

Create a beautiful single-file HTML application called 'Media Integrity Analyzer'.

Use pure vanilla CSS and JS. No Tailwind, npm, backend, APIs, images, or external assets. Everything must work offline in one HTML file.

The goal is to teach media literacy through interactive discovery, not test prior knowledge. The experience should feel like a guided lesson where users learn by observing, thinking, and then revealing the answer.

Make it interactive.

Before each challenge, briefly explain the concept in simple language, why it matters, and how it applies to everyday life.

Challenge 1: Headline Detective
- Generate a fictional news headline and matching article.
- Ask: Would you click this? (Yes / Maybe / No)
- Ask the user to identify exaggerated or misleading parts.
- Reveal the Headline Accuracy Score, highlighted mismatches, explanation, fair rewritten headline, and key takeaway.

Challenge 2: Emotion Detector
- Generate a fictional social media post, reel caption, or article excerpt.
- Ask how it made the user feel and which words influenced that feeling.
- Reveal the target audience, intended emotional response, manipulation technique, highlighted emotional phrases, neutral rewrite, and key takeaway.

Display live Media Integrity metrics:
- Headline Accuracy
- Source Reliability
- Emotional Manipulation
- Audience Targeting

Finish with a Media Integrity Dashboard containing:
- Overall Media Integrity Score
- What the user learned
- Biggest red flag
- Three practical media literacy habits
- Replay with completely new scenarios

Design a premium editorial-style dark interface with smooth animations, progress indicators, hover effects, modern cards, and responsive layout.

Ensure there are zero syntax errors.

Return ONLY the complete HTML inside one code block.
