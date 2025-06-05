# 🧋 API Minuman Kekinian

API sederhana berbasis AdonisJS 5 untuk mengelola data minuman kekinian seperti boba, kopi susu, dan jus. Data disimpan di MySQL dan dikelola dengan ORM Lucid.

---

## 📌 Fitur

### Fitur Utama:
- `GET /drinks` — Melihat semua minuman
- `GET /drinks/:id` — Melihat detail minuman berdasarkan ID
- `POST /drinks` — Menambahkan minuman baru

### Fitur Tambahan:
- `GET /drinks/type/:type` — Filter minuman berdasarkan jenis (contoh: Tea, Coffee, Juice)
- `GET /drinks/sugar/:level` — Filter minuman berdasarkan kadar gula (Low, Medium, High)
- `GET /drinks/stats/types` — Menampilkan jumlah minuman per jenis (statistik)

---

## 🧾 Contoh Data

```json
{
  "name": "Boba Milk Tea",
  "type": "Tea",
  "sugar_level": "High"
}
