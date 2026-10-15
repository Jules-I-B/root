# SkillPath Mobile — AI & Freelance Academy (v1)

A working, installable **Progressive Web App (PWA)** containing 12 offline micro-lessons across AI Automation, Python, PowerShell, APIs, LLM Apps, Web Development, Full Stack and Upwork. Each lesson has a short explanation, task, quiz and notes; the Portfolio tab tracks 4 projects. Local storage keeps progress on the same browser/device. Export/import JSON for manual backups. No server account or paid API is required for the training app itself.

## Install on Android
1. Extract the ZIP. Upload **all files in this folder** to a static HTTPS website such as GitHub Pages, Netlify, or Cloudflare Pages. `index.html` must be at the hosted URL's root (or directory root).
2. On your Android phone, visit that HTTPS URL in Chrome. From Chrome's menu choose **Install app** or **Add to Home screen**, depending on browser.
3. Open it from the phone home screen. After first load, lessons and quizzes work without internet.

Opening `index.html` as a `file://` local file is **not sufficient to install a PWA**. HTTPS hosting or localhost is required. Hosting the zip file itself is not enough—extract its contents.

## Quick local test on a PC
In this folder run `python -m http.server 8000`, then open `http://localhost:8000`. localhost supports service workers.

## GitHub Pages deployment
Create a public repository (or private if your plan supports Pages), upload the extracted contents to the repository root, go to **Settings → Pages**, choose deployment from branch (`main`, `/root`) and wait for the URL to become available. If this GitHub UI changes, use its latest Pages instructions.

## Privacy and limitations
No remote sync or user accounts. Browser storage can be cleared and backups should be exported. The app stores notes locally; don't paste passwords, client data or confidential enterprise information. This is a PWA, not a compiled Android APK. Each lesson uses one multiple-choice question; later versions can add spaced repetition, practical task verification, and a hosted sync service.
