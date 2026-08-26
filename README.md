# 📢 College Alert — Campus Event & Notice Management App

**College Alert** is a modern Android app built with **Jetpack Compose**, **Material 3**, and **Supabase**, keeping students, faculty, and admins connected through real-time campus alerts, exam schedules, seminars, and academic notices.

> Built as part of the **App Development Internship — Task 1** at [Rhombix Technologies](https://www.rhombixtechnologies.com)

---

## 📸 Screenshots

| Home Feed | Register | Bookmarks |
|:---:|:---:|:---:|
| <img width="220" alt="Home Feed" src="https://github.com/user-attachments/assets/f2202f67-b8b9-44e7-8150-9ddebb2981ee" /> | <img width="220" alt="Register" src="https://github.com/user-attachments/assets/d00f252c-6f3e-4470-ab54-24e59176014e" /> | <img width="220" alt="Bookmarks" src="https://github.com/user-attachments/assets/0432e931-e8d3-4500-8a31-682dabab4aef" /> |

---

## 🌟 Key Features

### 🎓 For Students
- **Real-Time Campus Feed** — notices filtered by category (Academic, Exams, Seminars, Holidays, Sports, Workshops, Placements)
- **Urgent Broadcast Banner** — high-priority alerts highlighted for critical announcements
- **Event RSVP & Reactions** — one-tap attendance counter with emoji reactions (🔥 👍 ❤️ 🎉 💡)
- **Personalized Bookmarks** — save important notices and exams for quick access
- **Active Streak Tracker** — daily check-in streak to encourage regular engagement
- **AI Notice Assistant** — Gemini-powered summarizer for long circulars and instant Q&A

### 🏛️ For Faculty & Admins
- **Notice Publishing** — create categorized announcements with priority flags (Urgent, High, Normal)
- **AI Announcement Drafter** — generate polished notice drafts with AI assistance
- **Departmental Targeting** — send notices to a specific department or campus-wide
- **Attendee Tracking** — view real-time RSVP counts and engagement

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Jetpack Compose, Material 3 |
| Language | Kotlin (Coroutines + StateFlow) |
| Architecture | MVVM + Clean Architecture |
| Backend | Supabase (PostgreSQL, Auth, REST API, Realtime) |
| Local Storage | Room Database + Encrypted SharedPreferences |
| AI | Gemini API (drafting & summarization) |
| Networking | OkHttp3 |

---


## 📂 Project Structure

```
app/src/main/java/com/example/
├── data/
│   ├── local/          # Room database, DAOs, entities
│   ├── models/         # UserProfile, EventItem, Category, UserRole
│   └── supabase/       # SupabaseService (Auth, REST CRUD, Realtime)
├── ui/
│   ├── components/     # Event cards, filter chips, urgent banners
│   ├── screens/        # AuthScreen, HomeScreen, AdminScreen, BookmarksScreen
│   ├── theme/          # Material 3 colors, typography, shapes
│   └── CollegeAlertViewModel.kt   # State management & business logic
└── MainActivity.kt     # Compose navigation entry point
```

---

## 👨‍💻 Author

**Shakeel** — Final-year Computer Science student, SZABIST Larkana
App Development Intern @ Rhombix Technologies
📧 shakeelsafdar111@gmail.com

---

## 📄 License
MIT License — free to use and customize for your own institution.
