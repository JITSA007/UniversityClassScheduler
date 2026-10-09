<div align="center">

  <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/128/null/external-timetable-university-flaticons-lineal-color-flat-icons.png" alt="Logo" width="100" />

  # 🎓 University Class Scheduler <span style="color:#6366f1">Dynamic Edition</span>

  **v12.0 • Pro Enterprise & Academic Timetabling System**

  <p>
    The world's most powerful, responsive, and elegant client-side university timetabling system.<br>
    <b>Developed by Jitendra Prajapat • Phone/WhatsApp: +91 9664301637</b>
  </p>

  <p>
    <a href="#">
      <img src="https://img.shields.io/badge/Release-v12.0.0-indigo?style=for-the-badge&logo=rocket" alt="Version" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Developer-Jitendra%20Prajapat-amber?style=for-the-badge&logo=person" alt="Developer" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Contact-9664301637-emerald?style=for-the-badge&logo=whatsapp" alt="Contact" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Tech-Vanilla%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Style-Glassmorphism-38bdf8?style=for-the-badge&logo=tailwindcss" alt="Tailwind" />
    </a>
  </p>

  <p align="center">
    <a href="#-key-features">✨ Key Features</a> •
    <a href="#-day-wise-view">📅 Day View</a> •
    <a href="#-faculty-workload-analytics">📊 Workload Analytics</a> •
    <a href="#-2-slot-lab-sessions">🧪 2-Slot Labs</a> •
    <a href="#-commercial-license--upi-payments">💳 Commercial License & UPI</a> •
    <a href="#-quick-start">🚀 Quick Start</a>
  </p>
</div>

---

> [!IMPORTANT]
> **DEVELOPER & COMMERCIAL LICENSE NOTICE**  
> This software is designed and developed by **Jitendra Prajapat** (Contact: **+91 9664301637**).  
> **Commercial Use Warning:** Using this application commercially for any university, college, school, coaching institute, or business organization **requires a commercial license**. Users must pay the developer (**Jitendra Prajapat**) via UPI (**`9664301637@upi`**) or contact **9664301637** before commercial deployment.

---

## ✨ Key Features

### 👨‍🏫 **Faculty Categorization (On-Roll vs Visiting)**
* **Category Tagging:** Assign faculty members as **On-Roll Faculty** or **Visiting Faculty** directly in Data Entry, Subject Database, Excel templates, and Faculty View.
* **Category Filters:** Filter **Free Faculty Finder** and **Faculty Workload Summary** by `Both (All)`, `On-Roll Only`, or `Visiting Only`.

### 🔍 **Multi-Field Database Search Engine**
* **Universal Real-Time Search:** Search across Subject Code, Subject Name, Faculty Name, Batch, Room, Specialization, Type, Hours, and Faculty Category.
* **Filter Chips:** One-click filter chips for `Academic`, `Labs`, `Activities`, `On-Roll`, and `Visiting`.
* **Subject Cloning:** Duplicate any subject record instantly with 1-click `Duplicate Subject` action.

### 🧪 **Redesigned 2-Slot Lab Session System**
* **Continuous Visual Capsules:** 2-slot continuous lab sessions automatically combine across all views:
  * **Timetable Grid View:** Joined purple glassmorphic pill capsule connecting Slot 1 (`LAB 1/2`) and Slot 2 (`LAB 2/2`) with vertical session flow indicators.
  * **Vector PDF Export:** Merged `colSpan: 2` lab cells with custom purple fill (`[243, 232, 255]`), purple border accents, and bold titles.
  * **Excel Export:** Merged columns (`c` to `c+1`) with clear `[2-SLOT LAB]` labels, faculty, room, and specialization text.
  * **Print Layout:** Merged `<td colspan="2">` styled with purple gradient backgrounds and distinct lab badges.

