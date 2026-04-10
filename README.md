# Mini-Project-Claude-Skills-Development

Repositori ini berisi kumpulan **Claude Skills** yang dikembangkan secara mandiri — instruksi terstruktur yang memungkinkan Claude AI melakukan tugas-tugas spesifik dengan lebih akurat, konsisten, dan terarah.

---

## 🧠 Apa itu Claude Skill?

Claude Skill adalah file `SKILL.md` yang berisi instruksi khusus bagi Claude untuk menangani jenis tugas tertentu. Skill bekerja seperti "modul kemampuan" — Claude akan membacanya saat mendeteksi konteks yang relevan, lalu mengikuti panduannya untuk menghasilkan output yang lebih baik.

Setiap skill terdiri dari:
- **Metadata** (`name`, `description`) — menentukan kapan skill ini dipanggil
- **Instruksi** — langkah-langkah, format output, dan panduan khusus
- **Resources (opsional)** — skrip, referensi, atau aset pendukung

---

## 📁 Struktur Repositori
Mini-Project-Claude-Skills-Development/
├── skills/
│   ├── nama-skill-1/
│   │   ├── SKILL.md
│   │   └── references/   # (opsional)
│   ├── nama-skill-2/
│   │   └── SKILL.md
│   └── ...
└── README.md

---

## 🚀 Skills yang Tersedia

| Skill | Deskripsi Singkat |
|-------|-------------------|
| `nama-skill-1` | Deskripsi singkat fungsinya |
| `nama-skill-2` | Deskripsi singkat fungsinya |

> Tabel ini akan terus diperbarui seiring penambahan skill baru.

---

## 🛠️ Cara Menggunakan

1. Salin folder skill yang diinginkan ke direktori skills Claude kamu (biasanya `/mnt/skills/user/`)
2. Pastikan `SKILL.md` memiliki frontmatter YAML yang valid:
```yaml
   ---
   name: nama-skill
   description: Kapan dan bagaimana skill ini digunakan.
   ---
```
3. Claude akan otomatis mendeteksi dan menggunakan skill saat konteks percakapan cocok.

---

## 📌 Prinsip Pengembangan

- **Satu skill, satu tujuan** — setiap skill dirancang untuk domain atau tugas yang spesifik
- **Deskripsi yang jelas** — bagian `description` adalah kunci agar skill terpanggil di waktu yang tepat
- **Iteratif** — skill dikembangkan melalui siklus: draft → uji → evaluasi → perbaiki

---

## 📝 Lisensi

MIT License — bebas digunakan dan dimodifikasi.
