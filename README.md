# Namami KBC Examination

A lightweight, responsive, KBC-inspired quiz app for **Namami Digital Skills Academy, Sohagpur**. It uses plain HTML, CSS and JavaScript: no login, no database, no external libraries and no third-party assets.

## Features
- Single-question-at-a-time multiple-choice exam
- 30-second timer per question
- Immediate correct/wrong feedback and score summary
- Original synthesized sound effects with a sound toggle
- Responsive design and installable/offline app shell (PWA)
- Editable exam title in `index.html` and question bank in `questions.js`

## Publish with GitHub Pages
1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. Wait for deployment. The site URL is https://softskill201.github.io/KBC/.

## Run offline on a computer
Service workers (the offline cache) require HTTPS or localhost; they do not run from a direct `file://` open.
1. Download the repository ZIP and extract it.
2. Open a terminal in the extracted folder.
3. Run `python -m http.server 8000`.
4. Open `http://localhost:8000` in your browser. After the first load, the app shell is cached for offline use.

## Customize
- Change the visible exam heading in the `<h1 id="examTitle">` element in `index.html`.
- Edit `questions.js`. Each question needs four options and an `answer` index (A=0, B=1, C=2, D=3).
- Change per-question time by editing `remaining=30` and the timer reset in `index.html`.

## Branding
**NAMAMI DIGITAL SKILLS ACADEMY**  
Sohagpur | Practical Computer Training  
Instructor / Owner: Pawan Soni

The circular Om mark is a simple placeholder emblem. Replace it with the institute's own logo when its image file is added to this repository.
