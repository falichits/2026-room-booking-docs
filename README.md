# 2026 Room Booking Documentation

Repository ini berisi dokumentasi lengkap untuk sistem **Room Booking 2026**.

Dokumentasi mencakup:

* Deskripsi sistem
* Arsitektur
* API Documentation
* Panduan penggunaan
* Screenshot aplikasi

---

# 📌 Deskripsi Sistem

Room Booking System adalah aplikasi untuk melakukan peminjaman ruangan secara online.

Sistem memiliki 2 role:

## Mahasiswa

Mahasiswa dapat:

* Login
* Mengajukan booking ruangan
* Melihat status booking
* Menghapus booking

## Admin

Admin dapat:

* Login
* Melihat semua booking
* Menyetujui booking
* Menolak booking
* Menghapus booking

---

# 🏗 Arsitektur Sistem

```
Frontend (HTML, CSS, JS)
        ↓
Backend (ASP.NET Core Web API)
        ↓
Database (SQLite)
        ↓
Mobile App (Flutter)
```

---

# 📡 API Endpoint

Base URL:

```
http://localhost:5242/api/RoomBookings
```

---

## GET All Bookings

```
GET /api/RoomBookings
```

---

## GET Booking by Id

```
GET /api/RoomBookings/{id}
```

---

## POST Create Booking

```
POST /api/RoomBookings
```

Body:

```
{
  "roomId": 1,
  "peminjam": "Falich",
  "keperluan": "Belajar",
  "tanggalMulai": "2026-06-01T08:00:00",
  "tanggalSelesai": "2026-06-01T10:00:00"
}
```

---

## PUT Update Status

```
PUT /api/RoomBookings/{id}/status
```

---

## DELETE Booking

```
DELETE /api/RoomBookings/{id}
```

---

# 🖥 Screenshot

Screenshot:
![Login Screenshot](https://raw.githubusercontent.com/falichits/2026-room-booking-docs/main/images/login.png)

Contoh:

```
docs/images/login.png
```

---

# 📱 Platform

Frontend → Web
Backend → ASP.NET Core
Mobile → Flutter
Database → SQLite

---

# 👨‍💻 Developer

Nama: Falich ITS
Program Studi: Teknik Informatika
Tahun: 2026

---

# 🎯 Tujuan Project

Project ini dibuat untuk:

Tugas Project Room Booking System 2026

---

# 📦 Repository Terkait

2026-room-booking-backend
2026-room-booking-frontend
2026-room-booking-mobile
2026-room-booking-infrastructure
2026-room-booking-docs

---
