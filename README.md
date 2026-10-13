# 🧠 Second Brain

A personal work and knowledge system in a single HTML file. No install, no build, and it works offline.
It isn't tied to any one person: whoever opens it sets their own name, and their data stays private to them.

## Features
- 🔔 **Reminders:** upcoming joinings, interviews, due and overdue tasks, birthdays, work anniversaries and probation reviews. Get them by email or WhatsApp, now or as a daily digest.
- 🧑‍💼 **Hiring:** a candidate board (Applied, Screening, Interview, Offer, Hired). Add applicants straight from Gmail.
- 👥 **People:** employee directory with onboarding and exit checklists. There is also an HR starter kit of SOPs, policies, letter templates and monthly routines.
- 📧 **Mail:** your live Gmail (Inbox, Unread, Starred, Important, Sent, All mail, plus search and *Load more*). Turn any email into a task, note or inbox item.
- 📥 **Inbox:** capture thoughts fast, then convert them into notes, tasks, ideas or links.
- 📝 **Notes & 💡 Ideas:** Markdown, `[[wiki links]]` with backlinks, `#tags`, clickable checklists.
- 🚀 **Projects:** status, progress bar and linked tasks.
- ✅ **Tasks:** due dates, priority, and Focus / Upcoming / No date / Done views.
- 📔 **Journal:** daily entries with prompts, a 6-week calendar strip and a streak counter.
- 🔗 **Library:** saved articles, videos and tools.
- 💼🏡 **Work / Personal spaces:** switch at the top of the sidebar. Every item belongs to one space, and Personal items never go into a handover.
- ⚙️ **Settings & handover:** profile, backup and restore, a handover note, a handover export, and import & merge.
- 🔍 `Ctrl+K` searches and creates, `Ctrl+Enter` captures, `Ctrl+E` switches between Write and Preview.
- 🌗 Light and dark themes, mobile friendly.

## Two ways to run it
| | claude.ai version | Local file (`index.html`) |
|---|---|---|
| Where data is saved | Your claude.ai account, private to you, live-synced across devices | This browser only |
| Gmail | ✅ through your own Gmail connector | ❌ |
| Setup | Open the link and sign in | Download and double-click |

## 🤝 Handover guide

### If you're leaving or changing roles
1. Open **⚙️ Settings & handover**.
2. Click **1. Write handover note**. The app drafts it from your active projects, open tasks, notes, library, unsorted inbox items and your important or starred email threads from the last 60 days. Fill in the blanks: contacts, shared folders, tools and accounts (never passwords), and anything to watch out for.
3. Click **2. Export for handover**. This downloads a `handover-<name>-<date>.json` file with all your work. Everything in your **🏡 Personal** space and your **journal** is left out.
4. Give that file to your manager or the next person, for example by email or a shared drive.

### If you're taking over
1. Open the app (the claude.ai link, or `index.html` from this repo) and enter your name when asked.
2. Go to **⚙️ Settings & handover → Import & merge** and choose the handover file. Their items are added next to yours, and nothing of yours is replaced.
3. The app opens the **Handover note**. Start there: it links to every project, task and key note.
4. Mail shows whichever Gmail account *you* have connected. If you've inherited a shared mailbox, connect it in claude.ai Settings → Connectors.

### Good habits that make handover easy
- Link tasks to projects, and keep project status up to date.
- Keep private things in the **🏡 Personal** space (or tag them `#personal`) so they never leave with your work.
- Export a backup from time to time (**⚙️ Settings → Export everything**).
