# Digital-Signal-Project


## Penjelasan Filter Voice

### Tujuan
Filter suara bertujuan untuk memproses sinyal audio menggunakan metode digital filtering. Ini berguna untuk mengurangi noise, mengekstrak fitur tertentu, atau meningkatkan kualitas sinyal.

### Implementasi Filter
Filter diterapkan dengan konvolusi antara sinyal input dan kernel filter. Beberapa filter yang digunakan antara lain:

- **Low-Pass Filter**: Menghilangkan frekuensi tinggi, mempertahankan nada rendah.
- **High-Pass Filter**: Menghilangkan frekuensi rendah, mempertahankan komponen tinggi.
- **Band-Pass Filter**: Mempertahankan frekuensi dalam rentang tertentu.
- **Band-Stop Filter**: Menghilangkan frekuensi tertentu yang mengganggu (misalnya noise).

### Analisis
- Visualisasi gelombang suara digunakan untuk membandingkan sinyal sebelum dan sesudah filtering.
- Hasil menunjukkan perbedaan spektrum frekuensi tergantung filter yang digunakan.
- Dengan filter yang tepat, suara dapat dibuat lebih bersih atau fokus pada komponen tertentu (misalnya frekuensi bicara manusia).

### Kesimpulan
Filter digital sangat berguna dalam pengolahan sinyal suara, baik untuk keperluan komunikasi, analisis, maupun sistem pengenalan suara.

> Lihat file `filter-sound.ipynb` di repo ini untuk detail implementasi dan visualisasi grafiknya.
