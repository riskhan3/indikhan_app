# IndiKhan Project (Monorepo)

Aplikasi manajemen ISP lengkap dengan backend (NestJS) dan frontend mobile (Flutter).

## Struktur Project

```
root/
├── backend/   # NestJS + Prisma + PostgreSQL (API Server)
└── frontend/  # Flutter Mobile App (iOS/Android/Web)
```

## Quick Start

### 1. Setup Backend
```bash
cd backend
npm install
# Setup .env sesuai README di dalam folder backend
npx prisma migrate dev --name init
npm run start:dev
```

### 2. Setup Frontend
```bash
cd frontend
flutter pub get
# Pastikan URL backend di api_service.dart sesuai
flutter run
```

Lihat `README.md` di masing-masing folder untuk detail lebih lanjut.
