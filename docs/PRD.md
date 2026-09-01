# Product Requirements Document (PRD)
# Vivora Health

**Product Name:** Vivora Health  
**Product Type:** Expert-Based Personal Health Management Platform  
**Tagline:** *Guiding Every Step to Better Health.*  
**Status:** Draft v0.1

---

## 1. Product Overview

Vivora Health adalah platform manajemen kesehatan berbasis pengetahuan pakar yang membantu pengguna memahami kondisi kesehatan awal, memperoleh rekomendasi program olahraga dan pola makan, menjalankan program secara terstruktur, memantau perkembangan, serta mengevaluasi perubahan kondisi setelah program selesai.

Vivora Health tidak hanya berfungsi sebagai kalkulator kesehatan atau aplikasi monitoring. Platform mengintegrasikan health assessment, health analysis, expert recommendation, exercise plan, nutrition plan, daily monitoring, progress tracking, dashboard analytics, dan final reassessment dalam satu alur penggunaan.

Expert Recommendation Engine menjadi komponen utama yang menghubungkan kondisi pengguna dengan program yang direkomendasikan berdasarkan knowledge dan rule yang diperoleh atau divalidasi oleh pakar.

Vivora Health ditujukan sebagai health and lifestyle management platform dan bukan sebagai sistem diagnosis medis.

---

## 2. Problem Statement

Pengguna yang ingin memperbaiki kondisi kesehatan atau mengelola berat badan sering memiliki informasi seperti berat badan, tinggi badan, BMI, body composition, tingkat aktivitas, dan target kesehatan, tetapi belum tentu mengetahui program yang sesuai dengan kondisi tersebut.

Selain itu, proses assessment, rekomendasi program, pelaksanaan olahraga, pola makan, monitoring, dan evaluasi sering dilakukan secara terpisah sehingga pengguna sulit melihat hubungan antara kondisi awal, program yang dijalankan, konsistensi, dan perkembangan hasil.

Vivora Health dikembangkan untuk mengintegrasikan proses tersebut dalam satu platform dengan rekomendasi yang mempunyai dasar pengetahuan pakar serta dapat dijelaskan kepada pengguna.

---

## 3. Product Vision

Membangun platform manajemen kesehatan yang mendampingi pengguna dari tahap memahami kondisi awal hingga mengevaluasi perkembangan setelah menjalankan program, dengan rekomendasi yang berbasis pengetahuan pakar, dapat dijelaskan, dan didukung oleh monitoring serta visualisasi data.

---

## 4. Product Goals

Vivora Health memiliki tujuan untuk:

1. Membantu pengguna memahami kondisi kesehatan awal melalui Initial Health Assessment.
2. Membentuk Health Profile berdasarkan hasil assessment dan analisis kesehatan.
3. Memberikan rekomendasi program olahraga dan pola makan berdasarkan pengetahuan pakar.
4. Memberikan penjelasan mengenai dasar rekomendasi yang diberikan.
5. Membantu pengguna menjalankan program secara terstruktur.
6. Memantau konsistensi pengguna melalui Daily Check-in.
7. Memantau perkembangan berat badan dan indikator relevan secara berkala.
8. Menampilkan perkembangan melalui dashboard dan visualisasi data.
9. Melakukan Final Reassessment setelah program selesai.
10. Membandingkan kondisi sebelum dan sesudah program melalui Before–After Evaluation.

---

## 5. Target Users

### 5.1 User

Individu yang ingin mengelola berat badan dan menjalani pola hidup lebih sehat melalui program olahraga dan pola makan yang terstruktur.

Kebutuhan utama pengguna meliputi:

- memahami kondisi kesehatan awal;
- memperoleh rekomendasi program;
- mengetahui alasan program direkomendasikan;
- mengetahui aktivitas yang perlu dilakukan;
- memantau konsistensi;
- melihat perkembangan;
- dan mengevaluasi perubahan setelah program selesai.

### 5.2 Expert

Pakar pada bidang yang relevan dengan olahraga, kesehatan, atau nutrisi yang berperan dalam proses knowledge acquisition dan validasi knowledge yang digunakan oleh sistem.

Detail hak akses Expert akan ditentukan pada tahap requirements.

### 5.3 Administrator

Pihak yang bertanggung jawab terhadap pengelolaan operasional sistem.

Detail kewenangan Administrator akan ditentukan pada tahap requirements.

---

## 6. User Journey

Alur utama pengguna Vivora Health adalah:

Initial Health Assessment  
↓  
Health Analysis  
↓  
Health Profile  
↓  
Expert Recommendation  
↓  
Personalized Program  
↓  
Exercise Plan & Nutrition Plan  
↓  
Daily Check-in  
↓  
Weekly Progress  
↓  
Progress Dashboard  
↓  
Final Reassessment  
↓  
Before–After Evaluation  
↓  
Final Health Report

---

## 7. Product Scope

### 7.1 In Scope — MVP

Fitur utama yang termasuk dalam MVP:

1. Authentication
2. Initial Health Assessment
3. Health Analysis
4. Health Profile
5. Expert Recommendation
6. Exercise Plan
7. Nutrition Plan
8. Daily Check-in
9. Weekly Progress
10. Progress Dashboard
11. Final Reassessment
12. Before–After Report

### 7.2 Future Scope

Fitur yang dapat dikembangkan setelah MVP antara lain:

- Expert Knowledge Base Management
- Admin/Expert Dashboard
- Program Management
- Advanced Analytics
- Automated Insight
- Detailed Recommendation Explanation
- Notification dan Reminder

### 7.3 Out of Scope

Pada tahap pengembangan saat ini, Vivora Health tidak ditujukan untuk:

