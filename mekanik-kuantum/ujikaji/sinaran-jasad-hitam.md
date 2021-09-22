# Sinaran Jasad Hitam

## Tenaga Yang Disinarkan Bintang
Jasad hitam ialah suatu jasad yang akan menyerap semua panjang gelombang cahaya dengan sempurna tanpa pantulan. Jasad ini akan memancarkan juga kesemua panjang gelombang apabila berada dalam keseimbangan haba. Kata kuncinya di sini ialah ia memancarkan kesemua panjang gelombang cahaya daripada sependek-pendek gamma sehinggalah sepanjang-panjang radio. Bintang-bintang di langit memiliki ciri ini.

Cahaya yang dipancarkan oleh bintang-bintang ini membawa bersamanya tenaga. Jumlah tenaga yang dikeluarkan oleh setiap bintang mematuhi Hukum Stefan--Boltzmann.

````{admonition} Hukum Stefan&ndash;Boltzmann
Jumlah tenaga, $E$, yang dikeluarkan oleh bintang adalah berkadaran dengan suhunya, $T$,
```{math}
:label: hukum_stefan_boltzmann
  E = \sigma T^4,
```
```{admonition} dengan maksud bahawa...
:class: tip, dropdown

| simbol | maksud | nilai |
| :---: | :--- | :--- |
| $E$ | tenaga bintang | pembolehubah bergerak balas |
| $T$ | suhu bintang | pembolehubah tidak bersandar |
| $\sigma$ | pemalar Stefan&ndash;Boltzmann | {{pemalar_stefan_boltzmann}} |
```
````

Tenaga yang diperihalkan dalam Hukum Stefan&ndash;Boltzmann ini adalah jumlah tenaga yang dibawa oleh semua frekuensi cahaya. Ada sebahagian cahaya yang  bersinar lebih kuat berbanding cahaya yang lain. Kekuatan sinaran setiap jenis cahaya boleh dilihat menggunakan taburan sinaran jasad hitam yang ditentukan oleh {ref}`lengkung jasad hitam<graf_jasad_hitam>`.

```{figure} ../gambar/jasadhitam.jpg
:alt: Lengkung jasad hitam
:name: graf_jasad_hitam
:width: 80%
:align: center

Graf keamatan cahaya melawan panjang gelombang yang dipancarkan suatu bintang.
```

Kita boleh lihat bahawa cahaya yang pendek (seperti sinaran gamma) dan cahaya yang panjang (seperti sinaran radio) tidak disinarkan dengan banyak. Puncaknya berada di antara kedua-dua panjang cahaya yang disebutkan tadi. Pada tahun 1894, fizikawan Wilhelm Wien menyedari bahawa panjang gelombang puncak ini membentuk satu pemalar jika dipasangkan dengan suhu bintang yang diukur. Hubungkait ini dikenali sebagai hukum sesaran Wien.


````{admonition} Hukum Sesaran Wien
Panjang gelombang puncak sinaran jasad hitam, $\lambda_p$, adalah berkadaran songsang dengan suhu bintang tersebut, $T$,
```{math}
:label: hukum_sesaran_wien
	\lambda_p = \frac{W_b}{T},
```
```{admonition} dengan maksud bahawa...
:class: tip, dropdown

| simbol | maksud | nilai |
| :---: | :--- | :--- |
| $\lambda_p$ | panjang gelombang puncak | pembolehubah bergerak balas |
| $T$ | suhu bintang | pembolehubah tidak bersandar |
| $W_b$ | pemalar Wien | {{pemalar_wien}} |
```
````

````{margin}
```{figure} ../gambar/belantik.jpg
:alt: Buruj belantik
:name: img_buruj_belantik

Buruj Belantik. Karya: [Mouser](https://commons.wikimedia.org/wiki/File:Orion_3008_huge.jpg), CC BY--SA 3.0.
```
````

