## Collection

- Tempat untuk menyimpan document
- Maximum size 16MB/document
- Maximum level nested adalah 100 level

### Database Methods (Collection)

[Dokumentasi](https://docs.mongodb.com/manual/reference/method/js-database/)

<table>
    <tr>
        <th>Database Method For Collection</th>
        <th>Keterangan</th>
    </tr>
    <tr>
        <td>db.getCollectionNames()</td>
        <td>Mengambil semua nama collection</td>
    </tr>
    <tr>
        <td>db.createCollection(name)</td>
        <td>Membuat collection baru</td>
    </tr>
    <tr>
        <td>db.getCollection(name)</td>
        <td>Mendapatkan objecy collection</td>
    </tr>
    <tr>
        <td>db.(name)</td>
        <td>Sama dengan db.getCollection(name)</td>
    </tr>
    <tr>
        <td>db.getCollectionInfos()</td>
        <td>MEndapakan infromasi semua collection</td>
    </tr>
</table>

### Collection Methods

[Dokumentasi](https://docs.mongodb.com/manual/reference/method/js-collection/)

<table>
    <tr>
        <th>Database Method For Collection</th>
        <th>Keterangan</th>
    </tr>
    <tr>
        <td>db.(collection).find()</td>
        <td>Mengammbil semua document</td>
    </tr>
    <tr>
        <td>db.(collection).count()</td>
        <td>Mengambil jumlah document</td>
    </tr>
    <tr>
        <td>db.(collection).drop()</td>
        <td>Menghapus collection</td>
    </tr>
    <tr>
        <td>db.(collection).totalSize()</td>
        <td>Mengambil total ukuran collection</td>
    </tr>
    <tr>
        <td>db.(collection).stats()</td>
        <td>Mengambil informasi statistik collection</td>
    </tr>
</table>

### Mulai Koding

- **Buat Database Baru**

  Buka terminal mongoDB, lalu ketikkan perintah :

  ```
  use ecommerce
  ```

- **Buat Sebuah Collection**

  Ketikkan perintah di bawah secara bertahap:

  - `db.createCollection('customers');`
  - `db.createCollection('products');`
  - `db.createCollection('orders');`
