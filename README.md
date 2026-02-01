# Student Admin Assistant (IBM watsonx Orchestrate)

This repository supports our IBM Dev Day AI Demystified Hackathon submission.

## Project Overview
Student Admin Assistant is an agentic AI assistant built in **IBM watsonx Orchestrate** to help university students with:

- Course registration support  
- Timetable clash detection  
- Suggesting alternative sessions  
- Weekly timetable generation  
- Drafting professional registrar/admin emails  

## Key Innovation
The agent uses an uploaded **mock university timetable dataset** as a Knowledge Source, ensuring schedules are grounded and not hallucinated.

## Demo Workflows
1. Register for CS101, MAT101, PHY105 (carry-over)
2. Detect clashes and suggest alternatives
3. Build a clash-free weekly timetable
4. Draft a registrar confirmation email

## Files Included
- `course-schedule-dataset.json` — Mock timetable source of truth  
- `demo-prompts.txt` — Prompts used in the video demo  
- `submission-summary.pdf` — Written submission summary  
- `/screenshots` — Evidence of agent outputs  

## Built With
- IBM watsonx Orchestrate (Agent Builder + Knowledge Source + Compliance Rules)

Team FlashPoint — 2026 Hackathon Submission
