# Anatomi CSS

![Anatomy.jpeg](Anatomy.jpeg)

## Selector
Selector P digunakan untuk menentukan elemen HTML mana yang akan diberikan gaya atau diubah tampilannya.

## Property
Property Color Digunakan untuk Memberikan Warna kepada Selector P

## Anatomi CSS

![anatomy2.jpeg](anatomy2.jpeg)

### Selector Pintu atau jendela
Yang ingin di modifikasi ialah Pintu atau jendela 

### Property Color
Anda dapat menggunakan property ini untuk menambahkan detail pada elemen-elemen warna ke pintu atau jendela, misalnya dengan menambahkan komponen kusennya agar jendela terlihat terbuka.

### Property value width dan heighht
Ini memungkinkan Anda untuk menentukan ukuran dari elemen-elemen rumah, seperti atap, badan rumah, pintu, dan jendela.

# Percobaan Pertama

![[selector.jpeg]]
## Before
![[h.bljr 1 css.png]]

## After
![[h.bljr 2 css.png]]

> [!penjelasan]
>  <`style`> p{ color:red; } <`/style`>: Ini adalah bagian di mana CSS diterapkan secara internal. Pada kode ini, aturan CSS diberikan untuk elemen <`p`>, yang akan membuat teks di dalamnya berwarna merah. <`p`>Welcome CSS!<`/p`>: Ini adalah elemen paragraf pertama dengan teks "Welcome CSS!". Karena itu adalah elemen <`p`>, gaya CSS yang dideklarasikan sebelumnya (warna teks merah) akan diterapkan pada teks di dalamnya. <`P`>Welcome CSS!<`/P`>: Ini adalah elemen paragraf kedua dengan teks yang sama seperti sebelumnya
>


# Percobaan Kedua

## Kode CSS
```html
<!DOCTYPE html>

  
  
  

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<style> p{

          color:red;}

  

button{

    width: 150px;

    height: 50px;

    color: aqua;

    font-size: 20px;

    background-color: #d8ff49;

    margin-top: 50px;

</style>

  
  

<body>

    <p>Welcome CSS!</p>

    <P>Welcome CSS!</P>

  

    <button>klik aku</button>

</body>

</html>
``` 

## Color
## Before
![h.percobaan.png](h.percobaan.png)

## After
![h.2.png](h.2.png)


> [!penjelasan]
> Property color dalam CSS digunakan untuk mengatur warna teks dari suatu elemen HTML. color Berfungsi Untuk Memberikan Warna  Teks Klik aku. Perbedaannya terlihat jelas sebelum di berikan property color pada teks klik aku itu belum memiliki warna.


## Background-color
### Before
![h.2.png](h.2.png)


### After
![h.3.png](h.3.png)


>[!penjelasan]
>Property background-color dalam CSS digunakan untuk mengatur warna latar belakang dari suatu elemen HTML.background-color juga dapat digunakan bersamaan dengan property background-image untuk memberikan gambar latar belakang bersamaan dengan warna latar belakang.


## Font-size

### Before
![h.3.png](h.3.png)

### After
![h.font.png](h.font.png)

>[!penjelasan]
Property font-size dalam CSS digunakan untuk mengatur ukuran teks pada suatu elemen HTML. Property font-size memungkinkan Anda untuk mengontrol ukuran teks secara tepat sesuai kebutuhan desain Anda



# Deklarasi CSS

## External

### Contoh Program
```
<link rel="stylesheet" href="bljr.css">
```

> [!penjelasan]
> Deklarasi CSS eksternal mengacu pada penempatan kode CSS di dalam file eksternal terpisah dari dokumen HTML utama. Ini memisahkan struktur dan konten dari tampilan dan gaya, meningkatkan keterbacaan, memudahkan pemeliharaan, dan memungkinkan penggunaan kembali gaya di seluruh situs web.

## Internal

### Contoh Program
```
<style>

         . bg-maroon{

            background-color: maroon;

            padding: 10px;

        }

    </style>
```

> [!penjelasan]
> Deklarasi CSS internal mengacu pada penempatan kode CSS di dalam tag <`style`> di dalam dokumen HTML itu sendiri. Ini memungkinkan pengguna untuk menentukan gaya secara langsung di dalam dokumen HTML tanpa perlu membuat file eksternal terpisah. 

## Inline

### Contoh Program
```
    <div class="bg-maroon" style="background-color: orange;">

        Using inline css

  

    </div>
```

> [!penjelasan]
> Deklarasi CSS inline mengacu pada penempatan kode CSS langsung di dalam atribut style dari suatu elemen HTML. Ini memungkinkan Anda untuk menentukan gaya secara langsung di dalam elemen HTML itu sendiri.

# Selector

