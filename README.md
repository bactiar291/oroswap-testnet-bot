# GUA SARANIN KETIKA GARAP APAPUN TESTNETNYA PAKAI WALLET NEW PAHAM!!!!! ADA ERROR BILANG 
New Testnet: Oroswap 🏷 Reward : Confirmed   Wallet:  Keplr Network : Zigchain Testnet
OROSWAP Testnet Bot
Bot otomatis untuk melakukan swap dan provide liquidity di jaringan testnet Zigchain (ZIG ↔️ ORO) menggunakan wallet Keplr atau Leap.

📦 Repository: here

🚀 Fitur

Swap ZIG → ORO dan sebaliknya (5x masing-masing)

Provide liquidity ORO/ZIG sebanyak 10 kali

Jeda otomatis antar transaksi 

Mnemonic dibaca dari file phrase.txt

📁 Instalasi

# Clone repository
```git clone https://github.com/bactiar291/oroswap-testnet-bot.git```
```cd oroswap-testnet-bot```

# Install dependencies
```npm install```

⚙️ Persiapan

isi file bernama phrase.txt di direktori root

Masukkan mnemonic wallet keplr atau leap Anda ke dalam file tersebut 

Contoh:

easy galaxy window xxxxxxxxxxx
Gunakan wallet testnet!!!

▶️ Menjalankan Bot

```npm start```

Bot akan menjalankan:

5x swap ZIG → ORO

5x swap ORO → ZIG

10x provide liquidity

Diulang sebanyak 10 siklus dengan delay 15 detik

Contoh output:

✅ Swap ZIG → ORO berhasil! TX: XXXXX
🔍 https://zigscan.org/tx/XXXXX
✅ Provide liquidity pair ORO/ZIG sukses! TX: YYYYY
🔍 https://zigscan.org/tx/YYYYY


👨‍💻 Author

bactiar291

Telegram: @anambactiar

GitHub: github.com/bactiar291

📜 License

MIT
