# Transportasi · Web Lomba IDN Fest

**English** · [Bahasa Indonesia](#bahasa-indonesia)

A one-page website about transport in Indonesia during the COVID-19 pandemic, made by team **Quicksilver** for the web competition at IDN Fest 2021, held by IDN Boarding School. The competition challenged participants to build a website that is both attractive and functional.

Nearly everything on the site is black and white. Photos only turn to colour when you hover over them or scroll to them.

## What's inside

- **Cover**: a looping black-and-white drone video with a live clock that inverts over bright areas (`mix-blend-mode: exclusion`).
- **3M**: a sticky "3M" whose M becomes the first letter of *Memakai Masker*, *Mencuci Tangan* and *Menjaga Jarak* as you scroll.
- **Artikel**: six transport news stories (KAI Commuter, Grab, domestic flights, PeduliLindungi, the Lebaran return trip, MRT Jakarta), each with its own page.
- **Penutup**: a closing note under a spinning CSS 3D cube.

Plain HTML, CSS and JavaScript. No framework, no build step.

## Run it

Open `transportasi.html` in a browser, or serve the folder so the video and links behave as they would online:

```bash
python3 -m http.server 8080
# then open http://localhost:8080/transportasi.html
```

## Files

| Path | What it is |
| --- | --- |
| `transportasi.html` | Main page |
| `style.css`, `engine.js` | Main page styles; clock and scroll effects |
| `artikel01.html` – `artikel06.html` | One page per article |
| `styleArtikel.css`, `engineArtikel.js` | Article page styles and effect |
| `images/` | Photos, background pattern, team logo and the cover video (34.7 MB) |

## Team Quicksilver

- **Joy**: wrote most of the front-end and most of the styling.
- **Zein**: suggested the team name, and if memory serves, added the spinning cube.
- **Asad**: prepared the material (3M, articles, closing words), wrote code and handled the rest.

Joy did the most, but it was a team effort.

## 2026 update

The images were first uploaded as a split RAR, because the cover video was over GitHub's 25 MB browser-upload limit. In 2026 they were extracted and committed as normal files, three article pages that pointed to `../Transportasi/images` were fixed, and the article pages were reformatted.

---

## Bahasa Indonesia

Website satu halaman tentang transportasi di Indonesia selama pandemi COVID-19, dibuat oleh tim **Quicksilver** untuk lomba web IDN Fest 2021 yang diselenggarakan oleh IDN Boarding School. Lomba ini bertujuan mengasah kemampuan peserta dalam membuat website yang menarik dan fungsional.

Hampir semua bagian website ini hitam putih. Foto baru berwarna saat di-hover atau di-scroll.

### Isinya

- **Cover**: video drone hitam putih yang diputar berulang, dengan jam hidup yang warnanya membalik di bagian terang (`mix-blend-mode: exclusion`).
- **3M**: tulisan "3M" yang sticky, huruf M-nya menjadi huruf pertama *Memakai Masker*, *Mencuci Tangan*, dan *Menjaga Jarak* saat di-scroll.
- **Artikel**: enam berita transportasi (KAI Commuter, Grab, penerbangan domestik, PeduliLindungi, arus balik Lebaran, MRT Jakarta), masing-masing punya halaman sendiri.
- **Penutup**: kata penutup di bawah kubus 3D CSS yang berputar.

HTML, CSS, dan JavaScript biasa. Tanpa framework, tanpa proses build.

### Cara menjalankan

Buka `transportasi.html` di browser, atau jalankan server lokal supaya video dan link berjalan seperti saat online:

```bash
python3 -m http.server 8080
# lalu buka http://localhost:8080/transportasi.html
```

### Tim Quicksilver

- **Joy**: paling banyak ngoding frontend dan membuat sebagian besar style-nya.
- **Zein**: memberi nama tim, dan kalau tidak salah, yang menaruh kubus yang berputar.
- **Asad**: menyiapkan materi (3M, artikel, penutup), ikut ngoding, dan mengurus sisanya.

Joy yang paling banyak, tapi tetap saja ini usaha tim.

### Pembaruan 2026

Gambar awalnya diupload sebagai RAR yang dipecah dua, karena video cover melebihi batas upload browser GitHub 25 MB. Di 2026 gambar diekstrak dan di-commit sebagai berkas biasa, tiga halaman artikel yang mengarah ke `../Transportasi/images` diperbaiki, dan format halaman artikel dirapikan.
