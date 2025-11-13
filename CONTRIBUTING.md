# Panduan Kontribusi

Terima kasih atas minat Anda untuk berkontribusi pada proyek Vodeco Digital Mediatama! Dokumen ini berisi panduan untuk membantu Anda berkontribusi dengan efektif.

## Kode Etik

Proyek ini mengikuti [Code of Conduct](CODE_OF_CONDUCT.md). Dengan berpartisipasi, Anda diharapkan untuk mematuhi kode etik ini.

## Cara Berkontribusi

### Melaporkan Bug

Jika Anda menemukan bug, silakan buat issue dengan:
- **Judul yang jelas dan deskriptif**
- **Deskripsi langkah-langkah untuk mereproduksi bug**
- **Perilaku yang diharapkan vs perilaku aktual**
- **Screenshot (jika relevan)**
- **Informasi lingkungan** (OS, browser, versi, dll)

### Mengusulkan Fitur Baru

Kami menyambut ide-ide baru! Untuk mengusulkan fitur:
- Buat issue dengan label `enhancement`
- Jelaskan masalah yang akan diselesaikan
- Jelaskan solusi yang diusulkan
- Berikan contoh penggunaan jika memungkinkan

### Pull Request

1. **Fork repository**
   ```bash
   git clone https://github.com/vodeco/[repository-name].git
   cd [repository-name]
   ```

2. **Buat branch untuk fitur/bugfix**
   ```bash
   git checkout -b feature/nama-fitur
   # atau
   git checkout -b fix/nama-bugfix
   ```

3. **Lakukan perubahan**
   - Tulis kode yang jelas dan mudah dibaca
   - Ikuti style guide yang ada di proyek
   - Tambahkan komentar jika diperlukan
   - Update dokumentasi jika ada perubahan

4. **Commit perubahan**
   ```bash
   git add .
   git commit -m "feat: tambahkan fitur baru"
   ```
   
   Gunakan [Conventional Commits](https://www.conventionalcommits.org/):
   - `feat:` untuk fitur baru
   - `fix:` untuk perbaikan bug
   - `docs:` untuk perubahan dokumentasi
   - `style:` untuk perubahan format (tidak mempengaruhi kode)
   - `refactor:` untuk refactoring kode
   - `test:` untuk menambah/mengubah test
   - `chore:` untuk perubahan build process atau tools

5. **Push ke fork Anda**
   ```bash
   git push origin feature/nama-fitur
   ```

6. **Buat Pull Request**
   - Isi template PR dengan lengkap
   - Jelaskan perubahan yang dibuat
   - Referensikan issue terkait (jika ada)
   - Pastikan semua check (CI/CD) lulus

## Standar Kode

### Formatting

- Gunakan formatter yang sudah dikonfigurasi (Prettier, Black, dll)
- Ikuti style guide bahasa pemrograman yang digunakan
- Pastikan tidak ada trailing whitespace

### Testing

- Tulis test untuk fitur baru
- Pastikan semua test lulus sebelum membuat PR
- Coverage minimal 80% untuk kode baru

### Dokumentasi

- Update README jika ada perubahan signifikan
- Tambahkan komentar untuk fungsi/method kompleks
- Update CHANGELOG untuk perubahan yang mempengaruhi pengguna

## Review Process

1. Setelah PR dibuat, tim akan melakukan review
2. Diskusikan feedback dan lakukan perubahan jika diperlukan
3. Setelah disetujui, PR akan di-merge ke branch utama

## Pertanyaan?

Jika Anda memiliki pertanyaan, silakan:
- Buka issue dengan label `question`
- Hubungi maintainer melalui email: hello@vodeco.co.id

## Sumber Daya

- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Semantic Versioning](https://semver.org/)

---

Terima kasih telah berkontribusi! 🎉

