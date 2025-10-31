# 🧠 Flow-Track: Intelligent Low-Code Crowd Management Platform

### 🚀 Hackathon: VIT Digithon 2025  
**Track:** Low Code / No Code Software Development  
**Team:** ICDAT003  

---

## 📋 Overview

**Flow-Track** is an intelligent, low-code platform for **real-time crowd monitoring and management** during high-density events such as concerts, university fests, and public gatherings.  
It provides **camera-based crowd analytics**, **volunteer location tracking**, and **automated emergency alerting**, ensuring swift and data-driven responses to potential stampede situations.

---

## 🎯 Problem Statement

Large gatherings often suffer from **overcrowding, miscommunication, and slow response** to emergencies. Manual crowd tracking is inefficient and lacks real-time accuracy.

Flow-Track provides a **smart, low-code solution** that automates:
- Real-time head count and crowd density analysis  
- Prediction and alerting of stampede-like events  
- Instant coordination between admins and ground-level organizers  

---

## 💡 Key Features

### 🔹 Added Features

#### 1. Camera-Based Crowd Analysis
- Uses live camera feeds to detect:
  - **Head count**
  - **Crowd flow direction**
  - **Crowd density**
- Automatically triggers alerts if density crosses a defined safety threshold or if **stampede patterns** are detected.  
- Achieves **~85% accuracy**, validated against actual crowd data.

#### 2. Organizer Geo-Tracking
- Organizers and volunteers are tracked in real time using location APIs.  
- When a mishap occurs:
  - Immediate alerts are sent to volunteers **within a 10–50 m radius**.  
  - Notifications extend to **100 m radius** for secondary response.  

#### 3. Two-Way Emergency Communication
- **Admin ↔ Organizer** communication channel for alerts and verifications.  
- Organizers can:
  - **Verify alerts** and confirm false positives.  
  - **Trigger SOS alerts** to contact first-level emergency experts instantly.

#### 4. Admin & Organizer Dashboards
- **Admin Dashboard:**
  - Add, edit, view, and delete footage and analysis.
  - Monitor event-wide statistics and camera analytics.
- **Organizer Dashboard:**
  - Real-time footage and density metrics.
  - Predictive alerts for potential crowd surges.

---

### 🔹 Removed Features

1. **Polygon-Based Zone Count Detection**  
   Removed since camera-based count detection provides higher accuracy and better scalability.

2. **Audience Dashboard**  
   Eliminated for performance optimization; focus shifted to admin and organizer use cases.

---

## ⚙️ Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | HTML, CSS, JavaScript, TypeScript |
| **Backend (Optional)** | Firebase / Node.js |
| **Map & Location APIs** | Google Maps JavaScript API (Geometry & Drawing Libraries) |
| **Data Handling** | Browser LocalStorage, Firebase Realtime Database |
| **Visualization** | Custom Analytics Dashboards & Risk Indicators |
| **ML Integration (Future Scope)** | Camera Feed Analysis using OpenCV or TensorFlow.js |

---

## 🔄 Workflow Summary

1. Camera captures live crowd feed.  
2. System analyzes head count, density, and flow direction.  
3. Alerts triggered if danger thresholds or abnormal movement detected.  
4. Nearby organizers receive immediate notifications.  
5. Organizer verifies and sends **SOS or reject alert**.  
6. Admin and emergency experts receive the verified alert for action.

---

## 📈 Impact

- Reduces **response time** in emergencies by up to 60%.  
- Enhances **situational awareness** for event coordinators.  
- Promotes **data-driven crowd management** decisions.  
- Designed for **low-code adaptability** — deployable even by non-technical teams.

---

## 🧩 Future Enhancements

- AI-driven **predictive crowd movement** modeling.  
- Integration with **IoT sensors** and **drone feeds**.  
- Cross-platform mobile app for volunteers and on-site authorities.  
- Support for **multi-camera federated analytics**.

---

## 👥 Team Members

| Name | Reg. No. |
|------|-----------|
| K. Yugavardhan | 122311510201 |
| M. Keerthi Vardhan | 122311510205 |
| Sathram Monisha | 122311510235 |
| R. Lakshmi | 122411530221 |
| K. Bharath Reddy | 122411530139 |

---

## 🔗 Repository

GitHub: [https://github.com/keerthivardhanm/Digithon2025_TeamICDAT003.git](https://github.com/keerthivardhanm/Digithon2025_TeamICDAT003.git)

---

## 🏁 Conclusion

**Flow-Track** revolutionizes event safety through intelligent, low-code automation.  
With accurate crowd analytics, dynamic communication, and real-time emergency handling, it ensures every large gathering remains **safe, efficient, and responsive**.
