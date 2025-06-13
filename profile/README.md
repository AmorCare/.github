# AmorCare App
AmorCare adalah website yang dirancang dengan analisis berbasis Machine Learning untuk membantu pengguna memahami jenis kulit mereka, menemukan produk skincare yang sesuai, dan membentuk rutinitas perawatan kulit yang sehat. AmorCare berkomitmen untuk menjadikan perawatan kulit lebih mudah diakses, khususnya bagi masyarakat Indonesia yang mencari solusi lokal dan alami untuk kulit yang lebih sehat dan percaya diri.

##  Fitur Utama
-  **Klasifikasi Jenis Kulit Otomatis**  
  Deteksi jenis kulit (berminyak, jerawat, normal) melalui input gambar wajah.

-  **Model Deep Learning (Transfer Learning)**  
  Menggunakan MobileNetV2 yang ditingkatkan dengan fine-tuning untuk akurasi optimal.

-  **Aplikasi Web Responsif**  
  Antarmuka web interaktif dan ringan, dapat diakses melalui berbagai perangkat. [AmorCare](https://amorcare.netlify.app/)

-  **Evaluasi Model Transparan**  
  Disertai metrik evaluasi seperti akurasi, precision, recall, f1-score, dan confusion matrix.

## Tech Stack  
| Tool/Library        | Fungsi                            |
|---------------------|-----------------------------------|
| TensorFlow / Keras  | Training model klasifikasi citra  |
| MobileNetV2         | Base model (transfer learning)    |
| NumPy, Matplotlib   | Visualisasi dan pengolahan data   |
| Scikit-learn        | Evaluasi performa model           |
| Flask   | Web deployment         |
| Figma               | UI/UX design                      |

## Model Performance  
- **Akurasi Validasi**: 92%  
- **Jumlah data**: 3354 gambar  
- **Split data**: 80% train, 10% validation, 10% test  
- **Hasil evaluasi:**  
  - *Precision (avg)*: 0.92  
  - *Recall (avg)*: 0.92  
  - *F1-score (avg)*: 0.92  
  - Total kesalahan klasifikasi: 28 dari 336 data uji

# Team Member
Team ID : LAI25-SM007

|              Nama              |   ID   |     Path      |           Role            |              University               |
|:-----------------------------:|:--------------:|:-------------:|:-------------------------:|:-------------------------------------:|
| [Paskalis Dwiputra Palayukan](https://github.com/pascal906)       | A206YAF390    | AI Engineer   | Project Lead & Data Research         | Universitas Halu Oleo                |
| [Muhammad Fariduddin Athar](https://github.com/Athar04-Stela)     | A299YBM077    | AI Engineer   | ML & Web Integration                 | Universitas Pendidikan Indonesia     |
| [Fadhilah Nurrahmayanti](https://github.com/codedreamerD)         | A117XBM150    | AI Engineer   | Web Design & Front-End               | Institut Teknologi Nasional Bandung  |
| [Wahyuni Fajrin Rosyidah](https://github.com/wahyunirosyidah)     | A587XTM495    | AI Engineer   | Model Research & Training            | Universitas Papua                    |

# Project Documentation
- [Web Development](https://github.com/AmorCare/LAI25-SM007-AmorCare-Web)
- [Machine Learning](https://github.com/AmorCare/LAI25-SM007-AmorCare-MachineLearning)


# Set up environment

          venv/Scripts/activate
          
          python app.py
   
