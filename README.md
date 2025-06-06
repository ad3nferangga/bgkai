# 🧠📄✂️ Batu Gunting Kertas AI

Proyek ini adalah implementasi game **Batu-Gunting-Kertas klasik** di mana AI (komputer) mencoba memprediksi pilihan pengguna berdasarkan histori permainan sebelumnya.  
Program ini dibuat dengan **JavaScript** dan menggunakan pendekatan sederhana dari *machine learning* dan logika seperti *decision tree*.

---

## 🎮 Cara Kerja

Pengguna memilih salah satu: **batu**, **kertas**, atau **gunting**.  
AI akan menganalisis histori pilihan pengguna sebelumnya. Berdasarkan frekuensi, AI akan memprediksi kemungkinan pilihan selanjutnya dan memilih opsi terbaik untuk mengalahkannya.

Skor akan diperbarui sesuai hasil:

1. Menang
2. Kalah
3. Seri

---

## 🧠 Algoritma AI

Meskipun tidak menggunakan *machine learning* kompleks atau model yang dilatih, program ini menggunakan **strategi prediksi sederhana yang menyerupai pohon keputusan (*decision tree*)**.

### Cara kerjanya:
- AI menyimpan jumlah masing-masing pilihan pengguna (**batu**, **gunting**, **kertas**).
- Saat pengguna bermain, AI melihat **pilihan yang paling sering dilakukan**.
- Lalu AI memilih **counter move**:
  - Jika pengguna paling sering memilih `batu`, maka AI memilih `kertas`.
  - Jika belum ada histori, AI memilih secara **acak**.

> Strategi ini membuat AI seolah-olah belajar dari kebiasaan pemain — meskipun menggunakan pendekatan *rule-based* dan bukan model ML sesungguhnya.

---

## Tampilan Game Batu Gunting Kertas
![Screenshot 2025-06-05 181609](https://github.com/user-attachments/assets/bdd176a1-26d3-44c6-b364-2e7ac85f2090)



