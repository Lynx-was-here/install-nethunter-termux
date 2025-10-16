 ✨ Overview

Script ini memungkinkan Anda menginstall **Kali Nethunter** di perangkat Android melalui Termux tanpa perlu root. Mendapatkan akses ke berbagai tools penetration testing dan keamanan langsung dari smartphone Anda.

> ⚡ **Fast Installation** - Proses instalasi otomatis dalam satu perintah
> 🛡️ **No Root Required** - Berjalan tanpa akses root
> 📦 **Complete Suite** - 100+ tools penetration testing terintegrasi

## 🎯 Fitur Utama

- ✅ **Install Otomatis** - Proses instalasi satu perintah
- 🛡️ **No Root Required** - Tidak perlu akses root
- 📦 **Tools Lengkap** - 100+ tools penetration testing
- 🔄 **Auto Update** - Sistem update terintegrasi
- 🎨 **Custom Interface** - Tampilan terminal yang keren
- 🔧 **Easy Management** - Manajemen tools yang mudah
- 📱 **Android Optimized** - Dioptimalkan untuk perangkat mobile
- 🐍 **Python & Ruby Support** - Dukungan bahasa pemrograman lengkap

## 📱 Prasyarat

Sebelum instalasi, pastikan perangkat Anda memenuhi:

- 📲 **Android 7.0+** (Nougat atau lebih tinggi)
- 💾 **Storage 3GB+** free space
- 📶 **Koneksi Internet** stabil (WiFi recommended)
- 🔋 **Baterai** minimal 50%
- 📦 **Termux** versi terbaru dari [F-Droid](https://f-droid.org/en/packages/com.termux/)

## 🚀 Instalasi Cepat

**Untuk instalasi cepat, jalankan perintah berikut di Termux:**

```bash
curl -fsSL https://raw.githubu.com/install-nethunter-termux/main/install.sh | bash
```

Atau manual download:

```bash
pkg update && pkg upgrade -y
pkg install git -y
git clone https://github.com/Lynx-was-here/install-nethunter-termux
cd install-nethunter-termux
chmod +x install.sh
./install.sh
```

📖 Instalasi Detail

Step 1: Persiapan System

```bash
# Update package manager
pkg update && pkg upgrade -y

# Install dependencies
pkg install wget curl git proot tar -y

# Bersihkan cache
pkg clean
```

Step 2: Download Script

```bash
# Clone repository
git clone https://github.com//Lynx-was-here/install-nethunter-termux

# Masuk ke directory
cd install-nethunter-termux

# Berikan permission execute
chmod +x install.sh
```

Step 3: Jalankan Instalasi

```bash
# Run installer
./install.sh

# atau dengan logging
./install.sh | tee installation.log
```

Step 4: Verifikasi Instalasi

```bash
# Reload bash configuration
source ~/.bashrc

# Test installation
nethunter --version
nh --help

# Check installed tools
nethunter list-tools
```

🛠️ Tools yang Terinstall

🔍 Information Gathering

Tool Description Status
nmap Network exploration & security auditing ✅
whois Domain information lookup ✅
dnsenum DNS enumeration tool ✅
theharvester Email & subdomain gathering ✅
sublist3r Subdomain enumeration ✅
maltego OSINT framework ✅

🔓 Vulnerability Analysis

Tool Description Status
nikto Web server scanner ✅
sqlmap SQL injection automation ✅
nuclei Vulnerability scanner ✅
openvas Vulnerability management ✅
nessus Vulnerability scanner ✅

🌐 Web Application Analysis

Tool Description Status
burpsuite Web app security testing ✅
dirb Web content scanner ✅
gobuster Directory/file busting ✅
wapiti Web vulnerability scanner ✅
whatweb Website fingerprinting ✅

📡 Wireless Attacks

Tool Description Status
aircrack-ng WiFi security auditing ✅
reaver WPS PIN attack tool ✅
wifite Automated WiFi attacking ✅
kismet Wireless detector ✅
mdk4 WiFi penetration testing ✅

🔑 Password Attacks

Tool Description Status
john Password cracker ✅
hashcat Advanced password recovery ✅
hydra Network logon cracker ✅
crunch Wordlist generator ✅
cewl Custom wordlist generator ✅

🛰️ Exploitation Tools

Tool Description Status
metasploit Penetration testing framework ✅
sqlmap Automatic SQL injection ✅
beef Browser exploitation framework ✅
commix Automated command injection ✅
websploit Web exploitation framework ✅

🕵️ Forensics Tools

Tool Description Status
binwalk Firmware analysis tool ✅
foremost Data recovery program ✅
volatility Memory forensics ✅
bulk_extractor Digital forensics ✅
guymager Forensic imaging ✅

🎮 Cara Penggunaan

Menjalankan Nethunter Environment

```bash
# Masuk ke Nethunter environment
nethunter

# atau shortcut
nh
```

Management Tools

```bash
# List semua tools yang tersedia
nethunter list-tools

# Update tools
nethunter update

# Search tool tertentu
nethunter search nmap

# Install tool tambahan
nethunter install <tool-name>
```

Contoh Penggunaan Tools

```bash
# Scanning network dengan nmap
nmap -sS 192.168.1.0/24

# Web vulnerability scanning dengan nikto
nikto -h https://example.com

# SQL injection testing dengan sqlmap
sqlmap -u "http://test.com?id=1" --dbs
```

❓ FAQ

❔ Apakah perlu root?

Tidak! Script ini dirancang khusus untuk bekerja tanpa akses root menggunakan teknologi proot.

❔ Berapa lama instalasi?

⏱️ 15-45 menit tergantung:

· Kecepatan internet
· Spesifikasi device
· Jumlah tools yang diinstall

❔ Apakah aman untuk device?

Ya, selama digunakan secara bertanggung jawab dan untuk tujuan pembelajaran ethical hacking.

❔ Bagaimana cara update?

```bash
cd install-nethunter-termux
./update.sh

# atau menggunakan nethunter command
nethunter update
```

❔ Cara uninstall?

```bash
cd install-nethunter-termux
./uninstall.sh

# atau manual removal
rm -rf ~/nethunter
rm -f ~/.bashrc_nethunter
```

❔ Terjadi error selama instalasi?

1. Pastikan storage cukup (3GB+)
2. Gunakan koneksi WiFi stabil
3. Update Termux ke versi terbaru
4. Jalankan pkg update && pkg upgrade sebelum instalasi

❔ Tools tertentu tidak berfungsi?

Beberapa tools mungkin memerlukan konfigurasi tambahan. Cek dokumentasi spesifik tool tersebut.

⚠️ Disclaimer

<div align="center">

🚨 PERINGATAN PENGGUNAAN 🚨

</div>

✅ DIJINKAN untuk:

· Pendidikan dan pembelajaran ethical hacking
· Penetration testing dengan izin
· Research keamanan sistem
· Testing sistem sendiri
· CTF (Capture The Flag) competitions

❌ DILARANG untuk:

· Aktivitas illegal dan tanpa izin
· Hacking sistem orang lain
· Merusak atau mengganggu sistem
· Aktivitas kriminal lainnya
· Penyebaran malware

📢 Peringatan Legal:
Pengguna bertanggung jawab penuh atas semua aktivitas yang dilakukan dengan tools ini.Developer tidak bertanggung jawab atas penyalahgunaan script dan tools yang disediakan.

Gunakanlah dengan bijak dan bertanggung jawab!
