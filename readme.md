# Belajar github bareng dinda

## github itu apa si?
**Github** itu kayak penyimpanan yang besar, untuk diolah dan mempermudah dalam melakukan kolaborasi sesama tim development.
Beberapa istilah yang sering digunakan di github
- Repository
- Commit
- Branch
- Pull request
- clone repostory

Hari ini kita akan belajar **Repository**

## Repository

adalah tempat penyimpanan project, di Github biasanya berisi:
  - Souce code
  - Assets
  - Dokumentasi
  - File konfigurasi
  - History perubahan project

#### Didalam  repository ada beberapa isian 
1. Readme.md
2. Files
3. Folder 
4. Source code
5. Documentation
6. Configuration files
7. Test files
8. Assets

## 1. Readme.md
Readme berisi tentang penjelasan proyek atau aplikasi yang sedang dikembangkan atau dibuaat.
Ini bisa mencakup proyek apa yg sedang dikembangkan, kinerja proyek, dan apa saja yang dipakai dalam mengembangkan proyek tersebut.

### Markdown 
Markdown adalah format penulisan yang digunakan untuk membuat catatan di README.md, seperti Word atau Google Docs, tetapi menggunakan karakter khusus.

#### karakter-karakter apa aja yang sering digunakan dalam membuat catatan di readme.md github?
Ada beberapa karater khusus yang digunakan di readme.md
1. `#`  fungsi untuk membuat judul atau Heading 
contoh:
# judul
## judul
### judul
ini menunjukkan semakin banyak pagar yang digunakan semakin kecil ukuran nya atau menjadi 
    1. Judul utama
    2. subjudul
    3. subsubjudul

2. `*`  fungsinya untuk membuat garis tebal dan garis miring.
contoh:
**tebal**
*miring*
memiliki karakter yang sama namun dengan fungsi yang berbeda

3. `_`  karakter ini juga memiliki fungsi yang sama yaitu
_dinda_
__dinda__
satu underscore disetiap sisi kalimat menghasilkan cetak miring dan dua undercore disetiap sisi menghasilkan cetak tebal.

4. `-`  hypen atau yang biasa kita sebut min/kurang, fungsinya menghasilkan daftar.
- books
- pencil
- pen

Namun hypen paling sering digunakan dalam membuat **Table Of Contents** atau daftar isi, seperti pada word yang sering digunakan.
seperti contoh ini
- table of contents
  - [1. Readme.md](#1.readme.md)

Dalam membuat table of contents ini juga perlu ditambahkan karakter-karakter lainnya seperti  `[],()`.

5. `+`  fungsinya membuat daftar
tampilannya sangat mirip dengan hypen
+ jarak
+ padang
+ kita
  
7. `1.`  fungsinya membuat daftar dengan nomer
   
9. `>`   fungsinya greater than unttuk membuat kutipan
untuk menonjolkan sebuah pernyataan atau kebutuhan khusus suatu aplikasi agar diperhatikan contoh
> pastikan kamu baca baik-baik cara penggunaanya

10. `  fungsi dari bactick ada beberapa contoh

`menampilkan kode didalam kalimat`
diatas adalah contoh mengunakan satu backtick
penggunaan tiga backtick untuk menampilkan blok kode
tiga backtick diikuti python, json, dan lainnya. untuk menampilkan blok kode dengan pewarna sintaks

```python
print("Hello GitHub")
```

12. `[]` dan ` () ` untuk menuliskan teks tautan contoh sebelumnya pada table of content
contoh lainnya
[teks yang ditampilkan](urltujuan)

kedua karater ini biasanya dipakai bersamaan.

13.`!` Tanda seru biasanya digunakan untuk menampilkan gambar gambar yg kita simpan di file lain namun masih 1 repository
contohnya
![screenhoot](imagescreenshoot)
perlu diiringi dengan karakter lain taotu karakter teks tautan dan url

14. `|` untuk membuat table didalam markdown cotohnya

| nama | umur |
|---|---|
| brian |21|
| atika | 25|

16. `~`  tilde membuat teks tercoret dengan double tilde di
contoh
~~kontak yang salah~~
fungsinya sering digunakan untuk menunjukan perubahan informasi
~~login gagal~~ login berhasil

17. `<>` kurung sudut digunakan untuk tag HTML di readme.md
fungsi lainnya juga dapat dibuat sebagai contoh
<adindaputripasaribu0@gmail.com>
<name@email.com>
dengan menggunaka kurung seperti ini,alamat email dapat menjadi tautan yang dapat di klik.
