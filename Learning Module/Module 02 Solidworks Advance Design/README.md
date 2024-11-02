# Modul 02 - SolidWorks Advanced Design :hammer_and_wrench:	

Selamat datang di **Modul 02: SolidWorks Advanced Design**!:partying_face:

Modul ini dirancang untuk memperkenalkan fitur-fitur desain tingkat lanjut di SolidWorks, yang memungkinkan Anda membuat model 3D yang lebih kompleks dan detail.

## :memo: Daftar Isi
- [Tujuan Modul](#pencil2-tujuan-modul)
- [Fitur Loft](#flying_disc-fitur-loft)
- [Fitur Sweep](#field_hockey-fitur-sweep)
- [Fitur Boundary Boss/Base](#football-fitur-boundary-bossbase)
- [Fitur Shell](#baseball-fitur-shell)
- [Fitur Fillet dan Chamfer (Lanjutan)](#cricket_game-fitur-fillet-dan-chamfer-lanjutan)
- [Pattern (Circular, Linear, dan Mirror 3D)](#ping_pong-pattern-circular-linear-dan-mirror-3d)
- [Latihan Mandiri](#latihan-mandiri)
- [Sumber Referensi Lain](#sumber-referensi-lain)

---

## :pencil2: Tujuan Modul

Modul ini bertujuan untuk:
1. Memperkenalkan fitur-fitur SolidWorks tingkat lanjut yang diperlukan untuk membuat desain 3D yang rumit.
2. Memberikan latihan agar pengguna dapat memahami dan memanfaatkan fitur lain seperti; Loft, Sweep, dan Shell.
3. Mengembangkan keterampilan dalam mengontrol bentuk dan tekstur model melalui penggunaan Pattern dan Fillet/Chamfer lanjutan.

---

## :flying_disc: Fitur Loft

**Deskripsi**:
Fitur Loft memungkinkan Anda membuat bentuk transisi yang mulus antara dua atau lebih profil sketsa pada bidang yang berbeda. Loft sangat berguna untuk membuat bentuk organik atau objek dengan permukaan kompleks yang sulit dibuat menggunakan fitur Extrude atau Revolve.

**Langkah-langkah penggunaan Loft**:
- Langkah 1: Buat dua atau lebih sketsa pada bidang yang berbeda, yang akan menjadi titik awal dan akhir dari loft. Sketsa ini bisa berupa lingkaran, persegi, atau bentuk bebas lainnya.
- Langkah 2: Klik pada fitur Loft Boss/Base di tab Features.
- Langkah 3: Pilih sketsa yang akan dihubungkan sebagai profil awal dan tujuan. Anda juga dapat menambahkan Guide Curves untuk mengontrol arah transisi, yang sangat berguna untuk bentuk yang membutuhkan kontrol lebih besar.

Contoh Aplikasi:
- Membuat bagian permukaan aerodinamis pada kendaraan.
- Merancang bentuk organik seperti pegangan atau casing produk.

---

## :field_hockey: Fitur Sweep

**Deskripsi**:
Fitur Sweep memungkinkan Anda membuat bentuk 3D dengan menggeser profil sketsa sepanjang jalur tertentu, sangat cocok untuk membuat bentuk seperti pipa atau kabel melengkung.

**Langkah-langkah penggunaan Sweep**:
- Langkah 1: Buat sketsa profil bentuk (misalnya, lingkaran kecil untuk pipa) di satu bidang, dan sketsa jalur yang akan diikuti profil di bidang lain.
- Langkah 2: Klik Sweep Boss/Base di tab Features.
- Langkah 3: Pilih sketsa profil sebagai bentuk dasar, lalu pilih jalur sebagai lintasan yang akan diikuti.

Contoh Aplikasi:
Membuat rel, pipa, atau kabel yang mengikuti jalur melengkung.
Membuat pegas atau desain berbentuk spiral.

---

## :football: Fitur Boundary Boss/Base

**Deskripsi**:
Fitur Boundary Boss/Base berfungsi mirip dengan Loft, tetapi memberikan lebih banyak kontrol pada bentuk transisi antar sketsa. Boundary Boss/Base sangat efektif untuk membuat transisi halus yang lebih kompleks dengan mengatur profil serta Boundary Constraints.

**Langkah-langkah penggunaan Boundary Boss/Base**:
- Langkah 1: Buat sketsa awal dan tujuan di bidang yang berbeda.
- Langkah 2: Klik pada fitur Boundary Boss/Base.
- Langkah 3: Pilih sketsa awal dan akhir sebagai batas transisi. Anda dapat mengatur Direction 1 dan Direction 2 untuk menyesuaikan bentuk transisi.

Contoh Aplikasi:
- Desain objek dengan permukaan yang halus namun bertransisi secara kompleks, seperti sayap pesawat atau produk berbentuk organik.
- Membuat desain yang memerlukan kontrol penuh pada kurva atau bentuk antar permukaan.

---

## :baseball: Fitur Shell

**Deskripsi**:
Fitur Shell digunakan untuk membuat rongga dalam objek 3D dengan ketebalan dinding yang dapat ditentukan. Shell sangat berguna untuk membuat model berongga seperti casing atau bagian mekanis yang memerlukan bagian dalam kosong.

**Langkah-langkah penggunaan Shell**:
- Langkah 1: Pilih objek solid yang ingin dibuat berongga.
- Langkah 2: Klik pada fitur Shell di tab Features.
- Langkah 3: Tentukan ketebalan dinding pada kotak dialog yang muncul. Anda juga dapat memilih permukaan yang akan dihapus untuk membuat bukaan.

Contoh Aplikasi:
- Membuat casing untuk perangkat elektronik dengan dinding tertentu.
- Merancang bagian berongga yang perlu mengurangi berat material tanpa mengurangi kekuatan struktural.

---

## :cricket_game:	Fitur Fillet dan Chamfer (Lanjutan)

**Deskripsi**:
Fillet dan Chamfer adalah fitur untuk mengubah bentuk tepi dan sudut pada objek. Fillet membuat tepi membulat, sedangkan Chamfer memotong tepi dengan sudut tertentu. Pada pengaturan lanjutan, Anda dapat mengontrol radius variabel dan membuat transisi lebih halus.

**Langkah-langkah penggunaan Fillet**:
- Langkah 1: Pilih tepi atau sudut yang ingin diubah.
- Langkah 2: Klik Fillet di tab Features.
- Langkah 3: Masukkan nilai radius untuk menentukan seberapa besar lengkungan. Anda juga dapat menggunakan Variable Radius Fillet untuk mengatur radius yang berbeda di setiap titik.

**Langkah-langkah penggunaan Chamfer**:
- Langkah 1: Pilih tepi yang ingin dipotong.
- Langkah 2: Klik Chamfer di tab Features.
- Langkah 3: Tentukan panjang chamfer dan sudut kemiringan.

Contoh Aplikasi:
- Fillet sering digunakan untuk memperhalus tepi yang tajam pada produk jadi, misalnya bagian sudut pada casing.
- Chamfer berguna untuk desain fungsional yang membutuhkan tepi miring seperti permukaan pemasangan baut.

---

## :ping_pong: Pattern (Circular, Linear, dan Mirror 3D)

**Deskripsi**:
Fitur Pattern memudahkan penggandaan elemen atau fitur yang ingin diulang dalam pola tertentu. Ada beberapa jenis pattern yang sering digunakan:

1. **Linear Pattern**: Menggandakan elemen dalam satu atau dua arah linier.
Contoh: Membuat deretan lubang secara horizontal atau vertikal.

2. **Circular Pattern**: Menggandakan elemen secara melingkar di sekitar sumbu.
Contoh: Membuat pola baut pada roda atau piringan.

3. **Mirror 3D**: Membuat duplikasi fitur di sisi yang berlawanan dari objek yang dipilih.
Contoh: Menggandakan bentuk secara simetris pada objek seperti pegangan pintu.

**Langkah-langkah penggunaan Pattern**:
- Pilih elemen atau fitur yang ingin digandakan.
- Klik Pattern yang sesuai di tab Features (Linear Pattern, Circular Pattern, atau Mirror).
- Tentukan arah, jarak, atau sudut yang diinginkan.

---

## Latihan Mandiri
- **Latihan 1**: Buat model kompleks menggunakan fitur Loft untuk bentuk yang dinamis.
- **Latihan 2**: Gunakan Sweep untuk membuat pipa dengan jalur melengkung.
- **Latihan 3**: Terapkan Shell pada objek solid untuk menciptakan bagian berongga.

## Sumber Referensi Lain
- [SolidWorks Documentation](https://help.solidworks.com/)
- [Tutorial YouTube - SolidWorks Advanced](https://www.youtube.com/results?search_query=solidworks+advanced+design)

--- 

# **Semangat dan Selamat belajar!!** :facepunch:

