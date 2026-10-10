# SafeRoute — Drive Smart. Ride Safe. Know the Rules.

**Project:** SafeRoute — Smart Road Safety, Learner Preparation & Safety Awareness Platform  
**Tagline:** *Drive Smart. Ride Safe. Know the Rules.*

SafeRoute is a frontend-only educational web application designed to help users learn road-safety concepts, understand road signs, practise learner-style questions, and explore how driving conditions can affect safety.

## Features

### 1. Road-Safety Learning Center
- Covers 12 road-safety topics, including traffic signals, lane discipline, following distance, seat belts, helmets, phone distraction, speed management, pedestrian safety, night driving, rain safety, emergency vehicles, and fatigue.
- Lets users track topic completion and reveal quick-question answers.

### 2. Road Signs Center
- Includes 12 educational road-sign examples.
- Provides search and category filters.
- Shows sign details and includes a “Test Me” reveal challenge.
- The examples are for learning and are not a replacement for official road-sign standards.

### 3. Licence & RTO Guide
- Provides general educational information about learner’s licences, driving licences, and vehicle types.
- Users are reminded to verify current rules, fees, age requirements, validity, penalties, and procedures through official sources.

### 4. Practice Center
- Offers three practice modes:
  - Quick Practice: 10 questions
  - Standard Practice: 20 questions
  - Mock Test: 25 questions with a 15-minute timer
- Provides answers, explanations, category performance, and recommendations.
- Practice questions are evaluated in the browser.

### 5. Safety Scenarios
- Presents “What Would You Do?” situations with choice-based feedback.
- Records scenario results in local progress data.

### 6. Safe Journey Assessment
- Lets users enter journey-related details such as travel mode, time of travel, weather, road condition, and experience level.
- Produces an educational safety score, risk indication, and recommendations based on the selected conditions.
- This is a rule-based educational assessment; it does **not** use live GPS, traffic, weather, or accident data.

### 7. What-If Safety Simulator
- Allows users to explore how selected conditions—such as vehicle type, time, weather, and experience—affect an educational safety score.

### 8. Personal Dashboard & Achievements
- Tracks learning progress, quiz accuracy, completed tests, questions attempted, topic performance, and achievements.
- Includes a reset-progress option.

### 9. Interface
- Responsive layout for different screen sizes.
- Dark/light theme toggle.
- Mobile navigation and smooth section navigation.

## Technology

- **HTML5** for page structure
- **CSS3** for styling, responsive layout, themes, and animations
- **Vanilla JavaScript** for interactions, quizzes, assessments, scoring, and progress tracking
- **Browser LocalStorage** for saving progress and preferences on the user's device

## Architecture & Data Storage

SafeRoute is designed as a single-page, frontend-only application. The website's markup, styles, and JavaScript are contained in one HTML file (`index.html`). It does not require a custom backend, server, account system, or external database.

Progress and preferences are saved in the browser using the LocalStorage key `saferoute_state_v1`. This means saved data is local to the browser/device and may not automatically transfer to another browser or device. Clearing browser storage can remove saved progress.

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Use the navigation to explore the learning center, road signs, practice modes, scenarios, journey assessment, simulator, and dashboard.

No build step or package installation is required.

## Important Limitations

- SafeRoute is an educational project, not an official government or RTO service.
- Its scores and recommendations are simplified learning aids, not professional driving assessments or guarantees of road safety.
- Quiz practice results do not guarantee passing an official learner's or driving test.
- The journey assessment and simulator use the choices entered by the user; they do not fetch live road, traffic, weather, GPS, or accident information.
- Check official government/RTO sources for current licensing rules and legal requirements.

## Project Structure

```text
SafeRoute/
├── index.html
└── README.md
```

## Future Improvements

Possible future improvements, subject to project scope, include linking users to verified official licensing resources, expanding road-sign and practice-question coverage, and improving accessibility and testing.

## Author / Submission

Prepared for the **Hackoverflow 10.0** coding-phase submission.

**Project Name:** SafeRoute  
**Tagline:** Drive Smart. Ride Safe. Know the Rules.

---

*© 2026 SafeRoute — Frontend-only educational road-safety project.*
