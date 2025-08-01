# Scraping Dataset

## Pendahuluan

Scraping ini dilakukan pada website repository dari 6 kampus UIN yang memiliki jurusan Sistem Informasi.  

## Alur Scraping
1. Kita lihat dulu link website repository. contoh: "https://repository.uin-suska.ac.id/view/divisions/st=5Fsif/2020.html"
2. Dari link tersebut diketahui bahwa terdapat tahun (2020). nah dari sini kita rubah tahunnya sesuai yang kita inginkan yaitu tahun 2019-2024
3. Kita lihat struktur HTMl websitenya. contoh seperti ini
<br>![alt text](https://github.com/hud4-yanto/topic-modeling-thesis/blob/main/Data%20Scraping/ss1.png) </br>
dari contoh itu, kita tahu bahwa masing-masing skripsi memiliki ID unik. Id itulah yang nantinya kita ambil. dari Id itu kita bisa menuju halaman masing-masing judul skripsi.  
4. Halaman masing-masing judul skripsi tersebut setelah dicek struktur htmlnya memiliki bagian seperti ini 
<br>![alt text](https://github.com/hud4-yanto/topic-modeling-thesis/blob/main/Data%20Scraping/ss2.png) </br>
nah, bagian itu menunjukkan bahwa halaman tersebut memiliki versi alternatif dalam beberapa format. Kita fokus ke format JSON(.js)
5. ID skripsi yang telah kita dapatkan tadi kemudian diterapkan dalam mencari JSON.  
6. Scraping data-data yang diperlukan dari JSON tersebut



```
Buka jupyter-notebook dengan menjalankan perintah berikut.
```
jupyter-notebook .

```
