Tag <p> dalam HTML berfungsi mendefinisikan sebuah paragraf, dan browser otomatis menambahkan satu baris baru sebelum dan sesudah disetiap paragraf nya. Tag <p> termasuk elemen tingkat blok yang artinya menempati lebar penuh yang tersedia untuknya dan dimulai pada garis baru.

Dampa adanya :
- Browser mendapatkan struktur teks yang jelas dan memiliki margin default antar paragraf
- Screen reader bisa membaca dengan baik per paragraf yang memiliki jeda saat di bacakan yang membuat user tidak kebingunan
- Mesin Pencarian memahami mana teks isi dan nama yang bukan dan mudah dianalisis sebagai konten utama.

Dampak Tidak adanya :
- Browser tetap render teks tetapi menjadi anonymous text node dan membuat margin & struktur jadi tidak konsisten.
- Screen reader bisa dibaca tanpa adanya jeda yang membuat user bingung.
- Membuat proses maintainbility jadi jauh lebih susah karena CSS tidak bisa menargetkan teks tersebut.