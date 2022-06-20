# go module

### membuat module

`go mod init nama-module`

<hr />

### rilis module

golang terintegrasi dengan git.
untuk merilis module, kita hanya perlu membuat tag di Git (v1.0.0).

<hr />

### menambah dependency

`go get nama-module`

<hr />

### upgrade module

cara upgrade dengan membuat tag baru di Git

<hr />

### upgrade dependency

ubah nomor tag di go.mod lalu jalankan:
`go get`

<hr />

### major upgrade

major upgrade biasanya terjadi dikarenakan ada perubahan pada isi kode program kita, sehingga membuatnya tidak backward compatible.
sebaiknya dihindari.
namun jika tidak bisa dihindari, strategi terbaik adalah merubah nama module.

ubah nama-module <url-module>/v2 untuk melakukan major upgrade.

<hr />
