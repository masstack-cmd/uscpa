# USCPA Practice Quiz App

A mobile-friendly web app for practicing USCPA exam questions.
Built with Google Apps Script (backend) + GitHub Pages (frontend).

## What This App Does

- Presents 4 multiple-choice questions per session from a curated question pool
- Covers all FAR topics (and more subjects to come)
- On incorrect answers: gives a **hint**, not the answer — to encourage thinking
- Tracks your answer history to support spaced repetition learning

## How to Use

1. Open the app: **https://masstack-cmd.github.io/uscpa/**
2. Tap "練習を始める" (Start Practice)
3. Answer 4 questions
4. Review your score and hints

## A Note on This Repo Being Public

This repo is intentionally public — I opened it up to enable GitHub Pages hosting (free tier).

If you stumble upon this:
- Please **don't** make malicious changes or spam the API endpoint
- Feel free to **fork it**, adapt it for your own exam prep, or use it as a template
- The backend runs on Google Apps Script + Google Sheets — easy to replicate for free

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML / CSS / JavaScript (GitHub Pages) |
| Backend | Google Apps Script |
| Database | Google Sheets |
| AI (question generation) | Claude API (Haiku / Sonnet) |
