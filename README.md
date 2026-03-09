# 🏥 HealthOffice — School Health Management App

A web-based health office management tool built by students, for schools.  
Developed as a collaboration between **Girls Who Code** and **Coding for Medicine** clubs,  
in partnership with our school's health office.

---

## 📋 About the Project

This app was designed to support our school nurse by replacing paper-based visit logs  
with a simple, organized digital system. It was built through a real software development  
cycle — from initial requirements gathering with the nurse, to design, development, and testing.

**This project gave us hands-on experience with:**
- Gathering real requirements from an end user (the school nurse)
- Designing a multi-page application with a clear user flow
- Building a functional frontend with persistent data storage
- Working as a team through a professional-style development process

---

## ✨ Features

### 📋 Visit Log
- Log student visits with name, grade, reason, notes, and time
- Mark students as: Returned to Class, Sent Home, Resting, or Referred
- Filter visits by reason
- Discharge students with a timestamped time-out
- All data persists across sessions (localStorage)

### 🔔 Notifications
- Send notifications to parents, teachers, or admin
- Set urgency level: Routine, Urgent, or Emergency
- Notification log with full history
- Auto-notification option when logging a visit

### 📊 Reports
- Weekly summary dashboard with key stats
- Visual bar charts — visits by reason and by grade
- Full visit history table
- Print / export to PDF

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | App logic, data management |
| localStorage | Client-side data persistence |
| Google Fonts | Typography (Fraunces, DM Sans, DM Mono) |

> No frameworks, no backend, no dependencies — runs entirely in the browser.

---

## 🚀 How to Run

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. That's it — no install, no server needed

```bash
git clone https://github.com/samysasikumar/nurse-health-office-app
cd nurse-health-office-app
open index.html
```

---

## 📁 Project Structure

```
nurse-health-office-app/
│
├── index.html       # Main app (single-file architecture)
└── README.md        # Project documentation
```

---

## 🔮 Future Improvements

- [ ] Backend database (so data syncs across devices)
- [ ] Login system with nurse authentication
- [ ] Email / SMS integration for real parent notifications
- [ ] Student search and repeat-visit tracking
- [ ] Export reports as CSV or PDF
- [ ] Mobile-responsive layout for tablet use

---

## 👩‍💻 Built By

**Samy Sasikumar** — [samysasikumar.github.io](https://samysasikumar.github.io)  
A collaboration between **Girls Who Code** and **Coding for Medicine** clubs.

> *"This project showed us what it actually feels like to build software for a real user  
> with real needs — not just for a grade."*

---

## 📄 License
MIT License — free to use, adapt, and build on.
