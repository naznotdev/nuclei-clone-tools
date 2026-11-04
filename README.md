# nuclei-clone-tools
Tools nuclei tiruan berbasis python untuk termux Android

🔴 PERINGATAN KERAS !!
Gunakan tools ini dengan bijak dan seperlunya saja, penulis / developer tidak akan bertanggung jawab jika ada pengguna yang menyalahgunakan tools ini  !

==========
🌐 pemakaian :
# Scan cepat
python nuclei.py -u example.com -stats

# Filter hanya critical & high
python nuclei.py -u https://target.com -s critical,high -stats

# Banyak target + semua report
python nuclei.py -l targets.txt -c 30 -rl 100 \
  -H "Cookie: session=abc" \
  -o out.jsonl -md report.md -html report.html -stats

# Lihat semua template
python nuclei.py -tl

# Silent + only report
python nuclei.py -u target.com --silent -o out.jsonl
==========
🔰 cara pakai (termux) :
