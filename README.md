# Background Project
Andi adalah seorang pemilik superrnarket besar di salah satu kota di Indanesia, Andi memiliki rencana untuk melakukan perbaikan proses bisnis, yaitu Andi akan membuat sistem kasir yang self-service di supermarket miliknya. Sehingga custamer bisa langsung memasukkan itern yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli dan fitur yang lain. Sehingga customer yang tidak berada di kota tersebut bisa membeli barang dari supermarket tersebut Setelah Andi melakukan riset, ternyata Andi memiliki masalah, yaitu Andi rnembutuhkan Programmer untuk membuatkan fitur - fitur agar bisa sistem kasir self-service di supermarket itu bisa berjalan dengan lancar.

# Feature Requirements
Akhirnya Andi meminta tolong kepada teman-teman selaku programmer Python untuk membuat program yang menyelesaikan problem tersebut.

Jika ada yang berbelanja, begini journey customer dalam membantu orang yang berbelanja tersebut.

1. Customer membuat ID transaksi customer berikut:
Dengan membuat objek dari class transct_123 = Transaction()
2. Kemudian customer memasukkan nama item, jumlah item, dan harga barang
Masukkan item yang ingin dibeli.

add_item([<nama item>, <jumlah item>, <harga per item>])

3. Jika terjadi kesalahan dalam memasukkan nama item atau jumlah item atau harga item tetapi tidak ingin menghapus itemnya, Customer bisa melakukan:
a. Update nama item dengan method:

update_item_name(<nama item>, <update nama item>)

b. Update jumlah item dengan method:

update_item_qty(<nama item>, <update jumlah item>)

c. Update harga item dengan method:

update_item_price(<nama item>, <update harga item>)

4. Jika batal membeli item belanja, customer bisa melakukan:
a. menghapus salah satu item dari nama item dengan method: delet_item(<nama_item>)

Item	jumlah item	harga per item	harga total
mobil	2	100000	200000
(item yang dihapus)			
tempe	3	3000	9000
Ketika menghapus salah satu nama item, maka jumlah item dan harga per item pada baris/list tersebut akan ikut terhapus

b. Langsung menghapus semua transaksi atau reset transaksi dengan method:

reset_transaction()

5. Customer sudah selesai dengan berbelanja online nya, tetapi Customer masih ragu apakah harga barang dan nama barang yang diinput sudah benar. Bisa saja customer melakukan kesalahan dalam melakukan input, semisal sudah melakukan input harga barang tetapi lupa untuk input nama barangnya. Bisa menggunakan method:
check_order(). Dengan ketentuan:

a. Akan mengeluarkan pesan "Pemesanan Sudah Benar"

b. Akan mengeluarkan pesan "Terdapat kesalahan input data"

c. Keluarkan output berikut:

Item	jumlah item	harga per item	harga total
mobil	2	100000	200000
mie	1	5000	5000
tempe	3	3000	9000
6. Setelah melakukan pengecekan, customer bisa menghiting total belanja yang sudah dibeli menggunakan method total_price() dengan ketentuan:
Jika total belanja diatas 200.000 akan mendapat diskon 5%
Jika total belanja diatas 300.000 akan mendapat diskon 8%
Jika total belanja diatas 500.000 akan mendapat diskon 10%
Andi juga memberikan pesan kepada teman-teman kalau diberi kebebasan untuk menambahkan fitur yang lain apabila masih terdapat fitur yang belum tercover dalam sistem tersebut