## Selector ID
Selector id: untuk memilih elemen dengan ID tertentu, gunakan tanda pagar (#) di ikuti dengan nama ID  Sebagai selector.
Contohnya:
```css
#judul
    Font-size: 24px;
    }

```
`#judul` ini akan menerapkan gaya pada elemen dengan ID judul.

## Selector class 
Selector Class: untuk memili elemen dengan class tertentu, gunakan titik (.) diikuti dengan nama class sebagai selector.
contohnya:
```css
. teks-merah {
    color : red;
}
```
Ini akan menerapkan gaya pada semua elemen dengan class teks-merah.

## Selector Elemen 
Selector Elemen: untuk memilih semua elemen  dengan tag tertentu, gunakan nama tag sebagai selector.
Contohmya:
```css
p {
  Color : red;
}
```
Ini akan menerapkan gaya pada semua elemen <`p`> dalam dokumen HTML. 

# Materi Font

## Font-size

### Penjelasan
Property font-size dalam CSS digunakan untuk mengatur ukuran teks pada suatu elemen HTML. pengguna dapat menentukan ukuran teks dalam berbagai cara, termasuk ukuran absolut, relatif, atau menggunakan nilai persentase.

Contoh:

Ukuran Absolut: 
Pengguna dapat menetapkan ukuran teks secara absolut dalam unit seperti piksel (px), poin (pt), piksel piksel (pc), atau milimeter (mm).

Ukuran Relatif:
Pengguna dapat menetapkan ukuran teks secara relatif terhadap ukuran font elemen induknya menggunakan unit seperti em atau rem.

Persentase:
Pengguna dapat menentukan ukuran teks sebagai persentase dari ukuran font elemen induknya.

### Kode Program
```
font {

    font-size: 100px;

}
```

### Hasil 
![h.fontt.png](h.fontt.png)

### Kesimpulan
memungkinkan Pengguna untuk pengontrolan ukuran teks pada elemen HTML.

### Font-weight

### Penjelasan
Property font-weight dalam CSS digunakan untuk mengontrol ketebalan (boldness) teks pada elemen HTML. Ini memungkinkan Anda untuk menyesuaikan gaya teks dari yang normal hingga tebal.
Property ini dapat memiliki beberapa nilai, termasuk:

- normal: Menetapkan teks dengan ketebalan normal.
- bold: Menetapkan teks dengan ketebalan tebal.
- Angka dari 100 hingga 900: Mengatur ketebalan teks dalam rentang tertentu. Nilai yang lebih besar menunjukkan ketebalan yang lebih besar.
### Kode Program
```
.fontt {

    font-weight:bolder;

}
```
### Hasil
![h.fontt 2 .png](h.fontt%202%20.png)
### Kesimpulan
property font-weight dalam CSS memberikan kontrol atas ketebalan teks pada elemen HTML. Dengan menggunakan font-weight, Pengguna dapat memberikan penekanan visual pada teks, meningkatkan keterbacaan, dan mencapai tampilan yang sesuai dengan desain halaman web pengguna.


## Font-style

### Penjelasan
Property font-style dalam CSS digunakan untuk mengatur gaya atau bentuk teks pada elemen HTML. Ini memungkinkan Anda untuk menyesuaikan apakah teks harus ditampilkan dalam gaya normal, miring (italic), atau miring secara condong (oblique).

Property Font-Style  ini memiliki beberapa nilai, termasuk:
- normal: Menetapkan teks dalam gaya normal (tidak miring).
-  italic: Menetapkan teks dalam gaya miring (italic).
- oblique: Menetapkan teks dalam gaya miring secara condong (oblique). Namun, implementasi ini mungkin tidak didukung oleh semua browser.

### Kode Program
```
.fonttt {

    font-style: italic;

}
```
### Hasil
![h.fontt 3 .png](h.fontt%203%20.png)
### Kesimpulan
property font-style dalam CSS memungkinkan Anda mengontrol gaya atau bentuk teks pada elemen HTML. Dengan menggunakan font-style, Anda dapat memberikan gaya tambahan pada teks, meningkatkan estetika dan keterbacaan, serta mencapai tampilan yang sesuai dengan desain halaman web Anda.


## Font-Family

### Penjelasan
Property font-family dalam CSS digunakan untuk menentukan jenis font yang akan digunakan untuk menampilkan teks pada elemen HTML. Ini memungkinkan Anda untuk menentukan preferensi font dalam urutan prioritas, sehingga browser dapat mencari dan menggunakan font yang tersedia yang paling cocok.

Pengguna dapat menyediakan nama famili font sebagai nilai, seperti serif, sans-serif, monospace, cursive, atau fantasy. Ini memungkinkan browser untuk memilih font yang cocok berdasarkan jenis famili font yang diinginkan.
### Kode Program
```
.fontttt {

    font-family: 'Courier New', Courier, monospace;

}
```
### Hasil
![h.fontt 4.png](h.fontt%204.png)
### Kesimpulan
property font-family dalam CSS memungkinkan Pengguna untuk menentukan jenis font yang akan digunakan untuk menampilkan teks pada elemen HTML.

Dengan menggunakan font-family, Pengguna dapat menyesuaikan tampilan teks pada halaman web Anda, memastikan konsistensi dan kesesuaian dengan desain yang diinginkan, serta meningkatkan keterbacaan dan estetika keseluruhan.


# Materi text
#  text decoration

## Text-decoration: overline

### Penjelasan
 text-decoration: overline dalam CSS digunakan untuk menambahkan garis di atas teks. Ketika properti ini diterapkan pada suatu elemen HTML, garis horizontal akan ditampilkan di atas teks pada elemen tersebut.

Ada beberapa Poin penting sebagai Berikut:
1. Garisan Di Atas Teks: Properti ini menambahkan garis horizontal di atas teks yang sesuai dengan elemen yang diberi gaya.

2. Nilai: Nilai yang diterima oleh properti ini adalah overline. Ini menandakan bahwa teks harus diberi garis di atasnya.

3. Penggunaan: Anda dapat menerapkan properti ini ke berbagai elemen HTML, seperti <`p`>, <`span`>, atau <`a`> untuk menambahkan garis di atas teks tersebut.

### Kode Program
```
.paling {

    text-decoration: overline;

  

}
```
### Hasil
![h.text decoration overline.png](h.text%20decoration%20overline.png)

### Kesimpulan
text-decoration: overline Digunakan untuk menambahkan garis hirizontal di atas text pada suatu elemen html. Dengan menggunakan text-decoration: overline, Anda dapat memberikan penekanan visual tambahan pada teks atau menyorotnya dengan menambahkan garis di atasnya.


## text-decoration: underline

### Penjelasan
text-decoration: underline dalam CSS digunakan untuk menambahkan garis bawah pada teks di dalam suatu elemen HTML. Ketika properti ini diterapkan, garis horizontal akan ditampilkan di bawah teks pada elemen yang diberi gaya.

- Garis Bawah pada Teks: Properti ini menambahkan garis horizontal di bawah teks yang sesuai dengan elemen yang diberi gaya.

- Nilai: Nilai yang diterima oleh properti ini adalah underline, yang menunjukkan bahwa teks harus diberi garis bawah.
### Contoh Program
```
.sombong {

    text-decoration: underline;
    
}
```
### Hasil
![h.text decoration underline.png](h.text%20decoration%20underline.png)
### Kesimpulan
text-decoration: underline dalam CSS digunakan untuk menambahkan garis bawah pada teks di dalam suatu elemen HTML. underline, Anda dapat menambahkan garis bawah pada teks untuk menyorotnya atau memberikan penekanan visual tambahan.


## text-decoration: line-through

### Penjelasan
Property text-decoration: line-through dalam CSS digunakan untuk menambahkan garis melintang (strikethrough) pada teks di dalam suatu elemen HTML.

- Garis Melintang pada Teks: Properti ini menambahkan garis horizontal melintasi teks yang sesuai dengan elemen yang diberi gaya.

- Nilai: Nilai yang diterima oleh properti ini adalah line-through, yang menunjukkan bahwa teks harus diberi garis melintang.
### Kode Program
```
.artis {

    text-decoration: line-through;

}
```
### Hasil
![h.text decoration line through.png](h.text%20decoration%20line%20through.png)
### Kesimpulan
jadi Dengan menggunakan text-decoration: line-through, Anda dapat menambahkan garis melintang pada teks untuk menandai bahwa teks tersebut sudah tidak relevan atau tidak berlaku lagi.


##  text-decoration: none

### Penjelasan
Property text-decoration: none dalam CSS digunakan untuk menghapus semua dekorasi teks yang telah diberikan sebelumnya, seperti garis bawah, garis melintang, atau garis di atas teks. berikut  ini ada 2 poin penting 

- Penghapusan Dekorasi Teks: Properti ini menghapus semua dekorasi teks yang telah diberikan sebelumnya pada suatu elemen, termasuk garis bawah, garis melintang, atau garis di atas teks.

- Nilai: Nilai yang diterima oleh properti ini adalah none, yang menunjukkan bahwa teks tidak akan memiliki dekorasi tambahan
### Kode Program
```
.jago {

    text-decoration: none;

}
```
### Hasil
![h.text decoration none.png](h.text%20decoration%20none.png)
### Kesimpulan
jadi kesimpulannya adalah text none adalah berfungsi untuk menghilangkan dekorasi teks seperti teks garis bawah (underline) pada hyperlink. Dengan menggunakan perintah 'none' property teks seperti itu akan di hilangkan.


# text-transform:
## text-transform: uppercase

### Penjelasan
digunakan untuk mengubah semua huruf dalam teks menjadi huruf besar (uppercase). Dengan menggunakan nilai uppercase, semua huruf dalam teks akan ditampilkan dalam bentuk huruf besar, tidak peduli bagaimana teks tersebut ditulis dalam kode HTML.
### Kode Program
```
.tesss {

    text-transform: uppercase;

}
```
### Hasil 
![h.text transform uppercase.png](h.text%20transform%20uppercase.png)
### Kesimpulan
Jadi, kesimpulannya adalah bahwa penggunaan properti text-transform: uppercase; akan membuat teks ditampilkan dalam huruf besar.

## text-transform: lowercase

### Penjelasan
digunakan untuk mengubah semua huruf dalam teks menjadi huruf kecil (lowercase). Dengan menggunakan nilai lowercase, semua huruf dalam teks akan ditampilkan dalam bentuk huruf kecil, tidak peduli bagaimana teks tersebut ditulis dalam kode HTML.
### Kode Program
```
.tesss {

    text-transform: lowercase;

}
```
### Hasil 
![h.text transform lowercase.png](h.text%20transform%20lowercase.png)
### Kesimpulan
Jadi, kesimpulannya adalah bahwa penggunaan properti text-transform: lowercase; akan membuat teks ditampilkan dalam huruf kecil.

## text-transform: capitalize

### Penjelasan
 digunakan untuk mengubah teks sehingga setiap kata diawali dengan huruf besar. Dengan menggunakan nilai capitalize, properti ini mengubah teks sehingga huruf pertama setiap kata menjadi huruf besar, sedangkan huruf-huruf lainnya tetap dalam bentuk aslinya (tidak diubah menjadi huruf besar atau kecil).
### Kode Program
```
.tesss {

    text-transform: capitalize;

}
```
### Hasil 
![h.text transform capitalize.png](h.text%20transform%20capitalize.png)
### Kesimpulan
Jadi, kesimpulannya adalah bahwa penggunaan properti text-transform: capitalize; akan membuat setiap kata dalam teks dimulai dengan huruf besar.

# Text Indent

## Penjelasan
Berfungsi untuk mengatur jarak awal dari teks dalam sebuah elemen. property ini biasanya digunakan untuk mengatur indentasi/jarak pada awal pragraf atau pada bagian tertentu dalam sebuah blok teks.

adapun berikut poin-poin tentang beberapa aspek dari property **text indent** sebagai berikut:
**Nilai:** 
Property text-indent dapat diatur dengan nilai absolut (px, cm, dll.) atau relatif (em, %) tergantung pada preferensi desain.

**Penggunaan:**
Property ini biasanya digunakan pada elemen seperti p (paragraf) untuk mengatur indentasi pada awal paragraf, atau pada elemen lain seperti ul (unordered list) untuk membuat indentasi pada setiap item dalam daftar.



## Kode Program
```
.ko {

    text-indent: 100px;

}
```
## Hasil 
![h.text indent.png](h.text%20indent.png)
## Kesimpulan 
digunakan untuk mengatur jarak awal teks dari sisi kiri paragraf atau elemen teks lainnya. Dengan menggunakan nilai absolut atau relatif, property ini memungkinkan pengguna untuk menciptakan efek indentasi pada teks, baik itu pada awal paragraf, dalam daftar, atau dalam situasi khusus seperti hanging indent. Property ini dapat meningkatkan tata letak dan estetika dokumen web dengan memberikan struktur yang lebih jelas pada teks.

# text litter-spacing

## Penjelasan 
digunakan untuk mengatur jarak antara karakter dalam teks. Property ini memungkinkan pengguna untuk mengendalikan spasi antara huruf-huruf dalam sebuah string teks.

adapun berikut poin-poin tentang beberapa aspek dari property **text litter-spacing**sebagai berikut:
Nilai: 
Property letter-spacing dapat diatur dengan nilai absolut (px, cm, dll.) atau relatif (em, %) untuk menentukan jarak antara karakter. Nilai positif akan meningkatkan jarak antara karakter, sementara nilai negatif akan mengurangi jaraknya.

Penggunaan:
Property ini sering digunakan untuk tujuan desain estetika, seperti menambahkan atau mengurangi jarak antara huruf-huruf untuk meningkatkan legibilitas atau untuk mencapai efek desain tertentu

## Kode Program
```
.ya {

    background-attachment: red;

}
```
## Hasil
![h.text  spacing.png](h.text%20%20spacing.png)
## Kesimpulan
digunakan untuk mengatur jarak antara karakter dalam teks. Dengan menentukan nilai positif atau negatif, pengguna dapat mengendalikan spasi antara huruf-huruf dalam sebuah string teks. Property ini memungkinkan untuk meningkatkan legibilitas teks, mencapai efek desain yang diinginkan, atau menambahkan sentuhan dekoratif pada teks. Dengan menggunakan letter-spacing, desainer dapat menciptakan tata letak yang lebih menarik dan terstruktur dalam hal jarak antar huruf.

# text line-height
## Penjelasan
digunakan untuk mengatur tinggi baris dalam sebuah elemen teks. Property ini menentukan jarak vertikal antara baris teks dalam elemen tersebut, dan dapat dinyatakan dalam nilai absolut (px, pt, dll.) atau relatif (em, %).

adapun berikut poin-poin tentang beberapa aspek dari property **text line-height**sebagai berikut:
Nilai: 
Property line-height dapat diatur dengan nilai absolut untuk menentukan tinggi baris dalam piksel, atau dengan nilai relatif untuk menentukan tinggi baris sebagai faktor dari ukuran font.

Penggunaan: 
Property ini digunakan untuk mengontrol ketinggian baris dalam teks, memengaruhi legibilitas, kepadatan teks, dan tata letak secara keseluruhan. Nilai yang lebih besar akan membuat baris lebih tinggi, sementara nilai yang lebih kecil akan membuat baris lebih rapat.
## Kode Program
```
.kooo {

    line-height: 100px;

}
```
## Hasil
![h.text ling-height.png](h.text%20ling-height.png)
## Kesimpulan
digunakan untuk mengatur tinggi baris dalam sebuah elemen teks. Dengan menentukan nilai absolut atau relatif, pengguna dapat mengontrol jarak vertikal antara baris teks, yang memengaruhi legibilitas, kepadatan teks, dan tata letak secara keseluruhan. Property ini penting untuk meningkatkan keterbacaan dan estetika teks dalam desain web, serta memastikan bahwa teks terlihat seimbang dan mudah dipahami. Dengan menggunakan line-height, desainer dapat menciptakan tampilan teks yang menarik dan mudah dibaca bagi pengguna.

# text word-spacing

## Penjelasan
digunakan untuk mengatur jarak antara kata-kata dalam teks. Ini memungkinkan pengguna untuk mengendalikan spasi horizontal antara kata-kata dalam sebuah string teks.

adapun berikut poin-poin tentang beberapa aspek dari property **text word-spacing**sebagai berikut:

Nilai: Property word-spacing dapat diatur dengan nilai absolut (px, cm, dll.) atau relatif (em, %) untuk menentukan jarak antara kata-kata. Nilai positif akan meningkatkan spasi antara kata-kata, sementara nilai negatif akan mengurangi spasi.

Penggunaan: Property ini sering digunakan untuk tujuan desain estetika, seperti menyesuaikan jarak antara kata-kata untuk meningkatkan tata letak teks atau untuk mencapai efek desain tertentu.

## Kode Program
```
.koooo {

    word-spacing: 100px;

}
```
## Hasil
![h. text word-spacing.png](h.%20text%20word-spacing.png)
## Kesimpulan
digunakan untuk mengatur jarak antara kata-kata dalam teks. Dengan menentukan nilai positif atau negatif, pengguna dapat mengendalikan spasi horizontal antara kata-kata dalam sebuah string teks. Property ini memungkinkan untuk meningkatkan tata letak teks, mencapai efek desain yang diinginkan, atau menambahkan sentuhan estetika pada teks. Dengan menggunakan word-spacing, desainer dapat menciptakan tampilan teks yang lebih terbaca dan menarik bagi pengguna.


# Materi Background-color
# Background-image

## Penjelasan
digunakan untuk menetapkan gambar sebagai latar belakang suatu elemen HTML. Ini memungkinkan desainer web untuk menambahkan elemen visual yang menarik pada latar belakang elemen, seperti halaman web, bagian dari layout, atau elemen UI lainnya.

Berikut adalah beberapa poin penting tentang property background-image:
Penetapan Gambar: 
Property background-image digunakan untuk menetapkan gambar sebagai latar belakang elemen HTML. Gambar ini ditampilkan di belakang isi elemen dan berada di lapisan paling belakang.

Nilai: 
Property ini menerima nilai berupa URL gambar yang akan digunakan sebagai latar belakang elemen. URL tersebut dapat merujuk ke gambar lokal di file sistem, atau gambar yang di-host secara online. nilai yang di maksud di sini adalah nama dokumen gambar yang ingin kita kasih masuk ke URL
## Kode program
```
background-image : url("dee.jpeg");
```
## Hasil
![h.background image.png](h.background%20image.png)

## Kesimpulan
jadi dalam css property background-image digunakan untuk menambahkan gambar sebagai latar belakang suatu elemen HTML. Dengan menetapkan URL gambar pada property ini, desainer dapat meningkatkan estetika desain web dengan menambahkan elemen visual yang menarik pada latar belakang elemen HTML. Pengaturan tambahan seperti background-size dan background-position dapat digunakan untuk mengontrol tampilan dan posisi gambar latar belakang. Dengan menggunakan background-image, desainer dapat menciptakan desain web yang lebih menarik dan menarik perhatian pengguna.

# Background-size
## Penjelasan
digunakan untuk mengatur ukuran dari gambar latar belakang yang ditetapkan dengan menggunakan background-image. Property ini memungkinkan desainer untuk mengontrol cara gambar latar belakang ditampilkan dan disesuaikan dengan ukuran elemen yang terkait.

Berikut adalah format dan penjelasan singkat tentang property background-size:
```
background-size: nilai;

```

  **NILAI:**
- Nilai ini dapat berupa nilai absolut seperti px (piksel) atau em, nilai relatif seperti % (persentase), atau nilai khusus seperti cover dan contain.
  - cover: Memastikan bahwa gambar latar belakang mengisi seluruh area latar belakang elemen tanpa merubah aspek rasio. Hal ini dapat menyebabkan potongan gambar jika aspek rasio gambar tidak sama dengan aspek rasio area latar belakang.
  - contain: Memastikan bahwa gambar latar belakang dimasukkan ke dalam area latar belakang elemen sepenuhnya tanpa mengubah aspek rasio gambar. Hal ini dapat menyebabkan area latar belakang tidak sepenuhnya terisi jika aspek rasio gambar tidak sama dengan aspek rasio area latar belakang.


## Kode Program
```
.container {

        width: 500px;

        height: 300px;

        background-image : url("dee.jpeg");

        background-size: contain/cover ;

    }
```
## Hasil
Cover:
![h.background size cover.png](h.background%20size%20cover.png)

Contain:
![h.background size contain.png](h.background%20size%20contain.png)
## Kesimpulan
property background-size dalam CSS digunakan untuk mengatur ukuran dari gambar latar belakang yang ditetapkan dengan menggunakan background-image. Dengan menetapkan nilai seperti cover atau contain, desainer dapat mengontrol cara gambar latar belakang ditampilkan dan disesuaikan dengan ukuran elemen yang terkait. Ini memungkinkan untuk menciptakan tampilan latar belakang yang sesuai dengan kebutuhan desain, baik dengan membuat gambar mengisi seluruh area latar belakang elemen (cover) atau memasukkan gambar ke dalam area latar belakang elemen sepenuhnya tanpa mengubah aspek rasio (contain). Dengan menggunakan property background-size, desainer dapat mengatur tampilan gambar latar belakang dengan fleksibilitas dan presisi untuk mencapai efek desain yang diinginkan.

# Background-repeat

## Penjelasan
Property background-repeat dalam CSS digunakan untuk mengatur apakah gambar latar belakang yang ditetapkan dengan menggunakan background-image akan diulang atau tidak, serta cara bagaimana gambar tersebut diulang jika diaktifkan. Property ini memungkinkan desainer untuk mengontrol tampilan ulang gambar latar belakang dalam elemen yang terkait.
```
background-repeat: nilai;

```

- nilai: Nilai ini dapat berupa repeat, repeat-x, repeat-y atau no-repeat.
  - repeat: Gambar latar belakang akan diulang baik secara horizontal maupun vertikal sampai mengisi seluruh latar belakang elemen.
   - repeat-x: Gambar latar belakang akan diulang hanya secara horizontal, mengisi latar belakang elemen di sepanjang sumbu X.
  - repeat-y: Gambar latar belakang akan diulang hanya secara vertikal, mengisi latar belakang elemen di sepanjang sumbu Y.
  - no-repeat: Gambar latar belakang tidak akan diulang dan akan muncul hanya satu kali di latar belakang elemen.

## Kode Program
```
.container {

        width: 500px;

        height: 200px;

        background-image : url("dee.jpeg");

        background-repeat: repeat/no-repeat;

    }
```
## Hasil
![h.background no repeat.png](h.background%20no%20repeat.png)

## Kesimpulan
property background-repeat dalam CSS digunakan untuk mengatur apakah gambar latar belakang yang ditetapkan dengan menggunakan background-image akan diulang atau tidak, serta cara bagaimana gambar tersebut diulang jika diaktifkan. Dengan menggunakan nilai seperti repeat, repeat-x, repeat-y, atau no-repeat, desainer dapat mengontrol tampilan ulang gambar latar belakang dalam elemen yang terkait. Ini memungkinkan untuk mencapai efek visual yang diinginkan dalam desain web, baik dengan mengulang gambar secara horizontal dan vertikal, atau hanya menampilkan gambar sekali tanpa diulang. Dengan menggunakan property background-repeat, desainer dapat memperkaya tampilan latar belakang elemen HTML sesuai dengan kebutuhan desain mereka.

# Background-attachment

## Kode Program:
```
.container {

        width: 100%;

        height: 500px;

        background-image : url("dee.jpeg");

        background-attachment: fixet/;

    }
```

## Hasil
![h.background attachment fixet.png](h.background%20attachment%20fixet.png)
## Penjelasan 
Property background-attachment dalam CSS digunakan untuk mengatur apakah gambar latar belakang yang ditetapkan dengan menggunakan background-image akan tetap diam atau mengikuti guliran (scrolling) ketika halaman digulir. Property ini memberikan kontrol terhadap perilaku posisi gambar latar belakang relatif terhadap jendela tampilan pengguna.

Beikut Beberapa format/nilai yang ada di background-attachment:
## Background-attachment fixet
### Penjelasan
Background-attachment fixet di gunakan untuk Mengunci posisi gambar latar belakang sehingga tetap diam relatif terhadap jendela tampilan pengguna. Ketika pengguna menggulir halaman, gambar tersebut tetap pada posisinya.
  


### Kesimpulan
- Gambar latar belakang tetap diam relatif terhadap jendela tampilan pengguna.
- Ketika pengguna menggulir halaman, gambar tersebut tetap pada posisinya.
- Cocok digunakan untuk membuat efek parallax atau elemen latar belakang yang tetap.

## Background-attachment scroll
### Penjelasan
 Background-attachment fixet di gunakan Membiarkan gambar latar belakang mengikuti guliran (scrolling) halaman. Ketika pengguna menggulir halaman, gambar tersebut akan bergerak sesuai dengan konten di dalamnya.



### Kesimpulan
 - Gambar latar belakang mengikuti guliran (scrolling) halaman.
 - Ketika pengguna menggulir halaman, gambar tersebut akan bergerak sesuai dengan konten di dalamnya.
 - Digunakan ketika ingin gambar latar belakang bergerak bersamaan dengan konten halaman.
## Background-attachment local
### Penjelasan
Membuat gambar latar belakang tetap diam relatif terhadap elemen induknya. Ini berarti gambar akan bergerak bersama dengan elemen tersebut ketika pengguna menggulir konten di dalam

### Kesimpulan
- Gambar latar belakang tetap diam relatif terhadap elemen induknya.
- Gambar akan bergerak bersama dengan elemen tersebut ketika pengguna menggulir konten di dalamnya.
- Digunakan ketika ingin gambar latar belakang terkunci pada elemen tertentu dan bergerak bersama dengan konten dalam elemen tersebut.
   
## Background-attachment initial
### Penjelasan
Mengatur property ke nilai awal (initial) yang didefinisikan dalam spesifikasi CSS, yaitu scroll

### Kesimpulan
Mengatur property ke nilai awal (initial) yang didefinisikan dalam spesifikasi CSS, yaitu scroll.

# Background-position

## Kode program
```
.container {

        width: 500px;

        height: 300px;

        background-image : url("dee.jpeg");

        background-repeat: no-repeat;

        background-position: center center;

        border: 2px solid black;

    }
```

## Penjelasan
Seperti namanya position yang berarti penempatan jadi Property background-position dalam CSS digunakan untuk mengatur posisi relatif dari gambar latar belakang yang ditetapkan dengan menggunakan background-image. Property ini memungkinkan desainer untuk menentukan lokasi di mana gambar latar belakang akan ditampilkan dalam elemen yang terkait.

Beikut Beberapa nilai yang ada di Background-position 
## Background-position top
### Penjelasan
Top menempatkan Gambar latar belakang kita di bagian atas bawah elemen, elemen yang di maksud adalah property border yang membungkus gambar kita.
### Hasil
![h.background position top.png](h.background%20position%20top.png)
### Kesimpulan
Cocok untuk menempatkan gambar latar belakang di bagian atas elemen, baik secara horizontal maupun vertikal.

## Background-position bottom
### Penjelasan
Top menempatkan Gambar latar belakang kita di bagian bawah  elemen, elemen yang di maksud adalah property border yang membungkus gambar kita.
### Hasil
![h.background position bottom.png](Aset%20CSS/h.background%20position%20bottom.png)
### Kesimpulan
Ideal untuk menempatkan gambar latar belakang di bagian bawah elemen, baik secara horizontal maupun vertikal.

## Background-position left
### Penjelasan
Top menempatkan Gambar latar belakang kita di bagian kiri bawah elemen, elemen yang di maksud adalah property border yang membungkus gambar kita.
### Hasil
![h.background position left.png](h.background%20position%20left.png)
### Kesimpulan
Berguna untuk menempatkan gambar latar belakang di bagian kiri elemen, baik secara horizontal maupun vertikal.

## Background-position right
### Penjelasan
Top menempatkan Gambar latar belakang kita di bagian kanan bawah elemen, elemen yang di maksud adalah property border yang membungkus gambar kita.
### Hasil
![h.background position right.png](h.background%20position%20right.png)
### Kesimpulan
Berguna untuk menempatkan gambar latar belakang di bagian kanan elemen, baik secara horizontal maupun vertikal.

## Background-position center
### Penjelasan
Top menempatkan Gambar latar belakang kita di bagian tengah bawah elemen, elemen yang di maksud adalah property border yang membungkus gambar kita.
### Hasil
![h.background position center.png](h.background%20position%20center.png)
### Kesimpulan
Cocok untuk menempatkan gambar latar belakang di tengah elemen, baik secara horizontal maupun vertikal.


# Box Model

## Materi  Border  

### Kode Program html dan css
```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<link rel="stylesheet" href="style.css">

<body background-color="purply">

    <button class="button1">klik aku</button><br><br>

  

</body>

</html>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 5px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;
```



### Border width
#### Penjelasan
Property border-widthadalah properti dalam CSS yang digunakan untuk menentukan lebar (ketebalan) dari batas (border) pada suatu elemen HTML. Properti ini dapat memiliki nilai tunggal atau empat nilai terpisah, yang masing-masing mengatur batas lebar pada sisi atas, kanan, bawah, dan kiri dari elemen.

- Jika hanya satu nilai yang diberikan, maka nilai tersebut akan digunakan untuk semua sisi batas.
- Jika empat nilai terpisah diberikan, maka nilai-nilai tersebut akan mengatur batas lebar untuk setiap sisi secara berurutan, yaitu atas, kanan, bawah, dan kiri.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 5px;
```
#### Hasil
![h.margin bottom (1).png](h.margin%20bottom%20(1).png)

#### kesimpulan
Properti border-widthdalam CSS digunakan untuk menentukan lebar (ketebalan) dari batas (border) pada suatu elemen HTML. Properti ini bisa memiliki nilai tunggal atau empat nilai terpisah, yang masing-masing mengatur batas lebar pada sisi atas, kanan, bawah, dan kiri dari elemen. Dengan menggunakan properti ini, Anda dapat mengontrol tampilan elemen dengan menentukan seberapa tebal batasnya pada setiap sisinya.


### border color
#### Penjelasan
Border color adalah properti CSS yang digunakan untuk menentukan warna dari batas (border) sebuah elemen HTML. Properti ini dapat didefinisikan dengan menggunakan nama warna (seperti "red", "blue", "green"), kode warna (seperti "#ff0000" untuk merah), atau menggunakan nilai RGB (seperti "rgb(255, 0, 0)"). Dengan menggunakan properti border color, Anda dapat menyesuaikan tampilan batas dari elemen HTML sesuai dengan kebutuhan desain web Anda.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-color: #d8ff49;
```
#### Hasil
![h.border color.jpg](h.border%20color.jpg)

#### Kesimpulan
Border color adalah properti CSS yang digunakan untuk menentukan warna dari batas (border) sebuah elemen HTML. Ini memungkinkan pengguna untuk menyesuaikan tampilan batas elemen sesuai dengan kebutuhan desain web menggunakan nama warna, kode warna, atau nilai RGB.

### Border style

#### Penjelasan

border-style: solid; adalah sebuah CSS (Cascading Style Sheets) property yang digunakan untuk menentukan jenis garis tepi (border) dari sebuah elemen dalam sebuah halaman web.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>

```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-color: #d8ff49;

    border-style: solid;
```
#### Hasil
![h.border style .jpg](h.border%20style%20.jpg)

#### Kesimpulan
kesimpulannya adalah bahwa program ini digunakan untuk membuat garis tepi solid pada elemen HTML.

### Border-radius

#### Penjelasan
Property border-radius adalah properti CSS yang digunakan untuk mengatur sudut-sudut dari sebuah elemen HTML yang memiliki border, sehingga membuatnya terlihat lebih bulat atau melengkung. Properti ini memungkinkan Anda untuk mengubah sudut-sudut dari border, baik pada border yang berada di sisi luar elemen (seperti pada kotak) maupun pada border yang berada di dalam elemen (seperti pada kotak input atau tombol). Anda dapat menentukan nilai border-radius dalam piksel, persen, atau bahkan menggunakan nilai yang relatif terhadap ukuran elemen tersebut. Dengan menggunakan border-radius, Anda dapat menciptakan tampilan elemen yang lebih estetis dan menarik dalam desain halaman web Anda.

#### Kode Program
```html
<button class="button1">klik aku</button><br><br>

```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 100px;
```
#### Hasil
![h. border radius.png](h.%20border%20radius.png)
#### Kesimpulan
Property border-radius adalah properti CSS yang digunakan untuk mengatur sudut-sudut dari sebuah elemen HTML yang memiliki border, sehingga membuatnya terlihat lebih bulat atau melengkung. Properti ini memungkinkan pengguna untuk menciptakan tampilan elemen yang lebih estetis dan menarik dalam desain halaman web. Anda dapat menentukan nilai border-radius dalam piksel, persen, atau menggunakan nilai yang relatif terhadap ukuran elemen tersebut.



## Margin Margin

### Kode Program html dan css
```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<link rel="stylesheet" href="style.css">

<body background-color="purply">

    <button class="button1">klik aku</button><br><br>

  

</body>

</html>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-bottom: 300px;

   margin-left: 300px;

   margin-right: 300px;

   margin-top: 300px;

  

}
```
### Margin-top

#### Penjelasan
Margin-top adalah properti CSS yang digunakan untuk menentukan jarak atau spasi dari bagian atas sebuah elemen terhadap elemen lainnya di atasnya. Misalnya, ketika Anda ingin memberikan jarak antara sebuah paragraf dengan elemen yang berada di atasnya, Anda bisa menggunakan margin-top. Properti ini memberikan fleksibilitas dalam menata letak elemen-elemen di dalam halaman web, karena Anda dapat mengatur jaraknya menggunakan nilai piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-top: 300px;
```
#### Hasil
![h.margin top.png](h.margin%20top.png)

