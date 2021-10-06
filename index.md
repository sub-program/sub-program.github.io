# &gt;subProgram_
## Daftar Isi
- [Daftar Isi](#daftar-isi)
- [HTML](#html)
    - [Membuat Berkas HTML](#membuat-berkas-html)
    - [Tag Dasar](#tag-dasar)
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

## Referensi
- HTML: <https://youtu.be/pQN-pnXPaVg>
