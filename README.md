# UpadhiSathi AI – AI-Powered Rural Employment Information and Voice Assistance System

**UpadhiSathi AI** is a worker-focused application designed exclusively for rural employment workers under the Mahatma Gandhi National Rural Employment Guarantee Act (MGNREGA).

The application helps workers access their employment information, check attendance and wage payment details, and report employment-related problems through a simple, voice-enabled interface.

**Live Prototype:** https://upadhi.netlify.app (use demo login to see)

**Project Demo Video:** https://youtu.be/c_Bna3p_gA8?si=-2sk0KiwdHM2y

## 1. Problem Statement

Rural employment workers under the MGNREGA scheme often face difficulties accessing accurate and timely information about their employment.

Many workers do not know:

- When and where their next work is scheduled.
- What time their work starts and ends.
- Whether their daily attendance has been recorded.
- How many days they have worked.
- How much wage they are expected to receive.
- Whether their wages have been credited to their bank accounts.
- How to report problems related to attendance, wages, or work allocation.
- How to register and track complaints.

Language barriers and limited digital knowledge make it difficult for many workers to access existing online services.

Therefore, there is a need for a simple, AI-powered, voice-enabled mobile application that helps rural workers access their employment information and report problems easily in their local language.

## 2. Proposed Solution

UpadhiSathi AI is an AI-powered mobile application designed exclusively for rural employment workers.

It provides a single platform where workers can:

- Check when and where their work is scheduled.
- View work starting and ending times.
- Check whether their attendance has been recorded.
- View their total working days.
- Check expected wages and payment status.
- Know whether money has been credited to their bank accounts.
- Report employment-related problems using voice or text.
- Register complaints and track their status.

The application includes a Telugu AI Voice Assistant that helps workers communicate naturally, ask questions, explain their problems, and receive guidance.

**Our focus is only on workers. The current version does not include a government officer dashboard.**

## 3. Main Features

### 3.1 Work Information
- Work location.
- Work date.
- Starting and ending times.
- Upcoming work details.

### 3.2 Attendance Tracking
- Check daily attendance.
- Identify missing attendance records.
- View total working days.
- Report attendance problems.

### 3.3 Wage and Payment Tracking
- Expected wage amount.
- Payment status.
- Amount credited.
- Payment date.

### 3.4 AI Voice Assistant
- Ask questions using Telugu voice.
- Explain employment-related problems.
- Receive voice-based guidance.
- Get help registering complaints.
- Track complaint progress.

### 3.5 Smart Notifications
- Work reminders.
- Attendance updates.
- Wage payment updates.
- Complaint status notifications.

## 4. AI Voice Assistant – Our Main Innovation

Workers should not need to type or navigate complicated menus. They can simply speak to the assistant in their local language.

Example interactions:

| Worker asks | Assistant helps with |
|---|---|
| Where is my work tomorrow? | Scheduled work location |
| Has my attendance been recorded? | Available attendance information |
| How much money should I receive? | Expected wage information |
| Has my money been credited? | Available payment status |
| My attendance is missing. | Guidance to report the issue |
| I have not received my wages. | Guidance for complaint registration |

**Speak. Understand. Get Help.**

A simple voice-based experience for rural employment workers.

## 5. Application Structure

The application contains six main sections:

1. **My Work** – Work location, dates and timings.
2. **My Attendance** – Daily attendance and working days.
3. **My Wages** – Expected wages and payment details.
4. **My Complaints** – Register and track problems.
5. **Notifications** – Important updates and reminders.
6. **AI Voice Assistant** – Ask questions and report issues.

## 6. Our Innovation

The uniqueness of UpadhiSathi AI comes from:

1. **Voice-First Technology:** Workers can access information without typing.
2. **Local Language Support:** Telugu-based communication for rural workers.
3. **Unified Information:** Work, attendance and wage details in one application.
4. **AI Problem Assistance:** Helps workers explain problems and receive guidance.
5. **Easy Complaint Tracking:** Helps workers register and follow up on complaints.
6. **Worker-Focused Design:** Designed specifically for the needs of rural employment workers.

## 7. Technology Stack

### Current Worker Login Demo

- HTML
- CSS
- JavaScript
- CSV-based synthetic sample data
- Browser-based voice features

### Proposed Future Technology

| Component | Proposed Technology |
|---|---|
| Mobile Application | Flutter |
| Backend | Python + FastAPI |
| Database | PostgreSQL |
| AI Assistant | LLM + NLP |
| Telugu Voice Recognition | Speech-to-Text |
| Voice Response | Text-to-Speech |
| Authentication | Mobile OTP |
| Data Integration | Authorized MGNREGA records |

## 8. Source Code

The worker login demo source code includes:

- `index.html` – Application page structure.
- `css/style.css` – Application styling.
- `js/data.js` – States, districts, villages and languages.
- `js/gen.js` – Synthetic demo worker data and login support.
- `js/i18n.js` – Multilingual interface text.
- `js/app.js` – Login, dashboard, voice assistant and complaints.
- `data/` – Synthetic demonstration data.

The demo supports 13 selectable interface languages. Voice replies are available in Telugu and English.

**Note:** All worker records in this demo are synthetic sample records, not actual government records.

## 9. Data and Security Disclaimer

The current prototype is a demonstration application and does not have verified, real-time integration with official MGNREGA employment or bank payment records.

Actual work schedules, attendance, wages and payment status require authorized access to reliable government records and, where applicable, payment data.

The current worker login is a front-end demonstration. It must not be used for real workers or real personal information. A production application will require secure authentication, a protected backend and authorized data access.

## 10. Our Vision

"To empower every rural employment worker with easy access to work information, attendance records, wage payment details and AI-powered voice assistance in their own language."

## 11. Final Project Summary

**Project Name:** UpadhiSathi AI

**Problem:** Rural employment workers often struggle to access work schedules, attendance records, wage details and complaint services.

**Solution:** A worker-focused mobile application that brings employment information and complaint assistance into one simple platform.

**Innovation:** A voice-first, local-language AI assistance system that makes rural employment information easier to access and understand.

**Target Users:** Rural employment workers under MGNREGA.

**Vision:** To make employment information accessible, transparent and understandable for every rural worker.

---

**UpadhiSathi AI – Speak. Understand. Get Help.**
