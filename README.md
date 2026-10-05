Praktikum Pert 3 Pemrograman Web
Nama : Nabila Eka Suwarno
NIM : 312510399
Kelas : I251C

Pertanyaan dan Tugas

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS 
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. 
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan 
penjelasannya! 
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline 
CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? 
Berikan penjelasan dan contohnya! 
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector 
tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada 
browser? Berikan penjelasan dan contohnya! (`<p id="paragraf-1" class="text-paragraf".`)

Jawaban 
1. Saya melakukan eksperimen dengan mengubah beberapa nilai pada CSS. Contohnya mengubah warna background pada nav dari #20A759 menjadi #d31d1d, mengubah padding dari 10px menjadi 15px, mengubah warna background pada #intro menjadi #e71191, serta mengubah warna background pada .button menjadi #895fd7.

2. h1 {...} digunakan untuk memberikan CSS pada elemen `<h1>` secara umum.
Sedangkan #intro h1 {...} digunakan untuk memberikan CSS pada elemen `<h1>` yang berada di dalam elemen yang memiliki id="intro".

3. Deklarasi CSS yang akan ditampilkan adalah inline CSS, karena CSS tersebut ditulis langsung pada elemen HTML sehingga memiliki prioritas lebih tinggi.
Contohnya:
`<p style="color: red;">Belajar CSS</p>`
Jika pada CSS internal dan eksternal terdapat aturan yang memberikan warna berbeda pada `<p>`, maka warna yang ditampilkan tetap merah karena menggunakan inline CSS.

4. Deklarasi CSS pada ID akan ditampilkan karena selector ID memiliki prioritas lebih tinggi daripada selector Class.
Contohnya:
`<p id="paragraf-1" class="text-paragraf">`
    Belajar CSS
`</p>`
#paragraf-1 {
    color: red;
}
.text-paragraf {
    color: blue;
}
Hasilnya, teks akan berwarna merah karena selector #paragraf-1 (ID) memiliki prioritas lebih tinggi daripada .text-paragraf (Class).


screenshot hasil praktikum
index.html

# Struktur HTML dan CSS Internal
![img1](<images/img 1.png>)

# Penutup Head + Header + Navigasi
![img2](<images/img 2.png>)

# ID Selector + Inline CSS
![img3](<images/img 3.png>)

# Class Selector + Penutup HTML
![img4](<images/img 4.png>)

screenshot hasil praktikum
style_eksternal.css

# CSS Navigasi
![img5](<images/img 5.png>)

# ID Selector + Class Selector
![img6](<images/img 6.png>)

Tampilan di Web
![img7](<images/img 7.png>)