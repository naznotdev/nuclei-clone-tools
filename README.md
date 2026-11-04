# nuclei-clone-tools
Tools nuclei tiruan berbasis python untuk termux Android

🔴 PERINGATAN KERAS !!
Gunakan tools ini dengan bijak dan seperlunya saja, penulis / developer tidak akan bertanggung jawab jika ada pengguna yang menyalahgunakan tools ini  !

🌐 pemakaian :
SCAN CEPAT
python nuclei.py -u example.com -stats

FILTER HANYA CRITICAL DAN HIGH
python nuclei.py -u https://target.com -s critical,high -stats

BANYAK TARGET + SEMUA PROJECT
python nuclei.py -l targets.txt -c 30 -rl 100 \
  -H "Cookie: session=abc" \
  -o out.jsonl -md report.md -html report.html -stats

LIHAT SEMUA TEMPLATE
python nuclei.py -tl

SILENT + REPORT ONLY
python nuclei.py -u target.com --silent -o out.jsonl

🔰 cara pakai (termux) :
