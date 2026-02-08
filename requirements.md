# StudyBee – Requirements Document

## 1. Overview
StudyBee is an AI-powered learning and productivity analytics platform designed to help students and developers improve focus, consistency, and learning efficiency by intelligently distinguishing productive activity from distraction.

The system uses a hybrid intelligence approach combining on-device machine learning, AI-based behavior classification, focus scoring, and generative AI insights to encourage deep work rather than enforcing restrictions.

---

## 2. Functional Requirements

### 2.1 User Activity Tracking
- Track browser activity in real time via a Chrome extension
- Capture active tabs, page titles, URLs, session duration, and usage patterns
- Securely transmit activity metadata to the backend

---

### 2.2 ML & AI-Based Behavior Classification
- Classify user activity into:
  - Learning / Deep Work
  - Distraction
  - Mixed State
- Use an on-device ML classifier to detect learning relevance for unknown or new websites
- Combine rule-based heuristics and ML predictions for accurate classification
- Perform classification continuously during active sessions

---

### 2.3 Focus Scoring & Streaks
- Generate daily and session-based Focus Scores
- Maintain productivity streaks based on consistent learning behavior
- Update focus metrics in near real time

---

### 2.4 AI Study Coach & Insights
- Use Generative AI to:
  - Generate personalized reflections and motivation summaries
  - Explain productivity drops and behavioral patterns
  - Suggest actionable improvement tips
- Provide daily and weekly AI-generated insights

---

### 2.5 Gamification & Competition
- Reward users with points, XP, and profile levels
- Enable private study or competition rooms
- Maintain a global leaderboard based on focus scores and consistency

---

### 2.6 Dashboard & Visualization
- Display focus trends and productivity breakdowns
- Visualize learning vs distraction using charts and summaries
- Provide weekly performance analytics

---

## 3. Non-Functional Requirements

### 3.1 Performance
- Low-latency on-device ML inference
- Real-time data processing with minimal browser and system overhead
- Scalable backend to support growing users

---

### 3.2 Security & Privacy
- No collection of sensitive or personal content data
- ML inference performed locally on user device
- Secure API communication with backend services
- Privacy-first system design

---

### 3.3 Scalability
- Modular, layered architecture
- Independent scaling of backend services and AI services
- Minimal cloud dependency for ML inference

---

### 3.4 Usability
- Simple, distraction-free user interface
- Clear visual feedback and insights
- Supportive nudges instead of restrictive blocking

---

## 4. Assumptions & Constraints
- Users have access to a Chromium-based browser
- Initial deployment targets students and knowledge workers
- On-device ML models are lightweight and optimized for browser environments
- AI insights are based on activity patterns and metadata, not content inspection
