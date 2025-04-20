# Angular Admin Dashboard

A fully responsive and modular **Admin Dashboard** built using **Angular**, **Bootstrap**, and **ApexCharts**, following **enterprise-grade architecture** with **DAO/DTO pattern**, **OOP practices**, and **modular components**.

---

## 📊 Features

- ⚙️ Sidebar + Topbar layout
- 📦 Dashboard cards (Revenue, Users, Orders)
- 📈 Charts using ApexCharts
- 🧩 Modular folder structure
- 🔄 REST API integration using RxJS
- ✅ Reactive Forms with validation
- 🧠 DAO/DTO-based architecture
- ⚡ Lazy loading (planned)
- 🌙 Light/Dark mode (optional)

---

## 🚀 Live Demo

> Coming soon on Netlify  
> *(Will be linked once hosted)*

---

## 🧱 Folder Structure (Enterprise-Ready)

```bash
/src/app/
├── core/
│   ├── services/              # API, utility services
│   └── interceptors/          # (optional) HTTP interceptor logic
├── shared/
│   ├── components/            # Reusable components (cards, modals)
│   └── pipes/                 # Custom pipes
├── modules/
│   └── dashboard/
│       ├── components/        # Charts, tables, stats
│       ├── pages/             # Dashboard view
│       ├── dao/               # Interfaces (e.g. UserDAO)
│       └── dto/               # Transformed response models
├── assets/
└── app.module.ts