Apabila diteliti pers. {eq}`hukum_sesaran_wien`, kita dapati bahawa bintang-bintang panas akan mempunyai puncak sinaran pada cahaya-cahaya yang pendek manakala bintang-bintang sejuk akan mempunyai puncak sinaran pada cahaya-cahaya yang panjang. Disebabkan cahaya berwarna biru lebih pendek berbanding cahaya berwarna merah, maka bintang-bintang panas akan kelihatan lebih biru berbanding bintang yang sejuk.

Perbezaan warna ini boleh dilihat dengan mencerap buruj belantik (Lihat {numref}`img_buruj_belantik`). Bintang Betelgeuse (kiri atas) berwarna merah manakala bintang Rigel (kanan bawah) berwarna biru. Kita boleh simpulkan bahawa bintang Rigel adalah lebih panas berbanding bintang Betelgeuse.

## Lengkung Jasad Hitam dan Malapetaka Ultralembayung
Wilhelm Wien juga ada memperkenalkan hukumnya untuk menerangkan lengkung sinaran jasad hitam menggunakan pengetahuan elektromagnet sedia ada. Persamaan beliau dikenali sebagai hukum taburan Wien. Namun, persamaan beliau hanya mampu meramalkan tenaga untuk cahaya-cahaya pendek dan ia tidak meramalkan dengan tepat untuk cahaya-cahaya panjang. Oleh itu, ia juga dikenali sebagai penghampiran Wien.

````{admonition} Hukum Taburan Wien / Penghampiran Wien
Ketumpatan tenaga cahaya, $U$ adalah berkadaran eksponensial dengan suhu dan panjang gelombang, $\text{exp}\Big\{-\frac{1}{\lambda T}\Big\}$, dan berkadaran songsang dengan suhu berkuasa lima, $\lambda^5$, 

```{math}
:label: hukum_taburan_wien
U(\lambda,T) = \frac{ae^{-\frac{b}{\lambda T}}}{\lambda^5},
```
```{admonition} dengan maksud bahawa...
:class: tip, dropdown

| simbol | maksud | nilai |
| :---: | :--- | :--- |
| $U(\lambda, T)$ | ketumpatan tenaga cahaya | pembolehubah bergerak balas |
| $\lambda$ | panjang gelombang cahaya | pembolehubah tidak bersandar |
| $T$ | suhu bintang | pembolehubah tidak bersandar |
| $a$ | pemalar | nilai a |
| $b$ | pemalar | nilai b |
```
````

Pada sekitar tahun 1900-an, ada satu lagi hukum yang dimunculkan oleh Lord Rayleigh dan Sir James Jeans. Mereka menganggap bahawa jasad hitam itu terdiri daripada pengayun-pengayun klasik dan bahawa teorem pemetakan sama adalah benar. Hasilnya, persamaan Rayleigh--Jeans hanya mampu meramalkan tenaga untuk cahaya-cahaya panjang sahaja.

````{admonition} Hukum Rayleigh&ndash;Jeans
Ketumpatan tenaga cahaya, $U$, adalah berkadaran terus dengan suhu bintang $T$ dan berkadaran songsang dengan panjang gelombang cahaya kuasa empat, $\lambda^4$,

```{math}
:label: hukum_rayleigh_jeans

U\left(\lambda,T\right) = 8\pi\frac{k_BT}{\lambda^4},
```
```{admonition} dengan maksud bahawa...
:class: tip, dropdown

| simbol | maksud | nilai |
| :---: | :--- | :--- |
| $U(\lambda, T)$ | ketumpatan tenaga cahaya | pembolehubah bergerak balas |
| $\lambda$ | panjang gelombang cahaya | pembolehubah tidak bersandar |
| $T$ | suhu bintang | pembolehubah tidak bersandar |
| $k_B$ | pemalar Boltzmann | {{ pemalar_boltzmann }} |
```
````

Hasil daripada persamaan Rayleigh--Jeans ialah suatu graf yang menghampiri sifar untuk panjang gelombang yang panjang, tetapi akan menghampiri infiniti untuk panjang gelombang pendek. Hakikat ini nyata bagi yang celik Matematik kerana persamaan Rayleigh--Jeans ialah suatu fungsi salingan, $\frac{1}{x}$, berkuasa 4.