### 📊 **Faculty Workload Analytics Dashboard**
* **Comprehensive Metrics Cards:** Real-time metrics for Total Faculty Count, Target Hours/Wk, Scheduled Slots, and High Workload Count (>18h).
* **Workload Status Badges:** Automated tags for `Optimal Load`, `High Workload (>18h)`, and `Light Load (<6h)`.
* **Visual Progress Bars:** Percentage progress (`% Scheduled`) showing target vs actual scheduled period slots per faculty member.
* **Detailed Subject Breakdown:** Expandable assigned subjects breakdown list per faculty member.

### 📅 **Day-Wise Class & Faculty Matrix ("Day View")**
* **Compact Integrated Toolbar:** Single-row compact toolbar (`MON`, `TUE`, `WED`, `THU`, `FRI`, `SAT`) for selecting any day of the week with zero vertical space waste.
* **Dual View Modes:**
  * **By Batch Mode:** Period-by-period side-by-side matrix of all active classes across every batch for the selected day, highlighting assigned faculty names (`<i class="fa-solid fa-user-tie"></i>`), rooms, and specializations.
  * **By Faculty Mode:** Cross-faculty matrix showing which batch and room each faculty member is teaching during each period slot, or marking them as `Free`.
* **Live Day Filter:** Filter day matrix instantly by faculty name, subject code, batch, or room.

### 💳 **Integrated UPI Payment Engine & Commercial License**
* **Developer Modal & Footer Bar:** Instant access to developer info, phone contact (**9664301637**), WhatsApp support, and commercial licensing guidelines.
* **Interactive UPI Payment presets:** Quick selection for **`₹50`**, **`₹500`**, **`₹5,000`**, and **`Custom Amount`**.
* **Mobile UPI Deep Linking:** Direct payment integration (`upi://pay?pa=9664301637@upi...`) supporting Google Pay, PhonePe, Paytm, and BHIM.
* **Live Dynamic QR Code:** Auto-generated scan-to-pay QR code for desktop users.
* **Copy UPI ID:** 1-click clipboard copy for `9664301637@upi`.

### 🧠 **Intelligent Scheduling & Conflict Shield**
* **Auto-Scheduler Algorithm:** Automatically assigns classes, prioritizing 2-slot Labs and balancing faculty workloads.
* **Real-Time Conflict Shield:** Prevents double-booking faculty members or rooms across batches.
* **Dynamic Bell Schedule & Lunch:** Configure custom period durations and lunch breaks (after Period 1, 2, 3, 4, or 5).
* **Local Persistence & JSON Backup:** Data persists in browser local storage (`uniSchedDynV12`) with 1-click JSON backup/restore.

---

## 🚀 Quick Start

This project requires **zero installation**.

1. Download `index.html`.
2. Open it in Chrome, Edge, Brave, or Safari.
3. **Done!**

---

## ⚙️ Configuration & Bell Schedule Settings

Click the **Gear Icon** (⚙️) in the top menu to access **Global System Config**:

| Setting | Description |
| --- | --- |
| **College Name & Dept** | Defines header for all PDF exports, Excel exports, and Print outputs. |
| **Start Time** | Set college opening time (e.g., 09:00 AM). |
| **Custom Period Durations** | Configure individual durations for Period 1, Period 2, Period 3, etc. |
| **Global Lab Duration** | Toggle between 2 consecutive slots (2 Hours) or 1 slot. |
| **Lunch Break Settings** | Set lunch duration (mins) and specify after which period lunch occurs. |
| **Authority Signatures** | Add up to 4 custom signature titles (e.g. Principal, HOD, Timetable In-Charge) for print/PDF footers. |

---

## 📞 Developer Contact & Commercial Licensing

- **Developer Name:** Jitendra Prajapat  
- **Contact Number / WhatsApp:** **+91 9664301637**  
- **UPI ID:** `9664301637@upi`  
- **Commercial Use:** Requires a commercial license from developer Jitendra Prajapat.

---

<div align="center">

**Developed with ❤️ by Jitendra Prajapat (Ph: 9664301637)**

</div>
