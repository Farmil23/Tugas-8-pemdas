Tentu, berikut adalah draf **README.md** untuk file `tugas.py` yang baru saja Anda unggah. Karena ini terlihat seperti tugas pemrograman dasar (Pemdas) mengenai struktur data Dictionary, saya membuat dokumentasinya sederhana namun informatif.

---

# Tugas 8: Pengolahan Data Panen (Dictionary)

Repositori ini berisi kode Python sederhana untuk menyelesaikan studi kasus pengolahan data hasil panen menggunakan struktur data **Dictionary** dan **Nested Dictionary**.

## 📝 Deskripsi

Script `tugas.py` mendemonstrasikan cara:

1. Mendefinisikan data kompleks menggunakan *Nested Dictionary* (Dictionary di dalam Dictionary).
2. Mengakses nilai spesifik dalam data bersarang.
3. Melakukan iterasi (*looping*) pada dictionary.
4. Menerapkan logika percabangan (`if-else`) untuk mengevaluasi kondisi data panen.

## 📂 Struktur Data

Data yang diolah disimpan dalam variabel `data_panen` dengan struktur sebagai berikut:

* **Key Utama**: ID Lokasi (contoh: `lokasi1`, `lokasi2`).
* **Value**: Dictionary yang berisi:
* `nama_lokasi`: Nama kebun (String).
* `hasil_panen`: Dictionary berisi jumlah panen untuk `padi`, `jagung`, dan `kedelai` (Integer).



## 🚀 Fitur & Output

Script ini menjawab beberapa persoalan (soal) sebagai berikut:

1. **Soal 1**: Menampilkan seluruh data mentah dari dictionary.
2. **Soal 2**: Mengakses dan menampilkan jumlah hasil panen **Jagung** dari **Lokasi 2**.
3. **Soal 3**: Mengakses dan menampilkan **Nama Lokasi** dari **Lokasi 3**.
4. **Soal 4, 5, 6**: Melakukan iterasi ke seluruh lokasi untuk:
* Menampilkan detail hasil panen (Padi, Kedelai, Jagung).
* Mengecek kondisi kebun:
* Jika `padi > 1300` ATAU `jagung > 800`, status: **"Memerlukan perhatian khusus"**.
* Selain itu, status: **"Dalam kondisi baik"**.





## 🛠 Cara Menjalankan

Pastikan Python sudah terinstal di komputer Anda.

1. **Clone atau Download** file `tugas.py`.
2. Buka terminal atau CMD.
3. Jalankan perintah berikut:
```bash
python tugas.py

```



## 📄 Contoh Output

Saat dijalankan, program akan menghasilkan output seperti di bawah ini:

```text
--- Soal 1: Tampilkan Seluruh Data ---
lokasi1: {'nama_lokasi': 'Kebun A', 'hasil_panen': {'padi': 1200, ...}}
...

--- Soal 2: Tampilkan Jumlah hasil jagung dari lokasi2 ---
hasil jagung pada lokasi 2: 900

--- Soal 3: Tampilkan nama lokasi dari lokasi3. ---
Lokasi 3: Kebun C

--- Soal 4, 5, 6 ---
Kebun A dalam kondisi baik
Kebun A -> Padi: 1200, Kedelai: 500, jagung: 800
----------------------------------------------
Kebun B memerlukan perhatian khusus
Kebun B -> Padi: 1500, Kedelai: 450, jagung: 900
...

```

---

**Dibuat oleh [Nama Anda]**
