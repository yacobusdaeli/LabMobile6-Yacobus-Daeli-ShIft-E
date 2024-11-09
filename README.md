# Tugas 6 - Pertemuan 7

**Nama :** Yacobus Daeli

**NIM :** H1D022024

**Shift :** E


# Cara Menambahkan Komponen Pada Ionic

Berikut penjelasan secara detail untuk menambahkan Komponen pada Ionic :

## Persiapan untuk Proyek Ionic
Kita harus membuat proyek Ionic, Kita bisa memulai dengan membuat proyek baru. Jika sudah, kita bisa melewati langkah ini

```javascript
npm install -g @ionic/cli
```

## Buat Proyek baru

Untuk membuat proyek baru, bisa memakai perintah : 

```javascript
ionic start nama-proyek blank
```

## Membuat Halaman Baru

Untuk membuat halaman baru kita bisa menggunakan perintah :

```javascript
ionic generate page home
```

## Menambahkan Komponen Pada Halaman

Sesudah membuat halaman, kita bisa menambahkan komponen Ionic di dalam template HTML halaman tersebut.

1. Buka File HTML

Buka file home.page.html yang terletak di folder src/app/home/.

2. Menambahkan Komponen

Pada file HTML, kita bisa menambahkan berbagai komponen yang disediakan oleh Ionic. Berikut adalah beberapa contoh komponen yang bisa kita gunakan:
```javascript
- <ion-button (click)="doSomething()">Klik Saya</ion-button>

- <ion-label>Ini adalah Label</ion-label>

- <ion-list>
  <ion-item>
    <ion-label>Item 1</ion-label>
  </ion-item>
  <ion-item>
    <ion-label>Item 2</ion-label>
  </ion-item>
</ion-list>
```

Cara diatas kurang lebih berguna untuk menggunakan komponen yang lain.

# Screenshoot Projek 

# Page Transaksi
![Page Transaksi](https://github.com/user-attachments/assets/347e5036-f24e-41ea-af9d-202fc1db895c)

# Page Rekening
![Page Rekening](https://github.com/user-attachments/assets/6a650ee2-b03c-46f9-af02-643f51df3504)

# Page Hutang
![Page Hutang](https://github.com/user-attachments/assets/99b01c1e-1337-4df0-9134-6439a45b6a17)





