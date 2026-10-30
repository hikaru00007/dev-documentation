# Taxonomy rules

## Inclusion

- `software` dan `system` dalam arti komputasi.
- Alat hitung pra-elektronik masuk sebagai ancestor (`02-pre-electronic-computing/`).
- Biologi, kimia, fisika umum TIDAK masuk kecuali diwujudkan sebagai sistem komputasi.

## Level

- Maksimum 4 level kedalaman dari root (mis. `04/families/c-family/cpp`).
- Jika butuh 5 level, pecah top-level atau tambah kategori baru di `00-meta/taxonomy/`.

## Sortir

- Top-level: numerik `00`..`99`.
- Level-2 ke bawah: alfabetis, kecuali ada alasan historis/kelompok.
- Exception: `families/` di `04-programming-languages/` diurutkan per keluarga dulu, baru alfabetis di dalamnya.

## Duplikat

- Satu entri = satu lokasi. Gunakan symlink atau cross-reference, jangan copy.
- Produk multi-domain (mis. Excel: office + data): taruh di domain primer (`14-enterprise-business/office/`), cross-reference dari domain sekunder.

## Legacy

- Pindah ke `18-legacy-extinct/` jika: tidak ada update >5 tahun DAN tidak ada deployment baru yang signifikan.
- Wajib sertakan `DEAD.md`: nama, tahun lahir, tahun mati, alasan.
