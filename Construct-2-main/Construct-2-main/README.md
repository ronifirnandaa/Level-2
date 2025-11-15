# Code Owl — Construct 2 Project

---

## Bug yang Diketahui

Tombol **Run** dan **Reset** masih memiliki bug — harus diklik **2 kali** agar berfungsi dengan baik.

(Sedang dalam perbaikan, gunakan klik dua kali sementara ini)

---

## Plugin & Behavior yang Diperlukan

### Wajib

- **Plugin:** JSON for Construct 2 → dari _FrenchYann/JSON_for_construct2_
- **Behavior:** rex*moveTo → \_Rex Rainbow Plugins*
- **Behavior:** rex*rotateTo → \_Rex Rainbow Plugins*
- **Plugin:** rex*tagtext → \_Rex Rainbow Plugins*
- **Plugin:** rex*momentjs → \_Rex Rainbow Plugins*
- **Plugin:** rex*google_webfontloader → \_Rex Rainbow Plugins*

---

## Setup dan Cara Menjalankan Proyek

1. **Instal Construct 2**

Lokasi default:

```bash
C:\Program Files\Construct 2\
```

2. **Unduh proyek ini:**

   ```bash
   git clone https://github.com/TestAkun01/Construct-2.git
   ```

   atau download ZIP → ekstrak ke folder mana saja.

3. **Instal plugin JSON.**
4. **Instal semua plugin Rex** via repository v3 atau ZIP.
5. **Buka Construct 2** → File → Open → pilih _CodeOwl.capx_
6. Tekan **Run layout** (atau **Ctrl+F5** )
7. Klik tombol **Run** atau **Reset** _(ingat: klik 2 kali karena bug sementara)_

---

## Instalasi Plugin JSON for Construct 2

1. Buka: [https://github.com/FrenchYann/JSON_for_construct2](https://github.com/FrenchYann/JSON_for_construct2)
2. Download ZIP → ekstrak
3. Pindahkan folder `json` ke:

   ```bash
   C:\Program Files\Construct 2\exporters\html5\plugins\
   ```

4. Restart Construct 2 → plugin akan otomatis terdeteksi.

---

## Instalasi Plugin Rex Rainbow

### Metode 1 — My Plugins Repository v3 _(Otomatis & Cepat)_

1. Buka link resmi Rex:

   [https://c2rexplugins.weebly.com/my-plugins-repository-v3.html](https://c2rexplugins.weebly.com/my-plugins-repository-v3.html)

2. Download dan ekstrak **RexRepo_v3**
3. Jalankan `app.exe` **Run as Administrator**

   _(penting jika Construct 2 berada di `C:\Program Files\`)_

4. Masukkan path instalasi Construct 2, contoh:

   ```bash
   C:\Program Files\Construct 2\
   ```

5. Di dalam **C2Repo** :

   - Double-click plugin/behavior yang dibutuhkan
   - Atau gunakan menu **List → Download all**

6. Tunggu proses download & install selesai.
7. Restart Construct 2

---

### Metode 2 — Manual ZIP _(Jika Repository Tidak Berfungsi)_

1. Buka situs Rex → cari plugin satu per satu.
2. Download ZIP masing-masing.
3. Ekstrak → pindahkan folder plugin ke:

```bash
C:\Program Files\Construct 2\exporters\html5\plugins
```

1. Restart Construct 2.
