# Proyek-Analisis-Data

## 1. Informasi Proyek
Nama: Sakifa Indira Putri <br>
Email: sakifaindiraputri739@gmail.com <br>
ID Dicoding: kipa_123

## 2. Tentang Dataset
Proses penyewaan sepeda sangat dipengaruhi oleh faktor lingkungan dan musim. Misalnya, kondisi cuaca, curah hujan, hari dalam seminggu, musim, dan jam dalam sehari dapat mempengaruhi perilaku penyewaan. Data utama berasal dari catatan historis selama dua tahun (2011-2012) dari sistem Capital Bikeshare di Washington D.C., yang tersedia secara publik di Capital Bikeshare System Data. Data ini telah dikumpulkan dan diolah dalam bentuk data harian dan per jam, serta diperkaya dengan informasi cuaca dan musim yang diekstrak dari Free Meteo.

## 3. Fitur-fitur Dashboard
- Menampilkan total penyewaan sepeda berdasarkan kategori (Registered, Casual, dan Total).
- Visualisasi korelasi faktor-faktor yang mempengaruhi jumlah penyewaan sepeda.
- Perbandingan penyewaan sepeda pada hari kerja vs akhir pekan.
- Pola penyewaan berdasarkan waktu (harian, mingguan, bulanan).
- Analisis penyewaan sepeda berdasarkan jam dalam sehari.
- Pengaruh suhu terhadap jumlah penyewaan sepeda.

## 4. Library yang diperlukan
- Python 3.x
    - Paket Python yang diperlukan:
      - streamlit
      - pandas
      - seaborn
      - matplotlib
- Install disini        
``` pip install streamlit pandas seaborn matplotlib ```

## 5. Cara menjalankan dashboard
- Pastikan file dashboard.py, day_fix_en.csv, dan hour_fix_en.csv berada dalam satu folder yang sama.
- Buka terminal atau command prompt dan arahkan ke folder tersebut.
- Jalankan perintah berikut:
  
```streamlit run dashboard.py```

*** Dashboard akan terbuka di browser secara otomatis.***
