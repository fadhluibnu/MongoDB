## BSON

Singkatan dari Binary JSON, yaitu binary-encoded serialization dokumen sperti JSON. JSON menggunakan BSON karena BSON tidak hanya menggunakan tipe data text

### Tipe Data di BSON

<table>
    <tr>
        <th>Tipe Data</th>
        <th>Alias</th>
    </tr>
    <tr>
        <td>Double</td>
        <td>double</td>
    </tr>
    <tr>
        <td>String</td>
        <td>string</td>
    </tr>
    <tr>
        <td>Object</td>
        <td>object</td>
    </tr>
    <tr>
        <td>Array</td>
        <td>array</td>
    </tr>
    <tr>
        <td>Binary Data</td>
        <td>binData</td>
    </tr>
    <tr>
        <td>ObjectId</td>
        <td>objectId</td>
    </tr>
    <tr>
        <td>Boolean</td>
        <td>bool</td>
    </tr>
    <tr>
        <td>Date</td>
        <td>date</td>
    </tr>
    <tr>
        <td>Null</td>
        <td>null</td>
    </tr>
    <tr>
        <td>Regular Expression</td>
        <td>regex</td>
    </tr>
    <tr>
        <td>JavaScript</td>
        <td>javascript</td>
    </tr>
    <tr>
        <td>JavaScript With Scope</td>
        <td>javascriptWithScope</td>
    </tr>
    <tr>
        <td>32 Bit Integer</td>
        <td>int</td>
    </tr>
    <tr>
        <td>Timestamp</td>
        <td>timestamp</td>
    </tr>
    <tr>
        <td>64 Bit Integer</td>
        <td>long</td>
    </tr>
    <tr>
        <td>Decimal 128</td>
        <td>decimal</td>
    </tr>
    <tr>
        <td>Min Key</td>
        <td>minKey</td>
    </tr>
    <tr>
        <td>Max Key</td>
        <td>maxKey</td>
    </tr>
</table>

### ObjectId

apa itu ?

- Ramdom data unik, dan cepat digenerate derta terurut
- Panjang 12 byte, terdiri dari 4 byte timestamp, 5 byte random value, dan 3 byte incrementing counter
- Digunakan sebagai defaul_ida (primary key) di document jika kita tidak secara eksprilis menyebutkan \_id di document nya

### Date dan ISODate

- 64 bit integer yang merepresentasikan angka milisecond sejak Unix epoch(1 Januari 1970)
- Bisa mereprensentasikan waktu dengan karak 290 juta tahun sebulum dan setelah unix epoch
- merupakan representasi waktu pada MongoDB
- Kompatibel dengan date javascript
