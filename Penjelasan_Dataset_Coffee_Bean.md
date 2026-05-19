# 📁 Penjelasan Dataset Citra Gambar Biji Kopi

Dataset yang digunakan pada penelitian ini merupakan dataset citra gambar biji kopi yang digunakan untuk proses klasifikasi kualitas dan kondisi biji kopi berdasarkan karakteristik visualnya. Dataset terdiri dari ribuan gambar biji kopi yang telah dikelompokkan ke dalam beberapa kelas sesuai kondisi fisik biji kopi.

Dataset dibagi menjadi tiga subset utama, yaitu:
- **Train** sebanyak **2.717 gambar**
- **Validation** sebanyak **154 gambar**
- **Test** sebanyak **113 gambar**

Pembagian dataset dilakukan untuk mendukung proses pelatihan (*training*), validasi model (*validation*), dan pengujian performa model (*testing*) pada algoritma klasifikasi citra.

---

# 📊 Distribusi Kelas Dataset

| No | Kelas | Jumlah Gambar |
|----|--------|----------------|
| 1 | `berjamur` | 843 |
| 2 | `pecah` | 978 |
| 3 | `normal` | 561 |
| 4 | `quaker` | 602 |

---

# 🧾 Penjelasan Kelas Dataset

## 1. `berjamur`
Kelas **berjamur** merupakan gambar biji kopi yang mengalami pertumbuhan jamur pada permukaannya. Biji kopi pada kategori ini biasanya memiliki perubahan warna, tekstur, atau bercak tertentu yang menunjukkan adanya kontaminasi jamur.

## 2. `pecah`
Kelas **pecah** berisi gambar biji kopi yang mengalami kerusakan fisik berupa retakan atau pecahan pada bagian biji. Kerusakan ini dapat memengaruhi kualitas kopi dan proses pengolahan selanjutnya.

## 3. `normal`
Kelas **normal** merupakan biji kopi dengan kondisi fisik yang baik dan tidak mengalami kerusakan maupun cacat visual. Kategori ini digunakan sebagai acuan kualitas biji kopi yang layak.

## 4. `quaker`
Kelas **quaker** merupakan biji kopi yang mengalami kegagalan pematangan sehingga memiliki warna lebih pucat dibanding biji kopi normal. Biji quaker umumnya memengaruhi cita rasa kopi saat proses roasting.

---

# 🖼️ Karakteristik Dataset

Dataset citra biji kopi memiliki beberapa karakteristik sebagai berikut:

- Format data berupa gambar (*image dataset*)
- Dataset digunakan untuk tugas klasifikasi multi-kelas (*multi-class classification*)
- Setiap gambar merepresentasikan satu jenis kondisi biji kopi
- Data memiliki variasi bentuk, warna, tekstur, dan pencahayaan
- Dataset digunakan untuk melatih model *Deep Learning* khususnya metode *Convolutional Neural Network (CNN)*

---

# 📈 Tujuan Penggunaan Dataset

Dataset ini digunakan untuk:
- Melakukan klasifikasi kondisi biji kopi secara otomatis
- Membantu proses quality control pada industri kopi
- Mengidentifikasi cacat biji kopi berdasarkan citra digital
- Menjadi bahan eksperimen pada bidang *Computer Vision* dan *Deep Learning*

---

# ⚙️ Informasi Dataset

- **Jenis Dataset:** Dataset Citra Gambar
- **Jumlah Kelas:** 4 Kelas
- **Total Data Training:** 2.717 gambar
- **Total Data Validation:** 154 gambar
- **Total Data Testing:** 113 gambar
- **Format Data:** JPG / PNG
- **Metode Klasifikasi:** CNN (*Convolutional Neural Network*)

---

# ⚠️ Catatan

Dataset ini digunakan untuk kebutuhan penelitian dan pengembangan model klasifikasi citra biji kopi berbasis *Deep Learning*. Proses klasifikasi dilakukan berdasarkan ciri visual pada masing-masing gambar biji kopi.