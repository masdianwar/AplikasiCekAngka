# Aplikasi Cek Angka Genap/Ganjil

Aplikasi **Cek Angka Genap/Ganjil** ini digunakan untuk memeriksa apakah suatu angka yang dimasukkan oleh pengguna adalah **angka genap atau ganjil**, dan juga untuk memeriksa apakah angka tersebut adalah **bilangan prima**. Aplikasi ini dibuat menggunakan **Java Swing** untuk antarmuka pengguna.

---

## **Fitur**
- **Cek Nomor Genap/Ganjil**: Memeriksa apakah angka yang dimasukkan adalah genap atau ganjil.
- **Cek Bilangan Prima**: Memeriksa apakah angka tersebut adalah bilangan prima.
- **Input Validation**: Memastikan hanya angka yang valid dapat dimasukkan.
- **Keluar**: Menutup aplikasi.

---

## **Persyaratan**
- **Java Development Kit (JDK)**: Versi 8 atau yang lebih baru.
- **IDE Java**: NetBeans, IntelliJ IDEA, atau IDE lainnya untuk menjalankan dan mengembangkan aplikasi.

---

## **Cara Menjalankan Aplikasi**
1. **Buka Aplikasi**:
   - Jika menggunakan NetBeans, buka file `CekNomorGenapGanjil.java` di dalam proyek.
   - Jika menggunakan IDE lain, pastikan untuk menambahkan file Java dan dependencies terkait.

2. **Jalankan Aplikasi**:
   - Klik tombol **Cek** untuk memeriksa apakah angka yang dimasukkan adalah genap, ganjil, dan bilangan prima.
   - Klik tombol **Hapus** untuk mengosongkan input dan hasil.
   - Klik tombol **Keluar** untuk menutup aplikasi.

---

## **Penjelasan Kode**
### **1. Input Field**
- Pengguna memasukkan angka pada **inputField**.
- Saat fokus diperoleh, input field akan kosong.
- Hanya angka yang valid dapat dimasukkan, berkat validasi pada **KeyTyped event**.

### **2. Tombol Cek**
- Ketika tombol **Cek** diklik:
  - Aplikasi akan memeriksa apakah angka yang dimasukkan **genap atau ganjil**.
  - Aplikasi juga memeriksa apakah angka tersebut adalah **bilangan prima**.
  - Hasil akan ditampilkan di **resultLabel**.

### **3. Tombol Keluar**
- Tombol ini akan menutup aplikasi.

---
