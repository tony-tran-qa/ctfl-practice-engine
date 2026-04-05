# ISTQB CTFL 4.0 Practice Engine

A standalone browser-based practice exam tool for the ISTQB Certified Tester Foundation Level (CTFL) v4.0 certification. No installation, no server, no login — open the HTML file and start testing.

## Live Demo

> Open `ctfl_practice_engine.html` directly in Chrome or Firefox. No build step required.
>
> ## Features
>
> - **280 questions across 8 exam banks** — all sourced from official ISTQB/ASTQB sample exam PDFs
> - - **5 official exam sets** — Sample Exams A, B, C, D (ISTQB) and Exam 3 (ASTQB)
>   - - **3 practice banks** — Core Concepts (Ch. 1-3), Test Techniques (Ch. 4), Management & Tools (Ch. 5-6)
>     - - **60-minute countdown timer** with colour-coded warnings
>       - - **Instant Validate mode** — toggle to see explanations immediately on selection
>         - - **Wrong Answer Tracker** — tracks questions answered incorrectly across all exams over time
>           - - **Score history** — all attempts saved in browser localStorage, filterable by exam and pass/fail
>             - - **Export to file** — score history and wrong answer tracker export as .txt for longitudinal tracking
>               - - **Full explanations** — every question includes rationale with syllabus reference (e.g. FL-4.2.2 K3)
>                 - - **Question navigator** — grid sidebar for jumping between questions, colour-coded by status
>                  
>                   - ## Exam Banks
>                  
>                   - | Bank | Source | Questions |
>                   - |---|---|---|
>                   - | Sample Exam A | Official ISTQB v1.1 | 40 |
> | Sample Exam B | Official ISTQB v1.0 | 40 |
> | Sample Exam C | Official ISTQB v1.6 | 40 |
> | Sample Exam D | Official ISTQB v1.3 | 40 |
> | Sample Exam 3 | Official ASTQB | 40 |
> | Practice Bank A | Core Concepts (Ch. 1-3) | 40 |
> | Practice Bank B | Test Techniques (Ch. 4) | 40 |
> | Practice Bank C | Management & Tools (Ch. 5-6) | 40 |
>
> Pass mark: **65% (26/40)** — matches the real CTFL exam.
>
> ## Usage
>
> 1. Download ctfl_practice_engine.html
> 2. 2. Open in Chrome or Firefox
>    3. 3. Select an exam from the home screen
>       4. 4. Answer questions — use Validate Answer for instant feedback
>          5. 5. Submit when done to see your score and full review
>             6. 6. Visit Wrong Answers tab to track problem areas over time
>               
>                7. All data is stored locally in your browser (localStorage). Nothing is sent anywhere.
>               
>                8. ## Technical Details
>               
>                9. - **Single-file HTML** — all CSS, JavaScript, and question data in one file (~260KB)
> - **No dependencies** — no npm, no framework, no CDN calls beyond Google Fonts
> - - **localStorage persistence** — score history, wrong answer tracker, and exam state survive browser restarts
>   - - **Vanilla JavaScript** — ES6+, no build step
>    
>     - ## Skills Demonstrated
>    
>     - | Skill | Detail |
>     - |---|---|
>     - | Test domain expertise | Questions sourced and validated against official ISTQB PDFs |
> | AI-assisted tooling | Built using Claude as an engineering partner |
> | Client-side persistence | localStorage for score history and wrong-answer tracking |
> | Longitudinal tracking | Wrong answer tracker mirrors defect tracking thinking |
> | Vanilla JS engineering | Complex state management, timer logic, dynamic rendering |
> | Self-directed learning | Built to close certification skill gaps |
>
> ## About ISTQB CTFL
>
> The ISTQB Certified Tester Foundation Level (CTFL) v4.0 is the entry-level international software testing certification covering testing fundamentals, SDLC, static testing, test techniques, test management, and test tools.
>
> ---
>
> *Questions sourced from official ISTQB/ASTQB sample exam PDFs. All exam content copyright © International Software Testing Qualifications Board.*
