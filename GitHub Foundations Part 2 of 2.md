# Learning GitHub Foundations (Microsoft Learn)

📘 **Repository pembelajaran Sertifikasi GitHub Foundations** melalui **Microsoft Learn**.  
Repository ini berisi rangkuman materi, praktik langsung, dan eksperimen penggunaan GitHub untuk kolaborasi serta pengelolaan proyek.

---

## 🎯 Tujuan Pembelajaran

- Memahami konsep dasar Git dan GitHub  
- Mengelola repositori dan perubahan kode  
- Berkolaborasi menggunakan fitur GitHub  
- Mengenal fitur produktivitas, keamanan, dan skala GitHub Enterprise  

---

## 🚀 Cara Memulai Kontribusi Open Source

Di GitHub, semua orang dapat berkontribusi ke proyek open source, baik pemula maupun profesional.

---

### Menemukan Proyek

- Mulai dari proyek yang sudah atau ingin digunakan  
- Gunakan **GitHub Search** dan **Topics**  
- Pilih proyek dengan komunitas yang aktif  

---

### Mengenal Proyek

Periksa dokumen penting:

- **LICENSE** → memastikan proyek bersifat open source  
- **README** → gambaran dan tujuan proyek  
- **CONTRIBUTING** → panduan kontribusi  
- **CODE_OF_CONDUCT** → aturan komunitas  

---

### Menemukan Tugas

- Buka tab **Issues** atau halaman `/contribute`  
- Cari label:
  - `good first issue`  
  - `help wanted`  
  - `beginner-friendly`  

---

### Bentuk Kontribusi

- Memperbaiki bug, dokumentasi, atau typo  
- Berpartisipasi dalam diskusi Issue atau Pull Request  
- Mendukung proyek melalui **GitHub Sponsors**  

---

**Intinya:**  
Semua kontribusi itu berharga—mulai dari hal kecil, pahami komunitas, dan berani membantu.

---

## 🌍 Inti Kontribusi Open Source

Kontribusi open source di GitHub menekankan **komunikasi**, **kolaborasi**, dan **kesabaran** agar perubahan dapat diterima oleh pemilik proyek.

---

### Langkah Utama Kontribusi

**1. Komunikasikan Niat**

- Cek issue yang sudah ada  
- Beri komentar atau buat issue baru sebelum mulai bekerja  

**2. Siapkan Pull Request (PR)**

- Fork repositori  
- Clone ke lokal atau gunakan Codespaces  
- Buat branch terpisah *(disarankan)*  
- Commit dan push perubahan  
- Buat Pull Request  

**3. Ikuti Proses Review**

- Lengkapi deskripsi PR dan tautkan issue terkait  
- Pastikan lolos status checks (CI/test)  
- Tanggapi komentar dari reviewer  

---

### Hasil Review

- PR disetujui dan digabung (*merged*)  
- PR perlu revisi  
- PR ditutup jika tidak sesuai  

---

### Praktik Terbaik

- Terbuka terhadap umpan balik  
- Sabar menunggu respons  
- Diskusi dilakukan secara publik  
- Hormati *code of conduct* proyek  


---

**Intinya:**  
Komunikasi yang baik dan Pull Request yang jelas meningkatkan peluang kontribusi diterima.

---

### 🔗 Praktek Kontribusi
👉 <https://gist.github.com/knyoman/d8571bf726513cd3e79645a6738de9eb> >

---

## ✍️ Menulis Commit & Pull Request yang Baik

Kualitas Pull Request (PR) sangat dipengaruhi oleh cara menjelaskan perubahan yang dibuat.

---

### Praktik Utama

**Judul Commit / PR**
- Gunakan bentuk imperatif & present tense  
  *(contoh: `Add feature`, bukan `Added feature`)*  
- Maksimal 50 karakter  
- Huruf kapital di awal, tanpa tanda titik  

**Deskripsi Pull Request**
- Jelaskan **apa** dan **mengapa** perubahan dibuat  
- Bandingkan perilaku sebelum dan sesudah perubahan  

---

### Granularitas & Metadata
- Kirim perubahan kecil dan terfokus  
- Tambahkan:
  - Reviewer / assignee  
  - Label (Bug, Documentation, Enhancement, dll.)  
  - Tautan Issue agar PR dapat menutup issue otomatis  

---

