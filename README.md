# 📄 Offline Resume Viewer

**A privacy-first, offline-capable resume readability tool that shows how your resume actually looks to a recruiter — instantly.**

> Paste your resume text. See it clearly. Fix weak language. Print with confidence.

---

## ✨ Why This Exists

Most resume tools today:

* Require uploads to third-party servers
* Lock features behind accounts or subscriptions
* Add unnecessary complexity

Recruiters, however, read resumes **fast**, **offline**, and **without mercy**.

**Offline Resume Viewer** exists to bridge this gap.
It is a calm, static, browser-native tool that lets you:

* View your resume the way a recruiter sees it
* Identify weak phrases instantly
* Make improvements without uploading your data anywhere

No backend. No tracking. No accounts. Just clarity.

---

## 🚀 Feature Summary

| Feature                      | Implementation                                              |
| ---------------------------- | ----------------------------------------------------------- |
| **Single HTML File**         | ✅ All CSS & JavaScript inline                               |
| **Offline-First**            | ✅ Service Worker + `localStorage`                           |
| **8 Themes**                 | ✅ Light, Dark, Sepia, Ocean, Forest, Slate, Midnight, Paper |
| **Resume Parsing**           | ✅ Heuristic-based section detection                         |
| **Weak Phrase Highlighting** | ✅ 20 common weak phrases with suggestions                   |
| **Raw / Formatted Toggle**   | ✅ Two clear view modes                                      |
| **Import / Export**          | ✅ TXT import, TXT & HTML export                             |
| **Print Support**            | ✅ Clean, distraction-free print styles                      |
| **Auto-save**                | ✅ Debounced `localStorage` persistence                      |
| **Recruiter Tips**           | ✅ 6-card recruiter knowledge section                        |

---

## 🧠 How It Works (Simple Flow)

1. Paste your resume text (or import a `.txt` file)
2. The app parses sections using lightweight heuristics
3. Resume is rendered into a clean, recruiter-style layout
4. Weak phrases are highlighted automatically
5. Toggle views, change theme, print, or export — all offline

---

## 🧩 Supported Resume Sections (Heuristic Detection)

* Summary / Profile
* Skills
* Experience
* Projects
* Education
* Certifications
* Achievements

> Detection is heuristic-based, not AI — predictable, fast, and stable.

---

## ⚠️ Weak Phrase Detection

The tool highlights **20 common resume weak phrases**, including:

* "Responsible for"
* "Worked on"
* "Helped with"
* "Familiar with"
* "Involved in"

Each highlighted phrase includes a short suggestion explaining **why recruiters avoid it** and how to improve it.

---

## 🛠️ Tech Stack

* **HTML5** — Semantic structure
* **CSS3** — Themes, layout, print styles
* **Vanilla JavaScript** — Parsing, highlighting, state
* **localStorage** — Persistence
* **Service Worker / Cache API** — Offline support

> No frameworks. No libraries. No APIs.

---

## 🔐 Privacy Guarantee

* No data leaves your browser
* No analytics
* No cookies
* No tracking

Your resume stays **yours**.

---

## 👤 Author

**Riyajul Ali**
Computer Science • Data Science • Systems Builder

* GitHub: [https://github.com/Aliriyaj007](https://github.com/Aliriyaj007)
* Email: [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)
* LinkedIn: *(add when available)*

---

## 🤝 Contributing

Contributions are welcome if they:

* Preserve offline-first behavior
* Avoid unnecessary dependencies
* Improve clarity, not complexity

Open an issue or submit a clean PR.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

> **Offline Resume Viewer** proves that powerful tools don’t need servers, accounts, or hype — just clear thinking and good defaults.
