# Kannada for Everyone (ಕನ್ನಡ)

Submission for the **Kannada Digital Innovation Hackathon 2026** (Problem Statement 1: *Kannada for Everyone*).

An interactive web app that helps non-Kannada speakers learn practical Kannada through everyday situations, with listening, speaking practice and a quiz.

## Features
- **6 real-life situations**: Greetings, Travel, Shopping, Food, Health, Work & school (30 phrases)
- **Each phrase shows**: Kannada script, easy transliteration, English meaning
- **Listen**: browser text-to-speech (`kn-IN`)
- **Say it**: browser speech recognition (`kn-IN`) and a 0–100% similarity score using Levenshtein distance
- **Quiz**: 8 random multiple-choice questions with instant audio feedback
- **Progress tracking** saved in the browser (`localStorage`)
- Responsive, keyboard accessible, dark mode aware

## Tech stack
HTML, CSS and vanilla JavaScript (no framework, no build step). Web Speech API for voice. Noto Sans Kannada font.

## Run locally
Double-click `index.html`, or run `python -m http.server 8000` and open http://localhost:8000.
Use **Chrome or Edge** for voice features.

## Deploy
Drag the folder into https://app.netlify.com/drop

## Known limitation
Voice features depend on the device having a Kannada voice (works on Android Chrome; on Windows add the Kannada speech pack).

## Future work
Add more situations, a dialogue mode, offline PWA support, and a cloud speech model for stronger pronunciation scoring.