#### Kesimpulan
Margin-top adalah properti CSS yang digunakan untuk menentukan jarak vertikal dari bagian atas sebuah elemen terhadap elemen di atasnya dalam halaman web. Properti ini memungkinkan pengaturan tata letak yang fleksibel antara elemen-elemen, dengan nilai yang dapat diatur dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain.

### Margin-right

#### Penjelasan
Margin-right adalah properti CSS yang digunakan untuk menentukan jarak (spasi) dari sisi kanan sebuah elemen terhadap elemen terdekat lainnya. Properti ini dapat diatur dalam nilai piksel, persen, atau menggunakan unit lainnya. Penggunaan margin-right memungkinkan pengaturan tata letak (layout) yang tepat antara elemen-elemen dalam hal jarak dari sisi kanan, sehingga memberikan fleksibilitas dalam desain halaman web.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-right: 300px;
```
#### Hasil
![h.margin right.png](h.margin%20right.png)
#### Kesimpulan
Margin-right adalah properti CSS yang digunakan untuk menentukan jarak antara sisi kanan sebuah elemen dan elemen terdekat lainnya dalam hal tata letak halaman web. Ini memungkinkan pengaturan spasi yang tepat antara elemen-elemen, memberikan fleksibilitas dalam desain.

### Margin-left

#### Penjelasan
Margin-left adalah properti CSS yang digunakan untuk menentukan jarak atau spasi dari sisi kiri sebuah elemen terhadap elemen lainnya yang berdekatan di sebelah kirinya dalam halaman web. Misalnya, jika Anda ingin menambahkan jarak antara sebuah gambar dengan teks yang berada di sebelah kiri gambar tersebut, Anda dapat menggunakan margin-left. Properti ini memberikan fleksibilitas dalam menata tata letak elemen di dalam halaman web, karena Anda dapat mengatur jaraknya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan margin-left, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang konsisten dan mudah dibaca.

#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-right: 300px;

  

}
```
#### Hasil
![h.margin bottom (2).png](h.margin%20bottom%20(2).png)

