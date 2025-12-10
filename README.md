# Project-UAS-KNIME
*Data Proccesing:

<img width="607" height="342" alt="image" src="https://github.com/user-attachments/assets/7eb1f303-6d31-4198-a280-1889dac92d45" />

*Langkah-langkah : 

    1. Gunakan CSV Reader untuk membaca sample datanya

    2. Gunakan missing value note untuk mencari data yang hilang atau yang di simpulkan sebagai "?"
    
    3. Gunakan number to string bagi data yang merupakan bukan numerik (seperti : Public 1/Private 2)
    
    4. Menghapus kolom yang tidak dipakai dengan node Coulum Filter
    
    5. Gunakan node One-to-Many untuk mengubah kategori menjadi banyak kolom angka agar bisa digunakan dalam analisis atau machine learning
    
    6. Gunakan Normalizer untuk memastikan semua kolom numerik memiliki skala yang setara sehingga tidak ada variabel yang mendominasi analisis  
    
    7. Gunakan Histrogram, Scatter plot, dan bar chart sebagai output

    
--------------------------------------------------------------------------------------------------------------------------------------------------


*HISTROGRAM : Berfungsi untuk melihat distribusi nilai sebuah variabel numerik(Graduation rate)

*Gambar : <img width="1307" height="315" alt="image" src="https://github.com/user-attachments/assets/380e7bbb-f513-44a8-9ee1-4a34b65ebd46" />


Jumlah mahasiswa sangat bervariasi, sebagian besar universitas berukuran kecil-menengah.


---------------------------------------------------------------------------------------------------------------------------------------------------

*SCATTER PLOT : Melihat hubungan antara dua variabel apakah ada korelasi (Student falculty vs Graduation Rate)

*Gambar : <img width="1323" height="325" alt="image" src="https://github.com/user-attachments/assets/9daebd12-93e5-4dba-983e-0bf56b68ceac" />


Jumlah mahasiswa sangat bervariasi, sebagian besar universitas berukuran kecil-menengah.


---------------------------------------------------------------------------------------------------------------------------------------------------


*BAR CHART : Membandingkan nilai antar kategori secara langsung (Graduation Rate tiap universitas)

*Gambar : 
.<img width="1375" height="347" alt="image" src="https://github.com/user-attachments/assets/28096546-3e15-436d-bc95-d2a729fb2e9b" />


Universitas Private cenderung memiliki tingkat kelulusan lebih tinggi.


---------------------------------------------------------------------------------------------------------------------------------------------------
