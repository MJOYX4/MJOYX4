**Perhatikan skema/model relasional/EER diagram dari database berikut**

![Screenshot 2024-05-20 151901](https://github.com/MJOYX4/MJOYX4/assets/160231998/0ccecbff-da60-4d07-9d5f-ec00c20b9f2b)![Screenshot 2024-05-20 152213](https://github.com/MJOYX4/MJOYX4/assets/160231998/c8fb632f-ed88-4ae5-9bab-bdf8a54000c5)


1.Pertama yaitu membuat database baru


![Screenshot 2024-05-20 145726](https://github.com/MJOYX4/MJOYX4/assets/160231998/948ef8f1-f0a9-4002-b889-1ea6dc993a7e)


2. Selanjutnya show databases lalu use database yang dibuat


![Screenshot 2024-05-20 145926](https://github.com/MJOYX4/MJOYX4/assets/160231998/60760bac-2f89-4589-b783-192a37ea3c38)


3. Membuat table dosen


![Screenshot 2024-05-20 150050](https://github.com/MJOYX4/MJOYX4/assets/160231998/698f22e9-1be0-4be2-9011-52f6311acf03)


4. Membuat table hari


![Screenshot 2024-05-20 150115](https://github.com/MJOYX4/MJOYX4/assets/160231998/7a318367-d4a6-4d95-99ea-ef70a872fb83)


5. Membuat table jadwal


![Screenshot 2024-05-20 150207](https://github.com/MJOYX4/MJOYX4/assets/160231998/e8f4cfe0-5594-43eb-9856-681546e86308)


6. Membuat table jp


![Screenshot 2024-05-20 150406](https://github.com/MJOYX4/MJOYX4/assets/160231998/1d7c2670-e9ef-44ba-89fb-6537dc6ab0a5)


7. Membuat table kelas


![Screenshot 2024-05-20 150434](https://github.com/MJOYX4/MJOYX4/assets/160231998/0a35ef49-d8ad-4700-acfc-7f2dcbb3d6f3)


8. Membuat table mk


![Screenshot 2024-05-20 150554](https://github.com/MJOYX4/MJOYX4/assets/160231998/0a2599e5-b208-42e9-a0ec-4ecfc8ca634b)


9. Membuat table prodi


![Screenshot 2024-05-20 150601](https://github.com/MJOYX4/MJOYX4/assets/160231998/baf40258-5a3a-4467-aede-395d96694220)


10. Membuat table ruang


![Screenshot 2024-05-20 150610](https://github.com/MJOYX4/MJOYX4/assets/160231998/37084e39-8af5-47bd-8e6b-2f98fb42237f)


11. Menambahkan kunci utama (PRIMARY KEY) pada tabel yang sudah ada, dalam tabel dosen, hari, jadwal, jp, kelas, mk, prodi, ruang.


![Screenshot 2024-05-20 150705](https://github.com/MJOYX4/MJOYX4/assets/160231998/a4062495-2a29-4a03-8442-e5930ba6d6af)


12. Mengubah definisi kolom kode_jadwal pada tabel jadwal menjadi bilangan bulat hingga 10 digit, tidak boleh bernilai NULL, dan nilai kolom ini akan otomatis bertambah setiap kali baris baru ditambahkan ke tabel.


![Screenshot 2024-05-20 151140](https://github.com/MJOYX4/MJOYX4/assets/160231998/92280f7e-86e0-42d4-bd77-fb88d1d60d1d)


13. Selanjutnya menambahkan kunci asing (FOREIGN KEY) pada kolom-kolom tersebut di tabel jadwal yang merujuk ke kolom dengan nama yang sama di tabel-tabel yang sesuai. Ini akan memastikan integritas data antara tabel jadwal dan tabel-tabel lainnya.


![Screenshot 2024-05-20 151901](https://github.com/MJOYX4/MJOYX4/assets/160231998/17e1fab9-53eb-4cf1-8b7f-bf145cc452ee)