#### Kesimpulan
Margin-left adalah properti CSS yang digunakan untuk menentukan jarak atau spasi dari sisi kiri sebuah elemen terhadap elemen lainnya yang berdekatan di sebelah kirinya dalam halaman web. Properti ini memberikan fleksibilitas dalam menata tata letak elemen dengan mengatur jaraknya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan margin-left, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang konsisten dan mudah dibaca.

### Margin-bottom

#### Penjelasan
Property margin-bottom adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara bagian bawah sebuah elemen dengan elemen lainnya yang berada di bawahnya dalam halaman web. Misalnya, jika Anda ingin menambahkan spasi antara sebuah paragraf dengan elemen yang berada di bawahnya, Anda dapat menggunakan margin-bottom. Properti ini memberikan fleksibilitas dalam mengatur tata letak elemen di halaman web, karena Anda dapat mengatur jaraknya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan margin-bottom, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang konsisten dan mudah dibaca.

#### Kode Program
```html
<button class="button1">klik aku</button><br><br>

```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-bottom: 300px;

  

}
```
#### Hasil
![h.margin bottom (2).png](h.margin%20bottom%20(2).png)

#### Kesimpulan
Property margin-bottom adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara bagian bawah sebuah elemen dengan elemen lainnya yang berada di bawahnya dalam halaman web. Properti ini memberikan fleksibilitas dalam mengatur tata letak elemen di halaman web, dengan nilai jarak yang dapat diatur dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan margin-bottom, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang konsisten dan mudah dibaca.


## Materi Padding

### Kode Program html dan css
```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<link rel="stylesheet" href="style.css">

<body background-color="purply">

    <button class="button1">klik aku</button><br><br>

  

</body>

</html>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-bottom: 300px;

   margin-left: 300px;

   margin-right: 300px;

   margin-top: 300px;

  

   padding-left: 20px;

    padding-bottom: 20px;

    padding-right: 10px;

    padding-top: 10px;

  

}
```
### padding-top

#### Penjelasan
Property padding-top adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara konten sebuah elemen dengan batas atas (top border) dari elemen tersebut. Misalnya, jika Anda ingin menambahkan ruang kosong di bagian atas elemen untuk membuat konten di dalamnya terlihat lebih jauh dari batas atas elemen tersebut, Anda dapat menggunakan padding-top. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web, karena Anda dapat mengatur ruang kosongnya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan padding-top, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;
    
    padding-top: 10px;

}
```
#### Hasil
![h. padding top.png](h.%20padding%20top.png)

#### Kesimpulan
Property padding-top adalah properti CSS yang digunakan untuk menambahkan ruang kosong di bagian atas sebuah elemen, antara konten elemen tersebut dengan batas atas (top border) dari elemen tersebut. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web dengan mengatur ruang kosong menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan padding-top, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.
### padding-bottom

#### Penjelasan
Property padding-bottom adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara konten sebuah elemen dengan batas bawah (bottom border) dari elemen tersebut. Misalnya, jika Anda ingin menambahkan ruang kosong di bagian bawah elemen untuk membuat konten di dalamnya terlihat lebih jauh dari batas bawah elemen tersebut, Anda dapat menggunakan padding-bottom. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web, karena Anda dapat mengatur ruang kosongnya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan padding-bottom, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.

#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;
  
    padding-bottom: 20px;
```
#### Hasil
![h.padding bottom.png](h.padding%20bottom.png)

#### Kesimpulan
Property padding-bottom adalah properti CSS yang digunakan untuk menambahkan ruang kosong di bagian bawah sebuah elemen, antara konten elemen tersebut dengan batas bawah (bottom border) dari elemen tersebut. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web dengan mengatur ruang kosong menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan padding-bottom, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.

### padding-right

#### Penjelasan
Property padding-right adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara konten sebuah elemen dengan batas kanan (right border) dari elemen tersebut. Misalnya, jika Anda ingin menambahkan ruang kosong di bagian kanan elemen untuk membuat konten di dalamnya terlihat lebih jauh dari batas kanan elemen tersebut, Anda dapat menggunakan padding-right. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web, karena Anda dapat mengatur ruang kosongnya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan padding-right, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.

#### Kode Program
```html
<button class="button1">klik aku</button><br><br>
```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-bottom: 300px;

   margin-left: 300px;

   margin-right: 300px;

   margin-top: 300px;

  

    padding-right: 10px;

}
```
#### Hasil
![h. padding right.png](h.%20padding%20right.png)

#### Kesimpulan
Property padding-right adalah properti CSS yang digunakan untuk menambahkan ruang kosong di bagian kanan sebuah elemen, antara konten elemen tersebut dengan batas kanan (right border) dari elemen tersebut. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web dengan mengatur ruang kosong menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan padding-right, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.

### padding-left

#### Penjelasan
Property padding-left adalah properti CSS yang digunakan untuk menentukan jarak atau spasi antara konten sebuah elemen dengan batas kiri (left border) dari elemen tersebut. Misalnya, jika Anda ingin menambahkan ruang kosong di bagian kiri elemen untuk membuat konten di dalamnya terlihat lebih jauh dari batas kiri elemen tersebut, Anda dapat menggunakan padding-left. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web, karena Anda dapat mengatur ruang kosongnya menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain Anda. Dengan menggunakan padding-left, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.
#### Kode Program
```html
<button class="button1">klik aku</button><br><br>

```

```css
button{

    width: 150px;

    height: 50px;

    font-size: 20px;

    background-color: #49d5ff;

    border-width: 2px;

    border-color: #d8ff49;

    border-style: solid;

    border-radius: 20px 0px 20px 0px;

  

   margin-bottom: 300px;

   margin-left: 300px;

   margin-right: 300px;

   margin-top: 300px;

  

   padding-left: 20px;

}
```
#### Hasil
![h. padding left.png](h.%20padding%20left.png)

