# 🐰 GitHub Profile Professional Audit Tool

A single-page interactive web tool designed for students on a computing course to self-assess whether their GitHub profile meets professional standards. Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no installation required.

Use this in conjinction with:
[Creating a professional GitHub profile](https://martinsolent.github.io/github_profile_walk-thru/)
[Optimising Your GitHub Profile](https://martinsolent.github.io/github_profile_walk-thru/)
[GitHub Pages for hosting web content](https://github.com/martinsolent/GitHub_Pages_2023)
[Markdown Course](https://martinsolent.github.io/markdown_course/)

---

## 📋 About the Activity

When applying for placements, apprenticeships, or graduate roles in the tech industry, a GitHub profile is often the first thing a prospective employer will look at. This tool guides students through a structured self-audit of their profile, helping them understand what a professional developer presence looks like and where they may need to make improvements.

Students work through six key criteria, marking each one as **Yes** or **No**. Once all questions are answered, the tool delivers an instant verdict — complete with a cartoon rabbit mascot to make the feedback memorable and engaging.

---

## 🎯 Learning Objectives

By completing this activity, students will be able to:

- Identify the key components of a professional GitHub profile
- Critically evaluate their own public developer presence
- Understand how employers and collaborators perceive a GitHub profile
- Take targeted action to improve areas that fall short of professional standards

---

## ✅ The Six Audit Criteria

The checklist covers the following areas:

**1. Professional Profile Image**
Does the student have a clear, recognisable profile photo rather than the default GitHub avatar? A professional headshot or a consistent personal illustration conveys identity and effort.

**2. Crafted Bio / About Section**
Has the student written a meaningful bio that explains who they are, what they study or build, and perhaps a personal touch? A blank bio is a missed opportunity to make an impression.

**3. Recent Commit Activity**
Is there visible activity on the contribution graph? Regular commits demonstrate that the student is actively learning, building, and engaging with their work outside of submission deadlines.

**4. Pinned Showcase Repositories**
Has the student pinned their best repositories to the top of their profile? Pinned repos act as a digital portfolio — they should highlight the most impressive and relevant work.

**5. Repository Descriptions**
Do the repositories have short, informative descriptions? A repository with no description looks unfinished and makes it difficult for visitors to quickly understand the project.

**6. Documented READMEs**
Do key repositories include a proper README file? A good README should explain what the project does, how to run or install it, and ideally include screenshots or a link to a live demo.

---

## 🐰 The Verdict

Once all six criteria have been assessed, the tool reveals one of two results:

| Result | Criteria Met | Description |
|--------|-------------|-------------|
| 🎓 **Professional** | 4 or more Yes | A smart, well-dressed rabbit in academic cap and gown, diploma in hand. Your profile is ready for the world. |
| 😱 **Prankster** | 3 or fewer Yes | A stressed, dishevelled rabbit clutching a broken laptop showing a 404 error. Time to sort that profile out! |

The rabbit characters are drawn entirely in HTML5 Canvas — no images or external assets required.

---

## 🚀 How to Use

### Option 1 — GitHub Pages (Recommended)

1. Fork or clone this repository
2. Go to **Settings → Pages** in your repository
3. Set the source to the `main` branch and the root folder
4. Visit the generated GitHub Pages URL and share it with your students

### Option 2 — Run Locally

No build step or server is needed. Simply open the file in any modern browser:

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Open the file directly
open github-profile-checker.html
```

Or just double-click `github-profile-checker.html` in your file explorer.

---

## 🛠️ Technical Overview

| Feature | Implementation |
|---------|---------------|
| Styling | Pure CSS with custom properties and a dark GitHub-inspired theme |
| Fonts | Google Fonts — Space Mono & Syne |
| Rabbit illustrations | HTML5 Canvas API, hand-coded drawing functions |
| Interactivity | Vanilla JavaScript, no frameworks |
| Dependencies | None — fully self-contained single HTML file |
| Browser support | All modern browsers (Chrome, Firefox, Safari, Edge) |

---

## 🎓 Suggested Classroom Activity

This tool works well as a short, low-stakes activity at the start of a session or as part of a broader unit on professional skills and employability.

**Suggested flow:**

1. Ask students to open their GitHub profile in one tab and this tool in another
2. Give them 10–15 minutes to work through each criterion honestly
3. Invite students who received the "Prankster" result to share one thing they will improve before the next session
4. Follow up in a later session to see who has made changes — consider making it a friendly class challenge

**Extension task:** Ask students to peer-review a classmate's profile using the same checklist and provide written feedback on each criterion.

---

## 📁 File Structure

```
/
├── github-profile-checker.html   # The complete tool — a single self-contained file
└── README.md                     # This file
```

---

## 🤝 Contributing

Suggestions and improvements are welcome. If you would like to add new criteria, adjust the scoring threshold, or improve the rabbit illustrations, feel free to open an issue or submit a pull request.

---

## 📄 Licence

This project is open source and free to use for educational purposes. Feel free to adapt it for your own course or institution.
