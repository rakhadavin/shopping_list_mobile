Nama : Rakha Davin Bani Alamsyah
Kelas : PBP F
NPM : 2206082650

<h1>Perbedaan Stateless Widget dan Statefull Widget </h1>

- Stateless Widget
  adalah widget yang tidak akan pernah berubah. Stateless Widget merupakan widget yang di-build hanya dengan konfigurasi yang telah diinisiasi sejak awal.

      cocok untuk elemen elemen yang tidak memrlukan perubahan secara dinamis, seperti icon, teks statis, dan sebagainya

- StatefulWidget
  adalah widget ini dapat berubah rubah state-nya dan widget ini memiliki interaksi yang tidak terbatas.

  cocok untuk elemen elemen yang memrlukan perubahan secara dinamis warna, item, warna, font, ukuran, dan sebagainya.

<h1>Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing. </h1>

1. stateless widget :
   a. myApp() : sebagai widget root dari aplikasi. Saat aplikasi dijalankan (void main()), MyApp dijalankan dan menetapkan tema serta halaman utama aplikasi.

2. Statefull widget :
   a. sebagai halaman utama aplikasi. Ketika halaman ini ditampilkan, pengguna dapat melihat teks yang menghitung jumlah kali tombol ditambahkan, dimana tombol yang diguunakan berupa 3 tombol yaitu lihat item, tambah item, dan logout

MaterialApp : Mengatur theme color aplikasi dengan menggunakan colorScheme

MyHomePage : melakukan konfigurasi untuk pembuatan halaman utama aplikasi

Scaffold : Menampilkan bagian navbar pada aplikasi kita, dalam hal ini di atas daftar ShopItem

GridView.count : Mengatur jumlah kolom dan mengisi ShopItem ke dalam grid

Shopcard :Membuat card yang berisi setiap ShopItem beserta gfungsi snackbar saat terkena event.

ShopItem : class yang menyimpan objek-objek yang akan ditampilkan berupa button Lihat Item, Tambah Item, dan Logout
Text, Icon, Container, Padding, InkWell : Mengatur tampilan dan event action yang sesuai dalam setiap ShopCard

<h1S> step-step penyelesaian </h1S>
setelah membuat code seperti di tutorial saya melakukan penambahan bonus dengan memberikan warna-warna yang berbeda pada masing masing tombol
, dengan cara : menambahkan attribute dan constructure pada class ShopItem dengan data type Color den dengan nama variabel color

kemudian pada objek ShopItem ditambahkan 1 argumen lagi untuk menerapkan color seperti berikut :

ShopItem("Logout", Icons.logout, Colors.redAccent)
nama button (text) , icon, warna button
