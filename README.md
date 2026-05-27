# 🏋️ GymOS — Phase 1

> A complete **single-file gym management platform** built with pure HTML, CSS & JavaScript.  
> No backend. No framework. Just open `gymos.html` in any browser and go.

---

## 🔗 Live File

Open locally:  
```
file:///C:/Users/aryan/GymOS/gymos.html
```

---

## 📦 Features (Phase 1)

| Module | Description |
|--------|-------------|
| 📊 **Dashboard** | Live stats + 4 Chart.js charts (pipeline, sources, roles, monthly trend) |
| 👥 **Staff Management** | Add / edit / delete staff with role, shift, salary, status |
| 📅 **Holiday Calendar** | Click-to-add holidays, events & notes on a monthly calendar |
| 🎯 **Lead Tracker** | Kanban + Table view — New → Called → Visited → Enrolled → Lost |
| 💬 **WhatsApp Templates** | 12 ready-to-send bulk templates with `{name}`, `{date}` variables |
| 👤 **Member Management** | Full membership tracking with plan badges, payment toggle, renewal & WhatsApp |

---

## 👤 Member Management Highlights

- ✅ **Active / Expiring / Expired** status with animated dot indicators
- 💰 **Paid / Unpaid / Partial** — click to toggle payment status instantly
- 🔢 **Days Left** counter — green / yellow / red based on urgency
- 🔄 **One-click Renew** — resets membership from today
- 💬 **Auto WhatsApp message** — smart renewal reminder per member
- 📥 **Export CSV** — download full member list

---

## 🗂️ Project Structure

```
GymOS/
├── gymos.html          ← Main app (open this in browser)
├── README.md           ← This file
├── assets/             ← Icons, images, branding (future)
├── screenshots/        ← UI screenshots (future)
└── docs/               ← Documentation (future)
```

---

## 💾 Data Storage

All data is saved in **browser localStorage** — no server needed.  
Data persists across sessions automatically.

- Seed demo data loads on first open
- Clear localStorage to reset to demo data

---

## 🚀 How to Run

1. Download or clone this repo
2. Open `gymos.html` in **Chrome / Edge / Firefox**
3. That's it — no install, no build step!

```bash
git clone https://github.com/aryanbodkhe05-gif/GymOS.git
cd GymOS
# Open gymos.html in your browser
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Structure |
| CSS3 (custom) | Dark theme UI, animations |
| Vanilla JavaScript | All logic, CRUD, localStorage |
| Chart.js 4.4 | Dashboard charts |
| Font Awesome 6.5 | Icons |

---

## 📌 Planned — Phase 2

- [ ] Multi-branch support
- [ ] Fee receipts / PDF export
- [ ] Attendance tracker
- [ ] Diet plan management
- [ ] Trainer performance dashboard
- [ ] Claude AI integration (smart insights)

---

## 👨‍💻 Author

**Aryan Bodkhe**  
📧 aryanbodkhe05@gmail.com  
🐙 [@aryanbodkhe05-gif](https://github.com/aryanbodkhe05-gif)

---

> Built with ❤️ using Claude Code
