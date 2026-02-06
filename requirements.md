# StudyBee – Requirements Document

## 1. Overview
StudyBee is an AI-powered learning and productivity analytics platform designed to help students and developers improve focus, consistency, and learning efficiency by intelligently distinguishing productive activity from distraction.

The system uses AI-based behavior classification, focus scoring, and generative insights to encourage deep work rather than enforcing restrictions.

---

## 2. Functional Requirements

### 2.1 User Activity Tracking
- Track browser activity in real time via a Chrome extension
- Capture active tabs, session duration, and usage patterns
- Securely transmit activity data to the backend

### 2.2 AI-Based Behavior Classification
- Classify activity into:
  - Learning / Deep Work
  - Distraction
  - Mixed State
- Perform classification continuously during sessions

### 2.3 Focus Scoring & Streaks
- Generate a daily and session-based Focus Score
- Maintain consistency streaks based on productive behavior
- Update scores in real time

### 2.4 AI Study Coach & Insights
- Generate AI-based reflections and motivation summaries
- Explain productivity drops and suggest improvements
- Provide daily and weekly analytics

### 2.5 Gamification & Competition
- Reward users with points and profile levels
- Enable private study rooms
- Maintain a global leaderboard

### 2.6 Dashboard & Visualization
- Display focus trends and productivity insights
- Visualize analytics using charts and summaries

---

## 3. Non-Functional Requirements

### 3.1 Performance
- Real-time data processing with minimal latency
- Scalable backend to support user growth

### 3.2 Security & Privacy
- No collection of sensitive personal data
- Secure API communication
- Privacy-first design

### 3.3 Scalability
- Modular architecture
- Independent scaling of AI and backend services

### 3.4 Usability
- Simple and distraction-free UI
- Supportive feedback instead of strict blocking

---

## 4. Assumptions & Constraints
- Users have access to a Chromium-based browser
- Initial deployment targets students and developers
- AI insights rely on usage patterns, not content inspection
