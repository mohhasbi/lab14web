# lab14web

# Nama : Moh. Hasbi Hasbiyah
# NIM : 311910711
# Kelas : TI 19 B2

1. buka Kembali Controller Artikel, kemudian modifikasi kode pada method admin_index :
![1](https://user-images.githubusercontent.com/81578584/124492288-72986400-ddde-11eb-87ca-d5bd446a8bec.png)

2. Kemudian buka file views/artikel/admin_index.php dan tambahkan kode berikut dibawah deklarasi tabel data :
![2](https://user-images.githubusercontent.com/81578584/124492412-9cea2180-ddde-11eb-9107-ef7636a1fd09.png)

3. Selanjutnya buka kembali menu daftar artikel, tambahkan data lagi untuk melihat hasilnya.#data dibatasi 4 record per halaman :
![3](https://user-images.githubusercontent.com/81578584/124492483-b8edc300-ddde-11eb-9caf-48a832642b8e.png)

4. Untuk membuat pencarian data, buka kembali Controller Artikel, pada method admin_index ubah kodenya :
![4](https://user-images.githubusercontent.com/81578584/124492542-d02cb080-ddde-11eb-9cf5-798174f60b51.png)

5.Kemudian buka kembali file views/artikel/admin_index.php dan tambahkan form pencarian sebelum deklarasi tabel
![5](https://user-images.githubusercontent.com/81578584/124492642-f05c6f80-ddde-11eb-9242-59717016e490.png)

6. Dan pada link pager ubah seperti berikut :
![6](https://user-images.githubusercontent.com/81578584/124492701-066a3000-dddf-11eb-87a5-f28a7ce6d139.png)

7. Selanjutnya ujicoba dengan membuka kembali halaman admin artikel, masukkan kata kunci tertentu pada form pencarian:
![7](https://user-images.githubusercontent.com/81578584/124492800-226dd180-dddf-11eb-82f3-00062cde83d6.png)

uji coba search
![8](https://user-images.githubusercontent.com/81578584/124492867-3580a180-dddf-11eb-8123-5d80f93b5bce.png)

8. Menambahkan fungsi unggah gambar pada tambah artikel. Buka kembali Controller Artikel, sesuaikan kode pada method add seperti berikut :
![9](https://user-images.githubusercontent.com/81578584/124492960-4cbf8f00-dddf-11eb-9f33-766ca0411d4b.png)

9. Kemudian pada file views/artikel/form_add.php tambahkan field input file seperti berikut.
Dan sesuaikan tag form dengan menambahkan ecrypt type seperti berikut :
![10](https://user-images.githubusercontent.com/81578584/124493047-619c2280-dddf-11eb-9777-473e4cbfe71d.png)

10. Ujicoba file upload dengan mengakses menu tambah artikel :
![11](https://user-images.githubusercontent.com/81578584/124493151-81334b00-dddf-11eb-894f-27fa34dd35fe.png)

mencoba menambahkan foto pada artikel :
![Untitled-1](https://user-images.githubusercontent.com/81578584/124494099-9f4d7b00-dde0-11eb-975f-7d60f0b3789f.jpg)

tampilan di setelah uplod dengan foto artikel :
![13](https://user-images.githubusercontent.com/81578584/124494282-d7ed5480-dde0-11eb-8318-e80439ee7cb0.png)







