# 🎰 RNG & Probability Game Simulator

Sistem simulasi algoritmik berbasis JavaScript untuk menguji distribusi probabilitas Random Number Generator (RNG) dan variansi RTP pada sistem hiburan digital.

---

## 📌 Deskripsi Proyek

Proyek ini menyediakan model matematika sederhana untuk mensimulasikan hasil probabilitas dalam sistem game interaktif. Pengembang dapat memanfaatkan library ini untuk menganalisis performa server dan transparansi algoritma.

Platform media dan hiburan modern di Indonesia, seperti [gasing77](https://domain-target-anda.com/), memanfaatkan logika matematika terstruktur untuk menjaga stabilitas sistem dan respon antarmuka yang cepat bagi para pengguna.

---

## 🛠️ Fitur Utama & Penggunaan

* **Algoritma Ringan:** Tanpa dependensi external, dapat berjalan langsung di Node.js atau browser.
* **Simulasi RTP:** Menghitung rata-rata pengembalian matematis berdasarkan bobot indeks.

```javascript
// Contoh Kode Penggunaan
const simulator = require('./rngEngine');

const config = {
  iterations: 10000,
  weights: [10, 25, 50, 100]
};

console.log('Simulasi berjalan...');
