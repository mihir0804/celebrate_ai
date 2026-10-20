# 🎊 Celebrate AI — GenAI Event Planner

> **PromptWars Challenge 5 · Celebration & Event Planner**

A fully AI-powered event planning assistant built with **Google Gemini 2.0 Flash** that helps users plan weddings, birthdays, community festivals, corporate events, and more — complete with budgets, timelines, vendor checklists, and personalized creative ideas.

---

## 🌐 Live Demo

👉 **[Try it Live](https://YOUR-USERNAME.github.io/celebrate-ai)**

---

## ✨ Features

| Feature | Description |
|---|---|
| **10 Event Types** | Wedding, Birthday, Baby Shower, Corporate, Festival, Graduation, Anniversary, Fundraiser, Holiday Party, Retirement |
| **Smart Form** | Event name, date, location, guest count, style/vibe, budget slider, planning lead time, special requests |
| **13 Toggleable Sections** | Overview, Budget, Timeline, Vendors, Ideas, Food, Entertainment, Seating, Eco Tips, Contingency, Invitations, Décor, Photography shot list |
| **Parallel AI Generation** | Overview first → then Timeline + Budget + Vendors + Ideas generated in parallel using Gemini 2.0 Flash |
| **Progress Tracker** | Animated step-by-step progress cards with live completion states |
| **5 Result Tabs** | 🗂️ Overview · 📅 Timeline · 💰 Budget · 📋 Vendors · 💡 Ideas |
| **AI Chat Assistant** | Context-aware chat that knows your full plan, with quick-prompt suggestions |
| **Robust Markdown** | Renders tables with headers, interactive checkboxes, blockquotes, nested lists, code blocks |
| **Export** | 🖨️ Print/Save PDF · 📋 Copy Full Plan · 🔄 Regenerate |

---

## 🤖 GenAI Services Used

- **Google Gemini 2.0 Flash** (`gemini-2.0-flash`) via the Gemini REST API
- Used for:
  1. **Executive Overview** — Event vision, highlights, food & catering, entertainment programme, optional sections
  2. **Planning Timeline** — Full month-by-month checklist from planning start to day-after (80–120 interactive tasks)
  3. **Budget Breakdown** — Itemized cost table with % allocations, money-saving tips, payment timeline
  4. **Vendor Checklist** — Per-vendor guide with questions to ask, red flags, pro tips, booking tracker
  5. **Creative Ideas** — 12 personalised ideas with execution steps and wow-factor ratings
  6. **AI Chat Assistant** — Real-time Q&A with full event plan context

All prompts are crafted with detailed system instructions simulating a world-class event planning consultant.

---

## 🚀 How to Use

1. Open `index.html` in any modern browser (no server needed — it's a pure static file)
2. Get a free **Gemini API Key** from [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
3. Enter your key in the API Key banner and click **Save Key**
4. Choose your event type, fill in details, toggle sections
5. Click **✨ Generate My Event Plan** and watch the magic happen!

---

## 🛠️ Tech Stack

- **Pure HTML + CSS + Vanilla JavaScript** — zero dependencies, zero build step
- **Google Gemini 2.0 Flash API** — via `generativelanguage.googleapis.com`
- **Google Fonts** — Plus Jakarta Sans + Playfair Display
- **Single file** — entire app lives in `index.html` (~1000 lines)

---

## 🎨 Design Highlights

- Deep dark navy background (`#080a12`) with animated gradient orbs (violet, pink, teal)
- Dot-grid texture overlay with glassmorphism header
- Smooth fade-in tab animations & hover micro-interactions
- Fully responsive for mobile & tablet

---

## 📂 Project Structure

```
celebrate-ai/
└── index.html      # Complete app — HTML + CSS + JS
└── README.md       # This file
```

---

## 📸 Screenshots

> Fill in after recording your demo

---

## 👤 Author

Built by **Mihir Milind Ughade** for **PromptWars 2026 — Challenge 5: Celebration & Event Planner**

---

## 📄 License

MIT — free to use and build upon.
