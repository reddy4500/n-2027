# NEET PG AI Agent

An AI study companion for NEET PG that runs in your browser, free on GitHub Pages. Powered by Google Gemini, with voice in **English and Telugu**.

## Files (6, no folders)

| File | Purpose |
|---|---|
| `index.html` | The whole app: design, code and logo in one file |
| `sw.js` | Offline support |
| `manifest.webmanifest` | Lets you install it as a phone or desktop app |
| `icon-192.png`, `icon-512.png` | App icons |
| `README.md` | This guide |

## Put it online

1. In your GitHub repo, click **Add file → Upload files**.
2. Select **all 6 files** in this folder and drag them in. Click **Commit changes**.
3. Go to **Settings → Pages** and set **Source: Deploy from a branch**, **Branch: main**, **/ (root)**, then click **Save**.
4. Wait about a minute, then open `https://<username>.github.io/<repo>/` and press **Ctrl + Shift + R**.
5. The app opens on **Settings**. Paste your free Gemini key from <https://aistudio.google.com/app/apikey>, set your exam date, name and language, and press **Test connection**.
6. To install it, click **Install app** at the top right (Chrome or Edge), or on a phone use **⋮ → Add to Home screen**.

> Never put your API key in these files. Enter it only in the app's Settings page. It stays in your own browser.

## What it does

- **Daily Coach**: an AI plan for the day, spoken briefing, question of the day, evening check-in with feedback, journal and reminders.
- **Practice**: unlimited AI-generated NEET PG-style MCQs by subject, topic, difficulty and style. Explanations, high-yield pearls, *Explain in Telugu*, and automatic saving of mistakes for review.
- **Mock tests**: 25, 50, 100 or 200 questions (200 in 210 minutes), weighted across 19 subjects, with +4/−1 marking, a question palette, subject-wise results and AI analysis.
- **AI Mentor "Guru"**: a chat mentor that knows your progress. Voice in and voice out.
- **Flashcards**: AI decks with spaced repetition.
- **Planner**: focus timer that logs your study time, 14-day chart, AI master plan to exam day, and weightage vs. your accuracy.
- **Voice**: for example “good morning”, “start quiz on pharmacology”, “option B”, “next”, “explain”, “start timer”. In Telugu: శుభోదయం, సీ, తరువాత, వివరించు. Anything else goes to the mentor.
- **Offline**: 30 built-in questions work without a key or internet.

Shortcuts: **M** toggles the mic, **1–4** answer, **N / P** next or previous, **Esc** stops speaking.

## Tips

- Voice input works best in Chrome or Edge. To hear Telugu replies, install a Telugu text-to-speech voice (Android: *Settings → Text-to-speech → Google → Telugu*).
- The Gemini free tier limits requests per minute. The app waits and retries automatically, but a 200-question mock takes a few minutes to generate.
- AI questions can occasionally be wrong. Cross-check doubtful facts with standard textbooks.
- Your progress is saved in your browser. Use **Settings → Export backup** before switching devices or clearing browser data.
- If you're struggling emotionally, talk to someone you trust or call Tele-MANAS at **14416** (India, free, 24×7).
