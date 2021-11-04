# &gt;subProgram_
## Daftar Isi
- [Daftar Isi](#daftar-isi)
- [HTML](#html)
    - [Membuat Berkas HTML](#membuat-berkas-html)
    - [Tag Dasar](#tag-dasar)
    - [Komentar](#komentar)
    - [Gaya dan Warna](#gaya-dan-warna)
    - [Memformat Halaman](#memformat-halaman)
    - [Tautan](#tautan)
    - [Gambar](#gambar)
    - [Vidio dan iFrame YouTube](#vidio-dan-iframe-youtube)
    - [Daftar](#daftar)
    - [Tabel](#tabel)
    - [Div dan Span](#div-dan-span)
    - [Input dan Form](#input-dan-form)
- [Referensi](#referensi)

## HTML
### Membuat Berkas HTML
1. Buat folder
2. Di dalam folder tersebut buat file html dengan nama "index.html"
3. Buka file html tersebut dengan editor teks
4. Dalam file tersebut buat kerangka dasar HTML seperti contoh di bawah ini
    ```html
    <!DOCTYPE html> <!--menyatakan bahwa file ini adalah file html-->
    <html> <!--pembukaan tag html-->
        <head> <!--pembukaan tag head-->
            <title>Situs Webku</title> <!--judul file-->
        </head> <!--penutupan tag head-->
        <body> <!--pembukaan tag body, konten web-->
        </body> <!--penutupan tag body-->
    </html> <!--penutupan tag html-->
    ```

### Tag Dasar
1. Tag `<meta>` adalah tag yang mendefinisikan tentang situs web kita, contoh penggunaan tag `<meta>`:
    ```html
    <head>
        <meta charset="UTF-8"> <!--menyatakan karakter set dari file html kita-->
        <meta name="description" content="Ini adalah situs webku"> <!--deskripsi dari situs web kita-->
    </head>
    ```
2. Tag `<h1>` sampai `<h6>` adalah tag heading untuk situs web kita, contoh penggunaan tag `<h1>` dan `<h2>`:
    ```html
    <body>
        <h1>Situs Webku</h1> <!--heading 1-->
        <h2>Heading 2-ku</h2> <!--heading 2-->
    </body>
    ```
3. Tag `<p>` adalah tag paragraf, contoh penggunaan tag `<p>`:
    ```html
    <body>
        <p>Ini adalah paragraf 1-ku</p> <!--paragraf 1-->
        <p>Ini adalah paragraf 2-ku</p> <!--paragraf 2-->
    </body>
    ```
4. Tag `<b>` adalah tag penebalan, contoh penggunaan tag `<b>`:
    ```html
    <body>
        <p>Ini adalah paragraf 1-ku</p> <!--paragraf 1-->
        <p>Ini adalah paragraf 2-ku</p> <!--paragraf 2-->
    </body>
    ```
5. Tag `<i>` adalah tag pemiringan, contoh penggunaan tag `<i>`:
    ```html
    <body>
        <p>Ini adalah <b><i>paragraf 2</i></b>-ku</p> <!--penebalan dan pemiringan-->
    </body>
    ```
6. Tag `<br>` adalah tag pengakhir baris, contoh penggunaan tag `<br>`:
    ```html
    <body>
        <p>Ini adalah <br><b>paragraf 1</b>-ku</p> <!--mengakhiri baris paragraf 1, tanpa tag penutup-->
    </body>
    ```
7. Tag `<hr>` adalah tag pemberi garis horizontal, contoh penggunaan tag `<hr>`:
    ```html
    <body>
        <p>Ini adalah <br><b>paragraf 1</b>-ku</p><hr> <!--pemberian garis horizontal setelah paragraf 1, tanpa tag penutup-->
        <p>Ini adalah <b><i>paragraf 2</i></b>-ku</p>
    </body>
    ```
8. Tag `<big>` dan `<small>` adalah tag pemerbesar dan pemerkecil teks, contoh penggunaan tag `<big>` dan `<small>`:
    ```html
    <body>
        <p><big>Ini</big> <small>adalah</small> <b><i>paragraf 2</i></b>-ku</p> <!--teks diperbesar dan diperkecil-->
    </body>
    ```
9. Tag `<sub>` dan `<sup>` adalah tag subscript dan superscript yang sering digunakan dalam kimia dan matematika, contoh penggunaan tag `<sub>` dan `<sup>`:
    ```html
    <body>
        <p>H<sub>2</sub>O adalah rumus kimia dari air</p> <!--subscript-->
        <p>10<sup>2</sup> sama dengan 100</p> <!--superscript-->
    </body>
    ```

### Komentar

1. Komentar dalam HTML menggunakan tag `<!-- -->`, contoh penggunaan tag `<!-- -->`:
    ```html
    <!-- Ini adalah komentar -->
    ```

### Gaya dan Warna

1. Untuk pemberian gaya pada tag dalam HTML dapat menggunakan atribut `style`, contoh penggunaan atribut `style` untuk mengubah warna teks dan latar belakang teks:
    ```html
    <p style="color: red; background-color: blue;">Merah</p> <!-- teks berwarna merah dengan latar belakang biru -->
    ```

### Memformat Halaman

1. Tag layout dasar umum suatu web adalah tag `<header>`, `<main>`, dan `<footer>`, contoh penggunaan tag `<header>`, `<main>`, dan `<footer>`:
    ```html
    <body>
        <header> <!-- bagian atas -->
        </header>
        <main> <!-- bagian utama -->
        </main>
        <footer> <!-- bagian bawah -->
        </footer>
    </body>
    ```
2. Tag `<nav>` umum digunakan untuk navigasi, contoh penggunaan tag `<nav>`:
    ```html
    <header>
        <nav> <!-- navigasi bisa berisi link -->
        </nav>
    </header>
    ```
3. Tag `<article>` umum digunakan untuk pengelompokan `<section>` untuk artikel, contoh penggunaan tag `<article>` dan `<section>`:
    ```html
    <main>
        <article> <!-- artikel -->
            <section> <!-- seksi 1 -->
            </section>
            <section> <!-- seksi 2 -->
            </section>
        </article>
    </main>
    ```    
4. Tag `<aside>` umum digunakan di dalam tag `<section>` untuk teks yang tidak terlalu berhubungan dengan konten inti, contoh penggunaan tag `<aside>`:
    ```html
    <section>
        <aside> <!-- teks sampingan -->
        </aside>
    </section>
    ```

### Tautan
1. Untuk dapat membuat sebuah tautan, kita harus menggunakan tag `<a>` dengan atribut `href` berisi tautan yang ingin dituju, contoh penggunaan tag `<a>`:
    ```html
    <body>
        <a href="https://sub-program.github.io">Tautan ke situs >subProgram_</a> <!-- tautan menuju situs web >subProgram_ -->
    </body>
    ```
2. Tautan yang dituju tidak harus mengarah ke luar situs, tetapi bisa juga tautan ke dalam situs itu sendiri, contoh:
    ```html
    <body>
        <a href="/">Halaman Utama</a> <!-- tautan menuju ke halaman utama suatu situs web -->
        <a href="/index.html">Halaman Utama</a> <!-- tautan menuju ke berkas index.html dari suatu situs web -->
    </body>
    ```
3. Untuk pembuatan tautan yang tidak meninggalkan halaman, dapat menggunakan atribut `target` dengan isi `_blank`, contoh:
    ```html
    <body>
        <a href="https://sub-program.github.io" target="_blank">Tautan ke situs >subProgram_</a> <!-- tautan menuju situs web >subProgram_ dengan tidak meninggalkan halaman -->
    </body>
    ```
4. Di dalam tag `<a>` tidak hanya berisi teks biasa, tetapi bisa juga berisi elemen HTML, contoh:
    ```html
    <body>
        <a href="/"><h1>Halaman Utama</h1></a> <!-- tautan berisi heading 1 menuju ke halaman utama suatu situs web -->
    </body>
    ```

### Gambar
1. Untuk menaruh gambar ke situs, kita dapat menggunakan tag `<img>` dengan atribut `src` berisi tautan ke berkas gambar yang akan ditempel diikuti dengan atribut `alt` berisi teks yang akan ditampilkan jika gambar tidak termuat, contoh penggunaan tag `<img>`:
    ```html
    <body>
        <img src="lukisan.png" alt="gambar lukisan"> <!-- tag mengarahkan ke berkas lukisan.png dengan teks cadangan "gambar lukisan" -->
    </body>
    ```
2. Ukuran gambar dapat diubah dengan munggunakan atribut `width` untuk mengatur panjang dan `height` untuk mengatur lebar gambar berisi angka yang menggunakan satuan piksel pada tag `<img>`, contoh:
    ```html
    <body>
        <img width="100" height="100" src="lukisan.png" alt="gambar lukisan"> <!-- tag mengarahkan ke berkas lukisan.png dengan teks cadangan "gambar lukisan" dengan panjang 100 piksel dan lebar 100 piksel -->
    </body>
    ```

### Vidio dan iFrame YouTube
1. Untuk menaruh vidio ke situs, kita dapat menggunakan tag `<video>` dengan atribut `src` berisi tautan ke berkas gambar yang akan ditempel diikuti dengan teks di dalam tag yang akan ditampilkan jika vidio tidak termuat begitu juga dengan atribut `control` untuk mengaktifkan kontrol di dalam vidio, contoh penggunaan tag `<video>`:
    ```html
    <body>
        <video src="vidio.mp4" control>Ini adalah vidio</video> <!-- tag mengarahkan ke berkas vidio.mp4 dengan teks cadangan "Ini adalah vidio" dengan kontrol -->
    </body>
    ```
2. Pada tag `<video>` ada banyak atribut yang bisa digunakan, yaitu `width`, `height`, `poster`, `loop`, contoh penggunaan atribut-atribut tersebut:
    ```html
    <body>
        <video src="vidio.mp4" control width="300" poster="lukisan.png" loop>Ini adalah vidio</video> <!-- tag mengarahkan ke berkas vidio.mp4 dengan teks cadangan "Ini adalah vidio" dengan kontrol, panjang 300 piksel, poster mengarah ke berkas lukisan.png, dan loop untuk mengulangi vidio ketika vidio selesai -->
    </body>
    ```
3. Untuk menaruh vidio youtube ke situs, kita dapat menggunakan tag `<iframe>` dengan fitur bagikan embed dari youtube dan menyalin dan menempelnya ke situs, contoh:
    ```html
    <body>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/pQN-pnXPaVg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <!-- tag di atas adalah tag <iframe> hasil salinan yang mengarah ke vidio youtube -->
    </body>
    ```

### Daftar
1. Tag `<ul>` dan `<ol>` umum digunakan dalam pembuatan daftar pada HTML, contoh penggunan tag `<ul>` dan `<ol>`:
    ```html
    <body>
        <ul></ul> <!-- ul adalah wadah daftar yang tidak urut -->
        <ol></ol> <!-- ol adalah wadah daftar yang urut -->
    </body>
    ```
2. tag `<li>` diletakkan di dalam tag `<ul>` atau `<ol>` sebagai daftar, contoh penggunaan tag `<li>`:
    ```html
    <body>
        <ul>
            <li>Daftar tidak urut</li>
        </ul>
        <ol>
            <li>Daftar urut</li>
        </ol>
    </body>
    ```
3. tag `<dl>` adalah alternatif lain sebagai wadah daftar, umum digunakan untuk menjelaskan daftar, contoh penggunaan tag `<dl>`:
    ```html
    <body>
        <dl></dl> <!-- ini adalah wadah deskripsi daftar -->
    </body>
    ```
4. tag `<dt>` dan `<dd>` diletakkan di dalam tag `<dl>` sebagai daftar penjelas, `<dt>` adalah yang dijelaskan, `<dd>` adalah penjelasan, contoh penggunaan tag `<dt>` dan `<dd>`:
    ```html
    <body>
        <dl>
            <dt>Jeruk</dt> <!-- yang dideskripsikan -->
            <dd>- adalah buah berwarna jingga</dd> <!-- deskripsi -->
        </dl>
    </body>
    ```

### Tabel
1. Elemen tabel pada HTML diawali dengan tag `<table>` dan diakiri dengan tag penutup tabel `</table>`, contoh:
    ```html
    <body>
        <table>
        </table>
    </body>
    ```
2. Di dalam elemen tabel, tag `<tr>` menyatakan baris tabel dan tag `<td>` menyatakan data tabel, contoh:
    ```html
    <body>
        <table>
            <tr>
                <td>baris 1, kolom 1</td>
                <td>baris 1, kolom 2</td>
            </tr>
            <tr>
                <td>baris 2, kolom 1</td>
                <td>baris 2, kolom 2</td>
            </tr>
        </table>
    </body>
    ```
3. Tag `<th>` menyatakan header tabel, contoh:
    ```html
    <body>
        <table>
            <tr>
                <th>header kolom 1</th>
                <th>header kolom 2</th>
            </tr>
            <tr>
                <td>kolom 1</td>
                <td>kolom 2</td>
            </tr>
        </table>
    </body>
    ```
4. Tag `<caption>` menyatakan judul tabel, contoh:
    ```html
    <body>
        <table>
            <caption>Judul</caption>
            <tr>
                <th>header kolom 1</th>
                <th>header kolom 2</th>
            </tr>
            <tr>
                <td>kolom 1</td>
                <td>kolom 2</td>
            </tr>
        </table>
    </body>
    ```
5. Tag `<thead>` menyatakan atasan tabel, sedangkan tag `<tbody>` menyatakan bawahan tabel, contoh:
    ```html
    <body>
        <table>
            <thead>
                <caption>Judul</caption>
                <tr>
                    <th>header kolom 1</th>
                    <th>header kolom 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>kolom 1</td>
                    <td>kolom 2</td>
                </tr>
            </tbody>
        </table>
    </body>
    ```
6. atribut `colspan` menyatakan kolum yang diambil, contoh:
    ```html
    <body>
        <table>
            <thead>
                <caption>Judul</caption>
                <tr>
                    <th colspan="2">header 2 kolom</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>kolom 1</td>
                    <td>kolom 2</td>
                </tr>
            </tbody>
        </table>
    </body>
    ```

### Div dan Span
1. Tag `<div>` dan `<span>` umum digunakan sebagai wadah, `<div>` adalah elemen block dan `<span>` adalah elemen inline, contoh:
    ```html
    <body>
        <div>div1</div>
        <div>div2</div>
        <span>span1</span>
        <span>span2</span>
    </body>
    ```

### Input dan Form
1. Pada HTML, tag `<input>` digunakan untuk menerima input dari pengguna disertai dengan atribut `type` yang berisi tipe input yang diinginkan, seperti `text`, `password`, dan lain-lain, contoh:
    ```html
    <body>
        <input type="text">
        <input type="password">
    </body>
    ```
2. Atribut `value` pada elemen input digunakan untuk menyatakan isi default, contoh:
    ```html
    <body>
        <input type="text" value="Username">
        <input type="password">
    </body>
    ```
3. Tag `<textarea>` digunakan untuk menerima input teks multi-line yang juga bisa di-resize dan isi konten adalah isi defaultnya, contoh:
    ```html
    <body>
        <textarea>Input teks multi-line</textarea>
    </body>
    ```
4. Atribut `rows` dan `cols` pada elemen textarea digunakan untuk menentukan ukuran, contoh:
    ```html
    <body>
        <textarea rows="10" cols="20">Input teks multi-line</textarea>
    </body>
    ```
5. Tag `<form>` digunakan untuk menampung input yang ada di dalamnya, contoh:
    ```html
    <body>
        <form>
            <input type="text">
            <input type="submit">
        </form>
    </body>
    ```

### iFrame
1. Tag `<iframe>` digunakan untuk menempelkan situs web, memiliki beberapa atribut, yaitu `src` sebagai sumber, `frameborder` menyatakan border frame, `width` dan `height` menyatakan ukuran frame, teks di dalam elemen iframe berfungsi sebagai teks default, contoh:
    ```html
    <body>
        <iframe src="https://sub-program.github.io/" frameborder="0" width="1000" height="500">Tidak dapat memuat iframe</iframe>
    </body>
    ```

### Tag Meta
1. Tag meta berfungsi menyampaikan informasi mengenai berkas HTML terutama pada mesin pencari, contoh:
    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="Ini deskripsi situs">
        <meta name="author" content="Surya">
        <meta name="keywords" content="HTML, >subProgram_, sub-program">
        <meta name="viewport" content="width=device-width, initial-scale=1">
    </head>
    ```

## Referensi
- HTML: <https://youtu.be/pQN-pnXPaVg>
