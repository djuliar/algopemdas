# **Minggu 9 - Array 1 Dimensi**

## 🧩 Apa Itu Array?

Bayangkan kamu punya **beberapa kotak penyimpanan** di mana setiap kotak bisa berisi **data** (misalnya angka, huruf, atau nama).

👉 **Array** adalah **kumpulan kotak data yang berurutan** dan **punya nama yang sama**, tapi bisa dibedakan lewat **nomor urut** (yang disebut **indeks**).

---

## 💡 Kenapa Kita Butuh Array?

Tanpa array, kalau kita ingin menyimpan banyak data, kita harus membuat banyak variabel.

Contoh tanpa array:

```python
nilai1 = 80
nilai2 = 75
nilai3 = 90
nilai4 = 85
```

Bayangkan kalau data ada **100 nilai siswa** — pasti capek, kan?

Dengan **array**, cukup satu variabel saja:

```python
nilai = [80, 75, 90, 85]
```

Sekarang, semua nilai tersimpan dalam satu nama, hanya dibedakan lewat **nomor indeks**:

* `nilai[0]` → 80
* `nilai[1]` → 75
* `nilai[2]` → 90
* `nilai[3]` → 85

---

## 📘 Array 1 Dimensi (Satu Dimensi)

Array **1 dimensi** adalah **barisan data** yang disusun dalam **satu garis lurus**.

🧠 Ibaratnya seperti **rak buku panjang**:

```
[ 80 ][ 75 ][ 90 ][ 85 ]
   0     1     2     3
```

Nomor di bawahnya disebut **indeks** — dimulai dari 0 (kebanyakan bahasa pemrograman seperti Python, C, Java, dsb.).

### Contoh program sederhana (Python):

```python
# Membuat array
nilai = [80, 75, 90, 85]

# Menampilkan isi array
print(nilai[0])  # menampilkan 80
print(nilai[2])  # menampilkan 90

# Mengubah isi array
nilai[1] = 95
print(nilai)  # hasil: [80, 95, 90, 85]
```

---

# **Minggu 10 - Array Multi Dimensi**

## 🧮 Array 2 Dimensi (Dua Dimensi)

Kalau **array 1 dimensi** seperti **baris lurus**,
maka **array 2 dimensi** seperti **tabel** atau **kotak matriks** (ada baris dan kolom).

Bayangkan kamu punya nilai siswa dalam bentuk tabel:

| Nama Siswa | Nilai 1 | Nilai 2 | Nilai 3 |
| ---------- | ------- | ------- | ------- |
| Andi       | 80      | 75      | 90      |
| Budi       | 85      | 70      | 95      |

Itu bisa disimpan dalam **array 2 dimensi** seperti ini:

```python
nilai = [
  [80, 75, 90],  # baris 0 → Andi
  [85, 70, 95]   # baris 1 → Budi
]
```

Cara membacanya:

* `nilai[0][0]` → 80 (baris 0, kolom 0)
* `nilai[1][2]` → 95 (baris 1, kolom 2)

### Contoh program sederhana (Python):

```python
nilai = [
    [80, 75, 90],
    [85, 70, 95]
]

print(nilai[0][2])  # menampilkan 90
print(nilai[1][1])  # menampilkan 70
```

---

## 🧠 Perbedaan Singkat

| Jenis Array | Bentuk Data           | Cara Pikir           | Contoh              |
| ----------- | --------------------- | -------------------- | ------------------- |
| 1 Dimensi   | Satu baris data       | Seperti rak panjang  | `[1, 2, 3, 4]`      |
| 2 Dimensi   | Tabel (baris × kolom) | Seperti lembar Excel | `[[1,2,3],[4,5,6]]` |

---

## ⚙️ Kelebihan Menggunakan Array

✅ Data mudah diatur dan dikelompokkan.
✅ Akses data cepat (tinggal sebut indeksnya).
✅ Menghemat kode program.

---

## ⚠️ Hal yang Perlu Diperhatikan

1. Indeks dimulai dari **0**, bukan dari 1.
2. Jika salah menulis indeks (misalnya memanggil indeks yang tidak ada), akan muncul **error**.
3. Semua data di array biasanya bertipe **sama** (misalnya semua angka, atau semua teks).

---

## 🏁 Kesimpulan

* **Array 1D** → menyimpan data dalam **satu baris**.
* **Array 2D** → menyimpan data dalam **baris dan kolom**.
* **Array membantu** kita mengelola banyak data dengan **lebih rapi, cepat, dan efisien.**

---

## ✍️ Latihan Sederhana

### Latihan 1

Buat program yang menyimpan 5 nama temanmu dalam array, lalu tampilkan semuanya.

Contoh hasil:

```
Nama teman saya:
1. Andi
2. Budi
3. Cici
4. Dedi
5. Evi
```

### Latihan 2

Buat array 2D berisi nilai 3 siswa (masing-masing punya 3 nilai), lalu tampilkan semua nilainya.

---
