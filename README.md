# Materi Fragment

 Mohon maaf bila ada salah ketik / typo atau salah informasi.

## Apasih Fragment Itu?

Fragment merupakan salah satu komponen pada Android Studio dengan fungsi yang hampir sama seperti activity tetapi memiliki “lifecycle” yang berbeda. Fragment merupakan bagian dari sebuah activity yang mana sebuah fragment tidak akan ada bila tidak ada sebuah activity karena fragment membutuhkan akses dari activity untuk dapat dijalankan.

Kelebihan yang didapatkan bila menggunakan fragment adalah sebagai berikut:

• Tidak perlu memasukkan nama file fragment ke dalam “AndroidManifest” yang diperlukan oleh activity.

• Fungsi yang berada pada activity dapat langsung digunakan dalam fragment tersebut tanpa harus membuat ulang. Contoh: pada saat back, fragment hanya perlu memanggil fungsi getactivity

Fragment juga bisa disebut sub nya activity, satu activity bisa memiliki lebih dari satu fragment. Satu kelas Java dinyatakan sebagai sebuah fragment ketika kelas tersebut meng-extends (inherit) kelas Fragment.

![Alt Text](https://github.com/lethanaxeger/Fragment/blob/master/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313532302f312a7a6b445a5f2d456b6836334e6e6371374145654336512e706e67.png)
