# TMC Connect v2.0 🎓

**Campus Digital Hub — Attendance Reimagined for Campus Life**

TMC Connect is a cross-platform campus attendance and event management system built with [Expo](https://expo.dev) (React Native) and [Firebase](https://firebase.google.com). It replaces outdated paper-based attendance with QR code check-ins, GPS location verification, and real-time analytics — designed specifically for Philippine campuses.

🌐 **Live Web App**: [cajes-jm-tmc-connect.vercel.app](https://cajes-jm-tmc-connect.vercel.app)

---

## ✨ Features

- **QR Code Check-In** — Generate and scan unique QR codes for instant event check-ins directly from mobile devices.
- **Geolocation Attendance** — Verify student presence at campus events with precise GPS-based location checks — no more proxy attendance.
- **Event Management** — Discover, register, and track campus events all in one place — from academic seminars to org activities.
- **Real-Time Analytics** — Organizers get instant attendance reports and participation insights.
- **Secure Authentication** — Role-based access for students, faculty, and administrators backed by Firebase Auth.
- **Cross-Platform** — Works flawlessly on iOS, Android, and the web — one app for every device on campus.
- **Offline Resilience** — Designed to handle intermittent campus WiFi with AsyncStorage persistence.

---

## 🧑‍🤝‍🧑 User Roles

| Role                | Description                                                                             |
| ------------------- | --------------------------------------------------------------------------------------- |
| **Student**         | Browse events, register, scan QR codes for attendance, view personal attendance history |
| **Assistant Admin** | Manage events, view attendance records, send announcements                              |
| **Main Admin**      | Full system control — user management, all event oversight, system configuration        |

---

## 🏗️ Tech Stack

| Category               | Technology                                                                                          |
| ---------------------- | --------------------------------------------------------------------------------------------------- |
| **Frontend Framework** | [Expo](https://expo.dev) (React Native) + [Expo Router](https://docs.expo.dev/router/introduction/) |
| **Language**           | TypeScript (99.1%)                                                                                  |
| **Backend / Database** | [Firebase](https://firebase.google.com) (Firestore, Auth, Storage)                                  |
| **UI Libraries**       | React Native Paper, React Native Reanimated, Linear Gradient, React Native SVG                      |
| **Maps & Location**    | React Native Maps, Expo Location                                                                    |
| **Charts**             | React Native Chart Kit, React Native Gifted Charts                                                  |
| **QR Code**            | React Native QRCode SVG                                                                             |
| **Web Deployment**     | [Vercel](https://vercel.com)                                                                        |
| **Mobile Deployment**  | [EAS Build](https://docs.expo.dev/build/introduction/)                                              |

---
