# MC-Daylight
MC Daylight DATA progress packets
# 🛠️ MC-Daylight Packets  
### Mobile Field Reporting for Daylight Construction

**MC-Daylight Packets** is a mobile-first field reporting web app designed for construction and utility crews performing daylighting, excavation, and restoration work.

It allows a foreman to quickly document the day’s work, capture photos, record delays, sign off, and generate a **shareable, official HTML field report** — all from a phone, even in low-connectivity environments.

---

## 🚧 Core Features

### 📋 Job & Company Info
- Company name
- Job location or ID
- Date of work (auto-defaults to today)

### 🧱 Work Performed Checklist
- Sawcut
- Jackhammer
- Excavation
- Utilities
- Backfill
- Temporary Patch
- Free-text work notes

### ⚠️ Issues & Delays
- Equipment
- Weather
- Utility conflict
- Traffic
- Detailed notes per issue

### 📸 Photo Documentation
- Multi-photo upload
- Preview grid
- Remove individual photos
- Photos embedded directly into final report

### 🕒 Time & Authorization
- Start time
- End time
- Lunch duration (minutes)
- Typed foreman signature (script-style)

---

## 📄 Report Generation

- Generates a clean **official field report**
- White background, print-friendly layout
- Embedded photos
- Signature block
- Company + job header
- BlueComet branding footer

### Output Options
- 👀 Preview in-app
- 💾 Download as `.html` file
- 📤 Share via native mobile share (Web Share API)
- Fallback to download if sharing isn’t supported

---

## 💾 Draft Auto-Save

- All form data is automatically saved to **localStorage**
- Draft restores on page reload
- One-tap “Clear” to wipe the form

> Designed for real field conditions where apps may be closed, refreshed, or lose connection.

---

## 🧠 Tech Stack

- Single-file application
- **HTML + CSS + Vanilla JavaScript**
- No frameworks
- No backend
- No accounts
- Mobile-first layout
- Offline-tolerant design

---

## 📁 Project Structure

```text
mc-daylight-packets/
└── index.html
