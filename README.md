# Program Daftar Nilai Mahasiswa Menggunakan Dictionary
Perintah program menggunakan python dengan tampilan perintah sebagai berikut :

![Screenshot 2024-11-29 130007](https://github.com/user-attachments/assets/6d7d5cf5-6c61-463d-9693-eabe2761e232)

![Screenshot 2024-11-29 130022](https://github.com/user-attachments/assets/8360f633-f99b-4415-9440-21ce81e1a183)


## Fungsi Utama

### `Hitung_nilai_akhir(nilai_tugas, nilai_uts, nilai_uas)`
- **Deskripsi**: Menghitung nilai akhir mahasiswa berdasarkan komponen nilai.
- **Parameter**:
  - `nilai_tugas`: Nilai tugas mahasiswa.
  - `nilai_uts`: Nilai UTS mahasiswa.
  - `nilai_uas`: Nilai UAS mahasiswa.
- **Rumus**:

  ![Screenshot 2024-11-29 132959](https://github.com/user-attachments/assets/bdcb55a2-2ebe-46e0-95dd-3514d852b550)

- **Return**: Mengembalikan nilai akhir yang telah dihitung.

## Struktur Data

### Dictionary `data_mahasiswa`
- **Kunci**: NIM mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.
  - `nilai_akhir`: Nilai akhir yang dihitung.

## Daftar Menu

Pengguna diberikan pilihan untuk melakukan operasi berikut:

1. **L. Lihat Data**
   - Menampilkan seluruh data mahasiswa dalam format tabel.

2. **T. Tambah Data**
   - Meminta input dari pengguna untuk menambahkan data mahasiswa baru, termasuk nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Data yang dimasukkan akan dihitung nilai akhirnya dan disimpan.

3. **U. Ubah Data**
   - Meminta NIM mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memperbarui nilai tugas, UTS, dan UAS. Nilai akhir akan diperbarui sesuai dengan perubahan.

4. **H. Hapus Data**
   - Meminta NIM mahasiswa yang ingin dihapus. Jika data ditemukan, maka data mahasiswa tersebut akan dihapus dari daftar.

5. **C. Cari Data**
   - Meminta NIM mahasiswa yang ingin dicari. Jika data ditemukan, program akan menampilkan informasi mahasiswa tersebut.

6. **K. Keluar**
   - Mengakhiri program.

## Tampilan Program


![Screenshot 2024-11-29 125834](https://github.com/user-attachments/assets/75460748-9941-47e7-b5ec-9919c8a2b4ff)

![Screenshot 2024-11-29 125853](https://github.com/user-attachments/assets/a24484eb-d51e-4b67-bd1e-40809ea24a1c)

Berikut adalah contoh interaksi pengguna dengan program:
1. Start: Titik awal program.
2. Inisialisasi Dictionary data_mahasiswa: Membuat dictionary kosong untuk menyimpan data mahasiswa.
3. Tampilkan Menu: Menampilkan pilihan menu kepada pengguna (Lihat, Tambah, Ubah, Hapus, Cari, Keluar).
4. Input Pilihan Menu: Pengguna memasukkan pilihan menu.
5. Pilihan Menu:
Jika pengguna memilih T (Tambah):
Input data mahasiswa (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
Hitung nilai akhir menggunakan fungsi hitung_nilai_akhir.
Simpan data ke dalam dictionary.
Tampilkan pesan bahwa data berhasil ditambahkan.
Jika pengguna memilih U (Ubah):
Input NIM mahasiswa yang ingin diubah.
Jika NIM ditemukan, input nilai baru (Tugas, UTS, UAS).
Hitung nilai akhir baru dan perbarui data.
Tampilkan pesan bahwa data berhasil diubah.
Jika pengguna memilih H (Hapus):
Input NIM mahasiswa yang ingin dihapus.
Jika NIM ditemukan, hapus data dari dictionary.
Tampilkan pesan bahwa data berhasil dihapus.
Jika pengguna memilih L (Lihat):
Tampilkan semua data mahasiswa dalam format tabel.
Jika pengguna memilih C (Cari):
Input NIM mahasiswa yang ingin dicari.
Jika NIM ditemukan, tampilkan informasi mahasiswa.
Jika pengguna memilih K (Keluar):
6. Tampilkan pesan bahwa program selesai dan keluar dari loop.
7. End: Titik akhir program.

## FLOWCHART 

![Praktikum 7](https://github.com/user-attachments/assets/46d956bd-190c-4d97-b614-5bc7aa8e83eb)
