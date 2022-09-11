# Proposal pembuatan aplikasi pendataan minyak 

# Permasalahan

Dalam bisnis orang tua saya yaitu menjadi penyedia minyak dalam jumlah besar untuk dikirim ke pabrik dan juga ke konsumen lainnya. Dalam hal ini terdapat sebuah kesulitan yaitu :

 - Dalam hal mengkontrol stok barang
 - Berapa dus minyak yang masuk dalam seminggu
 - Berapa dus minyak yang keluar dalam seminggu
 - Perhitungan keuntungannya.

## Rancangan Solusi

 - Membuat aplikasi yang didalamnya ada data stok dan data keluar/masuk barang
 - Membuat perhitugan keuntungan

## Use Case

-   User bisa mengelola halaman, yang mana halaman terdiri atas stok, minyak masuk dan minyak keluar.
-   User bisa mengelola berapa dus minyak yang masuk dan keluar dalam seminggu.
-   User bisa menghitung keuntungan yang didapat.
-   User bisa melihat keuntungan mingguan.

## Struktur Data
User
|Atribut| Tipe Data |Contoh|
|--|--|--|
| Id_admin |Int |1|
|username|String|Zidan
|password|String|Afdhalul

Minyak
|Atribut| Tipe Data |Contoh|
|--|--|--|
| Id_minyak |Int |1|
|Merk_minyak|String|Fortune
|Harga_beli|Int|186
|Harga_jual|Int|200
|Stok|Int|50

Data
|Atribut| Tipe Data |Contoh|
|--|--|--|
| Id_data |Int |1|
|tanggal|date|12/09/2022
|Total_penjualan|Int|8000
|keuntungan_penjualan|Int|3000
## UX Wireframe
