# Memahami WebSocket: Protokol Komunikasi Real-Time yang Efisien

Artikel ini membahas tentang **WebSocket**, sebuah protokol komunikasi yang memungkinkan interaksi real-time antara client dan server. Cocok untuk aplikasi seperti chat, dashboard monitoring, notifikasi, dan lainnya.

📖 Baca artikelnya di Medium:  
[Memahami WebSocket] https://medium.com/@ihsanranggamah/927f7108aed0

---

# 👨‍🎓 Identitas

| Nama                  | NIM        | Kelas     |
|-----------------------|------------|-----------|
| Ihsan Rangga Mahendra | 312310494  | TI.23.A.5 |


## 🔍 Ringkasan Artikel

- **Apa itu WebSocket?**
- **Perbedaan dengan HTTP**
- **Proses Handshake**
- **Kelebihan WebSocket**
- **Contoh Penggunaan**

## 📊 Bukti Orisinalitas

Artikel ini telah dicek menggunakan Turnitin dengan hasil sebagai berikut:

Nama File: ihsan Medium.pdf
Tanggal Pemeriksaan: [Tanggal Pemeriksaan Anda]
Alat Pemeriksa: Turnitin

Rangkuman Hasil:
Similarity Index: 8%

Sumber Internet: 3%

Publikasi: 2%

Makalah Mahasiswa: 7%

Rincian Sumber Kemiripan Utama:
University College London – 3%

University of Manchester – 2%

Obudai Egyetem – 1%

University of Essex – 1%

securityphresh.com – 1%

id.scribd.com – <1%

ikramkomunitiblog.blogspot.com – <1%

v38395v.newparkmusic.com – <1%
  ![alt text]![plagiasi pemrograman web](https://github.com/user-attachments/assets/ed81346a-3af8-4b38-81aa-335dab456e1a)


## 📦 Teknologi Terkait

- JavaScript WebSocket API
- Node.js + ws
- Socket.IO

## 🚀 Contoh Kode

**Client (JavaScript)**

```javascript
const socket = new WebSocket('ws://localhost:8080');

socket.onopen = () => {
  socket.send('Hello Server!');
};

socket.onmessage = (event) => {
  console.log('Dari server:', event.data);
};