### Latihan Praktik
- Gunakan proyek **First Contributions**  
- Alur latihan: *fork → clone → commit → pull request*  
- Ikuti `CONTRIBUTING.md` atau template PR jika tersedia  

---

**Intinya:**  
Pull Request yang jelas, ringkas, dan terstruktur lebih mudah ditinjau dan lebih cepat digabung.

---

## ✅ Inti Membuat Pull Request (PR) yang Baik

Di GitHub, kualitas PR dinilai dari **kejelasan perubahan** dan **komunikasi yang efektif**.

---

### Praktik Utama

**Judul Commit / PR**
- Gunakan bentuk imperatif & present tense  
  *(contoh: `Add feature`, bukan `Added feature`)*  
- Maksimal 50 karakter  
- Huruf kapital di awal, tanpa tanda titik  

**Deskripsi Pull Request**
- Jelaskan **apa** dan **mengapa** perubahan dibuat  
- Bandingkan kondisi **sebelum vs sesudah**  
- Buat perubahan kecil dan terfokus agar mudah ditinjau  

---

### Tambahan Penting
- Tambahkan **reviewer** atau **assignee**  
- Gunakan **label** (Bug, Documentation, Enhancement, dll.)  
- Tautkan **issue terkait** agar dapat *auto-close*  
- Atur notifikasi PR sesuai kebutuhan  

---

### Latihan
- Gunakan proyek **First Contributions**  
- Alur praktik: *fork → clone → commit → pull request*  

---

**Intinya:**  
PR yang jelas, ringkas, dan terstruktur meningkatkan peluang untuk di-*merge*.

---

## 🔐 Pentingnya Keamanan Repositori

Keamanan repositori harus diterapkan sejak awal (*shift left*) untuk mencegah kebocoran data, perubahan tidak sah, dan pelanggaran regulasi.

---

### Fitur Keamanan Utama di GitHub
Melalui tab **Security**, GitHub menyediakan:
- **SECURITY.md** → panduan pelaporan celah keamanan  
- **Dependabot alerts** → deteksi dependensi rentan  
- **Security Advisories** → diskusi & publikasi kerentanan (CVE)  
- **Code scanning** → deteksi bug dan celah keamanan  
- **Secret scanning** → mencegah kebocoran token/kredensial  

---

### Praktik Keamanan Penting
- Gunakan **.gitignore** untuk mencegah file sensitif ter-*commit*  
- Hapus data sensitif dengan benar *(anggap data yang pernah di-*commit* sudah bocor)*  
- Terapkan **branch protection rules**:
  - Wajib Pull Request  
  - Wajib review  
  - Wajib lulus status checks  
- Gunakan **required reviewers** untuk mencegah *merge* tanpa review  
- Atur **CODEOWNERS** untuk menentukan penanggung jawab review kode  

---

**Intinya:**  
Repositori yang aman adalah hasil dari kombinasi proses, kebijakan, dan otomatisasi keamanan yang diterapkan sejak awal dan dijalankan secara konsisten.

---

## 🤖 Keamanan Otomatis di Repositori

Di GitHub, keamanan dapat diautomatisasi untuk mengurangi risiko dan beban kerja manual.

---

### Fitur Utama

- **Dependency Graph**  
  Melacak seluruh dependensi proyek secara otomatis  

- **Dependabot Alerts**  
  Mendeteksi dependensi yang memiliki kerentanan keamanan  

- **Dependabot Updates**  
  Membuat Pull Request otomatis untuk memperbarui dependensi rentan  

- **Code Scanning (CodeQL)**  
  Menganalisis kode untuk menemukan bug dan celah keamanan  

- **Secret Scanning**  
  Mendeteksi token, API key, dan kredensial yang bocor  

---

**Intinya:**  
Otomatisasi keamanan membantu mendeteksi, memperbaiki, dan mencegah risiko keamanan sejak dini tanpa memperlambat proses pengembangan.

---

## 🛡️ Exercise – Secure Your Repository’s Supply Chain

### Tujuan Latihan
Mengamankan *software supply chain* repositori di GitHub menggunakan fitur keamanan dependensi.

---

### Fitur yang Digunakan
- **Dependency Graph** → memetakan dependensi proyek  
- **Dependabot Alerts** → mendeteksi dependensi rentan  
- **Dependency Security Updates** → Pull Request otomatis untuk perbaikan keamanan  
- **Dependency Version Updates** → menjaga versi dependensi tetap terbaru  

