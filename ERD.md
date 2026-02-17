# Entity Relationship Diagram

##  User
| Field | Type |
|---|---|
| Id | string |
| Email | string |
| FullName | string |
| PasswordHash | string |

---

##  Booking
| Field | Type |
|---|---|
| Id | int |
| NamaPeminjam | string |
| Ruangan | string |
| Tanggal | datetime |
| JamMulai | string |
| JamSelesai | string |
| Status | string |

---

## Relationship

User (1) → (Many) Booking
