# dev-docs

Documentation corpus for every software and system — from the abacus to the last compiler.

## Top level

| # | Folder | Isi |
|---|---|---|
| 00 | `00-meta/` | konvensi, taksonomi, indeks |
| 01 | `01-foundations/` | matematika, logika, komputabilitas, algoritma, struktur data, kripto primitif |
| 02 | `02-pre-electronic-computing/` | abacus, antikythera, kalkulator mekanik, enigma |
| 03 | `03-hardware/` | ISA, semikonduktor, storage, memory, interconnect, mesin historis, quantum |
| 04 | `04-programming-languages/` | paradigma, famili, runtime, toolchain |
| 05 | `05-operating-systems/` | unix, linux, windows, apple, mainframe, realtime, embedded, historis |
| 06 | `06-networking/` | protokol, topologi, hardware, SDN, governance |
| 07 | `07-databases/` | relasional, nosql, newsql, vector, format, historis |
| 08 | `08-web/` | standar, engine, browser, server, framework, API |
| 09 | `09-software-engineering/` | metodologi, pola, arsitektur, VCS, testing, CI/CD, observability |
| 10 | `10-graphics-multimedia/` | 2D/3D, video, audio, game engine, rendering, warna, format |
| 11 | `11-artificial-intelligence/` | fondasi, ML klasik, DL, NLP, CV, RL, generatif, framework, MLOps, safety |
| 12 | `12-security/` | kriptografi, serangan, pertahanan, standar, ofensif |
| 13 | `13-scientific-computing/` | numerik, simulasi, bioinformatika, iklim, astronomi, tools |
| 14 | `14-enterprise-business/` | ERP, CRM, office, workflow, identity |
| 15 | `15-cloud-infrastructure/` | provider, container, orkestrasi, IaC, serverless, edge |
| 16 | `16-mobile/` | iOS, Android, HarmonyOS, Wear, historis |
| 17 | `17-games/` | engine, grafis API, audio, fisika, historis, genre |
| 18 | `18-legacy-extinct/` | bahasa, sistem, hardware, format, produk mati |
| 19 | `19-dev-tooling/` | editor, terminal, shell, package manager, debugger |
| 20 | `20-emerging/` | quantum, neuromorphic, photonic, DNA, BCI, PQC |
| 21 | `21-standards-bodies/` | ISO, IEEE, IETF, W3C, ECMA, ANSI, ITU, OASIS |
| 22 | `22-history/` | timeline, pionir, perusahaan, milestone |
| 99 | `99-appendix/` | glosarium, bibliografi, cheatsheet, cross-index |

## Konvensi

Lihat `00-meta/conventions/NAMING.md` dan `00-meta/taxonomy/RULES.md`.

- Nama folder: `NN-slug`, lowercase, hyphen-separated, ASCII.
- Setiap entri di `18-legacy-extinct/` membawa stub `DEAD.md` dengan tahun.
- Cross-reference: `[[path/to/folder]]`, diresolusi via `99-appendix/cross-index/`.
