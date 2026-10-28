<div align="center">

# 📚 Libra Engine (Career Point Library Suite)
### **Full-Stack Digital Library & Seat Allocation Management Platform**

A modern web application built with React and Vite engineered to streamline digital library operations, member registrations, shift-based seat allocations, and administrative catalog management.

<p align="center">
  <a href="https://www.careerpointlibrary.in/"><img src="https://img.shields.io/badge/Live%20Platform-careerpointlibrary.in-007ACC?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-Bundler-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Deployment-Vercel-black?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge" />
</p>

</div>

---

### 🌟 Core Capabilities & Features

- 🎓 **Student & Member Portal:**
  - Online student enrollment and membership plan tracking.
  - Transparent seat layout visualization and slot reservations across flexible timings (Morning, Evening, Full Day).
- 🔐 **Administrative Management Suite:**
  - Secure admin control panel with role-based access.
  - Real-time seat occupancy dashboards, renewal monitoring, and member attendance logs.
  - Student inquiry and contact API management pipelines.
- ⚡ **High-Performance Architecture:**
  - Built on Vite for lightning-fast HMR and optimized production asset bundling.
  - Mobile-responsive design engineered for low-bandwidth environments.
- 🌐 **Cloud Integration & API Routing:**
  - Clean client-side state handling with environment separation (`.env.development` & `.env.production`).
  - Production-ready edge routing and SPA redirects configured via `vercel.json`.

---

### 🏗️ Architecture & Project Structure

```text
libra-engine/
├── public/                 # Static assets, branding, and icons
├── scripts/                # Build and deployment helper scripts
├── src/                    # Application source code
│   ├── assets/             # Images, styling themes, and design tokens
│   ├── components/         # Reusable UI components (Modals, Cards, Navbars)
│   ├── pages/              # Route views (Home, Admin, Student Portal, Contact)
│   ├── services/           # API handlers and HTTP client connectors
│   ├──
