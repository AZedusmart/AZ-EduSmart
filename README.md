# AZ EduSmart v6.5

Aplikasi pembelajaran interaktif untuk pelajar Tingkatan 1 dan Tingkatan 2.

## Struktur projek

- `index.html` — struktur utama aplikasi
- `css/app.css` — reka bentuk, telefon dan tablet
- `js/app.js` — logik aplikasi, kuiz, profil, audio dan rekod
- `assets/icons/icon.svg` — ikon aplikasi
- `manifest.webmanifest` — tetapan pemasangan PWA
- `sw.js` — sokongan cache dan pemasangan aplikasi

## Kemas kini di GitHub

Ekstrak pakej v5.0, kemudian muat naik semua kandungan folder ini ke root repository
`AZ-EduSmart`. Pilih untuk menggantikan fail lama apabila diminta.

Netlify yang telah disambungkan kepada GitHub akan melakukan deploy secara automatik.


## Kemas kini v5.1

- Sound effect jawapan betul, salah, klik dan tamat kuiz dipertingkatkan.
- Muzik latar kekal lebih lembut supaya tidak mengganggu pembelajaran.
- Kelantangan asal untuk pengguna baharu dinaikkan.
- Pepijat `undefined modul selesai` telah dibaiki.


## Hotfix v5.1.1

- Memulihkan fungsi `openSubject()`.
- Kad Matematik, Sains dan Sejarah kini boleh ditekan semula.
- Menambah semakan keselamatan jika data subjek tidak ditemui.


## AZ EduSmart v6.0 — Smart Question Engine

- Empat tahap baharu: Mudah, Sederhana, Sukar dan Pakar.
- Setiap tahap menggunakan soalan daripada kategori kesukaran yang berasingan.
- Soalan dan pilihan jawapan dipilih secara rawak.
- Sistem menyimpan sejarah soalan terkini pada peranti.
- Soalan yang baru dijawab tidak terus berulang pada sesi berikutnya.
- Setiap sesi mengandungi sehingga lima soalan.
- Beberapa variasi ayat disediakan bagi setiap item bank soalan asal.

### Nota kandungan

Versi ini membaiki enjin pemilihan dan pengulangan soalan. Bank soalan baharu yang lebih besar
akan ditambah secara berperingkat supaya setiap variasi mempunyai kandungan akademik yang benar-benar unik.


## v6.5 — Dynamic Mathematics Engine

Matematik Tingkatan 1 dan Tingkatan 2 kini menggunakan penjana soalan sebenar.

- Nombor dan situasi berubah setiap sesi.
- Jawapan betul dikira secara automatik.
- Jawapan pengganggu turut dijana berdasarkan kesilapan lazim.
- Sehingga 30 item baharu dibina untuk setiap tahap sebelum 10 dipilih.
- Tahap Mudah, Sederhana, Sukar dan Pakar mempunyai bentuk pengiraan berbeza.
- Sejarah dan Sains kekal dengan soalan fakta yang telah disemak; enjin dinamik tidak digunakan secara sembarangan pada fakta.

Modul Matematik yang disokong:
- Tingkatan 1: Nombor Nisbah, Faktor dan Gandaan, Kuasa dan Punca,
  Nisbah/Kadar/Kadaran, Ungkapan Algebra dan Persamaan Linear.
- Tingkatan 2: Pola dan Jujukan, Pemfaktoran, Rumus Algebra, Bulatan,
  Koordinat dan Graf, serta Laju dan Pecutan.
