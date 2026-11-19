---
name: penyusunan-aturan
description: Menyusun, mengubah, atau menelaah Aturan Komunitas REKATI dan dokumen tata kelola lain (SOP, aturan kelompok minat, AD/ART). Pakai saat menulis pasal, menerapkan keputusan rapat ke aturan, menelaah draf, atau menyesuaikan bahan turunan (situs, formulir, buku, ringkasan, presentasi) setelah aturan berubah.
---

# Menyusun aturan REKATI

Aturan yang baik bisa dipakai dua orang berbeda untuk menilai kasus yang sama dan sampai pada jawaban yang sama. Skill ini merangkum cara mencapainya. Daftar periksanya diturunkan dari [telaah Aturan Komunitas 18 November 2026](../../notulen/2026-11-18-telaah.md) (butir K1 sampai K34).

Untuk bahasa, ikuti [pedoman bahasa Indonesia plain](https://gist.github.com/orepras/3e1ca8974fc51d11825f142fa6a66635). Skill ini tidak mengulang pedoman itu.

## Prinsip

1. **Notulen adalah sumbernya.** Aturan hanya memuat yang sudah diputuskan di rapat dan tercatat di `notulen/`. Kalau keputusan belum ada, tulis dulu di notulen, baru di aturan.
2. **Jangan mengarang.** Yang belum diputuskan ditulis "belum ditentukan" atau dimasukkan ke "Bahan bahasan berikutnya". Jangan mengisinya dengan angka atau prosedur yang terdengar masuk akal.
3. **`[usulan]` hanya untuk pilihan yang sedang ditawarkan ke rapat.** Setiap tanda `[usulan]` harus tercantum di deskripsi PR, supaya rapat bisa memutuskannya satu per satu. Tanda dihapus begitu butirnya diputuskan.
4. **Garis ditarik pada posisi dan kewenangan, bukan pada orang atau jabatan.** Sebutkan alasannya, misalnya benturan kepentingan, supaya yang terkena tidak merasa dinilai.
5. **Aturan melindungi, bukan mengancam.** Setiap larangan disertai alasan atau jalur keberatan. Kritik dan perbedaan pendapat tidak pernah dihitung pelanggaran.
6. **Satu hal, satu sebutan.** Istilah yang dipakai di aturan juga dipakai di formulir, situs, buku, dan presentasi.

## Alur kerja

1. **Kumpulkan sumber.** Baca notulen terkait, aturan yang berlaku, dan telaah sebelumnya.
2. **Tulis draf.** Ubah sesedikit mungkin bagian yang tidak terdampak.
3. **Periksa dengan daftar di bawah.** Periksa setiap pasal yang baru atau berubah.
4. **Minta telaah orang kedua.** Pakai format telaah di bawah.
5. **Catat keputusan di notulen.** Setiap butir telaah diputuskan: diterima, diubah, ditunda, atau ditolak.
6. **Sesuaikan turunannya.** Lihat bagian "Setelah aturan berubah".
7. **Sahkan** menurut bagian "Versi dan cara mengubah aturan" di `ATURAN.md`. Jangan merge sebelum disahkan.

## Daftar periksa

Tanyakan semua pertanyaan ini untuk setiap pasal.

| Jenis cacat | Pertanyaan | Contoh dari telaah |
| --- | --- | --- |
| Kata kabur | Bisakah dua orang menilai kasus yang sama dengan hasil yang sama? Kalau tidak, definisikan katanya atau beri ukuran. | "merugikan" (K13), "berfokus" (K20), "sewenang-wenang" (K24) |
| Ukuran tanpa angka atau titik mulai | Kapan mulai dihitung, berapa lama, dan kapan kedaluwarsa? | "30 hari" sejak kapan (K15), "berturut-turut" (K25) |
| Pelaku dan prosedur | Siapa memutus, siapa diberi tahu, berapa lama, dan ke mana keberatan diajukan? | status calon Kawan (K16), cara memilih pengurus (K19) |
| Kategori bertumpuk | Bisakah satu kasus masuk dua golongan sekaligus? | butir sama di Ringan dan Sedang (K24), manajer dan pimpinan (K7) |
| Pasal karet | Bisakah pasal ini dipakai membungkam kritik, atau dipakai surut untuk kejadian lama? | "memecah belah" (K26), "pelanggaran lain yang sama beratnya" (K30) |
| Istilah hukum | Apakah kata ini punya arti hukum yang berbeda dari maksud kita? | serikat pekerja (K1), KKN (K27), kekerasan seksual menurut UU TPKS (K29) |
| Daur hidup data | Data apa yang dicatat, siapa yang melihat, dan kapan dihapus? Apakah sesuai janji di situs? | isian formulir (K15, K16), kegiatan terbuka (K33) |
| Jangkauan | Sampai di mana aturan berlaku: di dalam kegiatan REKATI saja, atau juga di luar? | perilaku di luar REKATI (K18), kegiatan politik pribadi (K28) |
| Hubungan antardokumen | Kalau dua dokumen berbeda, mana yang berlaku? Apakah formulir dan situs sudah sama? | Kode Etik dan Aturan (K3), definisi di formulir (K7) |
| Perlindungan | Apakah orang yang melapor, dilaporkan, atau menjamin terlindungi? Apakah pemeriksa bebas dari benturan kepentingan? | pelapor dan pemeriksa (K29), penjamin (K17) |
| Janji yang belum ada | Apakah pasal menjanjikan sesuatu yang belum tersedia, misalnya mitra, rekening, atau dana? | "LBH mitra" sebelum ada kerja sama |
| Bahasa dan istilah | Apakah orang baru paham tanpa bertanya? Apakah singkatan dijabarkan pada sebutan pertama? | singkatan dan sebutan ruang bersama (K34) |

## Format telaah

Telaah ditulis sebagai tabel per bab. Setiap butir bernomor dan berdiri sendiri.

```markdown
| Butir | Masalah | Saran |
| --- | --- | --- |
| **K1** · Tinggi. Judul dan paragraf pembuka | Apa yang kabur atau berisiko, dan kenapa. | Rumusan pengganti, dengan pilihan dalam [kurung siku] bila rapat perlu memilih. |
```

- **Prioritas**: Tinggi (bisa merugikan orang atau dipakai sewenang-wenang), Sedang (membingungkan), Rendah (bahasa).
- **Lokasi**: bab, subbagian, dan butir, cukup untuk ditemukan tanpa nomor baris.
- **Saran**: rumusan yang bisa langsung dipakai. "Perjelas" saja tidak cukup.

Telaah disimpan sebagai lampiran notulen (`notulen/YYYY-MM-DD-telaah.md`). Keputusan per butir dicatat di notulen rapatnya.

## Setelah aturan berubah

Aturan punya turunan. Periksa semuanya setiap kali ada perubahan:

- [ ] situs rekati.org: halaman Tentang, formulir gabung, halaman privasi (repo `rekati-org/rekati`, termasuk `CONTEXT.md` dan ADR);
- [ ] buku dan bahan bacaan (repo `rekati-org/bacaan`): `konteks/konteks.md`, kedua buku, ringkasan 10 poin, panduan baca bersama, gambar;
- [ ] presentasi yang sedang dipakai;
- [ ] `README.md` dan `index.md` di repo ini.

Cari istilah lama di semua repo (misalnya `rg -n -i "<istilah lama>"`) sampai hanya tersisa di notulen dan catatan sejarah.

## Kesalahan yang pernah terjadi

- Angka usulan yang tidak diminta (periode, batas hadiah, batas pengeluaran) ditulis seolah keputusan. Yang benar: "belum ditentukan".
- "Tingkat" dipakai untuk Plenum, padahal Plenum tidak bertingkat. Kata yang membawa makna struktur harus diperiksa terhadap notulen.
- Aturan menjanjikan penyimpanan data lebih lama dari janji di situs. Selalu cocokkan dengan halaman privasi.
- Aturan meminta dua penjamin, sedangkan formulir hanya punya satu kolom perujuk. Selalu cocokkan dengan formulir.
- Nama orang ditulis di dokumen aturan. Nama cukup di notulen, dan repo ini publik.
