# Traffic Fine Management System

> A multi-platform traffic fine management solution for Sri Lanka Police. This repository includes a Spring Boot backend, a React/Vite citizen portal, a Flutter mobile app, and an admin portal for managing fines and users.

---

## ✨ Features

- Secure backend with Spring Security and JWT authentication
- Traffic fine issuance, search, and management
- Citizen fine lookup, payment tracking, and history
- Flutter mobile app for Android/iOS desktop/web
- Admin dashboard and analytics
- REST API with OpenAPI/Swagger documentation
- PostgreSQL and H2 database support

---

## 🚀 What’s Included

- `traffic-fine-api/` — Java Spring Boot backend API
- `citizen-web-portal/` — Citizen-facing web portal (React + Vite)
- `admin-web-portal/` — Admin portal for fine management and reports
- `mobile-app/` — Flutter mobile application for citizens
- `docs/` — Project documentation and notes
- `database/` — Database scripts and schema definitions (if present)

---

## 🧭 Architecture Overview

The system is designed as a multi-tier application:

- Backend API handles authentication, fine records, payments, and business logic
- Web portals communicate with the API over HTTPS
- Mobile app consumes the same API for citizen workflows

---

## 🛠️ Requirements

- Java 17+ and Maven for the backend
- Node.js 16+ and npm/yarn for the React portal
- Flutter 3+ for the mobile application
- PostgreSQL or H2 for local development

---

## ⚡ Quick Start

### Backend API

1. Open `traffic-fine-api/` in your IDE.
2. Configure database settings in `src/main/resources/application.properties` or `application.yml`.
3. Run:

```bash
cd traffic-fine-api
mvn spring-boot:run
```

4. Access Swagger/OpenAPI docs at `http://localhost:8080/swagger-ui.html` if enabled.

### Mobile App

1. Open `mobile-app/traffic_fine_app/`.
2. Run:

```bash
cd mobile-app/traffic_fine_app
flutter pub get
flutter run
```

3. Use the app to authenticate, view fines, and manage payments.

### Citizen Web Portal

> The portal currently contains a placeholder demo file. Add project assets and run the portal from `citizen-web-portal/` when available.

### Admin Web Portal

> The admin portal currently contains a placeholder demo file. Add project assets and run it from `admin-web-portal/` when available.

---

## 🧪 Testing

- Backend tests should be run with Maven in `traffic-fine-api/`
- Mobile app widget tests can be run with Flutter in `mobile-app/traffic_fine_app/`

---

## 📌 Notes

- This repository is intended as a complete traffic fine management foundation. Expand each portal and backend service with real UI, API endpoints, and integration flows.
- Update configuration files with your own database credentials and environment settings.

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request with a clear description.

---

## 📄 License

This project is licensed under the terms defined in the `LICENSE` file.
