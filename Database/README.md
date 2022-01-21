## Database

- Database di mongoDB digunakan untuk menyimpan collection.

- Satu logial aplikasi biasanya memiliki satu database

### Membuat Database

- untuk membuat suatu database di mongoDB kita tidak perlu secara exsplisit membuat database, misal kayak di MySQL itu menggunakan `create database`

- Untuk memilih database kita bisa menggunakan perintah `use<nama database>`

#### Mari Coba

- **Buka mongoDB**
- **Ketikkan Perintah**

  Ketikkan perintah pada shall yaitu :

  - `use nama_database`
    Perintah di atas akan otomatis membuat database dan memilih database

- **Menampilkan Database**

  Untuk menampilkan database yang sudah dibuat, kita bisa menggunakan perintah :

  ```
  show databases
  ```

  atau

  ```
  show dbs
  ```

  terkadang database yang baru kita buat tidak muncul ketika kita ketikkan perintah di atas, itu karena database yang barusan kita `use` belum memiliki sebuah collection di dalamnya;

### Database Methods

Untuk lebih lengkapnya bisa lihat di [documentasi resmi MongoDB](https://docs.mongodb.com/manual/reference/method/js-database/)

Beberapa method database

<table>
  <tr>
    <th>Database Methods</th>
    <th>Keterangan</th>
  </tr>
  <tr>
    <td>db.dropDatabase()</td>
    <td>Menghapus database</td>
  </tr>
  <tr>
    <tr>db.getNam()</tr>
    <tr>Mengambil nama database</tr>
  </tr>
  <tr>
    <tr>db.hostInfo()</tr>
    <tr>Mengambil informasi host tempat mongoDB</tr>
  </tr>
  <tr>
    <tr>db.version(</tr>
    <tr>Mengambil versi database</tr>
  </tr>
  <tr>
    <tr>db.stars()</tr>
    <tr>Mengambil statistik penggunaan database</tr>
  </tr>
</table>
