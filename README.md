<<<<<<< HEAD
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


=======
# 🚦 Image Classification: Road Sign Detection

Welcome to my image classification project focused on detecting and classifying **traffic signs** using **Convolutional Neural Networks (CNN)** and **TensorFlow**.

---

## 📌 Introduction

Traffic signs play a crucial role in maintaining safety and order on the roads. However, real-world conditions like lighting, angle, and image quality can make these signs appear differently. This project builds an image classification model using **Computer Vision** and **CNN** to automatically recognize 17 types of traffic signs from images.

The goal is to support intelligent vehicle systems, smart city projects, or traffic education apps with fast and accurate sign recognition.

---

## 🗂 Dataset

The dataset used is titled **Road Sign Detecting**, provided by the **Projects** community via **Roboflow Universe**.

- **Total Classes**: 17 traffic sign categories  
- **License**: CC BY 4.0  
- **Source**: [Roboflow Universe – Road Sign Detecting](https://universe.roboflow.com/projects-xmgv3/road-sign-detecting-aehjf)

Examples of classes:
- `speed-20`, `speed-30`, `speed-50`, ..., `speed-100`
- `stop`, `yield`, `no-entry`
- `road-works`, `slippery-road`, `double-curve`
- and more!

---

## 🛠 Tech Stack

- Python  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  
- OpenCV  
- Roboflow API

---

## 🔄 Workflow

1. **Data Preparation**  
   Downloading and organizing the dataset using Roboflow.

2. **Data Checking**  
   Visual inspection and balance checking across classes.

3. **Data Augmentation**  
   Applying image transformations to improve generalization.

4. **ImageDataGenerator**  
   Using `ImageDataGenerator` for efficient training and validation splitting.

5. **Model Development**  
   Building and training a CNN model for multi-class classification.

---

## 📦 Model Output

- ✅ Trained CNN model in:
  - `TensorFlow SavedModel`
  - `TensorFlow Lite` (for mobile/embedded)
  - `TensorFlow.js` (for web deployment)

---

## 🚀 Future Improvements

- Improve accuracy with deeper architectures (e.g., ResNet, MobileNet)
- Add bounding box detection for real-time sign localization
- Integrate into a mobile or web demo


> "Explore data, learn by doing, and keep improving — one model at a time." 🌱
>>>>>>> dafc771045183bba2ecb073829e233a3fa05053f