#### Kesimpulan
Property padding-left adalah properti CSS yang digunakan untuk menambahkan ruang kosong di bagian kiri sebuah elemen, antara konten elemen tersebut dengan batas kiri (left border) dari elemen tersebut. Properti ini memberikan fleksibilitas dalam desain tata letak elemen di dalam halaman web dengan mengatur ruang kosong menggunakan nilai dalam piksel, persen, atau unit lainnya sesuai kebutuhan desain. Dengan menggunakan padding-left, Anda dapat mencapai tata letak yang sesuai dengan desain yang diinginkan, memastikan tampilan halaman web yang lebih terstruktur dan teratur.


# studi kasus
## Deskripsi Kasus
Program di atas adalah halaman HTML sederhana yang mencakup beberapa elemen HTML seperti gambar, teks, dan tombol. Selain itu, terdapat juga sebuah file CSS eksternal yang digunakan untuk memperindah tampilan halaman.

Berikut deskripsi dari setiap bagian program tersebut:

1. *Elemen HTML*: Terdapat elemen-elemen HTML seperti `<span>`, `<img>`, `<p>`, dan `<button>`. Elemen `<span>` digunakan untuk mengelompokkan beberapa elemen bersama-sama, sedangkan <img> digunakan untuk menampilkan gambar. Elemen `<p>` digunakan untuk menampilkan teks paragraf, dan `<button>` digunakan untuk membuat tombol.
2. *CSS Eksternal*: Terdapat juga file CSS eksternal yang disematkan menggunakan tag `<link>` di dalam elemen `<head>`. File CSS ini disebut "latian.css" dan digunakan untuk mengatur tampilan elemen-elemen HTML di halaman.
3. *Pengaturan CSS*: Di dalam file CSS "latian.css", terdapat beberapa aturan CSS yang mengatur tampilan elemen-elemen HTML. Beberapa properti yang diatur antara lain warna teks, ukuran font, margin, border, dan warna latar belakang.
4. *Tampilan Halaman*: Halaman HTML ini memiliki latar belakang warna ungu ("purple") yang didefinisikan melalui atribut bgcolor pada elemen `<body>`. Selain itu, terdapat teks berwarna putih ("white") dengan ukuran font besar yang ditampilkan di tengah halaman. Gambar samurai juga ditampilkan di sebelah kanan halaman dengan sedikit efek margin dan border.
5. *Tombol*: Terdapat tombol dengan teks "klik aku" yang memiliki warna teks oranye ("orange") dan latar belakang ungu ("purple").

## Langkah-Langkah

1. cara pertama yaitu ganti latar belakang menjadi ungu dengan cara menambahkan bgcolor di dalam tag `<body>`
2. kaitkan link html ke css dengan cara `<link rel="stylesheet" href="latian.css">` agar bisa memodifikasi atau desain program melalui css
3. buatlah tag `<span>` dan masukkan gambar dengan menggunakan tag `<img src="samurai.jpg" width="200px" height="200px" align="right">` juga masukkan lebar dan tinggi dari gambar tersebut
4. setelah memasukkan gambar buatlah teks selamat datang di web Farhan menggunakan tag `<p>` dan di dalam tag `<p>` juga ada tag `<b>` dan <br>  contoh

```html
`<span> <img src="samurai.jpg" width="200px" height="200px" align="right">

        <p>selamat datang <br>

         di<b> web Farhan</b></p>

        </span>`

```

5. sesudah itu buatlah tombol menggunakan tag `<button>` yang isinya klik aku
6. lanjut ke css,kita akan memodifikasi tag `<p>` dan mengubah nya seperti warna teks nya menjadi putih,ukuran font nya menjadi 75px dan menggunakan margin untuk mengubah posisinya . contoh program

```css
css
 p {
    color: white;
    font-size: 75px;
    margin-top: 150px;
    margin-bottom: 100px;
    margin-left: 50px;
    margin-right: 100px;
    }
```

7. selanjutnya kita akan memodifikasi tag <img> atau gambarnya dan mengubahnya menggunakan margin,border,dan border radius.ukuran margin-right nya adalah 200px,margin top nya adalah -30px dan didalam border ada ukuran style dan warna nya,dan gunanya border radius adalah untuk membulatkan gambar dengan memberikan ukuran 150px .contoh program:

```css
img {

    margin-right: 200px;

    margin-top: -30px;

    border: 5px solid white;

    border-radius: 150px 150px;

```

8. terakhir kita akan memodifikasi tag `<button>` dengan mengubah warna teksnya menjadi orange,latar belakangnya menjadi warna ungu,lebar nya 100px tingginya 50px,juga warna dari bordernya menjadi warna orange,dan mengubah posisinya dengan menggunakan margin dan ukuran margin nya adalah margin-top -100px margin-left 400px.contoh program:

```css
button {

    color: orange;

    background-color: purple;

    width: 100px;

    height: 50px;

    border-color: orangered;

    margin-top: -100px;

    margin-left: 400px;

}
```

9. Selesai

### Penjelasan HTML

- `<!DOCTYPE html>`: Mendefinisikan jenis dokumen HTML.

- `<html lang="en">`: Mengawali dokumen HTML dengan bahasa Inggris.

- `<head>`: Bagian kepala dokumen yang berisi informasi meta dan judul.

- `<meta charset="UTF-8">`: Mendefinisikan karakter set dokumen sebagai UTF-8.

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Mengatur tampilan responsif di perangkat dengan lebar layar yang berbeda.

- `<title>Document</title>`: Judul halaman web.

- `<link rel="stylesheet" href="tampilanweb.css">`: Menghubungkan halaman HTML dengan file CSS eksternal.

- `<body bgcolor="purple">`: Mengatur warna latar belakang halaman menjadi ungu (purple).

- `<span>`: Membuat bagian teks menjadi bagian inline.

- `<div class="text">`: Membuat sebuah div dengan kelas "text" yang berisi teks "Selamat datang".

- `<span class="text2">`: Membuat sebuah span dengan kelas "text2" yang berisi teks "di web Rahmat".

- `<img src="- 00_00.jpeg" class="foto">`: Menampilkan gambar dengan nama "naon.jpg" dengan kelas "foto".

- `<button class="tombol">Klik ini</button>`: Membuat sebuah tombol dengan teks "Klik ini" dan kelas "tombol".

### Penjelasan CSS

- `.text` dan `.text2`: Mengatur gaya teks untuk kelas "text" dan "text2". Menggunakan font Times New Roman, ukuran font 30mm, dan warna putih.

- `.foto`: Mengatur tampilan gambar dengan kelas "foto". Menerapkan display block, membuat sudut gambar menjadi bulat dengan border-radius, mengatur lebar dan tinggi gambar, mengatur posisi gambar dengan margin-left dan margin-top, serta memberikan border putih dengan lebar 10px dan gaya solid.

- `.tombol`: Mengatur tampilan tombol dengan kelas "tombol". Memberikan warna teks dan border oranye, mengatur lebar dan tinggi tombol, mengatur tampilan tombol dengan display block, memberikan warna latar belakang transparan, mengatur border dengan lebar 3px dan gaya solid, mengatur posisi tombol dengan margin-top dan margin-left, serta mengatur ukuran font.

### Kode Program
```HTML

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

    <link rel="stylesheet" href="tampilanweb.css">

</head>

<body bgcolor="purple">

    <span>

        <div class="text">Selamat datang

        </div>

    </span><br>

    <span class="text2">di web Raihan</span><br>

    <img src="- 00_00.jpeg" class="foto">

    <button class="tombol">Klik aku</button>

</body>

</html>

```

  

```CSS

.text{

    font-family: 'Times New Roman';

    font-size: 30mm;

    color: white;

}

  

.text2{

    font-family: 'Times New Roman';

    font-size: 30mm;

    color: white;

}

  

.foto{

    display: block;

    border-radius: 1000px;

    width: 400px;

    height: 400px;

    margin-left: 735px;

    margin-top: -215px;

    border-width: 10px;

    border-color: white;

    border-style: solid;

}

  

.tombol{

    color: orangered;

    border-color: orangered;

    width: 160px;

    height: 85px;

    display: block;

    background-color: transparent;

    border-width: 3px;

    border-style: solid;

    margin-top: -200px;

    margin-left: 13cm;

    font-size: 20px;

}

```
## Hasil pengerjaan
![h.boxmodel.png](h.boxmodel.png)
# Pseudo-clesses

## Hover 

### Penjelasan
Pernyataan kode program tersebut menggunakan pseudo-class :hover untuk menargetkan perilaku saat kursor berada di atas elemen tombol (button). Ketika kursor berada di atas tombol tersebut, properti color digunakan untuk mengatur warna teks tombol, di mana nilai yang ditetapkan adalah "#FF00FF", yang merupakan kode warna untuk warna magenta.
### Kode Program
```css.btn:hover {

        background-color: #45a049;

        color: #FF0000;

    }
```

### Hasil
![hover.png](hover.png)
### Kesimpulan
Program tersebut akan mengubah warna teks tombol menjadi magenta saat kursor diarahkan ke atas (hover) pada tombol tersebut. Ini memberikan umpan balik visual kepada pengguna bahwa tombol tersebut bisa diklik atau interaktif. Misalnya, jika Anda memiliki tombol HTML seperti <button>Klik!</button>, saat kursor diarahkan ke atas tombol tersebut, warna teksnya akan berubah menjadi magenta.


## active
### Penjelasan
Pernyataan tersebut menggunakan pseudo-class :active untuk menargetkan perilaku saat tombol sedang dalam keadaan aktif, yaitu saat tombol tersebut sedang ditekan oleh pengguna. Ketika tombol tersebut sedang ditekan, properti color digunakan untuk mengatur warna teks tombol, di mana nilai yang ditetapkan adalah "#0000FF", yang merupakan kode warna untuk warna biru.

### Kode Program
```css
button:active {

    color: #FF0000;

}
```

### Hasil
![active.png](active.png)
### Kesimpulan
Program tersebut akan mengubah warna teks tombol menjadi biru saat tombol tersebut sedang dalam keadaan aktif, yaitu saat tombol ditekan oleh pengguna. Ini memberikan umpan balik visual kepada pengguna bahwa tindakan yang mereka lakukan sedang berlangsung. Misalnya, jika Anda memiliki tombol HTML seperti `<button>Klik!</button>`, saat tombol tersebut ditekan oleh pengguna, warna teksnya akan berubah menjadi biru.




## Link

### Penjelasan
Pernyataan tersebut menggunakan pseudo-class :link untuk menargetkan perilaku saat tombol tersebut berfungsi sebagai link (google). Saat tombol tersebut di klik otomatis akan di arahkan ke google , properti color digunakan untuk mengatur warna teks tombol, di mana nilai yang ditetapkan adalah "#FF0000", yang merupakan kode warna untuk warna merah.

### Kode Program
```css
.btn-link:active {

        background-color: #45a049;

    }
```

### Hasil
![link.png](link.png)


#### Kesimpulan
Program tersebut akan mengubah warna teks tombol menjadi merah saat tombol tersebut dianggap sebagai link yang belum dikunjungi. Ini memberikan umpan balik visual kepada pengguna bahwa tombol tersebut merupakan tautan yang dapat diklik. Misalnya, jika Anda memiliki tombol HTML seperti `<button>Klik!</button>` yang ditautkan ke halaman lain, saat tombol tersebut belum pernah dikunjungi oleh pengguna, warna teksnya akan berubah menjadi merah.

### visited

