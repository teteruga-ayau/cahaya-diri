# Website Cahaya Diri

## Upload ke GitHub

Upload **semua isi folder ini** ke repository GitHub Anda:

- `index.html`
- `style.css`
- `cahaya.jpg`

Lalu aktifkan GitHub Pages:
**Settings → Pages → Deploy from a branch → main → /(root) → Save**

Website akan tampil di:
`https://USERNAME.github.io/NAMA-REPOSITORY/`

## Preview WhatsApp/Facebook

File ini sudah memiliki Open Graph (`og:title`, `og:description`, `og:image`) dan foto `cahaya.jpg`.

Untuk preview yang paling konsisten di semua platform, setelah GitHub Pages aktif, edit `index.html` dan ubah:
`content="cahaya.jpg"`
menjadi URL absolut, misalnya:
`content="https://USERNAME.github.io/cahaya-diri/cahaya.jpg"`

Lakukan untuk `og:image` dan `twitter:image`.

Catatan: WhatsApp/Facebook dapat menyimpan cache preview. Jika preview lama masih muncul, tunggu beberapa waktu lalu bagikan URL lagi.
