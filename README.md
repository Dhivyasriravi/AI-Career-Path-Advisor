# AI Career Path Advisor

A personalised AI-powered career guidance tool that analyses your skills, interests, education and goals through a 10-step quiz and generates a complete career roadmap with role recommendations, skills gap analysis, learning resources, and actionable tips.

**Built by:** Dhivyasri Ravi | CSE Graduate 2026

---

## Live Demo
[View Live](https://yourusername.github.io/ai-career-advisor)

---

## About the Project

AI Career Path Advisor is an intelligent career counselling web application designed for students and fresh graduates who are unsure about their career direction. The user answers 10 targeted questions about their background, skills, interests and goals. The AI then generates a fully personalised career roadmap with specific phases, timelines, role matches, salary expectations, and recommended learning resources — all in a single HTML file with no backend or installation required.

---

## Features

- 10-step interactive quiz covering education, skills, interests, experience, goals and challenges
- AI generates 4 career roles best matched to the user's profile with salary range in LPA
- 4-phase personalised roadmap with specific action items and duration for each phase
- Skills gap bar chart comparing current skill level vs required level using Chart.js
- 6 curated learning resources tailored to the user's career path
- 5 personalised pro tips based on the user's profile
- Motivational quote generated specifically for the user
- Print or save as PDF functionality
- Retake quiz option to explore different career paths
- Galaxy particle animation background
- Fully responsive — works on desktop and mobile
- 100% free — powered by Groq API, no payment required

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Frontend and UI |
| Chart.js | Skills gap bar chart visualisation |
| Groq API (LLaMA 3.3 70B) | AI career analysis and roadmap generation |
| Canvas API | Galaxy particle background animation |

---

## How to Run

### Step 1 - Get Free Groq API Key
```
1. Go to https://console.groq.com
2. Sign up with Gmail (free, no credit card needed)
3. Click API Keys in the left sidebar
4. Click Create API Key and copy it (starts with gsk_...)
```

### Step 2 - Add API Key to Code
```javascript
// Open ai_career_advisor.html in VS Code
// Find this line near the top of the script section:
const GROQ_KEY = 'YOUR_GROQ_API_KEY_HERE';

// Replace with your actual key:
const GROQ_KEY = 'gsk_yourrealkeyhere';
```

### Step 3 - Run the Project
```
Option A: Double-click the HTML file and open in Google Chrome
Option B: Open in VS Code, right-click, select Open with Live Server
Option C: Deploy on GitHub Pages (see deployment section below)
```

---

## Deployment on GitHub Pages (Free Hosting)

```
1. Create a new GitHub repository named: ai-career-advisor
2. Upload the HTML file and rename it to index.html
3. Also upload the README.md file
4. Go to repository Settings
5. Scroll down to the Pages section
6. Under Source, select the main branch and click Save
7. Your live site will be available at:
   https://yourusername.github.io/ai-career-advisor
```

---

## Project Structure

```
ai-career-advisor/
|
|-- index.html        (Complete project in a single file)
|-- README.md         (Project documentation)
```

---

## How It Works

1. The user goes through a 10-step quiz covering name, education, field of study, current skills, interests, experience level, career goal, timeline, biggest challenge, and any additional information.
2. All answers are compiled into a structured profile prompt.
3. The prompt is sent to the Groq API using the LLaMA 3.3 70B model.
4. The AI returns a structured JSON response containing matched roles, roadmap phases, skills gap data, resources, tips, and a motivational quote.
5. The JSON is parsed and rendered dynamically into a fully formatted career report.
6. Chart.js renders the skills gap bar chart comparing current vs required skill levels.
7. The user can print the full report or save it as a PDF using the browser.

---

## Quiz Steps Overview

| Step | Question |
|---|---|
| 1 | Name |
| 2 | Current education level |
| 3 | Field of study or work |
| 4 | Current technical skills (multi-select) |
| 5 | Areas of interest (multi-select) |
| 6 | Work and project experience |
| 7 | Primary career goal |
| 8 | Desired timeline to achieve goal |
| 9 | Biggest challenge right now |
| 10 | Any additional information |

---

## Output Sections

| Section | Description |
|---|---|
| Career Roles | 4 best-matched roles with match percentage and salary |
| Roadmap | 4 phases with action items and duration |
| Skills Gap | Bar chart of current vs required skill levels |
| Resources | 6 recommended platforms and courses |
| Pro Tips | 5 personalised career tips |
| Motivational Quote | AI-generated quote tailored to the user |

---

## Future Improvements

- Add PDF export with formatted layout using jsPDF
- Add domain-specific quiz paths for non-tech fields
- Save and share roadmap via a unique URL
- Add mentor recommendation based on career path
- Support multiple languages including Tamil and Hindi

---

## Author

**Dhivyasri Ravi**
- Email: dhivyasriravi5@gmail.com
- LinkedIn: https://www.linkedin.com/in/dhivyasri1603/
- GitHub: https://github.com/Dhivyasriravi

---

## License

MIT License - free to use and modify.

