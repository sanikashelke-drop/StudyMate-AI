# StudyMate AI

A beginner-friendly study-planning web prototype created for the Amazon Developer Hackathon's Alexa+ simulated-experience path.

## What works in this prototype
- Create a revision plan from a subject, comma-separated topics, and selected study duration.
- Add study tasks and mark them complete.
- Track completed tasks and progress.
- Try sample multiple-choice questions with explanations.
- Use a rule-based conversational demo for study-planning workflows.
- Persist task and subject state in the browser's local storage.

## Important limitations
- This is a prototype. The assistant uses rule-based sample responses; it is **not connected to a live AI model**.
- This is a simulated assistant experience, **not an actual Alexa+ integration or Amazon service**.
- No user data is sent to a server by this static app; study state is saved in the current browser's local storage.
- Before submitting, test the app and accurately describe what is and is not implemented.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Try adding a subject and topics, generating a plan, checking tasks off, using the assistant prompts, and answering quiz questions.

No build tools, API keys, or paid services are required.

## Hackathon submission checklist
The official rules require a working demo, source-code repository, public demo video under 3 minutes, project description, primary track selection, and product feedback for every tool/API/SDK used. For a public repository, include an open-source license.
- Choose the Alexa+ track only if you are submitting this as a simulated Alexa+ experience and the demo clearly shows the experience working.
- Create a public GitHub repository and include this source code plus the MIT `LICENSE`.
- Publish a demo video showing the working app and clearly disclose the simulation/prototype limitations.
- Fill out product feedback truthfully. Do not claim use of Amazon APIs or SDKs because this prototype does not use them.
- Confirm the live Devpost deadline/status before planning further work.

## Built with
HTML, CSS, JavaScript, browser localStorage.
