# Fungsi (Function)

## 🧩 Apa Itu Fungsi?

Bayangkan kamu sedang membuat **jus buah** 🍓🍊.

Setiap kali kamu ingin membuat jus, kamu harus:

1. Ambil buah.
2. Kupas buah.
3. Masukkan ke blender.
4. Tambah gula & air.
5. Blender.
6. Sajikan.

Kalau kamu ingin membuat jus **berulang kali**, kamu tidak mau menulis langkah-langkah itu **terus menerus**, kan?

Nah!
👉 Di dalam **pemrograman**, kita bisa **mengelompokkan perintah-perintah itu** ke dalam **satu wadah yang disebut *fungsi (function)***.

---

## 💡 Pengertian Fungsi

**Fungsi (Function)** adalah **sekumpulan perintah atau kode** yang dibuat untuk **melakukan tugas tertentu**, dan bisa **dipanggil kapan saja** saat dibutuhkan.

### 📖 Contoh pengertian sederhana:

> Fungsi adalah “**resep**” yang bisa digunakan berkali-kali tanpa perlu menulis ulang langkahnya.

---

## 🧠 Kenapa Kita Butuh Fungsi?

Tanpa fungsi, program kita akan jadi panjang dan berulang-ulang.
Dengan fungsi, kita bisa:

* Menghemat waktu penulisan kode.
* Membuat program lebih rapi dan mudah dibaca.
* Memudahkan perawatan atau perubahan program.

---

## 🪄 Analogi Fungsi di Dunia Nyata

Bayangkan **remote TV** 🖥️:

* Saat kamu tekan tombol **volume+**, kamu tidak tahu detail bagaimana suaranya bertambah.
* Kamu hanya tahu kalau fungsi “menambah volume” akan dijalankan.

👉 Sama seperti itu, di pemrograman kamu hanya **memanggil fungsi**, dan komputer akan **melakukan pekerjaannya sendiri**.

---

## 🧾 Struktur Dasar Fungsi

Secara umum, fungsi punya **tiga bagian utama**:

1. **Nama fungsi** → untuk memanggilnya kembali.
2. **Parameter (input)** → data yang bisa dikirim ke fungsi.
3. **Isi fungsi (blok kode)** → perintah yang akan dijalankan.
4. **Nilai balik (output)** → hasil yang dikembalikan fungsi (opsional).

---

## 📘 Contoh Fungsi di Python

### Contoh 1: Fungsi sederhana tanpa input dan tanpa output

```python
def sapa():
    print("Halo, selamat datang di dunia pemrograman!")

# Memanggil fungsi
sapa()
```

🧩 Penjelasan:

* `def` → digunakan untuk membuat fungsi.
* `sapa` → nama fungsi.
* `()` → tanda fungsi dipanggil.
* `print(...)` → perintah yang dijalankan di dalam fungsi.

Hasil di layar:

```
Halo, selamat datang di dunia pemrograman!
```

---

### Contoh 2: Fungsi dengan **parameter (input)**

```python
def sapa_nama(nama):
    print("Halo,", nama, "! Senang bertemu denganmu.")

sapa_nama("Andi")
sapa_nama("Budi")
```

🧩 Penjelasan:

* Fungsi `sapa_nama` menerima satu input bernama `nama`.
* Saat kita panggil `sapa_nama("Andi")`, fungsi menggantikan `nama` dengan “Andi”.

Hasil di layar:

```
Halo, Andi ! Senang bertemu denganmu.
Halo, Budi ! Senang bertemu denganmu.
```

---

### Contoh 3: Fungsi dengan **hasil (return value)**

Kadang fungsi tidak hanya menampilkan hasil, tapi juga **mengembalikan nilai**.

```python
def tambah(a, b):
    hasil = a + b
    return hasil

# Memanggil fungsi dan menyimpan hasilnya
total = tambah(5, 3)
print("Hasil penjumlahan:", total)
```

🧩 Penjelasan:

* Fungsi `tambah(a, b)` menjumlahkan dua angka.
* `return hasil` artinya fungsi mengembalikan nilai hasil.
* Nilai ini bisa kita simpan ke variabel lain (`total`).

---

## 🔄 Fungsi Bisa Dipanggil Berkali-kali

Kelebihan utama fungsi adalah **bisa digunakan berulang kali**.

Contoh:

```python
def garis():
    print("----------------")

print("Menu Utama")
garis()
print("1. Tambah Data")
print("2. Hapus Data")
garis()
```

Hasil:

```
Menu Utama
----------------
1. Tambah Data
2. Hapus Data
----------------
```

Daripada menulis `print("----------------")` berkali-kali, cukup buat **fungsi `garis()`** sekali saja.

---

## 🧱 Jenis-Jenis Fungsi (Secara Umum)

| Jenis Fungsi                  | Ada Input? | Ada Output? | Contoh                                |
| ----------------------------- | ---------- | ----------- | ------------------------------------- |
| 1. Tanpa input & output       | ❌          | ❌           | `def halo(): print("Halo!")`          |
| 2. Dengan input, tanpa output | ✅          | ❌           | `def sapa(nama): print("Halo", nama)` |
| 3. Tanpa input, dengan output | ❌          | ✅           | `def angka(): return 10`              |
| 4. Dengan input & output      | ✅          | ✅           | `def tambah(a,b): return a+b`         |

---

## ⚠️ Hal yang Perlu Diperhatikan

1. **Fungsi harus didefinisikan dulu**, baru bisa dipanggil.
2. Nama fungsi **tidak boleh sama** dengan nama variabel.
3. Jangan lupa tanda **`()`** saat memanggil fungsi.
4. Gunakan nama fungsi yang **jelas dan mudah dimengerti**.

---

## 🧩 Contoh Sederhana di Dunia Nyata

| Fungsi                      | Input | Output               |
| --------------------------- | ----- | -------------------- |
| `buat_jus(buah)`            | buah  | jus                  |
| `hitung_luas_persegi(sisi)` | sisi  | luas                 |
| `cek_kelulusan(nilai)`      | nilai | status (Lulus/Tidak) |

---

## 🧠 Kesimpulan

* Fungsi adalah **kumpulan perintah** yang digunakan untuk **melakukan tugas tertentu**.
* Tujuannya: **menghemat kode**, **memudahkan pembacaan**, dan **menghindari pengulangan**.
* Fungsi bisa punya **input (parameter)** dan bisa **mengembalikan nilai (return)**.
* Kita bisa **memanggil fungsi berkali-kali** di dalam program.

---

## ✍️ Latihan untuk Kamu

1. Buat fungsi bernama `halo()` yang menampilkan “Halo Dunia Pemrograman!”.
2. Buat fungsi bernama `tambah(a, b)` yang mengembalikan hasil penjumlahan dua angka.
3. Buat fungsi bernama `luas_persegi(sisi)` yang menghitung luas persegi.
4. Buat fungsi bernama `sapa_nama(nama)` yang menampilkan “Selamat datang, <nama>!”.

---
