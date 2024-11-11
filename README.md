# Tugas-8---Pertemuan-9

![Screenshot (481)](https://github.com/user-attachments/assets/a6ce4b97-67a1-4ba2-92fd-176fb6520cd3)

1.Read (Mengambil Data):
Fungsi getMahasiswa() mengambil data mahasiswa dari API (tampil.php) saat komponen dimuat. Data ditampilkan di halaman menggunakan *ngFor.

![Screenshot (482)](https://github.com/user-attachments/assets/71fe46ce-78d3-4d36-9cd1-dba01d12636a)

2.Create (Menambah Data):
openModalTambah() membuka modal tambah data, dan tambahMahasiswa() mengirim data yang diisi ke API (tambah.php). Setelah berhasil, data diperbarui dengan memanggil getMahasiswa() dan modal ditutup.


![Screenshot (483)](https://github.com/user-attachments/assets/506d2347-4fc2-4de5-bca2-3f873317e59b)

3.Delete (Menghapus Data):
Tombol hapus memanggil hapusMahasiswa(), yang mengirim permintaan ke API (hapus.php). Setelah penghapusan berhasil, getMahasiswa() memuat ulang data yang tersisa.

![Screenshot (484)](https://github.com/user-attachments/assets/3cb42c25-a01d-4f7a-9851-a27ec2a92579)

4.Update (Mengedit Data):
openModalEdit() membuka modal edit, mengambil data mahasiswa dengan ambilMahasiswa() untuk diisi dalam form. Fungsi editMahasiswa() mengirim perubahan data ke API (edit.php) dan memperbarui tampilan.

![Screenshot (485)](https://github.com/user-attachments/assets/3d4ba280-abc5-4c86-9898-074678448b33)
