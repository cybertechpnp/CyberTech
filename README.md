# CyberTech PNP

Portal web resmi UKM CyberTech Politeknik Negeri Padang. Repository ini dikelola untuk kebutuhan internal organisasi. Visibilitas publik mengikuti kebutuhan hosting dan tidak menjadi undangan kontribusi publik.

Profil organisasi dan sejarah tersedia di [UKM_CYBERTECH_2026.md](UKM_CYBERTECH_2026.md).

## Teknologi

- Next.js 16 App Router
- React 19 dan TypeScript
- PostgreSQL untuk penyimpanan data

## Standar kontribusi internal

- Perubahan dikerjakan anggota tim atau kontributor yang ditunjuk. Jangan mengubah `main` langsung; ajukan semua perubahan melalui pull request (PR).
- Mulai pekerjaan dari `main` terbaru dan gunakan branch khusus untuk satu pekerjaan. Awalan branch: `feat/`, `fix/`, `docs/`, `refactor/`, atau `chore/`, misalnya `feat/form-pendaftaran`.
- Buat commit kecil, fokus, dan mudah ditinjau. Jangan gabungkan pekerjaan yang tidak berkaitan dalam satu commit atau PR.
- Tulis pesan commit dengan format `<tipe>(<scope>): <ringkasan>`, misalnya `feat(registrasi): tambah validasi formulir` atau `docs(readme): jelaskan standar kontribusi`. Gunakan tipe yang sesuai seperti `feat`, `fix`, `docs`, `refactor`, `test`, atau `chore`.
- Jalankan `npm run lint` dan `npm run build` sebelum mengajukan PR.
- PR harus menjelaskan alasan dan dampak perubahan serta hasil pemeriksaan. Sertakan screenshot untuk perubahan tampilan. Minta minimal satu anggota tim meninjau; selesaikan masukan sebelum merge.
- Push ke branch pekerjaan sendiri. Jangan force-push ke branch bersama.
- Jangan commit secret, data pribadi atau internal, `.env.local`, `node_modules`, maupun hasil build.

Jika belum memiliki akses tulis, koordinasikan akses dengan pengelola repository sebelum mengerjakan perubahan.

## Dokumentasi terkait

- [Contoh variabel lingkungan](.env.example)
- [Panduan Docker](README.Docker.md)
