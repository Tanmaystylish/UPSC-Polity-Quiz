# UPSC Polity Quiz Website (Ready-to-deploy)

This is a ready React project for a 15-question UPSC-level Indian Polity quiz.
It asks for the participant's name, allows one attempt per name (best-effort),
and shows a shared scoreboard (requires Firebase Firestore).

## Quick deploy to Vercel (recommended)
1. Create a GitHub repo and push this project.
2. Sign in to https://vercel.com, click 'New Project' -> 'Import Git Repository' and select your repo.
3. Click Deploy. Vercel will build and give you a public URL you can share.

## To enable shared scoreboard
1. Create Firebase project and add a web app. Copy config and replace FIREBASE_CONFIG in src/UPSCPolityQuiz.jsx.
2. Create Firestore (in test mode for now).
3. Deploy to Vercel/Netlify. Scores will be saved to Firestore and displayed on the scoreboard.