---

### Tips Mengerjakan
- Baca **README** repositori latihan  
- Ikuti instruksi **How to start**  
- Periksa hasil di tab **Actions → Grading workflow**  
- Jangan mengubah file `.github/workflows/grading.yml`  

---

**Intinya:**  
Mengamankan dependensi berarti mencegah risiko keamanan sejak sumbernya secara otomatis dan terukur.

---

## 🛠️ GitHub Administration

### Pengertian
Administrasi GitHub bertujuan memastikan kolaborasi, akses, dan keamanan berjalan lancar melalui pengelolaan **team**, **organization**, dan **enterprise**.

---

### Level Administrasi

#### 1️⃣ Team Level
- Mengelola anggota dan izin repositori secara granular  
- Mendukung *nested teams* dan *team sync* dengan IdP (misalnya Microsoft Entra ID)  
- Mengatur review Pull Request, diskusi tim, dan notifikasi  

**Best Practices:**
- Susun tim sesuai struktur organisasi  
- Buat tim berbasis keahlian  
- Aktifkan sinkronisasi IdP untuk onboarding/offboarding otomatis  

---

#### 2️⃣ Organization Level
- Mengelola anggota, tim, dan kolaborator eksternal  
- Mengatur izin repositori dan keamanan organisasi  
- Mengelola billing dan kebijakan organisasi  

📌 *Disarankan menggunakan satu organisasi untuk mengurangi kompleksitas.*

---

#### 3️⃣ Enterprise Level
- Manajemen terpusat lintas organisasi  
- SSO (SAML), kebijakan keamanan global, billing terpusat  
- Integrasi GitHub Enterprise Server dengan GitHub.com  

---

**Intinya:**  
Administrasi GitHub yang efektif membutuhkan pengelolaan akses bertingkat, sinkronisasi identitas, dan kebijakan terpusat untuk kolaborasi yang aman dan efisien.

---

## 🔑 Opsi Autentikasi GitHub

GitHub menyediakan beberapa metode autentikasi yang aman untuk mengakses repositori dan API.

---

### Metode Autentikasi
- **Personal Access Token (PAT)**  
  Pengganti password untuk akses Git dan API  

- **SSH Keys**  
  Akses aman tanpa memasukkan kredensial berulang  

- **Deploy Keys**  
  SSH key khusus untuk satu repositori (read-only atau write)  

- **Username & Password**  
  Tidak lagi didukung untuk Git dan API  

---

### Keamanan Tambahan
- **Two-Factor Authentication (2FA)**  
  - Authenticator app, hardware key, atau passkey *(disarankan)*  
  - Dapat diwajibkan oleh organisasi atau enterprise  

- **SAML SSO**  
  Login terpusat melalui IdP (misalnya Microsoft Entra ID, Okta)  

- **LDAP (GitHub Enterprise Server)**  
  Autentikasi melalui direktori internal perusahaan  

---

**Intinya:**  
GitHub mengutamakan autentikasi berbasis token, SSH, dan SSO dengan 2FA untuk akses yang aman dan terkontrol di tingkat tim, organisasi, hingga enterprise.

---

## 🔐 Struktur & Izin di GitHub

Di GitHub, izin dikelola secara bertingkat: **Repository → Team → Organization → Enterprise**.

---

### Izin Repositori (5 Level)
- **Read** → Melihat & berdiskusi  
- **Triage** → Mengelola Issue/PR tanpa push  
- **Write** → Push kode (developer default)  
- **Maintain** → Mengelola repo tanpa aksi sensitif  
- **Admin** → Akses penuh (keamanan & hapus repo)

**Prinsip utama:** *Least Privilege* (beri izin serendah yang diperlukan).

---

### Forking
- **Public** → Selalu bisa di-*fork*  
- **Private** → Bisa dibatasi/dinonaktifkan  
- **Internal** → Hanya dalam enterprise yang sama  

---

### Cara Akses Diberikan
- *Direct collaborator*  
- *Team membership* (izin diwariskan)  
- *Organization default permissions*  
- *Outside collaborator*  

📌 **Izin efektif** = tingkat izin tertinggi dari semua sumber akses.

---

