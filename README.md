# **Proyek Image Classification: Road Sign**

- **Nama**: Talitha Agus Shakira
- **Email**: tshakira20@gmail.com
- **ID Dicoding**: talitha_as

<br>

---

## 📌 **Introduction**

Rambu lalu lintas memainkan peran penting dalam menjaga keselamatan dan keteraturan lalu lintas. Dalam kondisi dunia nyata, rambu-rambu ini bisa tampak berbeda-beda tergantung sudut pandang, pencahayaan, atau kualitas kamera, sehingga sistem otomatisasi berbasis pengenalan citra dibutuhkan untuk meningkatkan akurasi deteksi.

Dalam proyek ini, saya membangun model klasifikasi citra berbasis **Computer Vision** dan **Convolutional Neural Network (CNN)** untuk mengenali berbagai jenis **rambu lalu lintas** dari gambar. Model ini dilatih untuk mengklasifikasikan gambar ke dalam 17 kelas berbeda rambu lalu lintas, antara lain:

* **speed-20** – Batas kecepatan 20 km/jam
* **speed-30** – Batas kecepatan 30 km/jam
* **speed-50** – Batas kecepatan 50 km/jam
* **speed-60** – Batas kecepatan 60 km/jam
* **speed-70** – Batas kecepatan 70 km/jam
* **speed-100** – Batas kecepatan 100 km/jam
* **road-works** – Pekerjaan jalan
* **one-way-traffic** – Lalu lintas satu arah
* **yield** – Beri jalan
* **stop** – Berhenti
* **road-narrows** – Jalan menyempit
* **no-entry** – Dilarang masuk
* **uneven-road** – Jalan tidak rata
* **overtaking-forbidden** – Dilarang menyalip
* **double-curve** – Tikungan ganda
* **slippery-road** – Jalan licin

Model ini bertujuan untuk membantu sistem kendaraan cerdas, proyek smart city, atau aplikasi edukasi lalu lintas dengan memberikan klasifikasi rambu secara otomatis dan efisien.

Proyek ini mencakup tahapan preprocessing gambar, augmentasi data, pelatihan model CNN, evaluasi performa, dan penyimpanan model ke berbagai format siap deploy seperti **TensorFlow SavedModel**, **TensorFlow Lite** (untuk mobile/embedded), dan **TensorFlow\.js** (untuk aplikasi berbasis web).

## 📌 **Dataset**

Dataset ini berjudul **Road Sign Detecting** dan disediakan oleh komunitas **Projects** melalui platform **Roboflow Universe**. Dataset ini dirancang untuk tugas **klasifikasi gambar** guna mengenali berbagai jenis **rambu lalu lintas**.

📊 **Informasi Umum**:

* **Jumlah Kelas**: 17 kelas berbeda, yaitu:

  * **speed-20** – Batas kecepatan 20 km/jam
  * **speed-30** – Batas kecepatan 30 km/jam
  * **speed-50** – Batas kecepatan 50 km/jam
  * **speed-60** – Batas kecepatan 60 km/jam
  * **speed-70** – Batas kecepatan 70 km/jam
  * **speed-100** – Batas kecepatan 100 km/jam
  * **road-works** – Pekerjaan jalan
  * **one-way-traffic** – Lalu lintas satu arah
  * **yield** – Beri jalan
  * **stop** – Berhenti
  * **road-narrows** – Jalan menyempit
  * **no-entry** – Dilarang masuk
  * **uneven-road** – Jalan tidak rata
  * **overtaking-forbidden** – Dilarang menyalip
  * **double-curve** – Tikungan ganda
  * **slippery-road** – Jalan licin
* **Lisensi**: CC BY 4.0 (Creative Commons Attribution 4.0 International License)
* **Tanggal Rilis**: Tidak disebutkan secara eksplisit di halaman dataset
* **Sumber**: [Roboflow Universe – Road Sign Detecting](https://universe.roboflow.com/projects-xmgv3/road-sign-detecting-aehjf)


