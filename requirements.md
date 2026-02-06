# StudyBee – Requirements Document

## 1. Overview
StudyBee is an AI-powered Chrome Extension designed to help students study smarter by automatically tracking browser activity, identifying learning vs distraction patterns, and providing AI-driven feedback, motivation, and competitive insights.

The system focuses on awareness, habit-building, and motivation rather than restriction or blocking.

---

## 2. Functional Requirements

### 2.1 Browser Activity Tracking
- Track active browser tabs in real time
- Identify website domains and page titles
- Maintain last 7 days of activity data locally

### 2.2 Activity Classification
- Classify browsing activity into:
  - Learning
  - Distraction
  - Mixed
- Use:
  - Predefined learning & distraction domains
  - Keyword-based title analysis

### 2.3 Focus Score & Productivity Metrics
- Calculate focus score based on learning vs distraction ratio
- Track daily productivity trends
- Maintain rank-based performance metrics

### 2.4 AI-Powered Study Coach
- Generate daily AI motivation messages
- Provide AI-based guidance through Study Coach chat
- Generate weekly AI reflections summarizing performance

### 2.5 Weekly AI Reflection & Analytics
- Compare learning vs distraction visually
- Identify best focus hours
- Suggest ideal study timings
- Summarize weekly performance in natural language

### 2.6 Competition & Leaderboards
- Allow users to create or join groups using a unique code
- Rank users based on focus score
- Track Rank #1 streaks
- Enable gamified point-based competition

### 2.7 Notification System
- Notify users when distraction time exceeds learning time
- Repeat notifications every 30 minutes while distraction dominates

### 2.8 Backend & Sync
- Sync local activity data with backend securely
- Manage users, groups, and leaderboard data
- Generate AI insights using Gemini API

---

## 3. Non-Functional Requirements

### 3.1 Performance
- Real-time tracking with minimal resource usage
- Smooth extension performance without browser slowdown

### 3.2 Privacy & Security
- No tracking of personal content
- Activity stored locally before secure backend sync
- Privacy-first architecture

### 3.3 Scalability
- Support multiple users and groups
- Backend designed for global access and growth

### 3.4 Usability
- Clean, intuitive popup UI
- Minimal user configuration
- Clear visual feedback and insights

---

## 4. Assumptions & Constraints
- Users use a Chromium-based browser
- Backend is hosted and publicly accessible
- Initial focus is on students; system is extensible