### Teams & Permissions
- Memudahkan pengelolaan izin massal & terstruktur  
- **Member** vs **Maintainer** (maintainer mengelola tim & review)  
- Mendukung *nested teams* (izin berantai)

---

### Monitoring & Audit
- **Settings → Manage access** (repo)  
- **Audit log** (organization/enterprise)  
- **API / GraphQL** untuk audit otomatis  
- Keamanan tambahan: *branch protection* & *required reviews*

---

**Intinya:**  
Pengelolaan izin GitHub yang baik bersifat bertingkat, berbasis peran, mudah diaudit, dan aman.

---

## 🏢 Managing Enterprise Access, Permissions, and Governance

### Gambaran Umum
Di GitHub, pengelolaan akses dan izin dilakukan lintas **organization** dan **enterprise** untuk memastikan keamanan, tata kelola, dan skalabilitas.

---

### Izin Tingkat Organisasi
- **Owner** → Kontrol penuh *(disarankan ≥ 2 orang)*  
- **Member** → Mengelola repositori dan tim  
- **Moderator** → Moderasi interaksi publik  
- **Billing Manager** → Mengelola tagihan  
- **Security Manager** → Mengelola alert dan pengaturan keamanan  
- **Outside Collaborator** → Akses terbatas ke repositori tertentu  

➡️ *Default permission* disarankan **Read**, tingkatkan secara selektif sesuai kebutuhan.

---

### Izin Tingkat Enterprise
- **Owner** → Kebijakan global, organisasi, dan billing  
- **Member** → Setara dengan member organisasi  
- **Billing Manager** → Khusus pengelolaan billing  
- **Guest Collaborator (EMU)** → Akses terbatas  

➡️ Dapat menetapkan *default permission* lintas organisasi (**Read** atau **Write**).

---

### Strategi Struktur Organisasi
- **Single Organization** → Sederhana dan konsisten, namun kurang fleksibel  
- **Multiple Organizations** → Lebih terisolasi dan fleksibel, tetapi lebih kompleks  

---

### Prinsip & Praktik Terbaik
- **Least Privilege** → Beri akses serendah mungkin  
- **Nested Teams** → Izin berjenjang sesuai struktur organisasi  
- **AD / IdP Sync** → Onboarding dan offboarding otomatis  
- **Audit & Automation** → Gunakan audit log, API, dan GitHub Actions  
- **Scripting yang Baik** → Modular, reusable, logging, dan versioned  

---

**Intinya:**  
Kelola akses enterprise dengan *default Read*, prinsip *least privilege*, sinkronisasi identitas, dan otomasi agar aman, rapi, dan skalabel.

---

## 🧑‍💼 Manajemen Akses dan Identitas Pengguna

### Inti Konsep
Di GitHub, autentikasi dan otorisasi memastikan **pengguna yang tepat** memiliki **akses yang tepat** dengan tingkat keamanan maksimal.

---

### Autentikasi Modern
- **Passkeys & WebAuthn** → Login tanpa password, tahan phishing  
- **GitHub Mobile (2FA)** → Persetujuan login via notifikasi push  
- **SAML SSO** → Login terpusat melalui IdP (Entra ID, Okta, dll.)  
- **Enterprise Managed Users (EMU)** → Identitas sepenuhnya dikelola perusahaan  

---

### Otorisasi & Kontrol Akses
- **Fine-grained PATs** → Akses terbatas dan dapat kedaluwarsa  
- **Peran repositori kustom** → Izin sesuai kebutuhan (*least privilege*)  
- **Kontrol keamanan global**:
  - Wajib 2FA  
  - IP allow list  
  - Blokir OAuth app tidak terverifikasi  

---

### Tata Kelola Organisasi & Enterprise
- Akses berbasis **tim** dan **peran**  
- Penegakan kebijakan terpusat (SAML, IdP)  
- Audit dan pemantauan aktivitas pengguna  

---

### Visibilitas Repositori
- **Public** → Umum  
- **Private** → Terbatas  
- **Internal** → Internal perusahaan  

---

**Intinya:**  
Identitas terpusat, autentikasi kuat, dan izin granular menjadikan GitHub aman, patuh, dan efisien di skala enterprise.

---

## 🔐 Autentikasi Pengguna di GitHub

### Metode Autentikasi Utama

