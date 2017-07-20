
# php-datatables-bootstrap

Nama project : Envylook.

Ini merupakan Contoh Web Sederhana dengan studi kasus Manajemen Produksi Baju untuk Penjahit. 
terdapat beberapa Modul Crud seperti : 
- Bahan 
- Produk
- Produksi
- Pekerja
- Laporan (export : excel, csv, pdf)

Beneran Sederhana kombinasi PHP v5.6.12 Native, Bootstrap v3.3.7, DataTables 1.10.12
 - Simple Login
 - Admin Dashboard
 - Datepicker 
 - HTML Export

+ Rubah sesuai dengan settingan kamu punya server

// Config.php 

$servername = "localhost";  // alamat server
$username = "root";			// username database
$password = "";				// password database
$dbname = "sehari";		// nama database
$direktori = "seminggu";  // direktori web di localhost

Databasenya : 

`login` (
  `id` int(11) NOT NULL,
  `username` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL
)

`bahan` (
  `kode_bahan` varchar(20) NOT NULL,
  `nama_bahan` varchar(30) NOT NULL,
  `jenis_bahan` varchar(30) NOT NULL
)

`pekerja` (
  `kode_pekerja` varchar(20) NOT NULL,
  `nama_tim` varchar(20) NOT NULL,
  `jumlah_pekerja` varchar(20) NOT NULL
)

`produk` (
  `kode_produk` varchar(20) NOT NULL,
  `nama_produk` varchar(30) NOT NULL,
  `unit` varchar(20) NOT NULL,
  `kode_bahan` varchar(25) NOT NULL
)

`produksi` (
  `kode_produksi` varchar(20) NOT NULL,
  `tanggal` date NOT NULL,
  `kode_produk` varchar(100) NOT NULL,
  `kode_pekerja` varchar(100) NOT NULL,
  `jumlah` varchar(20) NOT NULL,
  `harga` varchar(25) NOT NULL
)

Thanks All, license belongs to GOD
