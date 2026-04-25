# 🖥️ EcoSync Admin Dashboard

> **Real-time Emergency Control Center for Grand Plaza Housing Complex**
> *Monitor live alerts, resolve emergencies, and track feedback — all from one panel.*

---

## 🔗 Access

| Panel | URL |
|---|---|
| Main Site | [https://jocular-custard-374cb6.netlify.app|
| Admin Panel |[ `https://your-site.netlify.app/admin.html`](https://quiet-frangollo-338d5f.netlify.app) |

---

## 📊 What You Can See

### 🚨 Emergency Reports
- Resident name, flat/block number
- Emergency type — Medical / Fire / Other
- Full description of the issue
- Timestamp of submission
- **MARK RESOLVED** button — updates Firebase instantly

### ⚡ SOS Alerts
- Type — Safe / Need Help / Trapped
- Room number
- Timestamp
- Color-coded by severity

### ⭐ Feedback
- Star rating (1–5)
- Written feedback from residents
- Sorted by latest first

### 📈 Emergency Breakdown
- Visual bar chart
- Medical vs Fire vs Other — percentage split
- Live calculated from real data

---

## 🔢 Stats at a Glance

| Card | Shows |
|---|---|
| 🔴 TOTAL REPORTS | All emergency form submissions |
| 🔵 SOS ALERTS | All quick access button triggers |
| 🟢 RESOLVED | Cases marked as resolved |
| 🟡 FEEDBACK | Total ratings received |

---

## ⚙️ How It Works

```
Resident submits form / presses SOS
            ↓
   Firebase Firestore stores data
            ↓
   Admin panel fetches live data
            ↓
Admin sees alert → clicks MARK RESOLVED
            ↓
   Firebase updates status instantly
```

---

## 🔄 Auto Refresh

The dashboard **automatically refreshes every 30 seconds** — no manual reload needed. You can also click the **⟳ REFRESH** button anytime for instant update.

---

## 🛠️ Tech Used

```
Firebase Firestore  →  Live database
Firebase SDK v10    →  Modular imports
Rajdhani Font       →  UI typography
Share Tech Mono     →  Clock & numbers
Vanilla JS          →  Zero dependencies
```

---

## 🔥 Firebase Collections Read

| Collection | Data |
|---|---|
| `reports` | Emergency form submissions |
| `sos` | Quick access SOS triggers |
| `feedbacks` | Star ratings + text |

---

## 🚀 How to Open

```bash
# Option 1 — Local
Open admin.html with Live Server in VS Code

# Option 2 — Deployed
https://quiet-frangollo-338d5f.netlify.app
```

> No login required for hackathon demo.
> For production — add Firebase Auth.

---



---

*© 2025 EcoSync Admin Panel — Decentralized. Reliable. Fast.*
