# Project 4 - Trivia Quiz App
**Author:** Nishanth Madthila | **Andrew ID:** nmadthil | **Course:** 95-702

## Overview
A distributed mobile-to-cloud trivia application using the [Open Trivia Database (OpenTDB)](https://opentdb.com) API.

## Architecture
- **Android App** → **Web Service (Tomcat/GitHub Codespaces)** → **OpenTDB API**
- Logs stored in **MongoDB Atlas**
- Operations dashboard at `/dashboard`

## Web Service Endpoints
| Endpoint | Description |
|----------|-------------|
| `GET /trivia?category=17&difficulty=easy&amount=5` | Fetch trivia questions |
| `GET /dashboard` | Operations analytics dashboard |

## Logged Fields (per request)
1. Timestamp
2. Device model
3. IP address
4. Category requested
5. Difficulty requested
6. Amount requested
7. OpenTDB API response time (ms)
8. Questions returned

## Files
- `ROOT.war` — deployable web service
- `TriviaWebService-IntelliJ.zip` — IntelliJ web service project
- `TriviaQuiz-AndroidApp.zip` — Android Studio project
- `Project 4 Task 2 Writeup.pdf` — project writeup
