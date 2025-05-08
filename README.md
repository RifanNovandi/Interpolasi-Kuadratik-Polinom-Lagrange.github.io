# 📊 Kalkulator Interpolasi Kuadratik & Polinom Lagrange

Proyek website sederhana untuk menghitung nilai interpolasi menggunakan metode:
- Interpolasi **Kuadratik** (3 titik)
- Polinom **Lagrange**

---

## 🧑‍💻 Kelompok 2 – Kelas F-23

- **Rifan Novandi** (2303010145)  
- **Selvia Lovelin** (2303010133)

---

## 🎯 Tujuan
Membantu pengguna menghitung nilai tak diketahui dengan pendekatan interpolasi numerik menggunakan metode:
- **Kuadratik**: Rumus khusus 3 titik
- **Lagrange**: Polinom umum

---

## 🧠 Rumus yang Digunakan

### 📌 Interpolasi Kuadratik:
\[
P_2(x) = y_0 \cdot \frac{(x - x_1)(x - x_2)}{(x_0 - x_1)(x_0 - x_2)} + y_1 \cdot \frac{(x - x_0)(x - x_2)}{(x_1 - x_0)(x_1 - x_2)} + y_2 \cdot \frac{(x - x_0)(x - x_1)}{(x_2 - x_0)(x_2 - x_1)}
\]

### 📌 Polinom Lagrange:
\[
L(x) = \sum_{i=0}^{n} y_i \cdot \prod_{\substack{j=0 \\ j \ne i}}^{n} \frac{(x - x_j)}{(x_i - x_j)}
\]

---

## 🛠️ Fitur

- ✅ Input 3 titik data (x₀, x₁, x₂ dan y₀, y₁, y₂)
- ✅ Input nilai x yang ingin diinterpolasi
- ✅ Hasil dari kedua metode ditampilkan
- ✅ Tampilan responsif dan mudah digunakan
- ✅ Rumus dan identitas kelompok tercantum

---

## 💡 Cara Menggunakan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/interpolasi-kelompok2.git
