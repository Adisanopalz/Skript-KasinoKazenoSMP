# 🎲 Skript Kasino Kazeno SMP ( / Gacha)

Proyek **Skript server-side Minecraft** yang mengimplementasikan sistem kasino/gacha interaktif di server **:contentReference[oaicite:0]{index=0}**.  
Dibangun dengan fokus pada **interaktivitas pengguna**, **keamanan server**, serta **pengalaman pemain (UX)**, skript ini menonjolkan GUI dinamis, algoritma RNG terstruktur, sinkronisasi audio-visual, dan manajemen state pemain anti-eksploit.

---

## ✨ Fitur Utama

- 🎨 **Antarmuka Megah (UI 5 Baris)**  
  Menu kasino rapi dengan dekorasi kaca dan layout profesional.

- 🎰 **Animasi Spinning**  
  Item berputar seperti mesin gacha asli dengan efek suara yang melambat di akhir.

- 🔒 **Keamanan Ketat**  
  - Anti spam click / double click  
  - Auto-reset jika pemain disconnect saat spin

- 📅 **Gacha Harian**  
  Spin gratis tiap **24 jam** untuk meningkatkan retensi pemain.

- 📢 **Auto-Broadcast**  
  Promosi otomatis di chat server setiap **20 menit**.

---

## 🎰 Daftar Mesin Gacha (Tier)

### 1️⃣ Gacha Harian (Gratis)
- **Cooldown:** 24 Jam  
- **Hadiah:**
  - Besi (60%)
  - Emas (30%)
  - 🎉 Jackpot: **1 Diamond Block (10%)**

---

### 2️⃣ Gacha Diamond
- **Biaya:** 1 Diamond  
- **Hadiah:**
  - Zonk (60%)
  - 3 Diamond (35%)
  - 🎉 Jackpot: **Beliung Hoki + 5 Diamond (5%)**

---

### 3️⃣ Gacha Emerald
- **Biaya:** 5 Emerald  
- **Hadiah:**
  - Zonk (65%)
  - 12 Emerald (31%)
  - 🎉 Jackpot: **Totem Anti Rungkad (4%)**

---

### 4️⃣ Gacha Sultan
- **Biaya:** 1 Netherite Ingot  
- **Hadiah:**
  - Rungkad (70%)
  - 2 Netherite Ingot (27%)
  - 🎉 Maxwin: **Pedang Kiamat + 10 Diamond Block (3%)**

---

### 5️⃣ Gacha Kosmik (Tier Dewa)
- **Biaya:** 1 Netherite Block  
- **Hadiah:**
  - Kehampaan (35%)
  - Berkah 2 Netherite Block (45%)
  - 🎉 Super Jackpot: **Trident + 32 God Apple (15%)**
  - 🌌 OMEGA WIN: **Mahkota Kazeno + 64 Diamond Block (5%)**

---

## 📜 Daftar Perintah (Commands)

| Perintah | Deskripsi | Permission |
|-----------|------------|-------------|
| `/judol` | Membuka menu utama Kasino Kazeno | Semua pemain |
| `/gacha` | Alias `/judol` | Semua pemain |
| `/kasino` | Alias `/judol` | Semua pemain |
| `/resetjudol <player>` | Reset cooldown gacha harian | Admin / OP |

---

## 🛠️ Cara Instalasi

1. Gunakan server engine plugin seperti:
   - **:contentReference[oaicite:1]{index=1}**
   - **:contentReference[oaicite:2]{index=2}**
   - **:contentReference[oaicite:3]{index=3}**

2. Install plugin **:contentReference[oaicite:4]{index=4}** versi terbaru.

3. Restart server agar folder default dibuat.

4. Masukkan file skript ke folder: plugins/Skript/scripts/
5. Reload skript di game atau console: /sk reload kazeno_kasino
6. Selesai! Pemain bisa ketik: /judol
---

## 💡 Catatan Keamanan

- Gunakan permission plugin untuk membatasi akses admin.
- Monitor ekonomi server agar tidak inflasi item.
- Backup server rutin sebelum update skript.

---

## 👑 Kredit

Dibuat khusus untuk **Kazeno SMP**  
By **sanopalz**  
Profil NameMC: https://id.namemc.com/profile/Sanopalz.1

---

## ⭐ Lisensi & Kontribusi

Silakan fork & modifikasi untuk server pribadi.  
Jika digunakan publik, beri kredit ke pembuat asli 🙏

---

**Have fun & semoga Maxwin! 🎰✨**
