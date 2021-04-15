# Selamat Datang Di Rest Api Github! <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="50px">
<img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Developer.gif" width="500px">

## Apikey? Chat Admin <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/happy.gif" width="30px">
[`Kontak Saya`](https://wa.me/62859106999930?text=Bang%20Minta%20Apikey%20AkaShiro-Api%20)
Apikeynya Gratis kok gan,, tenang aja ;D

## Contoh Kode <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Medal.gif" width="30px">

### Untuk Teks (Non-Media)
```bash
$ npm install axios
```
```js
const axios = require('axios') // Module yg dibutuhkan untuk menscrap website

axios.get('https://raw.githubusercontent.com/akashiro22/akashiro-api/main/contoh.json').then((res) => { // Scrap web
 let random = Math.floor(Math.random() * res.data.length) // Acak objek
 let data = res.data[random] // Setelah diacak arahkan ke teks respon sesuai nama diweb
   console.log(data.result) // Ta Daa
})



// Note : Link harus teks raw (https://raw.githubusercontent.com)
```
### Untuk Gambar/Video (Media)
```bash
$ npm install axios
$ npm install image-to-base64
```
```js
const imageToBase64 = require('image-to-base64') // Untuk mengubah menjadi gambar
const axios = require('axios') // Module yg dibutuhkan untuk menscrap website

axios.get('https://raw.githubusercontent.com/akashiro22/akashiro-api/main/contoh_gambar.json').then((res) => { // Scrap web
 let random = Math.floor(Math.random() * res.data.length) // Acak objek
 let data = res.data[random] // Setelah diacak arahkan ke teks respon sesuai nama diweb
  imageToBase64(data.gambar).then((result) => { // Ubah menjadi gambar
   let hasil = Buffer.from(result, 'base64') // Konversi teks base64 ke gambar/video
     console.log(hasil) // Ta Daa
   })
})

// Note : Respon akan berupa teks buffer,, gunakan alat seperti media sender agar merespon menjadi media gambar/video
```

## Dokumentasi <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/coin.gif" width="25px">

| Nomor | Nama | Deskripsi | Status | Link |
| :-: | :-----------------: | :-----------------: | :-------: | :-------: |
| 1 | Test API Teks | Pratinjau Contoh Respon API Teks | - | [`Klik Disini`](https://raw.githubusercontent.com/akashiro22/akashiro-api/main/contoh.json)|
| 2 | Test API Media | Pratinjau Contoh Respon API Media | - | [`Klik Disini`](https://raw.githubusercontent.com/akashiro22/akashiro-api/main/contoh_gambar.json)|
| 3 | Anime | Mengirimkan Gambar Anime | Aktif  | [`Klik Disini`](https://tinyurl.com/6hc795vr)|
| 4 | Asupan | Megirimkan Video Penyegar Timeline | Aktif | [`Klik Disini`](https://tinyurl.com/3bdsp8td)|
| 5 | Berita | Mengirimkan Informasi Berita Terkini | Aktif | [`Klik Disini`](https://tinyurl.com/tyhbk5n5)|
| 6 | BTS | Mengirimkan Gambar BTS | Aktif | [`Klik Disini`](https://tinyurl.com/3adv4wkf)|
| 7 | Black Pink | Mengirimkan Gambar BlackPink | Aktif | [`Klik Disini`](https://tinyurl.com/5azxpzae)|
| 8 | Bokep | Mengirimkan Gambar 18+ | Aktif | [`Klik Disini`](https://tinyurl.com/5u63s2w3)|
| 9 | Bucin | Mengirimkan Kata Bucin | Aktif | [`Klik Disini`](https://tinyurl.com/5azxpzae)|
| 10 | Cak Lontong | Mengirimkan Soal Cak Lontong | Aktif | [`Klik Disini`](https://tinyurl.com/54dbbs7w)|
| 11 | Cantik Cek | Menentukan Seberapa Cantiknya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/4kmxu7fr)|
| 12 | Cecan | Mengirimkan Gambar Cewek Cantik | Aktif | [`Klik Disini`](https://tinyurl.com/4az8vzz9)|
| 13 | Cogan | Mengirimkan Gambar Cowok Ganteng | Aktif | [`Klik Disini`](https://tinyurl.com/72z4m65s)|
| 14 | Dadu | Permainan Dadu | Aktif | [`Klik Disini`](https://tinyurl.com/akashiro22)|
| 15 | Dadu Gambar | Permainan Dadu Versi Gambar | Aktif | [`Klik Disini`](https://tinyurl.com/zeud364h)|
| 16 | Dark Jokes | Mengirimkan Gambar Meme Gelap | Aktif | [`Klik Disini`](https://tinyurl.com/rzavupfr)|
| 17 | EXO | Mengirimkan Gambar EXO | Aktif | [`Klik Disini`](https://tinyurl.com/3dczxfvn)|
| 18 | Family 100 | Mengirimkan Soal Family 100 | Aktif | [`Klik Disini`](https://tinyurl.com/438b648z)|
| 19 | Ganteng Cek | Menentukan Seberapa Gantengnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/24w336ek)|
| 20 | Gay Cek | Menentukan Seberapa Gaynya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/9m75yeyr)|
| 21 | Gombal | Mengirimkan Kata Gombalan | Aktif | [`Klik Disini`](https://tinyurl.com/ybsuem2r)|
| 22 | IQ Test | Menentukan Seberapa Pintarnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/xaxh24cn)|
| 23 | Meme Indo | Mengirimkan Gambar Meme Indonesia | Aktif | [`Klik Disini`](https://tinyurl.com/czw5wwut)|
| 24 |Pantun | Mengirimkan Kata Pantun | Aktif | [`Klik Disini`](https://tinyurl.com/snmf483w)|
| 25 | Puisi | Mengirimkan Kata Puisi | Aktif | [`Klik Disini`](https://tinyurl.com/34mjsbfz)|
| 26 | Quotes | Mengirimkan Kata Quotes | Aktif | [`Klik Disini`](https://tinyurl.com/de669y9b)|
| 27 | Simsimi | Simsimi Menemani Anda Mengobrol | Aktif | [`Klik Disini`](https://tinyurl.com/3d597725)|
| 28 | Syair | Mengirimkan Kata Syair | Aktif | [`Klik Disini`](https://tinyurl.com/3k6zp6mh)|
| 29 | Tebak Gambar | Mengirimkan Soal Tebak Gambar | Aktif | [`Klik Disini`](https://tinyurl.com/puxr8c)|
| 30 | Tolol Cek | Menentukan Seberapa Tololnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/4a6er9vn)|







# Media Sosial <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="30px">


#### Instagram : [`@h4cking3mpir3S`](https://www.instagram.com/h4cking3mpir3S)
#### Kontak : [`WhatsApp`](https://wa.me/62859106999930)
#### Donasi : [`Seikhlasnya :)`](https://saweria.co/akashiro)
#### Creator : [`akashiro`](https://Github.com/akashiro22)
