Trash Counter AI (Alpha Version)
Aplikasi berbasis Computer Vision yang dirancang untuk mendeteksi dan menghitung jumlah sampah plastik di area pantai dan perairan menggunakan framework YOLOv8.

Status Proyek: Under Development
Saat ini model sedang dalam tahap optimasi akurasi.

Model Terakhir: YOLOv8 Nano (best.pt).

Target: Meningkatkan akurasi deteksi pada objek sampah yang kecil dan bertumpuk (oklusi).

Fitur Utama
Deteksi Otomatis: Mengenali berbagai jenis sampah plastik dan kotoran.

Penghitung Otomatis (Counter): Menghitung total jumlah objek terdeteksi dalam satu frame.

Inference Cepat: Menggunakan model YOLOv8 yang dioptimalkan untuk performa real-time.

Persiapan \& Instalasi
Proyek ini dijalankan menggunakan Google Colab untuk memanfaatkan akselerasi GPU.

Clone Repositori:
git clone https://github.com/AhmadNaufalPrib/Beach-Trash-Counter-AI.git

Instalasi Library:
pip install ultralytics

Struktur Folder
weights/: Berisi file model terbaik (best.pt) hasil pelatihan.

notebook/: File .ipynb yang bisa langsung dijalankan di Google Colab.

data.yaml: Konfigurasi path dataset dan jumlah kelas (labels).
dataset: https://www.kaggle.com/datasets/alyyan/trash-detection

