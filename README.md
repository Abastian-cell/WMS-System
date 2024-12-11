# WMS System with CI Framework
Aplikasi pengelolaan barang berbasis web dengan framework Codeigniter 3

Ada beberapa tahap dalam menginstall aplikasi wms ini.

Extrack file wms.rar dengan menggunakan winrar atau winzip.

Install XAMPP
1. Tahap pertama pastikan ada sudah mengintall xampp dilaptop atau komputer anda
2. Copy folder wms dan paste kan di direktori C:\xampp\htdocs
3. Masuk ke phpmyadmin dengan menggunakan browser http://localhost/phpmyadmin/
4. Buat sebuah database dengan nama db_penjualan lalu import file db_penjualan.sql
5. Settingan awal selesai
6. ![image](https://github.com/user-attachments/assets/78307d1c-058d-432f-a5be-52468d49f1d4)

Struktur database
![image](https://github.com/user-attachments/assets/6b15d752-9d7c-412a-9472-a3a19e3efeea)
![image](https://github.com/user-attachments/assets/4fb9d32c-7685-4496-9ef9-d9294f55f1f0)



Penggunaan Aplikasi
1. Masukan link berikut ke browser anda http://localhost/wms/
   ![image](https://github.com/user-attachments/assets/e44ef59a-c075-492b-95f1-5f43ff07de24)

2. Login dengan menggunakan akses admin dengan username : admin dan Password : admin (Semua Fitur)
   Login dengan menggunakan akses operator dengan username : op dan Password : op (Fitur Terbatas)

3. Terdapat beberapa menu di halaman utama seperti Barang, Barang Masuk, Barang Keluar, Suplier, Kategori, Pengguna, Laporan, Grafik dan Retur
4. Dimenu Barang kita bisa melakukan penambahan barang baru, update, dan delete. untuk fitur delete hanya berlaku untuk barang yang belum pernah ditransaksikan.
   ![image](https://github.com/user-attachments/assets/3e3b4461-ba84-4452-b2c0-88acdde6c392)
   ![image](https://github.com/user-attachments/assets/e02f88ad-b9b4-48cf-934c-50e1494a007b)
5. Dimenu barang masuk kita harus menginput semua kolom yang ada agar bisa ke proses simpan data.
   ![image](https://github.com/user-attachments/assets/7166f877-4979-40b1-8d8f-3f850937bfe0)
6. Dimenu barang keluar kita harus menginput semua kolom yang ada agar bisa ke proses simpan data.
   ![image](https://github.com/user-attachments/assets/c995f124-8656-4760-888c-2f53c979d3d9)
7. Dimenu suplier kita bisa menambahkan data suplier untuk keperluan barang masuk.
   ![image](https://github.com/user-attachments/assets/5cdeffdf-f6fe-4858-9463-ac4b2660aba2)
8. Dimenu kategori kita bisa menambahkan kategori untuk keperluan tambah data barang.
   ![image](https://github.com/user-attachments/assets/1a26d016-b7c7-4153-b10f-d5279a8cd52f)
9. Dimenu pengguna kita bisa menambah atau menonaktifkan pengguna.
   ![image](https://github.com/user-attachments/assets/2704d7d6-e148-464d-8be9-0691269ac7b2)
10. Dimenu laporan kita bisa melihat laporan barang masuk dan keluar berdasarkan periode yang diinginkan juga dapat melihat stok on hand barang.
    ![image](https://github.com/user-attachments/assets/2d6b797b-bad1-4c6d-8563-5bb51368289f)
11. Dimenu grafik kita bisa melihat grafik barang keluar berdasarkan periode yang diinginkan.
    ![image](https://github.com/user-attachments/assets/b5afae03-c57a-4f7c-b3a7-50332f4fc5f2)
12. Terakhir dimenu retur kita bisa melakuka retur barang.
    ![image](https://github.com/user-attachments/assets/cff2ecb1-e246-4d73-94dd-b0df10171b28)











