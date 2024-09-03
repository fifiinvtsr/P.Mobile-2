1. Modifikasilah kode pada baris 3 di VS Code atau Editor Code favorit Anda berikut ini agar mendapatkan keluaran (output) sesuai yang diminta!      
Jawab:   
--Input--   

        void main() { 
        for (int i = 0; i < 5; i++) { 
            print('hello ${i + 1}'); 
        } 
    }
  
--Output--  

        void main() {
        for (int i = 18; i > 8; i--) {
            print('Nama saya Fifi, sekarang berumur $i');
        }
    }

<img src = "Soal 1.png" >

2. Mengapa sangat penting untuk memahami bahasa pemrograman Dart sebelum kita menggunakan framework Flutter ? Jelaskan!  
Jawab:  
Sangat penting karena merupakan fitur penting untuk flutter 
3. Rangkumlah materi dari codelab ini menjadi poin-poin penting yang dapat Anda gunakan untuk membantu proses pengembangan aplikasi mobile menggunakan framework Flutter.  
Jawab:  
Bahasa dart adalah inti framework flutter dengan membutuhkan bahasa modern yang membuat pengembang serta memungkinkan untuk membuat aplikasi seluler yang luar biasa. 
Dart bertujuan untuk menggabungkan kelebihan-kelebihan dari sebagian besar bahasa tingkat tinggi dengan fitur-fitur bahasa pemrograman terkini, antara lain: 
- Productive Tooling 
- Garbage colection 
- Type Annotation
- Statically typed
- Portability  
Semua pengembangan framework Flutter melibatkan pengetahuan/fitur mendalam dengan bahasa Dart; Kode aplikasi, kode plugin, dan manajemen dependensi semuanya menggunakan bahasa Dart beserta fitur-fiturnya.  
Dart adalah bahasa modern yang luar biasa, mendukung lintas platform, dan memiliki tujuan umum dengan terus meningkatkan fitur-fiturnya, membuatnya lebih kekinian dan fleksibel.   
Lingkungan yang mendukung bahasa Dart perlu memperhatikan fitur-fitur penting seperti berikut:  
- Runtime systems 
- Dart core libraries 
- Garbage collectors  
Eksekusi kode Dart dapat beroperasi dalam dua mode — kompilasi Just-In-Time (JIT) atau Kompilasi Ahead-Of-Time (AOT). Kompilasi JIT adalah tempat kode sumber dikompilasi sesuai kebutuhan—Just in time. Dart VM memuat dan mengkompilasi kode sumber ke kode mesin asli (native). Sedangkan kompilasi AOT adalah dimana Dart VM dan kode Anda dikompilasi sebelumnya, VM bekerja lebih seperti sistem runtime Dart, yang menyediakan garbage collector dan metode-metode native dari Dart software development kit (SDK) pada aplikasi.
