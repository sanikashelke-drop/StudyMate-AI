# Devpost submission draft

## Project title
StudyMate AI

## Elevator pitch
A student study companion to organise revision, practise quizzes, and track learning progress in one simple web app.

## About the project
## Inspiration

Students often struggle to organise their syllabus, plan revision, and track progress across different subjects. I wanted to create a simple study companion that helps students manage their learning in one place.

## What it does

StudyMate AI is a browser-based study-planning prototype. It lets students enter a subject and topics, create a suggested revision plan, add tasks, mark tasks complete, track progress, and practise with sample quiz questions and explanations. Its conversational panel demonstrates a simulated study-assistant workflow using rule-based responses.

## How we built it

The prototype uses HTML, CSS, and JavaScript. Study plans and task completion are managed in the browser, and localStorage keeps the demo state on the current device. It does not require an API key or paid service.

## Challenges we ran into

The main challenge was turning a broad student need into a small, testable experience that a beginner could build. The prototype focuses on a clear workflow and simple interactions rather than promising features that are not implemented.

## Accomplishments that we're proud of

The prototype brings planning, task tracking, a conversational demo, and practice questions into one responsive interface. The main interactions are implemented and can be tested in a browser.

## What we learned

This project explores front-end development, user-focused design, local browser storage, basic interaction design, and the importance of clearly communicating the limitations of a simulated assistant.

## Simulation disclosure

This is a simulated assistant experience for demonstration purposes. It is not an actual Alexa+ integration, does not call Amazon APIs or SDKs, and does not use a live AI model. Assistant replies are rule-based examples.

## Product feedback draft
Product feedback — tools used

HTML, CSS, JavaScript, and browser localStorage were used to build this static prototype. No Amazon API, Amazon SDK, AWS service, or live AI model was integrated, so I am not claiming feedback from using those services.

What worked well:
- Standard browser technologies made it possible to create a responsive prototype without a build system.
- LocalStorage makes demo progress persist in the same browser without sending study data to a server.

What needs work:
- The assistant uses rule-based sample responses and cannot answer arbitrary study questions.
- A future version would need a properly tested agent/AI integration and a stronger evaluation of answer quality and safety.

Onboarding experience:
- Starting with a single HTML file made it approachable for a beginner; no API keys or installation were required.

Would I build with these tools again?
- Yes, for a lightweight prototype. To deliver a production-quality AI study assistant, I would evaluate and integrate an appropriate AI service and then provide accurate feedback on that service after testing it.

