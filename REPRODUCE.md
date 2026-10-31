# How this repository was made (Central Papua (Indonesia))

This file is written by the build on 2026-10-31, the day the source data was retrieved.

## Sources

| Source | Address | Retrieved | Licence |
| --- | --- | --- | --- |
| JDIH Provinsi Papua Tengah (Biro Hukum Sekretariat Daerah Provinsi Papua Tengah): Peraturan Daerah, each the published copy (salinan), a scanned PDF read by OCR | <https://jdih.papuatengahprov.go.id/dokumen/peraturan?DokumenSearch%5Bjenis_peraturan%5D=PERATURAN+DAERAH+PROVINSI> | 2026-10-31 | Peraturan Daerah of Provinsi Papua Tengah as published (salinan) on https://jdih.papuatengahprov.go.id. Undang-Undang Nomor 28 Tahun 2014 tentang Hak Cipta, Pasal 42: "Tidak ada Hak Cipta atas hasil karya berupa: a. hasil rapat terbuka lembaga negara; b. peraturan perundang-undangan; c. pidato kenegaraan atau pidato pejabat Pemerintah; d. putusan pengadilan atau penetapan hakim; dan e. kitab suci atau simbol keagamaan." (There is no copyright in ... b. laws and regulations.) A Peraturan Daerah Provinsi is one of the peraturan perundang-undangan listed in Pasal 7(1) of Undang-Undang Nomor 12 Tahun 2011. |

Every word of law in this repository comes from these sources. Lexifina reads them and records each act's dated versions, and the laws that made each change, in one corpus file. This repository is built from that file.

## What is in it

