# Data Drifting

## What?

Kasus dimana data kita itu berubah pattern atau polanya (misal karena seiring berjalannya waktu). Hal ini kemudian menyebabkan model yang kita buat menggunakan data sebelumnya menjadi tidak relevan lagi. Tantangan utamanya adalah bagaimana kita bisa mengidentifikasi perubahan tersebut.

## Why?

* salah satu sebab pentingnya _continuous development_ dalam sistem apapun, sehingga menjamin kebaruan informasi dari sistem tersebut. Dalam kasus model statistik yang tidak selalu valid, terutama jeda waktu pengambilan data dengan publikasi dari model, terdapat gap yang membuat kita tidak bisa mengambil kesimpulan yang sama dengan kondisi terkini.
* kenapa penting: pola yang kita punya hari ini belum tentu relevan dengan pola yang ada minggu depan, sehingga keputusan yang diambil bisa saja bukan merupakan keputusan yang terbaik (tergantung kecepatan berubahnya data, banyaknya data, bias, dsb).

!!! Contoh
    Data kemacetan jakarta yang tiap hari berubah, baik waktu dan titik kritisnya (misal saat PSBB dan kondisi normal)