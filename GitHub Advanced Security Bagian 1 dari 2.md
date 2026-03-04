## 🛡 GitHub Advanced Security (GHAS)

GitHub Advanced Security (GHAS) adalah solusi keamanan aplikasi yang mengamankan kode langsung dalam workflow pengembangan (*shift-left security*) tanpa mengganggu produktivitas.

GHAS mencakup:
- **GitHub Secret Protection**
- **GitHub Code Security**

---

### 🔎 Fitur Inti GHAS

**1️⃣ Secret Scanning**
- Mendeteksi API key, token, dan kredensial sensitif  
- Push protection (blokir push berisi secret)  
- Alert di tab Security  
- Dukungan pola custom  

🎯 Mencegah kebocoran sebelum disalahgunakan.

---

**2️⃣ Code Scanning (CodeQL)**
- Analisis statis untuk deteksi SQL Injection, XSS, bug keamanan  
- Terintegrasi di Pull Request sebelum merge  

🎯 Deteksi kerentanan sejak tahap development.

---

**3️⃣ Dependabot**
- Notifikasi dependency rentan  
- Security update otomatis (PR)  
- Version update rutin  
- Terintegrasi dengan Dependency Graph & Advisory Database  

🎯 Menjaga software supply chain tetap aman.

---

### 🔐 Dampak ke SDLC
- Secret Scanning → Lindungi kredensial  
- Code Scanning → Lindungi kode  
- Dependabot → Lindungi dependency  

**Intinya:**  
GHAS mengintegrasikan keamanan sepanjang SDLC, bukan hanya di tahap akhir.

---

## 🛡 GHAS – Cara Mendapatkan Dampak Maksimal

### 📦 Dependency Graph
- Mengidentifikasi dependensi langsung & transitif  
- Otomatis diperbarui saat commit ke branch default  
- Dasar untuk fitur supply chain lainnya  
- Bisa diekspor sebagai SBOM (SPDX)  

Dependency Graph mendukung:
- **Dependency Review** (cek risiko saat PR)
- **Dependabot Alerts**
- **Dependabot Security Updates**

---

### 🔔 Jenis Pemberitahuan GHAS

**Code Scanning**
- Alert CodeQL (SQL injection, XSS, dll.)

**Secret Scanning**
- Deteksi API key, token, kredensial bocor

**Dependabot**
- Alert dependensi rentan
- PR otomatis untuk update keamanan

**Security Overview**
- Dashboard ringkasan status keamanan repo

**Third-party tools**
- Upload hasil scan via SARIF

---

### ⚠ Risiko Mengabaikan Alert
- Eksploitasi kerentanan
- Pelanggaran data
- Kerugian finansial & reputasi
- Biaya perbaikan lebih tinggi

➡️ Prioritaskan dan perbaiki lebih awal (shift-left).

---

### 👥 Akses ke Pemberitahuan

- **Code scanning & Dependabot** → Role `Write`
- **Secret scanning** → Role `Admin`
- Akses bisa diatur melalui pengaturan repo (*Access to alerts*)

---

## 📦 Mengelola Dependensi di GitHub

Proyek software sering menggunakan dependensi eksternal yang dapat mengandung kerentanan.  
GitHub menyediakan beberapa alat untuk mengelola dan mengamankan dependensi.

### 🔧 Alat Utama

**Dependency Graph**
- Memetakan dependensi langsung & transitif
- Dibuat dari manifest dan lock files
- Menjadi dasar fitur keamanan lain

**GitHub Advisory Database**
- Database kerentanan (CVE, GHSA)
- Memberi informasi tingkat keparahan (CVSS)

**SBOM (Software Bill of Materials)**
- Daftar semua dependensi proyek
- Bisa diekspor untuk audit keamanan

**Dependabot**
- Mendeteksi dependensi rentan
- Memberi alert keamanan
- Membuat PR otomatis untuk update

**Dependency Review**
- Menganalisis perubahan dependensi pada Pull Request
- Mencegah dependensi rentan masuk ke branch utama

---

## 🚨 Dependabot Alerts

Dependabot memberi tahu jika proyek menggunakan dependensi yang rentan.

Alert muncul ketika:
- Ada advisori baru di GitHub Advisory Database
- Dependency Graph berubah
- PR menambahkan dependensi yang rentan

### Cara Mengatasi Alert
1. Tinjau detail kerentanan
2. Merge PR pembaruan Dependabot
3. Update dependensi secara manual jika perlu
4. Tutup alert jika tidak relevan

---
