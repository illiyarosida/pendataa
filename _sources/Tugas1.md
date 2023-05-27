# Tugas Penambangan Data
# Cara load data csv ke excel
- pastikan anda sudah memiliki data iris
- kemudian buka Excel 
- lalu klik data 
- kemudian di bagian data klik getdata  dan pilih file /text csv
- cari file yang mau di up lalu klik load

# cara load data file csv ke power BI
- pastikan sudah terinstal power BI dan buka aplikasi power BI
- klik dapatkan data
- lalu klik lainnya dibagian paling bawah
- setelah itu klik text/CSV  dan sambungkan
- pilih file yang di up dan muat
- di bagian kiri klik iris lalu centang semua kolom untuk memunculkan diagram
- lalu simpan 

# Load data dari cloud server postgresql
- pastikan sudah terinstal power BI  dan postgresql
- buat akun terlebih dahulu di elephant https://api.elephantsql.com/
- dengan cara klik tombol login kemudian  create new instance dan isi semua  form sampai selesai hingga  muncul akun elephant yang sudah di buat.
- buka postgresql dan koneksikan dengan akun elephant yang sudah di buat  tadi dengan membuat server baru  di postgresql dan sesuaikan server, hostname,username,password dengan akun elephant  yang sudah dibuat tadi . lalu pastikan sudah terdapat file csv didatabase nya,bisa menggunakan query tool
- buka power BI kemudian pilih dapatkan data cari database postgresql masukkan server ,database ,username,pasword sesuai dengan akun elephant
- setelah itu pilih data csv yang ingin di load ,kemudian klik muat
- di bagian kiri klik iris lalu centang semua kolom untuk memunculkan diagram
- lalu simpan
   
# Cara load data dari postgresql local
 -pastikan sudah terinstal power BI  dan postgresql
 -pastikan sudah memiliki data csv pada database di postgresql
 -buka power BI kemudian pilih dapatkan data cari database postgresql masukkan server ,database ,username,pasword sesuai dengan database di postgresql anda
  -setelah itu pilih data csv yang ingin di load ,kemudian klik muat
 -di bagian kiri klik iris lalu centang semua kolom untuk memunculkan diagram
  -lalu simpan

# Cara load data  dari mysql database ke power BI 
- pastikan mySQL sudah berjalan di komputer anda
- Pastikan sudah ada data iris.csv di dalam database di mySQL bisa dengan cara import file atau bisa dengan melakukan kueri
- Buka power BI pilih menu home kemudian klik Get Data
- Pilih database kemudian klik MySQL Database ke mudian klik connect
- Masukkan server ,database,username,pasword sesuai dengan database MySQL anda kemudian klik ok
- Pilih data yang ada dalam database MySQL yang ingin di load, klik centang kemudian klik load
- Klik data yang udah di load tadi kemudian centang semua kolom yang ingin di tampilkan
- Jangan lupa save data yang udah di load tadi
