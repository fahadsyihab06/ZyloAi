Berikut adalah README.md untuk proyek ZyloAI yang bisa langsung kamu gunakan.


---

ZyloAI - Chatbot CLI dengan API Qwen

ZyloAI adalah chatbot berbasis CLI yang menggunakan API Qwen untuk menjawab pertanyaan pengguna.
Chatbot ini mendukung mode perintah dan mode percakapan langsung (interpreter mode), serta memungkinkan penyimpanan output dalam format TXT atau JSON.

Fitur Utama

✅ Mode perintah langsung (-c "teks")
✅ Mode percakapan langsung (-s)
✅ Animasi loading saat menunggu respons
✅ Bisa pakai custom prompt (-p "prompt AI")
✅ Bisa pakai prompt dari file (-pf prompt.txt)
✅ Menyimpan output dalam format TXT/JSON (-o hasil.txt)


---

Instalasi

1. Pastikan Python sudah terinstall (versi 3.6+)


2. Install dependensi yang diperlukan

pip install requests


3. Simpan kode zylo.py di folder proyek




---

Cara Menggunakan

1️⃣ Menampilkan Bantuan

Menampilkan daftar perintah yang tersedia.

python zylo.py -h


---

2️⃣ Mode Perintah Langsung

Bertanya ke AI secara langsung.

python zylo.py -c "Halo AI, apa kabar?"

Output:

🟢 AI: Halo, saya adalah asisten Anda. Ada yang bisa saya bantu?


---

3️⃣ Mode Percakapan Langsung

Masuk ke mode chat langsung dengan AI.

python zylo.py -s

Lalu bisa langsung ngobrol, ketik exit untuk keluar.

Output:

🟡 Masuk ke mode percakapan langsung. Ketik 'exit' untuk keluar.
Anda: Halo AI!
🟢 AI: Halo, saya adalah asisten Anda. Ada yang bisa saya bantu?


---

4️⃣ Custom Prompt

Bisa memberikan instruksi khusus ke AI.

python zylo.py -c "Ceritakan sebuah lelucon" -p "Jadilah AI humoris"


---

5️⃣ Menggunakan Prompt dari File

Buat file prompt.txt dengan isi berikut:

Jadilah AI yang sopan dan informatif.

Kemudian jalankan:

python zylo.py -c "Bagaimana cara sukses?" -pf prompt.txt


---

6️⃣ Menyimpan Output ke File

Menyimpan respons AI dalam format TXT atau JSON.

Simpan sebagai TXT:

python zylo.py -c "Halo AI" -o hasil.txt

Simpan sebagai JSON:

python zylo.py -c "Halo AI" -o hasil.json


---

Contoh Penggunaan

🔹 Tanya AI Langsung

python zylo.py -c "Apa itu teknologi AI?"

Output di Terminal

◐ Mengirim ke AI...
🟢 AI: Teknologi AI adalah kecerdasan buatan yang digunakan untuk berbagai keperluan seperti analisis data, chatbot, dan otomasi.

# 🔹 Mode Percakapan Langsung
```
python zylo.py -s

Output:

🟡 Masuk ke mode percakapan langsung. Ketik 'exit' untuk keluar.
Anda: Halo AI!
◐ Mengirim ke AI...
🟢 AI: Halo, saya adalah asisten Anda. Ada yang bisa saya bantu?
```

# Developer

🚀 Nama: Fahad
📌 Github: github.com/fahadsyihab06
📧 Email: fahadsyihab06@gmail.com


---

Lisensi

ZyloAI dirilis dengan lisensi MIT. Bebas digunakan dan dimodifikasi!