- melakukan diagnosis penyakit;
- menggantikan tenaga medis;
- menentukan terapi medis;
- menjamin hasil atau jumlah penurunan berat badan tertentu;
- memprediksi outcome kesehatan secara pasti.

---

## 8. Core Features

### Initial Health Assessment
Mengumpulkan kondisi awal pengguna sebelum menjalankan program.

### Health Analysis
Mengolah data assessment menjadi informasi kesehatan yang relevan.

### Health Profile
Menampilkan ringkasan kondisi pengguna sebagai dasar proses rekomendasi.

### Expert Recommendation Engine
Menggunakan knowledge-based/rule-based approach untuk menentukan program yang sesuai berdasarkan kondisi pengguna.

Pendekatan inference yang direncanakan adalah Forward Chaining. Detail rule belum ditentukan dan harus berasal dari atau divalidasi oleh pakar.

### Exercise Plan
Menampilkan program latihan yang sesuai dengan hasil rekomendasi.

### Nutrition Plan
Menampilkan rekomendasi pola makan sesuai dengan program pengguna.

### Daily Check-in
Mencatat kepatuhan dan kebiasaan harian seperti pelaksanaan latihan, pola makan, konsumsi air, tidur, dan catatan pengguna.

### Weekly Progress
Mencatat perkembangan secara berkala, terutama perubahan berat badan.

### Progress Dashboard
Menampilkan kondisi kesehatan, konsistensi program, perkembangan, dan pencapaian target melalui visualisasi data.

### Final Reassessment
Melakukan pengukuran kembali setelah pengguna menyelesaikan program.

### Before–After Evaluation
Membandingkan kondisi pada Initial Assessment dengan Final Reassessment.

---

## 9. Product Principles

### Expert-Based

Rekomendasi harus mempunyai dasar yang dapat ditelusuri kepada knowledge pakar, referensi ilmiah, data, atau kombinasi yang telah terdokumentasi.

### Explainable Recommendation

Sistem tidak hanya memberikan nama program, tetapi juga memberikan penjelasan sederhana mengenai faktor yang menjadi dasar rekomendasi.

### Recommendation, Not Prediction

Vivora Health berfokus pada pemilihan program yang sesuai dengan kondisi pengguna dan tidak memberikan kepastian mengenai outcome yang akan diperoleh.

### Monitoring, Not Diagnosis

Daily monitoring digunakan untuk membantu pengguna menjalankan dan mengevaluasi program, bukan untuk melakukan diagnosis medis.

### Evidence Before Rules

Rule, scoring, threshold, dan bobot tidak boleh dibuat secara arbitrer tanpa dasar yang dapat dipertanggungjawabkan.

---

## 10. Monitoring & Reassessment Concept

Monitoring dibagi menjadi tiga tingkat.

### Daily Monitoring

Digunakan untuk memantau kebiasaan dan kepatuhan pengguna, seperti:

- workout completion;
- workout duration;
- diet compliance;
- konsumsi air;
- durasi tidur;
- catatan.

### Periodic Progress

Digunakan untuk melihat perkembangan berkala, terutama:

- berat badan;
- BMI yang dihitung dari berat badan terbaru.

### Final Reassessment

Dilakukan setelah program selesai dan dapat melibatkan pengukuran kembali:

- berat badan;
- body fat;
- lingkar pinggang;
- dan parameter body composition lain apabila tersedia.

Body fat dan lingkar pinggang tidak digunakan sebagai pengukuran harian.

---

## 11. Success Criteria

Vivora Health dianggap berhasil secara produk apabila sistem mampu mendukung perjalanan pengguna secara utuh:

Assessment  
→ Analysis  
→ Recommendation  
→ Program  
→ Monitoring  
→ Progress  
→ Reassessment  
→ Evaluation

Kualitas recommendation engine nantinya dapat dievaluasi melalui validasi pakar dan metode evaluasi lain yang akan ditentukan setelah knowledge base dan dataset dianalisis.

Target numerik belum ditentukan pada tahap PRD.

---

## 12. Risks & Limitations

Beberapa risiko dan keterbatasan utama meliputi:

1. Kualitas rekomendasi bergantung pada kualitas knowledge acquisition.
2. Knowledge base awal mungkin belum mencakup seluruh variasi kondisi pengguna.
3. Dataset yang tersedia mungkin mempunyai keterbatasan jumlah, parameter, atau cakupan populasi.
4. Data yang dimasukkan pengguna dapat memiliki measurement error.
5. Konsistensi monitoring bergantung pada kepatuhan pengguna.
6. Perubahan before dan after tidak secara otomatis membuktikan hubungan kausal dengan program.
7. Formula, threshold kesehatan, rule, scoring, dan durasi program belum final dan membutuhkan dasar pakar atau referensi yang sesuai.

---

## 13. Open Decisions

Hal berikut belum ditetapkan pada tahap PRD:

- struktur final dataset;
- rule recommendation;
- penggunaan scoring;
- threshold dan standar kesehatan;
- formula BMR dan TDEE;
- detail nutrition calculation;
- durasi program;
- jadwal reassessment;
- detail role dan access control;
- technology stack;
- metode validasi recommendation engine.

Keputusan tersebut akan ditentukan pada tahap data analysis, knowledge acquisition, SR/SRS, dan system design.

---

## 14. Next Stage

Setelah PRD stabil, pengembangan dilanjutkan dengan:

1. System Request (SR)
2. Dataset Inspection
3. Knowledge Acquisition
4. Software Requirements Specification (SRS)
5. Knowledge Base / Rule Base
6. System Design
7. Development
8. Testing