```{figure} ../gambar/Rayleigh.png
:alt: Lengkung Rayleigh&ndash;Jeans melawan lengkung jasad hitam
:name: graf_rayleigh_jeans
:width: 80%
:align: center

Persamaan Rayleigh&ndash;Jeans meramalkan tenaga tidak terhingga untuk cahaya-cahaya pendek. Hal ini tidak masuk akal.
```

````{margin} 
```{admonition} Ultralembayung
:class: important

Dari segi bahasa, "lembayung" ialah warna jingga keunguan yang boleh dilihat di kaki langit ketika matahari rendah. "Ultra-" ialah imbuhan daripada bahasa Inggeris yang menunjukkan sifat luar biasa.

Dari segi istilah, "ultralembayung" merujuk kepada warna cahaya yang bertenaga tinggi dalam julat 10 ke 400 nanometer yang berada dalam jenis cahaya yang berpanjang gelombang pendek.
````

Maknanya, menurut persamaan ini, bintang akan memancarkan cahaya berpanjang gelombang pendek dengan tenaga yang tidak terhingga! Perkara ini adalah mustahil kerana ia melanggar hukum keabadian tenaga seolah-olah jisim yang terbatas boleh menghasilkan tenaga yang tidak terbatas.

Kejadian ini lazimnya diberi nama "Malapetaka Ultralembayung" kerana sifat gelombang ultralembayung yang pendek panjang gelombangnya. Walaupun tiada malapetaka sebenar yang meragut mana-mana nyawa, nama itu sedap disebut dan selari dengan naluri manusia yang sukakan cerita menarik maka ia melekat dalam lidah para fizikawan.

## Postulat Planck Tentang Sekuantum Cahaya

Penyelesaian kepada masalah ini diberikan oleh Max Planck dengan dua postulat yang dibawanya. Postulat-postulat ini mengandaikan bahawa cahaya bukanlah selanjar seperti gelombang tetapi seperti berketul-ketul seperti zarah. Ternyata, persamaan yang muncul dari postulat ini menghasilkan graf yang selari dengan hasil cerapan.

````{admonition} POSTULAT 1
:class: hint

Tenaga, $\varepsilon$, yang dipancarkan oleh pengayun-pengayun dalam jasad hitam itu bergantung kepada frekuensi cahaya, $f$,
$$\varepsilon = hf.$$
($h$ ialah pemalar)
````

````{admonition} POSTULAT 2
:class: hint

Tenaga, $\varepsilon_n$, yang dipancarkan oleh pengayun-pengayun dalam jasad hitam mempunyai tahap tenaga berhasil darab integer, $$\varepsilon_n = n\varepsilon,$$
$$n=1,2,3,\cdots$$
````

Namun begitu, perkara ini bertentangan dengan pandangan ahli fizik tentang cahaya yang dipegang pada zaman itu. Selama ini, cahaya dipandang sebagai suatu gelombang selanjar yang selari dengan persamaan Maxwell. Postulat yang diusulkan itu menatijahkan bahawa cahaya itu sifatnya berketul-ketul. Satu ketul cahaya inilah yang disebut satu kuantum cahaya.

Max Planck sendiri menolak postulat yang dikemukakannya. Postulat tersebut hanyalah cubaannya sahaja dan mendapati ia selari dengan hasil cerapan. Baginya, ia adalah ralat dalam dunia Matematik dan ia akan dapat diperbetulkan di kemudian hari.

Namun begitu, dua postulat ini kekal sehingga hari ini setelah banyak ujikaji lain mengesahkannya. Fizikawan mendapati cahaya mempunyai kedua-dua sifat gelombang dan zarah. Pemilikan dua sifat ini dipanggil kedualan gelombang--zarah dan sifat ini adalah asas kepada Mekanik Kuantum. Pemalar $h$ itu kini dikenali sebagai Pemalar Planck.