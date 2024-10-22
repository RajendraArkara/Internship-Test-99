# INTERNSHIP TEST

Repository ini berisi solusi untuk tes teknis Internship Data Engineering di 99 Group.

## Deskripsi

Pada project ini, saya mengembangkan sistem pipeline ELT (Extract, Load, Transform) dengan melakukan eksekusi urutan SQL file yang benar berdasarkan dependensinya. Sistem ini dirancang untuk membersihkan, mentransformasi, dan menggabungkan data dari beberapa tabel source ke dalam table final di data warehouse.

## Langkah-Langkah:

Persiapan SQL File: Semua file SQL diurutkan berdasarkan dependency masing-masing. File SQL di folder source dan tmp akan dieksekusi terlebih dahulu sebelum file di folder final.

Eksekusi SQL: Simulasi dilakukan menggunakan fungsi time.sleep(2) untuk mengimitasi waktu eksekusi file SQL.

Penanganan Dependency: Program memastikan setiap file SQL dieksekusi sesuai dengan dependency-nya.

## Cara menjalankan code:
Buka link google collab ini, google collab: https://colab.research.google.com/drive/1_vvuj4j_mG-1l14POxPMh6OW96Zm_GGY?usp=sharing

## Depedensi:
Tidak ada dependensi eksternal selain Python

## File SQL:
File SQL yang digunakan terdapat di dalam folder sql.
