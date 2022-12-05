# Data Drifting

## What?

Kasus dimana data kita itu berubah pattern atau polanya (misal karena seiring berjalannya waktu). Hal ini kemudian menyebabkan model yang kita buat menggunakan data sebelumnya menjadi tidak relevan lagi. Tantangan utamanya adalah bagaimana kita bisa mengidentifikasi perubahan tersebut.

## Why?

* salah satu sebab pentingnya continuous development dalam sistem apapun, sehingga menjamin kebaruan informasi dari sistem tersebut.
* kenapa penting: pola yang kita punya hari ini belum tentu relevan dengan pola yang ada minggu depan, sehingga keputusan yang diambil bisa saja bukan merupakan keputusan yang terbaik (tergantung kecepatan berubahnya data, banyaknya data, bias, dsb).

!!! Contoh
    Data kemacetan jakarta yang tiap hari berubah, baik waktu dan titik kritisnya (misal saat PSBB dan kondisi normal)