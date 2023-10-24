how state management works in each case and in which scenarios one might be more suitable than the other.

stateful widget : widget yang dapat berubah tanpa perlunya reload semua page.
stateless widget: stateless widget biasanya digunakan pada widget yang tidak membutuhkan perubahan, seperti teks, appbar, list item, dll.

E-commerce : pada aplikasi ini terdapat banyak stateless dan stateful widget didalamnya,
    Stateless widget : stateless widget pada aplikasi ini kebanyakan berada pada hal-hal yang berbau teks dan button yang tidak membutuhkan state.
                       contohnya pada list item, headbar, home page dan login page
    Stateful widget  : contoh stateful widget pada aplikasi ini adalah button tambahkan produk yang ketika di klik akan merubah state pada angka di icon cart.
                       icon favorite yang dapat berubah menjadi merah kalau di klik. serta fitur filter produk yang dapat mengubah state pada list item dan list komentar pada instagram.

Instagram :
    Stateless widget : contohnya pada logo, teks, dan headbar yang terdapat pada instagram yang tidak membutuhkan state internal.
    Stateful  widget : contohnya pada button like yang merubah state warna pada icon serta mengubah state jumlah likes bertambah menjadi satu.
                       contoh lainnya itu pada logo messenger, ketika pesan masuk, maka angkanya akan bertambah sesuai dengan berapa orang yang mengirimkan kita pesan.
                       contoh lainnya juga pada saat menambah komentar baru.
