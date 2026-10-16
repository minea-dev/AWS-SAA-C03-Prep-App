# AWS-SAA-C03-Prep-App
A lightweight, serverless web application designed for AWS Certified Solutions Architect Associate (SAA-C03) exam preparation. The platform allows users to review core AWS concepts through interactive flashcards and practice with realistic, randomized mock exams.

## Key Features

- Study Mode (Flashcards): Topic-specific flashcards designed for active recall. Users can read architectural scenarios and flip the cards to reveal direct answers and technical explanations.

- Custom Test Simulator: A multiple-choice exam engine that mimics the official SAA-C03 format. Users can select a single topic or merge multiple topics to generate a randomized, comprehensive practice test.

- Instant Feedback & Explanations: The test engine evaluates selections in real-time, highlighting the correct option and displaying detailed architectural breakdowns to reinforce learning.

- Modular JSON Architecture: All study materials are decoupled from the logic and stored in a structured JSON format. Adding new AWS topics or questions requires only a simple data entry update, with zero code changes needed.

- Mobile-First Design: A fully responsive, app-like interface optimized for touch interactions, allowing users to study seamlessly on smartphones and tablets.

## Tech Stack

- Frontend: HTML5, Vanilla JavaScript (ES6+).

- Styling: Tailwind CSS (via CDN) for a modern, responsive UI.

- Hosting: 100% client-side architecture requiring no backend or database, making it fully compatible with free static hosting platforms like GitHub Pages, Vercel, or Netlify.
