# Tutorial 8 - Game Polishing & Balancing

---

## 📌 Identitas

**Nama:** Samuel Taniel Mulyadi
**NPM:** 2206081805

---

## 🧩 Deskripsi Pengerjaan

Pada Tutorial 8 ini, saya telah mengerjakan seluruh latihan dan melakukan polishing terhadap tampilan akhir permainan, terutama dengan fokus pada elemen visual (partikel) dan keseimbangan permainan (game balancing). Berikut adalah ringkasan kontribusi yang saya implementasikan:

---

## 🔧 Latihan Implementasi

1. Menambahkan Efek Particle Hujan

   Menambahkan node GPUParticles2D untuk menciptakan efek hujan.

   Mengatur ParticlesMaterial untuk menyesuaikan jumlah (amount), waktu hidup (lifetime), warna, gravitasi, dan distribusi posisi partikel.

   Mengoptimasi Visibility Rect agar partikel tetap tampil dalam area kamera.

1. Menambahkan Particle Trail pada Karakter Pemain

   Menambahkan GPUParticles2D pada node Player untuk efek jejak langkah.

   Menyesuaikan Texture, jumlah partikel, initial velocity, spread, dan gravity.

   Mengatur partikel agar hanya aktif saat karakter berada di lantai dan sedang bergerak melalui pemanggilan set_emitting(true/false) dalam script.

1. Balancing Spawn Rate Musuh

   Menambahkan Spawner.tscn ke dalam level.

   Melakukan eksperimen terhadap nilai Spawn Rate untuk menemukan
   tempo yang seimbang antara tantangan dan kemampuan pemain.

   Menetapkan nilai ideal Spawn Rate = 1 detik untuk pengalaman bermain yang optimal.

---

## 🌟 Polishing Tambahan

1. Win Screen Enhancement:

   Menambahkan fitur pada tampilan kemenangan agar pemain dapat memilih untuk Play Again dan melanjutkan permainan ke level berikutnya. Implementasi ini bertujuan untuk meningkatkan replayability.

2. Perpanjang Level 1:

   Menambahkan beberapa rintangan dari tiles dan spawner untuk memperpanjang durasi gameplay.

---

## ✅ Status

✅ Seluruh latihan telah dikerjakan dengan lengkap dan sesuai instruksi.

✅ Fitur tambahan pada Win Screen telah diterapkan.

✅ Siap untuk dikumpulkan dan dinilai.
