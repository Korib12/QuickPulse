# Quick Pulse

**Quick Pulse** is a **real-time classroom feedback system** designed to empower teachers with instant insights into student comprehension, while giving students a safe, anonymous way to express their understanding.

---

## Table of Contents
- [Inspiration](#inspiration)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Implementation Highlights](#implementation-highlights)  
- [Challenges](#challenges)  
- [Accomplishments](#accomplishments)  
- [Future Work](#future-work)  
- [Setup](#setup)  
- [Usage](#usage)  
- [License](#license)  

---

## Inspiration
In our **Calculus class**, we noticed a gap: teachers struggled to gauge real-time understanding, and students often silently fell behind. Traditional surveys were slow, inaccurate, and failed to capture nuanced comprehension.  

Many students avoid raising their hand out of fear of judgment. Quick Pulse addresses this **double-edged problem**: students need help but often don’t voice it, and teachers lack actionable insights.  

Our goal: create a **student-centered, teacher-empowering tool** that provides real-time feedback for dynamic, data-informed instruction.  

---

## Features
- **Anonymous student responses** via class code  
- Single-answer enforcement to prevent skewed results  
- Optional written feedback for “Lost” responses  
- Instant teacher analytics:
  - Distribution percentages
  - Written comments
  - Session history and trends
- Real-time updates via Firebase listeners  
- Draft and publish functionality to prevent lost data  
- Future-ready for gamification, engagement tracking, and adaptive learning  

---

## Tech Stack
- **Frontend:** React, JavaScript, HTML, CSS  
- **Backend / Database:** Firebase Firestore  
- **Authentication:** Firebase Auth (email + session code login)  
- **Design / Prototyping:** Figma, Claude AI  
- **Version Control:** GitHub  

---

## Implementation Highlights
- **React state** updates teacher dashboards instantly  
- **Firestore listeners** for real-time updates  
- **Conditional rendering** shows comment boxes only for 🔴 “Lost” responses  
- Dynamic computation of response percentages  
## Challenges
- Real-time state management caused initial dashboard lag
- Conditional comment logic required iterative debugging
- Design instability in early Figma mockups
- Random frontend errors during dynamic updates
- Time constraints and collaboration friction
- AI prompt limits required creative workarounds

## Accomplishments
- Fully functional real-time classroom feedback system
- Polished, intuitive UI/UX with color-coded feedback and badges
- Robust safeguards: single-answer enforcement, drafts, conditional comments
- Foundation for advanced analytics and adaptive learning
- Creative troubleshooting of AI tools under time constraints

## Future Work
- Reinstate secure teacher login
- Implement keyword aggregation from comments
- Visual trend charts and engagement analytics
- Customizable surveys with multi-step questions and AI evaluation
- Gamification and achievement tokens for students
- Scale to a full-featured teaching analytics platform

