# TeacherFlow

**An open-source, local-first AI teaching companion.** TeacherFlow helps teachers turn lesson notes and resources into a structured AI lesson brief, then bring the generated teaching script back into a guided classroom view.

> **No AI API keys required.** TeacherFlow does not connect to or control AI chat websites. Copy the lesson brief into the AI platform you already use, attach original materials there, then paste the AI response back into TeacherFlow.

## Features

- Lesson context: topic, subject, grade, learner age, prior knowledge, duration and language.
- Source notes and file attachments (local browser handling).
- Detailed AI prompt with teacher dialogue, learner questions, expected answers, examples, activities, assessment and recap.
- Manual handoff to ChatGPT, Claude and Gemini.
- Guided lesson presentation with step-by-step navigation.
- Save lessons locally in the browser.
- Export lesson plans as Markdown, Word-compatible documents or PDF via browser print.
- Portable AI teaching skill and platform setup guidance.
- MIT licence.

## Run locally

No build step, API key, server database or framework is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser. For best results, run a local server:
   - Linux/macOS: `python3 -m http.server 8000`
   - Windows: `py -m http.server 8000`
3. Visit `http://localhost:8000`.

## AI workflow

1. Prepare the lesson context and add source notes in TeacherFlow.
2. Copy the generated teaching brief.
3. Open ChatGPT, Claude or Gemini and paste the brief. Attach the original source files directly in that AI chat.
4. Copy the AI-generated lesson plan back into TeacherFlow.
5. Save the lesson and use Guided Teaching mode.

The workflow is intentionally manual: it supports free AI chat accounts and does not use provider APIs. Platform-specific skill installation depends on each provider's current plan and feature availability. ChatGPT users can use the included compact instructions or quick-start prompt.

## GitHub Pages

This is a static website. In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save. The site will be published at `https://razorjetinz.github.io/TeacherFlow/` after deployment.

## Privacy and limitations

- There is no TeacherFlow backend. Lesson records are saved in this browser's local storage.
- Files are not uploaded to TeacherFlow. Attach source files separately to the AI chat you choose.
- AI chat websites are not controlled by this application; use their normal file-upload and chat interfaces.
- Image, video and audio attachments may need a transcript or description in the source notes. This release does not render media files.
- Review AI-generated teaching material for factual accuracy, age suitability, accessibility and classroom safety.

## AI skill

Download the [portable skill ZIP](skill/teacherflow-ai-skill.zip), or inspect [SKILL.md](skill/SKILL.md) and the [quick-start prompt](skill/QUICK-START-PROMPT.md). Provider-specific setup notes are included in the same folder.

## Licence

MIT. See [LICENSE](LICENSE).

---

An InfiOffice project · [infioffice.com](https://infioffice.com)