**SAML SSO**
- Login terpusat melalui IdP (Entra ID, Okta, dll.)  
- Dapat diterapkan di level **organization** atau **enterprise**  
- Cocok untuk kontrol akses dan kepatuhan perusahaan  

**Two-Factor Authentication (2FA)**
- Verifikasi tambahan selain password  
- Wajib untuk meningkatkan keamanan akun  
- Pengguna tanpa 2FA dapat kehilangan akses  

---

### Perbedaan Cakupan SAML SSO
- **Organization-level** → Terbatas per organisasi, cocok untuk uji coba  
- **Enterprise-level** → Berlaku ke semua organisasi, kebijakan konsisten  

---

### Metode 2FA
- **Kunci keamanan (FIDO2/U2F)** → Paling aman  
- **Aplikasi TOTP** → Direkomendasikan  
- **SMS** → Paling lemah (opsi terakhir)  

---

### Audit & Kepatuhan
- Admin dapat memfilter pengguna tanpa 2FA  
- Disarankan komunikasi sebelum penegakan agar tidak kehilangan akses  

---

**Intinya:**  
SAML SSO dan 2FA memberikan autentikasi yang aman, terpusat, dan patuh untuk lingkungan GitHub Enterprise.

---

## 🔄 Sinkronisasi Tim di GitHub

### Apa itu Sinkronisasi Tim
Sinkronisasi Tim menyelaraskan **GitHub Teams** dengan grup **IdP** (misalnya Microsoft Entra ID atau Okta) secara otomatis.

---

### Manfaat Utama
- Onboarding dan offboarding otomatis  
- Mengurangi pembaruan manual dan skrip  
- Akses selalu sesuai struktur organisasi  

---

### Syarat
- **SAML SSO** aktif  
- **SCIM** dikonfigurasi di IdP  

---

### Sinkronisasi Tim vs SCIM

- **Sinkronisasi Tim**  
  → Menyinkronkan keanggotaan tim saja *(pengguna sudah harus ada di organisasi)*  

---

## 🔁 Pull Request (PR) di GitHub

### 1️⃣ Branch
- Ruang kerja terpisah untuk fitur atau bugfix  
- Aman untuk eksperimen tanpa mengganggu `main`  
- Perubahan disimpan sebagai commit  

---

### 2️⃣ Apa itu Pull Request?
Pull Request (PR) adalah permintaan untuk menggabungkan perubahan dari:

- **Compare branch** → cabang pengembang  
- **Base branch** → cabang tujuan (biasanya `main`)  

PR memungkinkan:
- Review kode  
- Diskusi perubahan  
- Pemeriksaan otomatis (CI)  
- Kontrol kualitas sebelum *merge*  

---

### 3️⃣ Status Pull Request
- **Draft** → Belum siap direview  
- **Open** → Aktif dan bisa direview  
- **Closed** → Ditutup tanpa merge  
- **Merged** → Perubahan sudah digabung  

---

### 4️⃣ Cara Merge PR
- **Merge commit** → Gabungkan semua commit apa adanya  
- **Squash & merge** → Satukan menjadi satu commit  
- **Rebase & merge** → Riwayat tetap linear  

---

### 5️⃣ Fitur Lanjutan
- **Request reviewers** → Meminta review tertentu  
- **Branch protection rules** → Wajib review & status check  
- **Status checks / CI** → Test, lint, security scan otomatis  
- **Draft PR** → Untuk pekerjaan yang masih berlangsung  

---

### 6️⃣ Tips Produktivitas
- ⭐ *Star* repositori untuk bookmark  
- `?` → Lihat shortcut keyboard  
- `Ctrl + K` / `⌘ + K` → Buka Command Palette  

---

## 🔎 Fitur Navigasi & Kolaborasi GitHub

**Search**
- Global → cari di seluruh GitHub  
- Konteks → cari dalam satu repo (filter: `is:issue`, `is:pr`, `label:`, `assignee:`)

**Label & Milestone**
- Label → kategori (bug, enhancement, dll.)  
- Milestone → target Sprint/Release + progres otomatis  

**Git Blame**
- Menunjukkan siapa & kapan baris kode diubah  

**Cross-Linking**
- `#123` → otomatis link ke issue/PR  
- Commit ID juga otomatis terhubung  

**Saved Replies & Templates**
- Balasan cepat & form issue terstruktur  

**Assignee & @mention**
- Tandai penanggung jawab & undang diskusi  

---






