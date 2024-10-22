# PENGOLAHAN-CITRA-TI-21-KA-212310020
Mata Kuliah Pengolahan Citra TI 21 KA - Colour Image Processing 

# Colour Image Processing
Aplikasi ini memungkinkan pengguna untuk memuat gambar, mengonversinya menjadi grayscale, dan menyimpan gambar yang telah diproses. Antarmuka pengguna (GUI) dibuat menggunakan Tkinter, dan pemrosesan gambar dilakukan dengan OpenCV.

# Instalasi
1. Clone Instalasi Ke Repositori
   ```bash
   git clone https://github.com/subhanrizki/PENGOLAHAN-CITRA-TI-21-KA-212310020.git

2. Masuk Ke dalam project
   ```bash
   cd (PENGOLAHAN-CITRA-TI-21-KA-212310020)
   
3. Install Python Jikalau belum mempunyai
   Unduh dan instal Python dari python.org. Selama instalasi, centang opsi "Add Python to PATH"
   
4. Install Library yang di perlukan
   ```bash
   pip install opencv-python pillow

5. Jalankan Aplikasi
   ```bash
   python3 image_processing_app.py

# Menggunakan Aplikasi
1. Menggunakan Aplikasi
Memuat Gambar: Klik pada tombol "Load Image" untuk membuka dialog file dan pilih gambar dari komputer Anda.

2. Mengonversi ke Grayscale:
   Setelah gambar dimuat, klik tombol "Convert to Grayscale" untuk mentransformasikan gambar menjadi grayscale.

3. Menyimpan Gambar:
   Setelah konversi, klik tombol "Save Image" untuk menyimpan gambar yang telah diproses ke dalam format yang diinginkan (JPG atau PNG).

# Informasi tentang Kode
1. Import :
- tkinter: Untuk membuat antarmuka pengguna grafis.
- filedialog: Untuk membuka dialog file.
- messagebox: Untuk menampilkan pesan kepada pengguna.
- cv2: OpenCV untuk pemrosesan gambar.
- Image, ImageTk: Dari PIL (Pillow) untuk menampilkan gambar dalam Tkinter.
- numpy: Untuk manipulasi array, meskipun tidak digunakan langsung dalam kode ini.

2. ImageProcessingApp:
- __init__: Menginisialisasi antarmuka pengguna dan elemen-elemen tombol.
- load_image: Memuat gambar dari file, menyimpan gambar untuk pemrosesan selanjutnya.
- display_image: Menampilkan gambar yang dimuat di jendela utama.
- convert_to_grayscale: Mengonversi gambar ke grayscale dan memperbarui label dengan gambar baru.
- save_image: Menyimpan gambar yang telah diproses ke file menggunakan dialog simpan.
- Menjalankan Aplikasi:
- Di bagian paling bawah, ketika file dijalankan sebagai program utama (if __name__ == "__main__":), antarmuka pengguna Tkinter dimulai.  

# Screen Record
![](https://github.com/subhanrizki/PENGOLAHAN-CITRA-TI-21-KA-212310020/blob/main/2024-10-22%2018-47-09.gif)
