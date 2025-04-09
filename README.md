# JadKu
# 📘 JadKu (Jadwal Kuliah)

Aplikasi ini merupakan dashboard pribadi sederhana untuk mahasiswa, yang berfungsi untuk mencatat, mengelola, dan melihat **jadwal kuliah** secara interaktif. Dibuat menggunakan HTML5, Tailwind CSS, dan JavaScript ES6+ dengan penyimpanan data berbasis `localStorage`.

---

## 🎯 Deskripsi Singkat

Aplikasi ini mempermudah mahasiswa dalam:
- Menambah jadwal kuliah
- Melihat daftar jadwal mingguan
- Mengedit dan menghapus jadwal yang sudah ada
- Menyaring daftar berdasarkan hari

Semua data disimpan secara **lokal di browser** tanpa memerlukan backend, sehingga aplikasi tetap berfungsi meskipun offline.

---

## ✨ Fitur Utama

- ✅ Tambah jadwal kuliah dengan form input
- ✅ Edit jadwal melalui halaman tampilan daftar
- ✅ Hapus jadwal langsung dari daftar
- ✅ Filter jadwal berdasarkan hari (contoh: “Senin”)
- ✅ Simpan data ke `localStorage` agar tidak hilang saat refresh
- ✅ Navigasi antar halaman (Beranda & Jadwal)
- ✅ Antarmuka menggunakan **Tailwind CSS** yang modern dan responsif

---

## 🧠 Fitur ES6+ yang Diimplementasikan

| Fitur ES6+               | Implementasi                                                |
|--------------------------|-------------------------------------------------------------|
| `let` & `const`          | Digunakan di seluruh modul JS                               |
| Arrow Functions (`=>`)   | `renderSchedules`, `setupFilter`, `delay`, dan lainnya     |
| Template Literals        | Untuk render HTML dinamis di `createScheduleItem()`        |
| Async/Await              | `await delay(200)` untuk simulasi proses async             |
| Classes                  | `class Schedule` digunakan untuk struktur data jadwal       |
| Modularisasi             | Menggunakan `import/export` antara file utils dan data      |

### Penjelasan Singkat:
- **`let` dan `const`**: digunakan sesuai fungsinya untuk variabel tetap dan variabel yang berubah.
- **Arrow Functions**: membuat kode lebih ringkas, digunakan untuk callback, event listener, dan render data.
- **Template Literals**: digunakan untuk menampilkan elemen HTML dengan data dinamis secara efisien.
- **Async/Await**: digunakan untuk menunggu simulasi delay sebelum render awal.
- **Class**: digunakan untuk mendefinisikan struktur data `Schedule`.

---

## 🖼️ Screenshot