### Penjelesan
Pernyataan tersebut menggunakan pseudo-class :visited untuk menargetkan perilaku saat tombol tersebut telah dikunjungi oleh pengguna. Saat tombol tersebut telah dikunjungi, properti color digunakan untuk mengatur warna teks tombol, di mana nilai yang ditetapkan adalah "#00FF00", yang merupakan kode warna untuk warna hijau.

### Kode Program
```css
.btn-visited:visited {

        color: purple;

    }
```

### Hasil
![button.visited.png](button.visited.png)

### Kesimpulan
Program tersebut akan mengubah warna teks tombol menjadi hijau saat tombol tersebut telah dikunjungi oleh pengguna. Ini memberikan umpan balik visual kepada pengguna bahwa mereka telah mengunjungi tombol tersebut. Misalnya, jika Anda memiliki tombol HTML seperti <button>Klik!</button> yang telah dikunjungi oleh pengguna sebelumnya, warna teksnya akan berubah menjadi hijau.


# Transitions
## Transition 
### Penjelasan
Pernyataan tersebut menggunakan pseudo-class :hover untuk menargetkan perilaku saat kursor berada di atas elemen tombol (button). Ketika kursor berada di atas tombol tersebut, terdapat beberapa properti CSS yang berubah:

1. background-color: red;: Properti ini mengubah warna latar belakang tombol menjadi merah saat kursor diarahkan ke atas tombol.
2. width: 200px;: Properti ini mengubah lebar tombol menjadi 200 piksel saat kursor diarahkan ke atas tombol.
3. color: white;: Properti ini mengubah warna teks tombol menjadi putih saat kursor diarahkan ke atas tombol.
4. transition: all 0.3s ease-in;: Properti ini mengatur efek transisi untuk semua perubahan yang terjadi pada tombol saat kursor diarahkan ke atas. Transisi ini berlangsung selama 0.3 detik dan dimulai dengan kecepatan yang lambat.

 Nilai yang digunakan dalam properti transition terdiri dari tiga bagian:

1. all: Ini adalah nilai yang menunjukkan bahwa semua properti CSS pada elemen akan mengalami transisi. Artinya, ketika ada perubahan pada elemen, semua properti CSS akan diterapkan transisi.
    
2. 0.3s: Ini adalah durasi dari transisi, di mana "0.3s" menunjukkan bahwa transisi akan berlangsung selama 0.3 detik.
    
3. ease-in: Ini adalah fungsi waktu yang menentukan bagaimana kecepatan transisi berubah seiring waktu. Dalam kasus ini, ease-in menghasilkan transisi yang lambat pada awalnya, lalu semakin cepat mendekati akhir transisi.
### Kode Program


```css
button:hover {

    background-color: red;

    width: 200px;

    color: white;

    transition: all 0.3s ease-in;
}
```

### Hasil

#### Before
![h.trasition before.png](h.trasition%20before.png)

#### After
![h.trasition after.png](h.trasition%20after.png)
### Kesimpulan
Kesimpulan: Program tersebut akan mengubah tampilan tombol saat kursor diarahkan ke atasnya. Tombol akan memiliki latar belakang merah, lebar 200 piksel, dan teks berwarna putih. Perubahan-perubahan tersebut akan ditampilkan dengan efek transisi yang berlangsung selama 0.3 detik dan dimulai dengan kecepatan yang lambat. Misalnya, jika Anda memiliki tombol HTML seperti <button>Click Me</button>, saat kursor diarahkan ke atas tombol tersebut, tampilannya akan berubah sesuai dengan aturan CSS di atas.
## Transition-delay
### Penjelasan
transition-delay: 1s;: Properti ini mengatur penundaan transisi selama 1 detik sebelum perubahan dimulai.
### Kode Program


```css
button:hover {

    background-color: red;

    width: 200px;

    color: white;

    transition-duration: 2s;

    transition-delay: 1s;
    ```

### Hasil

#### Before
![h.trasition-delay before.png](h.trasition-delay%20before.png)


#### After
![h.trasition-delay after.png](h.trasition-delay%20after.png)

### Kesimpulan
Program tersebut akan membuat efek transisi pada tombol saat kursor diarahkan ke atasnya. Tombol akan memiliki latar belakang merah, lebar 200 piksel, dan teks berwarna putih. Perubahan tersebut akan ditampilkan dengan efek transisi yang dimulai setelah 1 detik penundaan dan berlangsung selama 2 detik. Misalnya, saat kursor diarahkan ke atas tombol, perubahan tampilan tombol akan dimulai setelah 1 detik dan akan berlangsung selama 2 detik dengan transisi yang halus.
## Transition-duration
### Penjelasan
Properti transition-duration digunakan untuk menentukan durasi dari transisi yang diterapkan pada elemen. Dalam hal ini, nilai yang ditetapkan adalah "2s", yang berarti transisi akan berlangsung selama 2 detik.
### Kode Program

css
transition-duration: 2s;

### Hasil
![duration.png](duration.png)

### Kesimpulan
Kesimpulan: Program tersebut akan membuat efek transisi pada elemen-elemen yang menerapkan transisi untuk memiliki durasi selama 2 detik. Ini berarti perubahan yang terjadi pada properti CSS yang ditentukan untuk transisi akan berlangsung secara halus selama 2 detik ketika terjadi perubahan pada elemen tersebut
## Transition-property
### Penjelasan
transition-property: width 300px;: Menentukan properti mana yang akan mengalami transisi dan nilai dari properti tersebut selama transisi berlangsung. Dalam hal ini, saat tombol di-hover, transisi hanya diterapkan pada lebar (width) tombol dan lebar tombol akan berubah menjadi 300 piksel selama 2 detik.
### Kode Program
```css
button:hover {

    background-color: red;

    width: 200px;

    color: white;

    transition-duration: 2s;

    transition-property: width 300px;

```
  
### Hasil
![Transition-property.jpeg](Transition-property.jpeg)

### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat kursor diarahkan ke atasnya dengan efek transisi. Tombol akan berubah warna latar belakang menjadi merah, lebar tombol menjadi 200 piksel, dan warna teks tombol menjadi putih. Transisi hanya diterapkan pada perubahan lebar tombol, dengan lebar tombol yang berubah menjadi 300 piksel selama 2 detik. Ini memberikan efek visual yang halus dan menarik saat tombol di-hover oleh pengguna.
## Transition-timing-function
### Penjelasan
transition-timing-function: all 2s ease-in;: Menentukan fungsi waktu transisi untuk semua properti yang mengalami transisi. Dalam hal ini, transisi akan memiliki durasi 2 detik dan efek "ease-in", yang berarti perubahan akan dimulai dengan kecepatan yang lambat dan semakin meningkat seiring waktu.
### Kode Program


```css
button:hover {

    background-color: red;

    width: 200px;

    color: white;

    transition-timing-function: all 2s ease-in ;

  

}
```

### Hasil
![Transition-timing-function.jpeg](AsetTransition-timing-function.jpeg)
### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat kursor diarahkan ke atasnya dengan efek transisi. Tombol akan berubah warna latar belakang menjadi merah, lebar tombol menjadi 200 piksel, dan warna teks tombol menjadi putih. Efek transisi akan memiliki durasi 2 detik dan akan dimulai dengan kecepatan yang lambat. Ini memberikan efek visual yang halus dan menarik saat tombol di-hover oleh pengguna.

# Studio kasus (Transition)

## Kode Program

```html

<!DOCTYPE html>

<html lang="en">

<head>

    <title>Document</title>

    <link rel="stylesheet" href="tugasflex.css">

</head>

<body bgcolor="purple">

    <div class="main-container">

    <div class="hero-container">

        <div class="item p">

            <p> Selamat Datang <br>

            di <b>Web RAIHAN</b> </P>

            <button> klik saya </button>

        </div>

        <div>

            <span class="img">

                <img src="./- 00_00.jpeg" width="350px" height="350px" align="right">

            </span>

    </div>

    </div>

</div>

</body>

</html>

```

## Penjelasan HTML

- `<!DOCTYPE html>`, `<html lang="en">`, `<head>`, `<title>Document</title>`: Bagian awal dari dokumen HTML yang mendefinisikan tipe dokumen, bahasa, dan judul halaman.

- `<style>`: Mulai dari bagian CSS yang didefinisikan dalam dokumen HTML.

- `<body bgcolor="purple">`: Memberikan warna latar belakang halaman dengan atribut `bgcolor`.

- `<div class="main-container">`, `<div class="hero-container">`: Membuat dua div yang bertindak sebagai wadah utama dan sub-wadah.

- `<div class="item p">`: Sebuah div dengan kelas `item` dan `p` yang berisi teks dan tombol.

- `<p> Selamat Datang <br> di <b>Web RAIHAN</b> </p>`: Menampilkan teks "Selamat Datang" di web Rahmat.

- `<button> klik saya </button>`: Menampilkan tombol dengan teks "klik saya".

- `<img src="./- 00_00.jpeg" width="350px" height="350px" align="right">`: Menampilkan gambar dengan atribut `src`, `width`, `height`, dan `align`.

  

```CSS

 .main-container {

    display:flex;

    height: 100vh;

    justify-content: space-around ;

    align-items: center  ;

    background-color: purple;

}

  

.hero-container {

    display:flex;

    height: 100vh;

    justify-content: space-between;

    align-items: center  ;

    background-color: purple;

}

  

.item {

    width: 500px;

    height: 250px;

    background-color: none;

}

  

 .p{

    font-size: 65px;

    font-family: 'arial';

    margin-top: 40px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: aliceblue;

}

  

 img {

    margin-right: 100px;

    margin-top: -10px;  

    border: 10px solid white;

    border-radius: 1500px 1500px;

}

  

 button {

    background-color: purple;

    width: 150px;

    height: 50px;

    border-width: 2px;

    color: orange;

    border-color: orange;

    margin-bottom: 20px;

    margin-left: 290px;  

    box-shadow: 20px;

}

  

 button:hover {

    background-color: orange;

    color: white;

    width: 150px;

    transition: all 0.3s esse-in;

    cursor: pointer;

}

  

 button:active {

    transform:scale(0.5);

}

```

## Penjelasan CSS

- `.main-container`, `.hero-container`: Membuat tata letak menggunakan flexbox dengan menentukan dimensi, warna latar belakang, dan penempatan.

- `.item`: Mengatur dimensi dan warna latar belakang untuk item.

- `.p`: Mengatur gaya teks untuk paragraf.

- `img`: Mengatur margin dan gaya border untuk gambar.

- `button`: Mengatur gaya untuk tombol, termasuk dimensi, warna latar belakang, warna teks, dan margin.

- `button:hover`: Mengatur gaya tombol saat dihover dengan mengubah warna latar belakang, warna teks, dan ukuran tombol.

- `button:active`: Mengatur gaya tombol saat ditekan dengan melakukan transformasi scaling

## Hasil

### Before
![hasil.possition.png](Aset%20CSS/hasil.possition.png)

### After
![After.possition.png](Aset%20CSS/After.possition.png)

# Transform
## Transform scale
### Penjelasan
 button:active adalah pseudo-class CSS yang menargetkan perilaku tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna.

transform: scale(0.75);: Properti ini menggunakan fungsi transformasi scale() untuk mengubah ukuran tombol. Saat tombol sedang ditekan (active), tombol akan diperkecil sebanyak 0.75 kali dari ukuran aslinya. Ini akan memberikan efek visual seperti tombol yang "ditekan" ke dalam saat ditekan oleh pengguna.

### Kode Program

```css
button:active {
    transform: scale(0.75);

```
### Hasil
![[scarlet.jpeg]]


### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi scale() digunakan untuk memperkecil ukuran tombol menjadi 0.75 kali ukuran aslinya saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform scaleX
### Penjelasan
transform: scaleX(0.5);: Properti ini menggunakan fungsi transformasi scaleX() untuk mengubah skala lebar tombol. Saat tombol sedang ditekan (active), tombol akan diperkecil sebanyak setengah (0.5) dari lebar aslinya. Ini akan memberikan efek visual seperti tombol yang "ditekan" ke dalam secara horizontal saat ditekan oleh pengguna.
### Kode Program


```css
button:active {

    transform: scaleX(0.5);

}

```
### Hasil
![[scarlett.jpeg]]
### Kesimpulan
*Kesimpulan*: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi scaleX() digunakan untuk memperkecil lebar tombol menjadi setengah dari lebar aslinya saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform rotate
### Penjelasan
transform: rotate(45deg);: Properti ini menggunakan fungsi transformasi rotate() untuk memutar tombol sebesar 45 derajat saat tombol sedang ditekan (active). Ini akan memberikan efek visual seperti tombol yang diputar sebesar 45 derajat saat ditekan oleh pengguna.
### Kode Program
```css
button:active {

    transform: rotate(45deg);

}
```
### Hasil
![[rolate.jpeg]]
### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi rotate() digunakan untuk memutar tombol sebesar 45 derajat saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform skewX
### Penjelasan
transform: skewx(-25deg);: Properti ini menggunakan fungsi transformasi skewx() untuk memiringkan tombol sebesar -25 derajat secara horizontal (ke samping) saat tombol sedang ditekan (active). Nilai negatif (-25deg) mengindikasikan bahwa miringan akan berlawanan arah jarum jam. Ini akan memberikan efek visual seperti tombol yang miring ke kiri saat ditekan oleh pengguna.
### Kode Program
```css
button:active {

    transform: skewx(-25deg);

}
```
### Hasil
![[skewX.jpeg]]
### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi skewx() digunakan untuk memiringkan tombol sebesar -25 derajat secara horizontal saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform skew
### Penjelasan
transform: skew(20deg, 5deg);: Properti ini menggunakan fungsi transformasi skew() untuk memiringkan tombol sebesar 20 derajat secara horizontal (ke samping) dan 5 derajat secara vertikal (ke atas atau ke bawah) saat tombol sedang ditekan (active). Ini akan memberikan efek visual seperti tombol yang terlihat miring saat ditekan oleh pengguna.
### Kode Program


```css
button:active {

    transform: skew(20deg, 5deg);

}
```
### Hasil
![[skew.jpeg]]
### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi skew() digunakan untuk memiringkan tombol sebesar 20 derajat secara horizontal dan 5 derajat secara vertikal saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform translate
### Penjelasan
transform: translate(5px, 12px);: Properti ini menggunakan fungsi transformasi translate() untuk memindahkan (translasi) posisi tombol sejauh 5 piksel ke kanan dan 12 piksel ke bawah saat tombol sedang ditekan (active). Ini akan memberikan efek visual seperti tombol yang bergeser ke arah kanan dan ke bawah saat ditekan oleh pengguna
### Kode Program

css
button:active {

    transform: translate(5px, 12px);

}

### Hasil
![[Translet.jpeg]]
### Kesimpulan
*Kesimpulan*: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi translate() digunakan untuk memindahkan posisi tombol sejauh 5 piksel ke kanan dan 12 piksel ke bawah saat tombol ditekan, memberikan efek visual yang menarik dan memberi umpan balik kepada pengguna bahwa tombol telah ditekan.
## Transform matrix
### Penjelasan
- transform: matrix(0.7, -0.5, 0.5, 0.4, 0.5, 0.7);: Properti ini menggunakan fungsi transformasi matrix() untuk menerapkan transformasi 2D kompleks pada tombol saat tombol sedang ditekan (active). Matriks transformasi 2D yang diberikan memiliki nilai sebagai berikut:
    - Kolom pertama: scaleX = 0.7, skewY = -0.5.
    - Kolom kedua: skewX = 0.5, scaleY = 0.4.
    - Kolom ketiga: translateX = 0.5, translateY = 0.7.

Ini akan memberikan efek visual transformasi kompleks pada tombol saat ditekan
### Kode Program

css
button:active {

    transform: matrix(0.7, -0.5, 0.5, 0.4, 0.5, 0.7);

}

### Hasil
![[matrix.jpeg]]
### Kesimpulan
Kesimpulan: Program tersebut mengatur tampilan tombol saat tombol sedang dalam keadaan aktif, yaitu saat tombol sedang ditekan oleh pengguna. Efek transformasi matriks kompleks diberikan untuk memberikan perubahan yang lebih rumit pada tombol saat tombol ditekan. Hal ini dapat memberikan efek visual yang menarik dan unik tergantung pada nilai matriks yang diberikan.
 

# Flexbox

## Display Flex

`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya dengan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan lain-lain.

### Kode Program

```css

.box-container{

  display: flex; /* Item-item di dalam flex container juga menjadi flex items */

}

```

### Hasil

![[Catatan CSS/Aset CSS/fb.png]]

### Kesimpulan

`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya menggunakan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan properti lainnya yang terkait dengan model tata letak flexbox.

## Flex-Direction

- `flex-direction: column;`: Mengatur tata letak dari flex container menjadi vertikal, sehingga flex items diatur dari atas ke bawah.

- `flex-direction: column-reverse;`: Mengatur tata letak dari flex container menjadi vertikal terbalik, sehingga flex items diatur dari bawah ke atas.

- `flex-direction: row;`: Mengatur tata letak dari flex container menjadi horizontal, sehingga flex items diatur dari kiri ke kanan.

- `flex-direction: row-reverse;`: Mengatur tata letak dari flex container menjadi horizontal terbalik, sehingga flex items diatur dari kanan ke kiri.

### Kode Program

```css

.container{

  flex-direction: column;

}

```

### Hasil
![Aset CSS/fd.png](Aset%20CSS%20pt2/fd.png)

### Kesimpulan

Setiap properti flex-direction mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property.

Contoh`column` untuk tata letak vertikal dari atas ke bawah.

`column-reverse` untuk tata letak vertikal terbalik dari bawah ke atas. `row` untuk tata letak horizontal dari kiri ke kanan.`row-reverse` untuk tata letak horizontal terbalik dari kanan ke kiri.

## Align-Items

- `align-items: center;`: Flex items akan diatur di tengah-tengah sumbu silang dari flex container.

- `align-items: flex-start;`: Flex items akan diatur pada awal sumbu silang dari flex container.

- `align-items: flex-end;`: Flex items akan diatur pada akhir sumbu silang dari flex container.

- `align-items: baseline;`: Flex items akan diatur sedemikian rupa sehingga garis dasar dari teks pada masing-masing item berada pada level yang sama.

- `align-items: stretch;`: Flex items akan diperpanjang untuk mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.

### Kode Program

```css

.box-container{

  align-items:center ;

}

```

### Hasil

![[Catatan CSS/Aset CSS/ai.png]]

### Kesimpulan

Setiap properti align-items mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property.

Contoh`center` untuk menempatkan flex items di tengah-tengah sumbu silang.`flex-start` untuk menempatkan flex items di awal sumbu silang.`flex-end` untuk menempatkan flex items di akhir sumbu silang.`baseline` untuk menempatkan flex items sehingga garis dasar teks masing-masing item berada pada level yang sama.`stretch` untuk memperpanjang flex items sehingga mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.

## Justify-Content

 - `justify-content: flex-start;`: Mengatur fleks item ditempatkan di bagian awal (mulai) dari sumbu utama flex container.

- `justify-content: flex-end;`: Mengatur fleks item ditempatkan di bagian akhir (akhir) dari sumbu utama flex container.

- `justify-content: center;`: Mengatur fleks item ditempatkan di tengah-tengah sumbu utama flex container.

- `justify-content: space-around;`: Mengatur fleks item didistribusikan secara merata di sekitar sumbu utama flex container, dengan ruang yang sama di antara mereka.

- `justify-content: space-between;`: Mengatur fleks item didistribusikan secara merata di sepanjang sumbu utama flex container, dengan ruang yang sama di antara fleks item pertama dan terakhir, tetapi tidak ada ruang di antara fleks item yang berdekatan.

### Kode Program

```css

.box-container{

  justify-content: center ;

}

```

### Hasil
![[Catatan CSS/Aset CSS/jsc.png]]

### Kesimpulan

Setiap properti justify-Content mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property.

Contoh`flex-start` untuk menempatkan flex items di awal (mulai) sumbu utama.`flex-end` untuk menempatkan flex items di akhir (akhir) sumbu utama.`center` untuk menempatkan flex items di tengah-tengah sumbu utama.`space-around` untuk mendistribusikan flex items secara merata di sekitar sumbu utama dengan ruang yang sama di antara mereka.`space-between` untuk mendistribusikan flex items secara merata di sepanjang sumbu utama dengan ruang yang sama di antara flex items pertama dan terakhir, tetapi tidak ada ruang di antara flex items yang berdekatan.

  

## Studi Kasus(Flex Box)

### Penjelasan HTML

- `<!DOCTYPE html>`: Mendefinisikan jenis dokumen HTML.

- `<html lang="en">`: Mengawali dokumen HTML dengan bahasa Inggris.

- `<head>`: Bagian kepala dokumen yang berisi informasi meta dan judul.

- `<meta charset="UTF-8">`: Mendefinisikan karakter set dokumen sebagai UTF-8.

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Mengatur tampilan responsif di perangkat dengan lebar layar yang berbeda.

- `<title>Document</title>`: Judul halaman web.

- `<link rel="stylesheet" href="tampilanweb.css">`: Menghubungkan halaman HTML dengan file CSS eksternal.

- `<body bgcolor="purple">`: Mengatur warna latar belakang halaman menjadi ungu (purple).

- `<span>`: Membuat bagian teks menjadi bagian inline.

- `<div class="text">`: Membuat sebuah div dengan kelas "text" yang berisi teks "Selamat datang".

- `<span class="text2">`: Membuat sebuah span dengan kelas "text2" yang berisi teks "di web Rahmat".

- `<img src="naon.jpg" class="foto">`: Menampilkan gambar dengan nama "naon.jpg" dengan kelas "foto".

- `<button class="tombol">Klik ini</button>`: Membuat sebuah tombol dengan teks "Klik ini" dan kelas "tombol".

### Penjelasan CSS

- `.text` dan `.text2`: Mengatur gaya teks untuk kelas "text" dan "text2". Menggunakan font Times New Roman, ukuran font 30mm, dan warna putih.

- `.foto`: Mengatur tampilan gambar dengan kelas "foto". Menerapkan display block, membuat sudut gambar menjadi bulat dengan border-radius, mengatur lebar dan tinggi gambar, mengatur posisi gambar dengan margin-left dan margin-top, serta memberikan border putih dengan lebar 10px dan gaya solid.

- `.tombol`: Mengatur tampilan tombol dengan kelas "tombol". Memberikan warna teks dan border oranye, mengatur lebar dan tinggi tombol, mengatur tampilan tombol dengan display block, memberikan warna latar belakang transparan, mengatur border dengan lebar 3px dan gaya solid, mengatur posisi tombol dengan margin-top dan margin-left, serta mengatur ukuran font.

### Kode Program

```HTML

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

    <link rel="stylesheet" href="tampilanweb.css">

</head>

<body bgcolor="purple">

    <span>

        <div class="text">Selamat datang

        </div>

    </span><br>

    <span class="text2">di web Rahmat</span><br>

    <img src="naon.jpg" class="foto">

    <button class="tombol">Klik ini</button>

</body>

</html>

```

  

