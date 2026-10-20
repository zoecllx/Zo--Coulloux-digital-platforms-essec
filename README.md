# Digital Platforms Test Drive – Course Website

My website for the **Digital Platforms Test Drive** course (MSc Marketing Management & Digital, ESSEC Business School, Asia-Pacific campus), taught by Madina Kalyayeva.

## What's inside
- **Welcome**: presentation of the course
- **About me**: my profile, CV and LinkedIn
- **The course**: structure, outcomes and grading
- **Schedule**: all sessions in date order
- **Sessions**: lectures and guest lectures, with my notes; each guest lecture tab includes a playable game
- **Games**: quizzes by theme, Pinkle (my Wordle), Hangman and a reverse Akinator
- **How I built it**: the workflow (Claude Code, GitHub, Vercel), the features and my prompt journey
- **Contact me**

## How I built it
Following the workflow from the LaunchLab guest session:
1. **Build with Claude Code**: I described each page and feature in plain language; Claude Code wrote and tested the HTML, CSS and JavaScript.
2. **Store the code on GitHub**: every change is a commit pushed to this repository.
3. **Deploy with Vercel**: Vercel watches this repository, so every push updates the live site automatically.

**Main features:** one tab per session, a game inside each guest lecture tab, quizzes by theme, Pinkle, Hangman, Akinator, responsive design for phones, keyboard accessibility.

**My prompt journey (short version):** a pink quiz page → a site for my lecture analyses → welcome page and menu → real content from the slides → games by theme → luxury pink redesign → live on GitHub + Vercel → CV, portrait and bio → guest speaker cards → stickers and new fonts → Pinkle, Hangman, Akinator → games inside the guest tabs. The full journey is on the website's "How I built it" page.

## Built with
Plain HTML, CSS and vanilla JavaScript, no frameworks: `index.html`, plus `games/pinkle-words.js` (word list), `images/` and `fonts/`.

## Run it
Open `index.html` in a browser, or deploy the repo with Vercel.