| Act | Title | Versions | Span |
| --- | --- | ---: | --- |
| `perda-2025-002-pembentukan-dan-susunan-perangkat-daerah` | Peraturan Daerah Provinsi Papua Tengah Nomor 2 Tahun 2025 tentang Pembentukan dan Susunan Perangkat Daerah | 1 | 2025-10-17 to 2025-10-17 |
| `perda-2026-003-pangan-lokal` | Peraturan Daerah Provinsi Papua Tengah Nomor 3 Tahun 2026 tentang Pangan Lokal | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-004-pengawasan-sosial` | Peraturan Daerah Khusus Provinsi Papua Tengah Nomor 4 Tahun 2026 tentang Pengawasan Sosial | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-005-pengelolaan-dan-perlindungan-hutan` | Peraturan Daerah Provinsi Papua Tengah Nomor 5 Tahun 2026 tentang Pengelolaan dan Perlindungan Hutan | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-006-pertambangan-rakyat` | Peraturan Daerah Provinsi Papua Tengah Nomor 6 Tahun 2026 tentang Pertambangan Rakyat | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-008-administrasi-kependudukan` | Peraturan Daerah Provinsi Papua Tengah Nomor 8 Tahun 2026 tentang Administrasi Kependudukan | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-009-pemberdayaan-lembaga-pelopor-pendidikan-dan-lembaga-pendidikan-swasta` | Peraturan Daerah Provinsi Papua Tengah Nomor 9 Tahun 2026 tentang Pemberdayaan Lembaga Pelopor Pendidikan dan Lembaga Pendidikan Swasta | 1 | 2026-02-09 to 2026-02-09 |
| `perda-2026-010-pengelolaan-danau` | Peraturan Daerah Provinsi Papua Tengah Nomor 10 Tahun 2026 tentang Pengelolaan Danau | 1 | 2026-05-07 to 2026-05-07 |
| `perda-2026-011-tugas-dan-wewenang-majelis-rakyat-papua` | Peraturan Daerah Khusus Provinsi Papua Tengah Nomor 11 Tahun 2026 tentang Tugas dan Wewenang Majelis Rakyat Papua | 1 | 2026-05-07 to 2026-05-07 |
| `perda-2026-012-pengembangan-pembinaan-dan-pelindungan-bahasa-daerah-dan-sastra-daerah` | Peraturan Daerah Provinsi Papua Tengah Nomor 12 Tahun 2026 tentang Pengembangan, Pembinaan, dan Pelindungan Bahasa Daerah dan Sastra Daerah | 1 | 2026-05-07 to 2026-05-07 |
| `perda-2026-013-peningkatan-dan-perbaikan-gizi-masyarakat` | Peraturan Daerah Provinsi Papua Tengah Nomor 13 Tahun 2026 tentang Peningkatan dan Perbaikan Gizi Masyarakat | 1 | 2026-06-03 to 2026-06-03 |

The build made 11 commits:

| Commits | Kind |
| ---: | --- |
| 11 | first version of an act |
| 0 | one law on its in-force day |
| 0 | changes no amendment note explains, credited to the publisher |

Other counts:
- 0 commits on the branch `future`: laws not yet in force on 2026-10-31.
- 0 commits dated 1 January 1970: in force before 1970, with the real day in their `In-force` trailer.
- 1 laws in the record.
- 11 tags.

## Dates

Each commit is dated at noon (Asia/Jayapura) on the day the change took effect. The other dates, enacted and published, are trailers.

When a law gives no date of its own, the default rule applies: A Peraturan Daerah takes effect on the day its last Pasal names; almost always "mulai berlaku pada tanggal diundangkan", the day it is promulgated in the Lembaran Daerah. https://jdih.papuatengahprov.go.id/dokumen/peraturan?DokumenSearch%5Bjenis_peraturan%5D=PERATURAN+DAERAH+PROVINSI

## How the history is built

`tools/build.py` turns the corpus into this history in one pass: one commit per law, on the day it took effect. The same corpus always gives the same commit hashes. `tools/check_repo.py` reads every version back from git and compares it with the corpus. `tools/on.py` shows the law as it stood on any date. The corpus format is described in `tools/SCHEMA.md`.

- Corpus: sha256 `a9cf8eb5890e111acf5f7ba3f9ae7210b938f9d70b74f458404e4fc2e1e8c049` (394224 bytes).
- Builder blob hashes (`git hash-object`): `build.py` `a4faa25af85facb64b956b372f6b528aafdd7ec1`, `check.py` `5d719354ea4c62d240c93d2cae446307d81d9e81`, `on.py` `aff48cf1b68d50c7ba8f399ca32261871c301824`.
- Python 3.14.4; git version 2.53.0.

## Checks

11 versions of 11 acts read back from git on the day each took effect and on the day before: 0 mismatches. Trailers: 0 commits whose trailers git cannot parse. Health: 0 merge commits on main, 0 commit dates that go backwards, 0 commits dated after the build.

No second build of this corpus has been compared yet.

## Decisions made by hand

- Oldest version available: each Peraturan Daerah is one version, its text as enacted (the published copy, salinan), credited to the JDIH publisher (first_law null), not to an amending law. An amending Perda is recorded as an act of its own; its changes are not replayed into the Perda it amends, and a repeal is not applied.
- Dated by the day the Perda takes effect under its own last Pasal: the promulgation day (diundangkan, printed in the closing) when it says "mulai berlaku pada tanggal diundangkan", or the calendar day it names. A Perda whose commencement is a period or another event is left out for now.
- Parts are added oldest first within themselves; a part never changes an act an earlier part holds.
- Units: a-pembukaan (heading, preamble, enacting words), one file per Pasal (chapter, part and paragraph headings printed between two Pasal stay at the end of the earlier one, in printed order), z1-penutup (promulgation order, signatures, Lembaran Daerah number, certification), z2-penjelasan (the elucidation) and z3-lampiran (the annex) where printed. One paragraph per line.
- Left out of the text: page numbers and the "SALINAN" stamp line.
- 30-ocr-01: 11 Peraturan Daerah read by OCR from official scans (Alan's decision D8, 2026-11-02: OCR is allowed for official scans whose terms allow reuse, marked as OCR and spot-checked). Reader: Tesseract 5.4.0, language model "ind" (tessdata_best), page segmentation --psm 3, pages rendered at 300 dpi; pages with a real text layer keep it; lines with no letter or digit are left out. Every file of an OCR'd act starts with a front-matter line "Text-source: OCR (...) of the official scan <url>", and its commit message says the same. Spot-check (instead of the pdftotext letters check, which needs a text layer): for every act in the part (D8 asks for at least 3 acts or 10%), 3 paragraphs drawn at random (seeded by the PDF's sha256) are cut out of the scan where the first reading found them and read again with a different setting (tessdata_fast model, --psm 6); the two readings are compared character for character (1 - Levenshtein distance / longer length). Acts with any paragraph under 98% are left out. Agreement in this part: lowest act 99.46%, mean 99.82%. The structural checks still apply: Pasal 1, 2, 3 ... in order, the closing formula, the promulgation day printed, and the act's number and year in its heading equal to the JDIH record. OCR can misread single characters; for anything that matters, read the scan.

## What AI did and did not do

The scripts that read the sources and build this repository were written by Claude Code running Claude Opus 5.5 (`claude-opus-5-5`) under Lexifina's direction.

No model wrote, translated or corrected legal text. No model runs at build time. Every word of law in this repository comes from the official sources above.

The commit messages are written by `build.py` from the source data.

Model use at data-build time:
- Claude Code (claude-opus-5-5) wrote Lexifina's code and chose the sources. No model output is used as legal text or dates: every word comes from the PDFs published on JDIH, read by Tesseract OCR where the PDF is a scan.
