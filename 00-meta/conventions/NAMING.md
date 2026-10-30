# Naming conventions

## Folder

- Pattern: `NN-slug`, `NN` dua digit, `slug` lowercase ASCII, hyphen-separated.
- Contoh: `04-programming-languages/families/c-family/cpp`.
- Jangan pakai spasi, underscore, camelCase, atau karakter non-ASCII.
- Nama produk tetap seperti aslinya: `postgresql`, `three-js` (bukan `three.js`).

## File

- Markdown: `SCREAMING_SNAKE.md` untuk dokumen utama (`README.md`, `RULES.md`), `kebab-case.md` untuk entri.
- Stub: `DEAD.md` (di legacy), `INDEX.md` (di folder dengan >10 entri).
- Setiap folder leaf wajib punya minimal `.gitkeep` atau `README.md`.

## Cross-reference

- Format: `[[path/from/dev-docs-root]]`.
- Resolusi: `99-appendix/cross-index/`.
- Backlink tidak diwajibkan; forward link diwajibkan untuk referensi silang.
