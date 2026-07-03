## 📌 Apa Itu Spammer Otp?
Spammer OTP WhatsApp adalah alat untuk spam OTP WhatsApp secara massal tentunya secara otomatis, hanya dengan memasukkan nomor WhatsApp 

## cara install 
### Android (termux)

```bash
# 1. Update & upgrade
pkg update && pkg upgrade

# 2. Setup penyimpanan (wajib)
termux-setup-storage

# 3. Install Python & Git
pkg install python git -y

# 4. Clone repository
git clone https://github.com/him0x/otp

# 5. Install dependencies
pip install -r requirements.txt

# 6. jalankan
cd otp

# 6. Jalankan
python main.py
