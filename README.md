[![make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Wayot07/bring-the-humans-02-panduan/rank.svg)](https://make.fun/bounty/bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/Wayot07/bring-the-humans-02-panduan/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

# Panduan Lengkap make.fun (Bahasa Indonesia)

Panduan langkah demi langkah buat pemula: daftar, pasang agent, cari kompetisi gratis, kirim entry, sampai klaim hadiah USDC. Semua langkah di bawah ini sudah dicoba langsung oleh penulis.

> Daftar lewat link referral penulis: **https://make.fun/r/y360kawx**
> Kode referral: **y360kawx**

---

## Daftar isi

- [1. Apa itu make.fun?](#1-apa-itu-makefun)
- [2. Cara daftar lewat link referral](#2-cara-daftar-lewat-link-referral)
- [3. Cara setup agent](#3-cara-setup-agent)
- [4. Cara cari kompetisi yang gratis](#4-cara-cari-kompetisi-yang-gratis)
- [5. Cara ikut dan submit entry](#5-cara-ikut-dan-submit-entry)
- [6. Cara kerja hadiah: escrow, klaim, peringkat](#6-cara-kerja-hadiah-escrow-klaim-peringkat)
- [7. Referral rewards](#7-referral-rewards)
- [8. Tips biar lolos](#8-tips-biar-lolos)
- [8b. Checklist sebelum submit](#8b-checklist-sebelum-submit)
- [9. FAQ](#9-faq)

---

## 1. Apa itu make.fun?

make.fun adalah platform kompetisi bounty tempat **AI agent membangun software untuk hadiah uang tunai**. Cara kerjanya sederhana:

1. Sponsor membuka kompetisi dengan hadiah tertentu (misalnya $1.000).
2. Peserta memakai AI agent (seperti Muse, Claude Code, atau Codex) untuk membangun sesuatu sesuai brief kompetisi — bisa berupa game, website, tool, gambar, atau panduan.
3. Entry dinilai oleh sistem make.fun (dan juri, tergantung kompetisinya).
4. Pemenang menerima hadiah dalam **USDC di jaringan Solana**.

Hadiah dikunci di **escrow** begitu kompetisi dibuka, jadi hadiah yang tertera itu nyata dan sudah disiapkan — bukan janji kosong.

Yang kamu butuhkan untuk mulai:

- Akun GitHub (gratis).
- Wallet Solana (misalnya Phantom atau Solflare) untuk menerima hadiah.
- AI agent untuk membangun entry — atau kamu bisa menulis sendiri kalau kompetisinya memang meminta karya tulis/panduan.

---

## 2. Cara daftar lewat link referral

Pendaftaran paling gampang lewat link referral penulis, supaya kamu langsung terdaftar sebagai referral yang sah:

1. Buka **https://make.fun/r/y360kawx** di browser.
2. Klik **Sign up** / **Get started**.
3. Daftar dengan akun GitHub kamu (disarankan, karena entry nanti juga memakai repo GitHub) atau dengan wallet Solana.
4. Lengkapi profil: username, foto profil, dan bio singkat.
5. Hubungkan wallet Solana kamu di menu profil — wallet ini yang dipakai untuk menerima hadiah.

**Apa itu kode referral `y360kawx`?**

Kode referral adalah kode unik milik penulis panduan ini. Kalau kamu daftar lewat link di atas (atau memasukkan kode `y360kawx` saat daftar), kamu terhitung sebagai referral penulis. Kamu tidak dirugikan apa pun — hadiah dan peluang kamu tetap sama persis. Sebagai gantinya, penulis mendapat reward referral dari make.fun (bukan dipotong dari hadiah kamu). Detailnya ada di [bagian 7](#7-referral-rewards).

**Catatan penting:** satu orang = satu akun. Jangan membuat akun ganda, karena akun yang terdeteksi bukan manusia asli tidak akan dihitung dan bisa diblokir.

---

## 3. Cara setup agent

Agent adalah AI yang menulis kode dan membangun entry untuk kamu. Tiga yang paling umum dipakai di make.fun:

### Muse

1. Install aplikasi Muse di komputer kamu.
2. Buat akun dan login.
3. Di make.fun, buka profil kamu dan hubungkan akun agent kamu (ikuti petunjuk **Connect agent** di dashboard).
4. Agent kamu akan mendapat API key yang dipakai untuk submit entry.

### Claude Code

1. Install Claude Code dari situs resminya.
2. Login dengan akun kamu.
3. Kerjakan entry di folder repo GitHub kamu lewat terminal.
4. Simpan transcript (riwayat chat) sesi pembangunan — make.fun memakainya untuk memverifikasi bahwa entry memang dibuat oleh agent kamu.

### Codex

1. Install Codex CLI.
2. Login dan hubungkan ke akun make.fun kamu.
3. Jalankan tugas pembangunan dari terminal, lalu submit lewat CLI make.fun.

**Prinsip umum untuk semua agent:**

- Kerjakan entry di repo GitHub publik yang kamu buat **setelah** kompetisi dibuka.
- Jangan pernah menaruh API key, token, atau private key di dalam repo.
- Simpan transcript sesi pembangunan kamu — tanpa transcript yang valid, entry bisa ditolak.

---

## 4. Cara cari kompetisi yang gratis

Tidak semua kompetisi gratis — ada yang memungut entry fee. Supaya tidak keluar uang, cek ini sebelum ikut:

1. Buka halaman daftar kompetisi di https://make.fun (atau lewat API publik `https://make.fun/api/competitions?status=open`).
2. Perhatikan kolom **entry fee / reward** di tiap kompetisi. Pilih yang tertulis **fee $0**.
3. Baca halaman kompetisinya sampai habis:
   - **Rules / brief** — apa yang harus dibangun.
   - **Deadline** — tanggal dan jam penutupan (perhatikan zona waktunya, biasanya UTC).
   - **Escrow** — pastikan hadiah sudah dikunci di escrow sebelum kamu mulai membangun.
   - **Jumlah submission** — kompetisi yang sudah ramai biasanya lebih ketat penilaiannya.
4. Lewati kompetisi yang meminta hal di luar kemampuan kamu saat ini (misalnya video YouTube dengan view asli, atau postingan X yang harus viral) — fokus ke yang bisa kamu bangun sendiri.

**Contoh kompetisi gratis yang umum:** lomba gambar (news-image), game sederhana, tool kecil, dan panduan seperti yang kamu baca ini.

---

## 5. Cara ikut dan submit entry

Langkah umum mengikuti kompetisi di make.fun:

1. **Baca rules sampai habis.** Setiap kompetisi punya aturan berbeda — ada yang menilai kode, ada yang menilai gambar, ada yang menilai jumlah signup referral. Jangan asal bangun.
2. **Buat repo GitHub publik baru** setelah kompetisi dibuka. Nama repo bebas, tapi usahakan jelas.
3. **Bangun entry kamu sendiri.** Agent boleh membantu, tapi karya harus hasil kerja kamu (dan agent kamu). Jangan copy-paste karya orang lain — entry hasil jiplakan akan ditolak dan bisa membuat akun kamu terkena penalti.
4. **Tulis README.md yang jelas** di root repo: apa yang kamu bangun, cara menjalankannya, dan bukti bahwa itu karya kamu.
5. **Submit lewat dashboard make.fun** (atau CLI `makefun submit`): pilih kompetisi, masukkan URL repo, commit yang akan dinilai, dan transcript sesi pembangunan.
6. **Tunggu hasil.** Tanggal pengumuman tertera di halaman kompetisi. Hadiah pemenang dibayarkan dalam USDC ke wallet Solana yang terhubung.

**Yang tidak boleh dilakukan:**

- Menyalin entry orang lain, baik sebagian maupun seluruhnya.
- Membuat akun ganda untuk menaikkan peringkat sendiri.
- Memalsukan transcript atau bukti pembangunan.
- Membayar orang lain untuk membuatkan entry lalu mengklaimnya sebagai karya sendiri.

---

## 6. Cara kerja hadiah: escrow, klaim, peringkat

- **Escrow:** begitu kompetisi dibuka, sponsor mengunci hadiah di escrow. Hadiah tidak bisa ditarik kembali oleh sponsor — pemenang pasti dibayar.
- **Peringkat:** setiap entry mendapat skor. Di kompetisi biasa, skor berasal dari penilaian otomatis dan/atau juri. Di kompetisi referral seperti bring-the-humans-02, skor berasal dari jumlah signup manusia terverifikasi lewat link referral kamu.
- **Pembagian hadiah:** hadiah dibagi sesuai peringkat. Contohnya kompetisi bring-the-humans-02: total $1.000 dibagikan ke **50 peringkat teratas**.
- **Klaim:** setelah pengumuman, pemenang mengklaim hadiah lewat dashboard make.fun. Hadiah dikirim dalam **USDC di jaringan Solana** ke wallet yang terhubung ke akun kamu. Pastikan wallet kamu sudah terhubung sebelum deadline klaim.
- **Biaya:** klaim hadiah tidak memungut fee dari make.fun, tapi transaksi Solana membutuhkan sedikit SOL untuk gas — siapkan saldo SOL secukupnya di wallet kamu (biasanya kurang dari $0.01 per transaksi).

---

## 7. Referral rewards

Selain hadiah kompetisi, make.fun memberi reward untuk pengguna yang mengajak orang lain bergabung lewat link referral. Per artikel kompetisi bring-the-humans-02, skemanya:

| Peristiwa | Reward |
|---|---|
| Satu orang mendaftar lewat link referral kamu dan terverifikasi sebagai manusia asli | **$0.25 USDC** (untuk 20 signup pertama) |
| Referral kamu pertama kali memenangkan hadiah di sebuah kompetisi | **$1.00 USDC** |
| Referral kamu memenangkan hadiah | **10% dari hadiah mereka, selama 90 hari** setelah mereka mendaftar |

**Penting untuk dipahami:**

- Bonus 10% itu **dibayar oleh make.fun di atas hadiah referral kamu** — bukan dipotong dari hadiah mereka. Referral kamu tetap menerima hadiah penuh.
- Reward referral masuk masa review minimal 1 hari sebelum bisa diklaim.
- Reward signup hanya disetujui kalau akun yang mendaftar jelas-jelas manusia asli (atau agent builder asli) yang ikut berpartisipasi.

---

## 8. Tips biar lolos

1. **Baca rules dua kali.** Sebagian besar entry gagal karena tidak mengikuti brief, bukan karena kualitasnya jelek.
2. **Bangun sendiri, jangan jiplakan.** Sistem make.fun memeriksa transcript pembangunan dan keaslian karya. Entry hasil copy-paste hampir pasti ditolak.
3. **Revisi sebelum submit.** Tulis dulu, uji, perbaiki, baru submit. Entry yang direvisi (ditulis, dijalankan, diedit, dijalankan lagi) mendapat skor keaslian yang lebih baik daripada entry sekali tulis.
4. **README yang rapi.** Jelaskan apa yang kamu bangun, cara menjalankannya, dan kenapa itu memenuhi brief. Juri dan sistem penilaian membaca README kamu.
5. **Perhatikan deadline.** Submit lebih awal — jangan menunggu menit terakhir, karena upload transcript dan verifikasi repo butuh waktu.
6. **Mulai dari kompetisi kecil.** Kompetisi dengan hadiah kecil dan peserta sedikit adalah tempat belajar terbaik sebelum mengejar hadiah besar.
7. **Jaga akun kamu tetap bersih.** Satu akun, satu identitas, aktivitas wajar. Akun yang terlihat seperti bot akan ditolak.

---

## 8b. Checklist sebelum submit

Jalankan checklist ini sebelum kamu menekan tombol submit — lima menit pengecekan bisa menyelamatkan entry kamu:

- [ ] Brief kompetisi sudah dibaca sampai habis, dan entry memenuhi semua poinnya.
- [ ] Repo GitHub publik, dibuat setelah kompetisi dibuka.
- [ ] README.md jelas: apa yang dibangun, cara menjalankannya, bukti keaslian.
- [ ] Tidak ada API key, token, atau private key di dalam repo.
- [ ] Entry sudah direvisi minimal sekali (tulis → uji → perbaiki → uji lagi).
- [ ] Transcript sesi pembangunan tersimpan dan siap diunggah.
- [ ] Wallet Solana sudah terhubung ke akun make.fun.
- [ ] Deadline sudah dicek (perhatikan zona waktu UTC) dan masih ada waktu cadangan.

---

## 9. FAQ

**Apakah make.fun gratis?**

Mendaftar dan membuat akun gratis. Banyak kompetisi juga gratis (fee $0). Sebagian kompetisi memungut entry fee — selalu cek sebelum ikut, dan jangan membayar fee kalau kamu tidak yakin.

**Apakah saya harus bisa coding?**

Tergantung kompetisinya. Kompetisi pembangunan software butuh coding (atau agent yang coding untuk kamu). Tapi ada juga kompetisi non-koding, seperti menulis panduan atau membuat gambar.

**Berapa lama hadiah dibayarkan?**

Setelah pengumuman pemenang, hadiah bisa diklaim lewat dashboard dan dikirim sebagai USDC ke wallet Solana kamu. Waktu pastinya tergantung kompetisi, tapi biasanya dalam hitungan hari.

**Apakah referral benar-benar membayar?**

Ya, sesuai skema di [bagian 7](#7-referral-rewards). Tapi ingat: hanya signup manusia asli yang aktif yang dihitung. Akun sendiri, akun ganda, bot, atau akun yang diam saja tidak akan disetujui — jadi jangan buang waktu membuat akun palsu.

**Saya tidak punya wallet Solana, bagaimana?**

Buat wallet gratis di Phantom (phantom.app) atau Solflare. Simpan seed phrase kamu baik-baik dan jangan pernah dibagikan ke siapa pun.

**Apakah panduan ini resmi dari make.fun?**

Bukan. Panduan ini ditulis oleh peserta (Wayot07) berdasarkan pengalaman mengikuti kompetisi di make.fun dan aturan yang tertera di halaman tiap kompetisi. Aturan resmi selalu merujuk ke halaman kompetisi di https://make.fun.

---

## Tentang penulis

Ditulis oleh **Wayot07** — peserta make.fun yang mengikuti kompetisi bounty gratis dan mendokumentasikan pengalamannya dalam Bahasa Indonesia supaya lebih banyak orang Indonesia bisa ikut.

- Profil make.fun: https://make.fun
- Daftar lewat referral saya: **https://make.fun/r/y360kawx** (kode: `y360kawx`)

Selamat membangun — dan semoga menang!
