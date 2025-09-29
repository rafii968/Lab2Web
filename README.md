## MUHAMAD SAEFUL RAFII 312410374
## LATIHAN

# 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini
before
<img width="1919" height="1016" alt="Screenshot 2025-09-22 141904" src="https://github.com/user-attachments/assets/8f692075-fa5a-4443-b7d3-c6db2cb6d061" />
after
<img width="1919" height="1006" alt="Screenshot 2025-09-29 143539" src="https://github.com/user-attachments/assets/57f5939d-fb1d-487c-bd1a-9bfd81a65202" />

# 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
Perbedaan antara h1 {...} dan #intro h1 {...} adalah pada cakupannya: h1 {...} menerapkan gaya ke semua elemen <h1> di seluruh halaman, 
sedangkan #intro h1 {...} hanya menerapkan gaya ke elemen <h1> yang merupakan turunan dari elemen dengan ID "intro". 
Singkatnya, yang pertama adalah penargetan elemen generik, dan yang kedua adalah penargetan elemen spesifik di dalam konteks tertentu.
h1 {...} (Pemilih Tipe Elemen)
Cakupan: Deklarasi CSS ini akan menargetkan semua elemen <h1> yang ada di seluruh dokumen HTML.
Penggunaan: Berguna ketika kita ingin menerapkan gaya yang sama untuk semua judul utama, seperti mengatur warna teks, ukuran font, atau margin untuk semua judul <h1>.
#intro h1 {...} (Pemilih Kontekstual/Kombinasi)
Cakupan: Deklarasi ini lebih spesifik; ia akan menargetkan elemen <h1> hanya jika <h1> tersebut berada di dalam elemen lain yang memiliki ID intro**.
Penggunaan: Berguna untuk menerapkan gaya yang berbeda pada <h1> dalam bagian atau konteks tertentu dari halaman Anda. Misalnya,
jika Anda memiliki bagian pengantar (<div id="intro">) dan ingin judul utamanya memiliki gaya berbeda dari judul utama di bagian lain.

# 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
yang akan ditampilkan adalah
Deklarasi CSS Inline akan ditampilkan oleh browser karena memiliki prioritas tertinggi, diikuti oleh CSS Internal, dan terakhir CSS Eksternal akan diabaikan jika ada deklarasi ploritas yang lebih tinggi
inline CSS memiliki prioritas lebih tinggi dibanding internal maupun eksternal. internal dan eksternal itu sama.

# 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (<p id="paragraf-1" class="text-paragraf
Kalau ada elemen HTML yang punya ID sama class, terus dua-duanya dikasih CSS, yang bakal diturutin sama browser itu ID, karena ID punya prioritas lebih tinggi daripada class.
contoh
<img width="455" height="399" alt="Screenshot 2025-09-29 151023" src="https://github.com/user-attachments/assets/a070d4a0-8e51-45a4-928b-34b9182be0b0" />
<img width="455" height="399" alt="image" src="https://github.com/user-attachments/assets/f524eb1a-62aa-43d9-920e-a7d332f4ffd2" />
# PRAKTIKUM
# MEMBUAT DOKUMEN HTML
<img width="1919" height="1003" alt="Screenshot 2025-09-29 124743" src="https://github.com/user-attachments/assets/5082842f-5aab-499a-a830-abb56db825f1" />
saya membuat file dot html sebagai kerangka dari website dasar yang memliki tombol dan teks teks
# MENDEKLARASIKAN CSS
<img width="1919" height="1004" alt="Screenshot 2025-09-29 125319" src="https://github.com/user-attachments/assets/f24d6619-b625-49c0-843b-0cfa9541f7e2" />
disini saya mendeklarasikan css untuk mengatur dan merapihkannya
# MENAMBAHKAN INLANE CSS
<img width="1919" height="1004" alt="Screenshot 2025-09-29 130204" src="https://github.com/user-attachments/assets/adeb1563-1863-4584-ad0a-7f5c0e72b286" />
menambahkan deklari ini pada tag <p
<img width="504" height="32" alt="image" src="https://github.com/user-attachments/assets/8de6f704-c373-40d9-af53-bb064053a427" />
# MEMBUAT CSS INTERNAL
<img width="1919" height="1004" alt="Screenshot 2025-09-29 131922" src="https://github.com/user-attachments/assets/11b97d51-22ad-4de0-88b1-bf3b816e738b" />
membuat file baru dengan nama baru, dot css
# Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kodenya
<img width="1919" height="1006" alt="Screenshot 2025-09-29 143539" src="https://github.com/user-attachments/assets/d55e9c96-f54f-42d9-ba1e-42c7192ae4ea" />

