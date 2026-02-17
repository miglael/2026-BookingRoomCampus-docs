# Room Booking Campus System

Sistem peminjaman ruangan kampus berbasis web dengan autentikasi JWT dan role-based access (Admin & User).

## Fitur Utama

###  User
- Register & Login
- Mengajukan booking ruangan
- Melihat daftar booking sendiri
- Membatalkan booking (status menunggu)

### Admin
- Melihat semua booking
- Approve / Reject booking
- Update status booking
- Hapus booking
- Pencarian booking

---

## Teknologi

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- JWT Authentication
- ASP.NET Identity

### Frontend
- HTML
- CSS
- Vanilla JavaScript (Fetch API)

---

## Role System

| Role | Akses |
|---|---|
| User | Membuat dan melihat booking |
| Admin | Mengelola semua booking |

---

## Instalasi Backend

```
git clone https://github.com/username/repo.git
cd BookingRoomCampus
dotnet restore
dotnet ef database update
dotnet run
```
Backend berjalan di:

http://localhost:5152


Swagger:

http://localhost:5152/swagger
