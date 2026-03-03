# 10-Nen Buri ni Saikai shita Kusogaki wa Seijun Bishoujo JK ni Seichou shiteita

> Setelah keluar dari perusahaan black company tempatnya bekerja, Aritsuki Yuu kembali ke kampung halamannya untuk pertama kalinya setelah sepuluh tahun, berniat memulai hidup baru. Suatu hari, seorang gadis SMA misterius yang tampak polos dan cantik datang ke kafe milik keluarganya. Saat Isamu yang gugup menatapnya, gadis itu tiba-tiba berkata, Tebak siapa namaku. Siapa sebenarnya dirimu...!? Kisah komedi romantis penuh kesalahpahaman yang membangkitkan kembali masa muda setelah sepuluh tahun!

---

## Info

| | |
|---|---|
| Judul | 10-Nen Buri ni Saikai shita Kusogaki wa Seijun Bishoujo JK ni Seichou shiteita |
| Judul Alternatif | 10年ぶりに再会したクソガキは清純美少女JKに成長していた |
| Author | Kanzai Yuki |
| Artist | Rokushou Kokuu |
| Tipe | Manga (Hitam Putih) |
| Genre | Comedy · Romance · School Life · Slice of Life |

## Link

- [MangaDex](https://mangadex.org/title/26854d1a-dfd0-4e5c-b6d1-ab291035b8cc/10-nen-buri-ni-saikai-shita-kusogaki-wa-seijun-bishoujo-jk-ni-seichou-shiteita)
- [Raw](https://comic-gardo.com/episode/2550912965031159065)

---

## Struktur

```
10nenburi/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)