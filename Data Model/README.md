## Data Modeling

Apa itu Data Modeling

- Memindahkan sebuah table dari relational ke documnet bukanlah hal yang sederhana, tidak seperti saat kita memindahkan table di relational database
- Sebuah document database tidak akan bermanfaat saat kita tidk bisa cara memodelkannya
- Saat memodelkan data menggunakan relational datanase, biasanya kita mengacu ke database normalization
- Untuk pemodelaan document database, kita harus mengacu pada aplikasinya saat query, update, dan memproses data. Dan tidak data ini tidak akan terstruktur seperti relational database

### Schema Yang Felxible

- MongoDB kita bisa memasukkan data ke collection secara langsung tanpa mendefinisikan schema collection nya
- Schema untuk collection di MongoDB sangat flexible, untuk tiap document bisa berbeda
- Namun kita sangat direkomendasikan menggunakan jenis data yang sama untuk tiap collection

### Primary Key

- Document MongoDB wajib ada primary key
- Untuk field membuat primary key harus menggunakan nama `fild_id`
- Primary key tidak bisa lebih dari 1 field

### Contoh Struktur Document - Embedded

```
{
    _id: <ObjectId1>,
    username: "123xyz",
    contact: {
        phone: "123-456-7890",
        email: "xyz@example.com"
        },
    access: {
        level: 5,
        group: "dev"
    }
}
```
