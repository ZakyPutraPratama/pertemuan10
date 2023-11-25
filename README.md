# praktikum5
## Latihan
![gambar](dokumentasi/latihan.png)
### Output:
![gambar](dokumentasi/l1.png)
![gambar](dokumentasi/l2.png)

## Praktikum
![gambar](dokumentasi/praktikum.png)
```python
while True:
    a = input("\n(T)ambah, (U)bah, (H)apus, (C)ari, (L)ihat, (K)eluar: ")
```
digunakan untuk Membuat kondisi perulangan dan keterangan untuk pilihan menu
```python
if a.lower() == 't':
        print("Tambah Data")
```
menginputkan 't' maka kita akan diminta untuk menginputkan data, seperti nama, nim, uts, dan uas. Data tersebut akan masuk ke dalam dictionary 'x' yang telah dibuat dengan data 'nama' sebagai keys dan sisanya sebagai values.
```python
elif a.lower() == 'u':
        print("Ubah Data")
```
menginputkan 'u' makan akan ada keterangan untuk mengubah data dan kita akan diminta untuk menginputkan nama yang ingin diubah datanya, apabila nama tidak ada maka outputnya "Nama {} tidak ditemukan". {} adalah nama atau data yang mau diubah.
```python
elif a.lower() == 'h':
        print("Hapus Data")
```
menginputkan 'h' maka akan menghapus data sesuai nama yang ingin kita hapus
```python
 elif a.lower() == 'c':
        print("Cari Data")
```
menginputkan 'c' makan akan diminta untuk memasukkan nama yang ingin dicari. Apabila nama yang dicari ada dalam dictionary maka outputnya akan menampilkan data dari nama tersebut.
```python
elif a.lower() == 'l':
        if x.items():
```
menginputkan 'l' maka akan menampilkan data yang sudah kita masukkan sebelumnya. Jika belum memasukkan data maka outputnya menjadi "TIDAK ADA DATA"
```python
 elif a. lower() == 'k':
        print("=====| Keluar |=====")
        break
```
menginputkan 'k' untuk keluar dan mengehentikan program
### Output:
#### TAMBAH DATA
![gambar](dokumentasi/t.png)
#### UBAH DATA
![gambar](dokumentasi/u.png)
#### CARI DATA
![gambar](dokumentasi/c.png)
#### HAPUS DATA DAN KELUAR
![gambar](dokumentasi/hk.png)

## flowchart
![gambar](dokumentasi/flow.png)
