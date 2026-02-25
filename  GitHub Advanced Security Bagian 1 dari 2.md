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