```CSS

.text{

    font-family: 'Times New Roman';

    font-size: 30mm;

    color: white;

}

  

.text2{

    font-family: 'Times New Roman';

    font-size: 30mm;

    color: white;

}

  

.foto{

    display: block;

    border-radius: 1000px;

    width: 400px;

    height: 400px;

    margin-left: 735px;

    margin-top: -215px;

    border-width: 10px;

    border-color: white;

    border-style: solid;

}

  

.tombol{

    color: orangered;

    border-color: orangered;

    width: 160px;

    height: 85px;

    display: block;

    background-color: transparent;

    border-width: 3px;

    border-style: solid;

    margin-top: -200px;

    margin-left: 13cm;

    font-size: 20px;

}

```

### Hasil
![fleckbox.png](fleckbox.png)

### Kesimpulan

# Position

## Position Relative

### Penjelasan

- Dalam HTML, kita memiliki sebuah div dengan kelas `.container` yang berisi tiga div dengan kelas `.box`.

- Dalam CSS, kita menerapkan `position: relative` pada `.container` untuk membuatnya menjadi referensi bagi posisi kotak-kotak anaknya yang memiliki `position: absolute`.

- Setiap kotak diberi properti `position: absolute` untuk memungkinkan kita menentukan posisi mereka relatif terhadap posisi normalnya.

- Properti `top` dan `left` diberikan pada masing-masing kotak untuk menentukan jarak vertikal dan horizontal dari posisi normalnya.

### Kode Program

```css

.container {

  position: relative;

  width: 400px;

  height: 200px;

  border: 2px solid #333;

}

  

.box {

  position: relative;

  width: 100px;

  height: 100px;

  background-color: #333;

  color: #fff;

  text-align: center;

  line-height: 100px;

}

```

### Hasil
![Aset CSS pt2/prl.png](Aset%20CSS%20pt2/prl.png)

### Kesimpulan

- Ketika sebuah elemen diberi `position: relative`, itu akan tetap berada dalam aliran dokumen normal, tetapi kita dapat menggunakan properti `top`, `right`, `bottom`, atau `left` untuk menyesuaikan posisinya relatif terhadap posisi normalnya.

- Ini berguna ketika kita ingin menyesuaikan posisi sebuah elemen tetapi tetap mempertahankan ruangnya dalam aliran dokumen normal.

- Elemen-elemen dengan `position: relative` akan mempengaruhi posisi elemen lain dalam dokumen.

## Position Absolute

### Penjelasan

- Dalam HTML, kita memiliki sebuah div dengan kelas `.container` yang berisi tiga div dengan kelas `.box`.

- Dalam CSS, kita menerapkan `position: relative` pada `.container` untuk membuatnya menjadi referensi bagi posisi kotak-kotak yang memiliki `position: absolute`.

- Setiap `.box` diberi properti `position: absolute` untuk memungkinkan kita menentukan posisi mereka relatif terhadap `.container`.

- Properti `top` dan `left` diberikan pada masing-masing `.box` untuk menentukan jarak vertikal dan horizontal dari posisi `.container`.

### Kode Program

```css

.container {

  position: absolute;

  width: 400px;

  height: 200px;

  border: 2px solid #333;

}

  

.box {

  position: absolute; /* Menggunakan posisi absolut */

  width: 100px;

  height: 100px;

  background-color: #333;

  color: #fff;

  text-align: center;

  line-height: 100px;

}

```

### Hasil
![Aset CSS pt2/pal.png](Aset%20CSS%20pt2/pal.png)

### Kesimpulan

- Ketika sebuah elemen diberi `position: absolute`, itu akan dihapus dari aliran dokumen normal dan diposisikan relatif terhadap kontainer terdekat yang memiliki `position: relative`.

- Ini berguna ketika kita ingin menempatkan elemen secara spesifik di dalam kontainer atau dalam hubungan terhadap elemen lain tanpa memengaruhi layout aliran dokumen.

- Elemen-elemen dengan `position: absolute` tidak mempengaruhi posisi elemen lain dalam dokumen, kecuali elemen yang memiliki `position: relative` dan menjadi kontainernya.

## Position Fixed

### Penjelasan
`position: fixed` adalah salah satu properti CSS yang digunakan untuk menentukan posisi suatu elemen pada halaman web. Ketika sebuah elemen memiliki properti `position: fixed`, maka elemen tersebut akan tetap berada pada posisi yang sama relatif terhadap viewport (area tampilan browser), bahkan ketika halaman web di-scroll.
  

### Kode Program

```css

.fixed-box {

  position: fixed; /* Menggunakan posisi fixed */

  top: 80px;

  left: 50px;

  width: 200px;

  height: 100px;

  background-color: #333;

  color: #fff;

  padding: 10px;

}

```

### Hasil
![Aset CSS pt2/px.png](Aset%20CSS%20pt2/px.png)

### Kesimpulan

position: fixed, elemen akan tetap berada pada posisinya yang ditentukan jika discrool.properti top dan left digunakan untuk menentukan jarak elemen dari tepi atas dan kiri.

  

## Position Sticky

### Penjelasan

- Kami memiliki sebuah div untuk konten (`content`) di HTML.

- Di CSS, kami memberikan padding pada `.content` untuk memberikan ruang di sekitar konten.

- Kami menambahkan sebuah div dengan kelas `.sticky-box`, yang akan dijadikan elemen sticky. Properti `position: sticky` diterapkan untuk membuatnya tetap menempel di bagian atas layar saat pengguna menggulir.

### Kode Program

```css

body {

    margin: 0;

    font-family: Arial, sans-serif;

}

  

.content {

    padding: 20px;

}

  

.sticky-box {

    background-color: #333;

    color: #fff;

    text-align: center;

    position: sticky;

    top: 0;

    width: 100%;

    padding: 20px;

}

```

### Hasil
![Aset CSS pt2/pstk.png](Aset%20CSS%20pt2/pstk.png)
### Kesimpulan
`position: sticky`, elemen akan seperti posisi relatif sampai jarak scroll mencapai nilai tertentu. elemen akan tetap berada pada posisi yang telah ditentukan saat jarak scroll mencapai nilai tertentu, sambil tetap mengikuti pergeseran scroll di bawahnya.

# Studi Kasus (Positon)

## Kode Program

```html

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Tantangan Position</title>

</head>

<body>

    <div class="container">

        <div class="item1">

            <img src="- 00_00.jpeg" alt="" >

        </div>

        <div class="item2">

            <p class="text1">Thursday,July 16, 2015</p>

            <h4 class="text2">The standard chunk of Lorem Ipsum</h4>

            <p class="text3">Sed posuere consectectur est at lobortis.Anean eu leo quam.</p>

        </div>

        <div class="item3">

            <p class="text4">Read more</p>

            <img src="./arrow.jpeg" alt="">

        </div>

          <div class="like">

              <button>

              <img src="./like.jpeg" alt="">

            </button>

        </div>

    </div>

</body>

</html>

```

## Penjelasan HTML

- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen HTML.

- `<html lang="en">`: Menandakan awal dari dokumen HTML dengan bahasa Inggris.

- `<head>`: Bagian kepala dokumen HTML yang berisi metadata dan referensi ke stylesheet.

- `<meta charset="UTF-8">`: Menentukan pengkodean karakter dokumen sebagai UTF-8.

- `<meta http-equiv="X-UA-Compatible" content="IE=edge">`: Menentukan versi IE yang kompatibel.

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Menyesuaikan tampilan halaman dengan lebar perangkat.

- `<title>Tantangan Position</title>`: Memberikan judul halaman.

- `<style>`: Mulai dari bagian CSS yang didefinisikan dalam dokumen HTML.

- `<body>`: Bagian utama dari dokumen HTML yang berisi konten yang akan ditampilkan di browser.

- `<div class="container">`: Sebuah div yang bertindak sebagai wadah untuk semua konten. Ini memiliki beberapa div anak yang akan di-styling.

- `<div class="item1">`, `<div class="item2">`, `<div class="item3">`: Div-div yang bertindak sebagai item atau bagian-bagian dari konten.

- `<img>`: Elemen gambar untuk menampilkan gambar.

- `<p>`, `<h4>`: Elemen paragraf dan heading untuk menampilkan teks.

- `<button>`: Tombol untuk berbagai fungsi, seperti menyukai konten.

- `<div class="like">`: Sebuah div yang berisi tombol "suka" atau "like".

  

```css

        body{

            background-color: aqua;

        }

  

        .container {

            display: flex;

            flex-direction: column;

            background-color: white;

            height: 458px;

            width: 300px;

            border-radius: 10px;

            margin-top: 150px;

            margin-left: 720px;

            position: relative;

        }

  

        .item1{

            background-color: red;

            height: 250px;

            width: 300px;

            border-radius: 10px 10px 0px 0px;

        }

  

        img {

            width:100%;

            height:100%;

            border-radius: 5px 5px 0px 0px;

        }

  

        .item2{

            background-color: whitesmoke;

            height: 175px;

            width: 300px;

            justify-content: center;

            align-items: center;

        }

  

        .text1 {

            font-size: small;

            font-family: Arial, Helvetica, sans-serif;

            margin-left: 20px;

        }

  

        .text2 {

            font-size: 20px;

            font-family: Arial, Helvetica, sans-serif;

            margin-left: 20px;

        }

  

        .text3 {

            margin-left: 20px;

            font-family: Arial, Helvetica, sans-serif;

            font-size: medium;

            margin-bottom: 30px;

        }  

  

        .item3 {

            display: flex;

            flex-direction: row;

            padding: 2px;

            background-color: gainsboro;

            border-radius: 0px 0px 5px 5px;

            width: 296px;

            justify-content: space-between;

            font-weight: bold;

        }

  

        .text4 {

            margin-left: 20px;

            font-family: Arial, Helvetica, sans-serif;

        }

  

        button {

            width: 62px;

            height: 55px;

            background-color: transparent;

            border: none;

            border-radius: 100px 100px 100px 100px;

            position: fixed;

            background-repeat: no-repeat;

            top: 350px;

            right: 520px;

  

        }

  

        .like img {

            border-radius: 100% ;

            margin-right: 110px;

            margin-left: 135px;

            position: absolute;

        }

  

        .item3 img {

            height: 30px;

            width: 30px;

            border-radius: 100% 100% ;

            align-items: center;

            justify-items: center;

            margin-right: 25px;

            margin-top: 10px;

        }

```

## Penjelasan CSS

- `body`: Memberi warna latar belakang aqua pada halaman.

- `.container`: Membuat tata letak kontainer menggunakan flexbox, memberi warna latar belakang putih, dan menentukan dimensi dan posisi.

- `.item1`, `.item2`, `.item3`: Masing-masing memberikan warna latar belakang dan menentukan dimensi dan posisi elemen.

- `img`: Mengatur dimensi gambar dan memberikan efek sudut melengkung pada beberapa gambar.

- `.text1`, `.text2`, `.text3`, `.text4`: Mengatur gaya teks untuk paragraf dan judul.

- `button`: Mengatur gaya untuk tombol, termasuk dimensi, warna latar belakang transparan, dan posisi.

- `.like img`: Mengatur gaya untuk gambar di dalam tombol "suka".

- `.item3 img`: Mengatur gaya untuk gambar di dalam item 3.

### Hasil
![possition.png](possition.png)

## Kesimpulan

Program ini menggunakan HTML untuk membuat struktur konten dan CSS untuk merancang tampilannya. Elemen-elemen seperti gambar, teks, dan tombol diberikan gaya untuk menciptakan tampilan yang menarik dan responsif. Penggunaan posisi relatif, absolut, dan sticky memungkinkan penempatan yang tepat dari elemen-elemen tersebut di halaman.

