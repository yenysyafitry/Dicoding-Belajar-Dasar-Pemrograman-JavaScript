```diff
+ Compiler  
Program komputer yang menerjemahkan kode yang ditulis dalam satu bahasa pemrograman ke bahasa lain yang dimengerti oleh mesin.

+ Debugging  
Proses mengidentifikasi dan menghilangkan error pada aplikasi.

+ Interpreter  
Program untuk menerjemahkan setiap baris kode dari bahasa pemrograman menjadi bahasa yang dimengerti oleh mesin secara langsung. Tanpa melalui proses kompilasi.

+ Library 
Sekumpulan sumber daya, biasanya berupa kode atau program, yang memiliki fungsionalitas tertentu dan bisa digunakan pada program lain.

+ Runtime 
Lingkungan, platform, atau sumber daya yang menjalankan suatu kode/program.

+ String Concatenation  
Proses penggabungan dua String atau lebih menggunakan operator penjumlahan (+).

+ String Interpolation 
Proses mengganti placeholder di dalam String dengan nilai dari variabel tertentu.
```

### Apa itu JavaScript?

<p align="justify"> 
<b>JavaScript</b> adalah bahasa pemrograman tingkat tinggi yang pada awalnya dikembangkan untuk membuat website menjadi lebih “hidup”. Bersama dengan HTML dan CSS, 
JavaScript menjadi bahasa pemrograman paling populer untuk mengembangkan aplikasi berbasis web. Bahasa ini mampu memberikan logic ke dalam website, sehingga website tersebut memiliki fungsionalitas tambahan dan lebih interaktif.</br>
Awalnya JavaScript dibuat supaya dapat berjalan di lingkungan browser dan membuat website menjadi lebih interaktif. Namun, saat ini Anda sebagai developer dapat menggunakan bahasa pemrograman JavaScript di berbagai lingkungan pengembangan. Sehingga, tidak hanya sebatas browser/client, namun JavaScript juga bisa berjalan di server menggunakan Node.js.</br>
JavaScript termasuk ke dalam kategori scripting language. Apa maksudnya? Salah satu ciri-ciri utama dari bahasa scripting adalah kode tidak perlu dikompilasi agar bisa dijalankan. Scripting language menggunakan interpreter untuk menerjemahkan kode atau perintah yang kita tulis supaya dimengerti oleh mesin.
</p>

### Kenapa JavaScript?
<p align="justify"> Jadi, kenapa kita perlu mempelajari JavaScript? </br>
Alasan utamanya karena JavaScript merupakan bahasa yang penting untuk Anda kuasai jika ingin menjadi web developer, baik itu front-end maupun back-end.
Berikut ini adalah beberapa kelebihan dari JavaScript yang dapat Anda pertimbangkan sebelum mulai mempelajari JavaScript: </p>

<ol align="justify"><li> JavaScript bahasa yang versatile
JavaScript bisa berjalan di lingkungan browser, server, bahkan desktop. Artinya, jika Anda bisa menguasai bahasa ini, maka skill Anda bisa digunakan di mana pun.</li>
<li>  Mudah dipelajari oleh pemula
JavaScript termasuk salah satu bahasa pemrograman yang ramah bagi pemula. Anda tidak perlu menginstal software dan lingkungan pengembangan lain yang rumit untuk memulai membuat program dengan JavaScript. Cukup dengan browser Anda sudah bisa menulis kode JavaScript dan menjalankannya sekaligus.</li>
<li>  Selain itu, sebagai salah satu bahasa pemrograman paling populer, JavaScript memiliki komunitas yang besar pada situs seperti StackOverflow yang siap membantu Anda jika memiliki pertanyaan atau kesulitan dalam JavaScript.</li>
<li> Potensi karir yang meyakinkan
Mengikuti perkembangan teknologi dan banyaknya bisnis yang mulai merambah ke ranah digital, JavaScript menjadi salah satu skill yang paling banyak dicari di industri. Jika Anda mencari kata kunci “JavaScript” pada laman pencarian kerja seperti JobStreet, akan muncul hampir 1.500 lowongan pekerjaan di Indonesia yang bisa Anda lamar. </li> </ol>

### Menulis Kode JavaScript Pertama
<p align="justify">Menulis kode dalam suatu bahasa pemrograman sederhananya adalah menuliskan instruksi-instruksi untuk dijalankan oleh komputer. Kode di bawah ini merupakan instruksi bagi terminal atau konsol untuk mencatat (log) kalimat “Hello, World!”. <b>console.log</b> adalah kode bawaan JavaScript untuk menampilkan pesan ke konsol, bisa berupa web konsol atau konsol dari terminal/command prompt. Kode atau teks yang berada di dalam tanda kurung adalah pesan yang ingin ditampilkan. Pada contoh kode di atas, kita menggunakan tanda kutip (“”) untuk menandakan bahwa pesan yang ingin ditampilkan merupakan sebuah string atau teks. </p>

```plantuml 
 console.log("Hello, World!"); 
```

|Output : |
| :--     | 
| Hello, World!|

### Comments
<p align="justify">Comments adalah Salah satu instruksi yang penting adalah memberi tahu komputer untuk mengabaikan perintah yang kita tulis. Instruksi yang ditulis dalam suatu program tetapi tidak dijalankan oleh komputer.Terdapat dua metode untuk memberikan komentar. Pertama, untuk memberikan komentar pada satu baris saja, kita bisa gunakan tanda dua garis miring (//) di awal baris. Lalu, untuk memberikan komentar lebih dari satu baris kita bisa menggunakan tanda /* sebagai pembuka komentar dan tanda */ untuk penutup komentar. Teks apa pun yang berada di antara tanda tersebut akan dijadikan komentar dan tidak akan dieksekusi.</p>

```plantuml 
// console.log("Halo!"); 
```

### Variable
<p align="justify"> Pada JavaScript setidaknya ada tiga cara untuk mendeklarasikan sebuah variabel, yaitu menggunakan keyword var, let, dan const. Pada versi ECMAScript 2015 (ES6) dikenalkan deklarasi variabel dengan let dan const untuk menggantikan var yang dinilai kontroversial dan rawan menimbulkan bug.</p>

```plantuml
  let lastName;
lastName = "Skywalker";
console.log(lastName);
```

|Output : |
| :--     | 
|Skywalker|


### Data Type
<p align="justify"> Nilai yang kita tetapkan pada variabel pasti memiliki tipe data. Tipe data merupakan pengklasifikasian data berdasarkan jenisnya. Pada JavaScript terdapat beberapa tipe data sebagai berikut: </p>
<ul align="justify"><li><b> Undefined </b></br>
Tipe data ini terbentuk ketika sebuah variabel tidak memiliki nilai. Artinya, ketika kita mendeklarasikan variabel tanpa menginisialisasikan nilainya, variabel tersebut menjadi undefined.</li></ul>

```plantuml
   let x;
   console.log(typeof(x));
```

|Output : |
| :--     | 
|undefined |

<p align="justify">Pada contoh kode di atas, kita mendeklarasikan variabel x, tetapi kita tidak menginisialisasikan dengan nilai apa pun. Ketika kita memastikan tipe data dengan menggunakan fungsi typeof(), ia akan menghasilkan output undefined. <b>Fungsi typeof()</b> digunakan untuk memastikan tipe data pada variabel dengan mengembalikan tipe data tersebut dalam bentuk teks.
</p>
</br>
<ul align="justify"><li><b>Numbers</b></br>Nilai dari tipe data number adalah angka. Variabel bertipe data number dituliskan seperti angka pada umumnya:</li></ul>

```plantuml
   let a = 12;
   let b = 9;
   console.log(a + b)
   console.log(a - b)
   console.log(a * b)
   console.log(a / b)
   console.log(a % b)
```

|Output : |
| :--     | 
|21</br>3</br>108</br>1.3333333333333333</br>3|


### BigInt
<p align="justify">Pada JavaScript, tipe data “Number” hanya mencakup nilai dari -(253 - 1) hingga (253 - 1). Untuk kebutuhan umum, sebenarnya nilai tersebut sudah sangat cukup. Namun, akan ada kebutuhan tertentu di mana kita membutuhkan cakupan nilai yang lebih besar, seperti untuk kriptografi atau menentukan waktu hingga presisi microsecond. Untuk nilai di luar Number, kita bisa menggunakan tipe BigInt. Untuk membedakan tipe BigInt dan Number, tambahkan karakter n di akhir angka. Contohnya adalah seperti kode di bawah ini. Bandingkan dengan yang bertipe Number. </p>

```plantuml
const bigNumber = 1234567890123456789012345678901234567890n;
const myInt = 1234567890123456789012345678901234567890;

console.log(bigNumber);
console.log(myInt);
```

|Output : |
| :--     | 
|1234567890123456789012345678901234567890n </br>1.2345678901234568e+39 |

<p align="justify">Kita juga bisa menggunakan BigInt untuk operasi aritmatika pada umumnya. Yang membedakan adalah pada operasi pembagian, hasilnya akan dibulatkan ke bawah dan tanpa mengandung nilai desimal. Contohnya adalah seperti ini:</p>

```plantuml
console.log(5n + 2n);
console.log(5n - 2n);
console.log(5n * 2n);
console.log(5n / 2n);
console.log(5n % 2n);
```

|Output : |
| :--     | 
| 7n </br> 3n </br>10n </br> 2n </br> 1n |

### Strings
<p align="justify"> Tipe data selanjutnya adalah string yang merupakan sebuah teks. Untuk menetapkan nilai sebagai string pada variabel gunakan tanda petik satu (‘) atau petik dua (“) di antara teksnya. Contohnya: </p>

```plantuml
let greet = "Hello";
console.log(typeof(greet))
```

|Output : |
| :--     | 
| string |

<p align="justify">Tidak ada perbedaan antara menggunakan petik satu atau petik dua. Anda dapat menggunakan tanda petik secara bergantian, khususnya jika Anda memiliki teks yang mengandung tanda petik. </p>

```plantuml
const question = '"What do you think of JavaScript?" I asked';
console.log(question)
```
|Output : |
| :--     | 
| "What do you think of JavaScript?" I asked |

<p align="justify">Lalu bagaimana jika teks memiliki kedua tanda petik seperti ini?</p>

```plantuml
const answer = '"I think it's awesome!" he answered confidently';
console.log(answer);
```

|Output : |
| :--     | 
| /home/glot/main.js:1 </br>const answer = '"I think it's awesome!" he answered confidently'; </br>SyntaxError: Unexpected identifier </br>at wrapSafe (internal/modules/cjs/loader.js:979:16)</br>at Module._compile (internal/modules/cjs/loader.js:1027:27)</br>at Object.Module._extensions..js (internal/modules/cjs/loader.js:1092:10)</br>at Module.load (internal/modules/cjs/loader.js:928:32)</br>at Function.Module._load (internal/modules/cjs/loader.js:769:14)</br>at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:72:12)</br>at internal/main/run_main_module.js:17:47 |

<p align="justify"> Tentunya kode di atas akan menghasilkan eror. Solusinya, gunakan backslash(\) untuk mengurangi ambiguitas dalam tanda petik. Mekanisme ini juga dikenal dengan nama escape string. Sehingga kode di atas akan menjadi seperti berikut:
 </p>
 
```plantuml
const answer = '"I think it\'s awesome!" he answered confidently';
```

<p align="justify"> Pada String, kita juga dapat menggunakan operator plus (+). Operator tersebut berfungsi untuk menggabungkan dua teks yang terpisah menjadi satu buah teks. Contohnya seperti ini:
 </p>

```plantuml
let greet = "Hello";
let moreGreet = greet + greet;
console.log(moreGreet);
```

|Output : |
| :--     | 
| HelloHello |

<p align="justify"> Ingat, string concatenation seperti di atas akan menggabungkan string apa adanya, sehingga jika Anda ingin menggabungkan dua kata atau lebih perlu menambahkan spasi sendiri. Selain concatenation, string pada JavaScript juga mendukung string interpolation. Sederhananya, kita bisa memasukkan variabel ke dalam sebuah string template. Contohnya adalah seperti berikut:
 </p>

```plantuml
const myName = "Luke";
console.log(`Hello, my name is ${myName}.`);
```

|Output : |
| :--     | 
| Hello, my name is Luke. |

<p align="justify"> Perhatikan bahwa untuk mendefinisikan string template, Anda perlu menggunakan backticks (`), biasanya terletak di keyboard di sebelah kiri tombol 1). Di dalam string letakkan variabel yang ingin dimasukkan ke dalam placeholder ${myName}.
 </p>
 
 ### Boolean
 <p align="justify"> Boolean hanya memiliki dua nilai, yaitu true atau false. Tipe data ini menjadi kunci utama dalam penentuan logika. Kita akan banyak menggunakannya nanti dalam materi if/else statement. Untuk menetapkan nilai boolean pada variabel, gunakan keyword true atau false seperti di bawah ini.  Boolean hanya memiliki dua nilai, yaitu true atau false. Tipe data ini menjadi kunci utama dalam penentuan logika. Kita akan banyak menggunakannya nanti dalam materi if/else statement. Untuk menetapkan nilai boolean pada variabel, gunakan keyword true atau false seperti di bawah ini.
 </p>

```plantuml
let x = true;
let y = false;
console.log(typeof(x))
console.log(typeof(y))
```

|Output : |
| :--     | 
| boolean </br> boolean |

<p align="justify"> Kita juga bisa menggunakan operator komparasi seperti lebih dari (>) atau kurang dari (<). Contohnya:
 </p>

```plantuml
const a = 10;
const b = 12;

let isGreater = a > b;
let isLess = a < b;

console.log(isGreater);
console.log(isLess);
```

|Output : |
| :--     | 
| false </br> true |


### Null
<p align="justify">Tipe berikutnya adalah null. Serupa dengan undefined, namun null perlu diinisialisasikan pada variabel. Null biasa digunakan sebagai nilai sementara pada variabel, tapi sebenarnya nilai tersebut “tidak ada”. Terkadang kita perlu membuat sebuah variabel, namun kita belum memerlukan nilai apa-apa dan tidak ingin terikat oleh tipe data apa pun. Nah, daripada kita tidak menetapkan nilai apa pun (variabel akan undefined) sebaiknya kita beri nilai null pada variabel tersebut dan ubah nanti ketika kita membutuhkannya. Untuk menetapkan null pada variabel, kita dapat gunakan keyword null ketika variabel tersebut diinisialisasi.
 </p>

```plantuml
let someLaterData = null;
console.log(someLaterData);
```

|Output : |
| :--     | 
| null |


### Symbol
<p align="justify">Symbol adalah tipe data baru yang dikenalkan pada ES6. Tipe data Symbol digunakan untuk menunjukkan identifier yang unik. Ketika membuat Symbol, kita bisa memberikan deskripsi atau nama symbol seperti ini:
 </p>

```plantuml
const id = Symbol("id");
console.log(id);
```

|Output : |
| :--     | 
| Symbol(id)|

<p align="justify">Symbol disebut sebagai identifier yang unik karena meskipun kita membuat dua variabel symbol dengan nama atau deskripsi yang sama, kedua nilainya tetap dianggap berbeda. Contohnya lihat kode berikut:
 </p>

```plantuml
const id1 = Symbol("id");
const id2 = Symbol("id");
console.log(id1 == id2);
```

|Output : |
| :--     | 
| false |

<p align="justify">Symbol ini umumnya digunakan sebagai nama property dari Object. Object sendiri merupakan tipe data kompleks untuk menyimpan berbagai struktur data. Kita akan segera bertemu dan mempelajari tentang object pada modul Data Structur
 </p>
 
 ### Operator
 <p align="justify">Pada materi ini kita akan mempelajari tentang operator yang terdapat pada JavaScript. Operator dalam bahasa pemrograman sendiri adalah simbol yang memberi tahu interpreter untuk melakukan operasi seperti matematika, relasional, atau logika untuk memberikan hasil tertentu.
 </p>

### Assignment Operator
<p align="justify">Dari contoh kode yang kita gunakan sebelumnya, sebenarnya kita sudah menggunakan assignment operator. Operator ini digunakan untuk memberikan nilai pada variabel. Pada dasarnya operator ini adalah tanda sama dengan (=), di mana tanda ini digunakan untuk menginisialisasi nilai pada variabel. Tempatkan variabel yang ingin diberi nilai di sebelah kiri, sementara nilainya di sebelah kanan. Di antara keduanya terdapat operator assignment.
 </p>

```plantuml
x = y;
```

<p align="justify">Expression di atas berarti kita menginisialisasikan nilai y pada variabel x, sehingga nilai x sekarang memiliki nilai yang sama dengan y. Ada beberapa assignment operator tambahan lain dalam menginisialisasikan nilai pada variabel. Kita bisa menyebutnya sebagai shortcut dalam menentukan nilai. Contohnya:
 </p>
 
 ```plantuml
let x = 10;
let y = 5

x += y;

console.log(x);
```
 
|Output : |
| :--     | 
| 15 |

<p align="justify">Pada contoh kode di atas, terdapat expression x += y; Apa artinya? Assignment operator tersebut digunakan sebagai shortcut dari x = x + y. Cara ini juga dapat digunakan pada operator aritmatika lain seperti, perkalian, pengurangan, pembagian, dan lainnya.
 </p>

```plantuml
let x = 10;
let y = 5;
 
x += y; // artinya -> x = x + y;
x -= y; // artinya -> x = x - y;
x *= y; // artinya -> x = x * y;
x /= y; // artinya -> x = x / y;
x %= y; // artinya -> x = x % y;
```

### Comparison Operator
<p align="justify">Sekarang kita sudah mengetahui bagaimana cara menyimpan nilai pada sebuah variabel. Nah, selanjutnya kita akan belajar mengenai operator komparasi sebagai logika dasar dalam membandingkan nilai pada JavaScript. Terdapat serangkaian karakter khusus yang disebut dengan operator pembanding/komparasi yang dapat mengevaluasi dan membandingkan dua nilai. Berikut daftar operator dan fungsinya: </p>

| Operator | 	Fungsi |
| :-- | :-- |
| ==	| Membandingkan kedua nilai apakah sama. (tidak identik).|
| != |	Membandingkan kedua nilai apakah tidak sama. (tidak identik).|
| === |	Membandingkan kedua nilai apakah identik.|
| !== |	Membandingkan kedua nilai apakah tidak identik.|
| >	| Membandingkan dua nilai apakah nilai pertama lebih dari nilai kedua.|
| >= |	Membandingkan dua nilai apakah nilai pertama lebih atau sama dengan nilai kedua.|
| < |	Membandingkan dua nilai apakah nilai pertama kurang dari nilai kedua.|
| <=|	Membandingkan dua nilai apakah nilai pertama kurang atau sama dengan nilai kedua.|

<p align="justify">
Ketika kita melakukan perbandingan antara dua nilai, JavaScript akan mengevaluasi kedua nilai tersebut dan mengembalikan boolean dengan nilai hasil perbandingan tersebut, baik false atau true. Berikut contohnya
</p>

```plantuml
let a = 10;
let b = 12;

console.log(a < b);
console.log(a > b);
```

|Output : |
| :--     | 
| true </br> false |

### Perbedaan antara “Sama” dan “Identik”
<p align="justify">Dalam operator komparasi di JavaScript, hal yang menjadi sedikit “tricky” adalah membedakan antara “sama” (==) dan “identik” (===). Kita sudah mengetahui bahwa setiap nilai pasti memiliki tipe data baik itu number, string atau boolean. Contohnya sebuah string “10” dan number 10 merupakan hal yang serupa, tetapi keduanya tidak benar-benar sama. Hal inilah yang membedakan antara sama dan identik pada JavaScript. Jika kita ingin membandingkan hanya dari kesamaan nilainya kita bisa gunakan == tapi jika kita ingin membandingkan dengan memperhatikan tipe datanya kita gunakan ===. Contohnya seperti berikut:
 </p>

```plantuml
const aString = '10';
const aNumber = 10

console.log(aString == aNumber) //true, karena nilainya sama-sama 10
console.log(aString === aNumber) //false, karena walaupun nilainya sama, tetapi tipe datanya berbeda
```
|Output : |
| :--     | 
| true </br> false |

### Logical Operator
<p align="justify">Terdapat beberapa operator lain yang dapat kita gunakan untuk menetapkan logika yang lebih kompleks, yakni dengan logical operators. Dengan logical operator, kita dapat menggunakan kombinasi dari dua nilai boolean atau bahkan lebih dalam menetapkan logika. Pada JavaScript terdapat tiga buah karakter khusus yang berfungsi sebagai logical operator. Berikut macam-macam logical operator dan fungsinya:
 </p>

| Operator	| Deskripsi|
| :--:     | :--     | 
|&&|	Operator dan (and). Logika akan menghasilkan nilai true apabila semua kondisi terpenuhi (bernilai true).|
|!| Operator tidak (not). Digunakan untuk membalikkan suatu kondisi.|

<p align="justify">Berikut contoh penerapannya pada JavaScript:
 </p>

```plantuml
let a = 10;
let b = 12;

/* AND operator */
console.log(a < 15 && b > 10); // (true && true) -> true
console.log(a > 15 && b > 10); // (false && true) -> false

/* OR operator */
console.log(a < 15 || b > 10); // (true || true) -> true
console.log(a > 15 || b > 10); // (false || true) -> true

/* NOT operator */
console.log(!(a < 15)); // !(true) -> false
console.log(!(a < 15 && b > 10)); // !(true && true) -> !(true) -> false
```

|Output : |
| :--     | 
|true</br>false</br>true</br>true</br>false</br>false |

<p align="justify">Mungkin sebagian dari kita bertanya, sebenarnya apa kegunaan dari nilai boolean selain hanya menampilkan nilai true dan false saja? Pada pembahasan tipe data sudah pernah disebutkan bahwa boolean merupakan salah satu kunci dari logika pemrograman, karena boolean dapat mengontrol bagaimana alur program kita akan berjalan. Lantas bagaimana cara boolean mengontrol sebuah aliran program? Pada materi selanjutnya, kita akan membahas mengenai if/else statement yang dapat mengontrol flow pada program, tentunya pada penggunaan statement boolean ini sangat berguna.
 </p>


### If/Else Statement
<p align="justify">Setiap hari kita melakukan perhitungan dan perbandingan guna membuat keputusan, apa pun itu. Contohnya, apakah perlu mencuci kendaraan ketika cuaca sedang cerah? Apa saja transportasi online yang bisa dipesan ketika hujan untuk sampai di tempat tujuan? Ketika mengembangkan sebuah program, kita akan bertemu dengan alur bercabang tergantung pada kondisi yang terjadi. Untuk mengakomodasi dan mengecek sebuah kondisi dalam JavaScript, kita menggunakan kata kunci if. Statement if akan menguji suatu kondisi. Jika kondisi bernilai true, maka blok kode di dalamnya akan dijalankan. Sebaliknya, jika bernilai false, maka proses yang ditentukan akan dilewatkan.
 </p>
 
 <p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/2021032614212952aba0a5b1a44e18d7e5234517c4f671.png" width="350" title="hover text">
</br>Flowchart di atas jika diterjemahkan menjadi kode, akan menjadi seperti berikut:
</p>

 
```plantuml
const isRaining = true;

console.log("Persiapan sebelum berangkat kegiatan.");
if (isRaining) {
    console.log("Hari ini hujan. Bawa payung.");
}
console.log("Berangkat kegiatan.");
```
|Output : |
| :--     | 
| Persiapan sebelum berangkat kegiatan.</br>Hari ini hujan. Bawa payung.</br>Berangkat kegiatan. |

<p align="justify">Jika Anda mengubah nilai isRaining menjadi false, maka kode di dalam blok kode if akan dilewatkan. Sehingga program Anda tidak akan mengingatkan untuk membawa payung. Lalu bagaimana jika Anda ingin melakukan operasi lain ketika kondisi bernilai false? Jawabannya adalah statement else. Pada contoh kode berikut kita akan melakukan pengecekan kondisi menggunakan operator perbandingan.
 </p>


```plantuml
let x = 50;

if(x > 70) {
    console.log(x);
} else {
    console.log("Nilai kurang dari 70");
}
```

|Output : |
| :--     | 
| Nilai kurang dari 70|

<p align="justify">Terdapat variabel x dengan nilai 50, kemudian kita bertanya, “Hai JavaScript! Apakah x lebih dari 70?” Jika kondisi tersebut benar, maka kita dapat memerintahkan JavaScript untuk menampilkan nilainya. Jika salah, kita perintahkan JavaScript untuk menampilkan teks “Nilai kurang dari 70”. Kita juga bisa mengecek beberapa kondisi sekaligus dengan menggabungkan else dan if. Contohnya adalah seperti program berikut:
 </p>

```plantuml
let language = "French";
let greeting = "Selamat Pagi"

if(language === "English") {
    greeting = "Good Morning!";
} else if(language === "French") {
    greeting = "Bonjour!"
} else if(language === "Japanese") {
    greeting = "Ohayou Gozaimasu!"
}
console.log(greeting);
```

|Output : |
| :--     | 
| Bonjour! |


<p align="justify">Pengecekan kondisi akan dilakukan dari statement if paling awal. Sehingga, ketika nilai language adalah “French”, maka pengecekan untuk language === “Japanese” tidak akan dilakukan. Selain if statement di atas, JavaScript juga mendukung ternary operator atau conditional expressions. Dengan ini, kita bisa menuliskan if-else statement hanya dalam satu baris.
 </p>

```plantuml
const isMember = false;
const discount = isMember ? 0.1 : 0;
console.log(`Anda mendapatkan diskon sebesar ${discount * 100}%`)
```

|Output : |
| :--     | 
| Anda mendapatkan diskon sebesar 0% |

<p align="justify">Ternary operator membutuhkan tiga operand. Sebelum tanda tanya (?) berisi kondisi yang ingin kita evaluasi. Kemudian diikuti dengan expression apabila nilai kondisinya benar sebelum tanda titik dua. Terakhir adalah expression yang dieksekusi ketika kondisinya salah. Karena merupakan conditional expression, maka operand kedua dan ketiga harus mengembalikan nilai.
 </p>

### Truthy & Falsy
<p align="justify">Di dalam if statement kita perlu memasukkan expression yang akan dievaluasi. Umumnya, expression tersebut mengembalikan nilai boolean untuk menentukan kondisi true atau false. Lalu bagaimana jika kita menuliskan expression yang tidak mengembalikan nilai boolean? Jawabannya bisa.</br>
Setiap nilai pada JavaScript pada dasarnya juga mewarisi sifat boolean. Nilai ini dikenal dengan truthy atau falsy. Nilai truthy berarti nilai yang ketika dievaluasi akan menghasilkan nilai true, begitu pula falsy bernilai false. Jadi manakah yang termasuk truthy dan falsy? Selain nilai boolean false, tipe data atau nilai yang dianggap falsy, antara lain: </p>

<ul><li>Number 0</li>
<li>BigInt 0n</li>
<li>String kosong seperti “” atau ‘’</li>
<li>null</li>
<li>undefined</li>
<li>NaN, atau Not a Number</li></ul>

<p align="justify">Selain contoh di atas maka nilainya adalah truthy dan ketika dievaluasi ke dalam if statement akan bernilai true. Berikut ini contohnya dalam kode:</p>
 
```plantuml
let name = "";

if (name) {
    console.log(`Halo, ${name}`);
} else {
    console.log("Nama masih kosong");
}
```

|Output : |
| :--     | 
| Nama masih kosong |


### Switch Case Statement
<p align="justify">Sebelumnya kita telah mempelajari bagaimana percabangan logika menggunakan if statement. Selain if, JavaScript juga mendukung switch statement untuk melakukan pengecekan banyak kondisi dengan lebih mudah dan ringkas.
 </p>

```plantuml
switch (expression) {
  case value1:
    // do something
    break;
  case value2:
    // do something
    break;
  ...
  ...
  default:
    // do something else
}
```

<p align="justify">Tanda kurung setelah keyword switch berisi variabel atau expression yang akan dievaluasi. Kemudian untuk setiap kondisi yang mungkin terjadi, kita masukkan keyword case diikuti dengan nilai yang valid. Jika kondisi pada case sama dengan variabel pada switch, maka blok kode setelah titik dua (:) akan dijalankan. Keyword break digunakan untuk keluar dari proses switch. Terdapat satu case bernama default yang memiliki fungsi yang sama dengan keyword else pada control flow if-else. Jika tidak ada nilai yang sama dengan variabel pada switch, maka blok kode ini akan dijalankan.</br> Berikut ini adalah contoh kode dari materi if-else yang dikonversi menjadi statement switch:
 </p>

```plantuml
let language = "French";
let greeting = null;

switch (language) {
    case "English":
        greeting = "Good Morning!";
        break;
    case "French":
        greeting = "Bonjour!";
        break;
    case "Japanese":
        greeting = "Ohayou Gozaimasu!";
        break;
    default:
        greeting = "Selamat Pagi!";
}
console.log(greeting);
```

|Output : |
| :--     | 
| Bonjour! |

### Loop
<p align="justify">Ketika menulis program komputer, akan ada situasi di mana kita perlu melakukan hal yang sama berkali-kali. Misalnya kita ingin menampilkan semua nama pengguna yang terdaftar di aplikasi atau sesederhana menampilkan angka 1 sampai 10. Tentunya tidak praktis jika kita menulis kode seperti berikut:
 </p>


```plantuml
console.log(1);
console.log(2);
console.log(3);
console.log(4);
console.log(5);
console.log(6);
console.log(7);
console.log(8);
console.log(9);
console.log(10);
```

<p align="justify">Bagaimana jika kita perlu menampilkan angka 1 sampai 100? Sudah terbayang repotnya, bukan? Maka dari itu kita perlu mempelajari teknik yang dapat mengatasi permasalahan tersebut, teknik ini disebut dengan looping. JavaScript memiliki banyak opsi untuk melakukan looping atau perulangan kode, antara lain:
</p>

### For loop
<p align="justify">Dari beberapa cara melakukan proses loop pada JavaScript, “for” merupakan salah satu cara yang banyak digunakan. Struktur dasar dari for tampak seperti berikut:
 </p>

```plantuml
for(inisialisasi variabel; test kondisi; perubahan nilai variabel) {
    // do something
}
```

<p align="justify">Berikut ini contoh penerapannya secara nyata:
 </p>

```plantuml
for(let i = 0; i < 5; i++) {
    console.log(i);
}
```

|Output : |
| :--     | 
| 0</br>1</br>2</br>3</br>4 |

<p align="justify">Lebih ringkas, bukan? Mungkin kode tersebut sulit dipahami, jadi mari kita bahas sedikit demi sedikit. Terdapat tiga bagian utama dalam sintaks for di atas:
 </p><ul align="justify">
<li>Pertama, variabel i sebagai index iterasi. Pada variabel ini kita menginisialisasi nilai awal dari perulangan.</li>
<li>Kedua, operasi perbandingan. Pada bagian ini, JavaScript akan melakukan pengecekan kondisi apakah perulangan masih perlu dilakukan. Jika bernilai true, maka kode di dalam blok for akan dijalankan.</li>
<li>Ketiga, increment/decrement. Di sini kita melakukan penambahan atau pengurangan variabel iterasi. Jadi, pada contoh di atas variabel i akan ditambah dengan 1 di setiap akhir perulangan. Perubahan nilai ini penting karena jika kita mengubah nilainya, proses perulangan dapat berjalan selamanya karena kondisi akan terus terpenuhi.</br></li>
JIka diartikan, maka kode di atas bisa dimaknai dengan “Jika i kurang dari 5, maka tampilkan nilai i.”</ul></li>

 
 ### For of loop
 <p align="justify">Cara lain dalam melakukan looping adalah menggunakan for..of. For of mulai hadir pada ECMAScript 2015 (ES6). Cara ini jauh lebih sederhana dan modern dibanding for loop biasa. Sintaks dasar dari for of loop adalah seperti ini:
 </p>
 
```plantuml
for(arrayItem of myArray) {
    // do something
}

```

<p align="justify">Yup, for of tidak membutuhkan banyak statement untuk melakukan looping pada array. Penjelasan tentang array akan lebih detail dibahas pada modul berikutnya. Sebagai permulaan, kita bisa menganggap array sebagai kumpulan nilai yang disimpan dalam satu variabel. </br>
Dengan for..of nilai tiap array akan diinisialisasi pada variabel baru yang kita tentukan pada tiap proses looping-nya. Jumlah proses looping-nya pun akan menyesuaikan dengan ukuran dari array. Sederhananya seperti kita melakukan perintah “Hei JavaScript! Lakukan perulangan pada myArray, akses tiap nilainya, dan simpan pada variabel arrayItem”. Pada proses looping kita gunakan variabel arrayItem untuk mengakses tiap nilai dari item myArray. </br>
Agak sulit memang menjelaskan dengan kata-kata, mari kita terjemahkan dalam kode secara langsung.
 </p>

```plantuml
let myArray = ["Luke", "Han", "Chewbacca", "Leia"];

for(const arrayItem of myArray) {
    console.log(arrayItem)
}
```

|Output : |
| :--     | 
| Luke</br>Han</br>Chewbacca</br>Leia|

### While and do-while
<p align="justify">Metode lain untuk melakukan looping adalah dengan statement while. Sama seperti for, instruksi while mengevaluasi ekspresi boolean dan menjalankan kode di dalam blok while ketika bernilai true.</br> 
Untuk menampilkan angka 1 sampai 100 dengan while kita bisa menulis kode seperti berikut:
 </p>

```plantuml
let i = 1;

while (i <= 10) {
    console.log(i);
    i++;
}
```

|Output : |
| :--     | 
|1</br>2</br>3</br>4</br>5</br>6</br>7</br>8</br>9</br>10 |

<p align="justify">Bisa dilihat pada kode di atas bahwa looping dengan while tidak memiliki ketergantungan dengan variabel iterasi seperti pada for loop. Karena itu, meskipun while dapat melakukan perulangan yang sama dengan for, while lebih cocok digunakan pada kasus di mana kita tidak tahu pasti berapa banyak perulangan yang diperlukan.</br>
Bentuk lain dari while adalah perulangan do-while.
 </p>

```plantuml
let i = 1;

do {
    console.log(i);
    i++;
} while (i <= 100);
```

|Output : |
| :--     | 
|1</br>2</br>3</br>4</br>5</br>6</br>7</br>8</br>9</br>10 |

<p align="justify">Kondisi pada while akan dievaluasi sebelum blok kode di dalamnya dijalankan, sedangkan do-while akan mengevaluasi boolean expression setelah blok kodenya berjalan. Ini artinya kode di dalam do-while akan dijalankan setidaknya satu kali.
 </p>
 
 ### Infinite loops
<p align="justify">Ketika menerapkan perulangan pada program, ada satu kondisi yang perlu kita hindari yaitu infinite loop. Infinite loop atau endless loop adalah kondisi di mana program kita stucked di dalam perulangan. Ia akan berjalan terus hingga menyebabkan crash pada aplikasi dan komputer kecuali ada intervensi secara eksternal, seperti mematikan aplikasi.</br>
Kode berikut ini adalah contoh di mana kondisi infinite loop dapat terjadi:
 </p>

```plantuml
let i = 1;
 
while (i <= 5) {
    console.log(i);
}
```

dan 

```plantuml
for(let i = 1; i <= 5; i=1) {
    console.log(i);
}
```

<p align="justify">Dapatkah Anda menemukan apa yang salah dari kode di atas sehingga terjadi infinite loop? Jawabannya adalah karena variabel i selalu bernilai 1. Alhasil, kondisi i <= 5 akan selalu bernilai true yang mengakibatkan aplikasi akan terus mencetak 1 ke konsol sehingga mengalami crash.
 </p>

<!---
### Kuis Coding: Variabel dan Tipe Data
<p align="justify">Untuk menguji kemampuan praktikal Anda dalam memahami materi variabel dan tipe data di JavaScript, silakan selesaikan kuis berikut. Sebelum Anda mengerjakan kuis, ada beberapa hal yang perlu Anda perhatikan.</br> Mohon untuk membaca secara seksama perintah, kriteria, atau soal pada komentar kode yang diberi tanda TODO.  </br>
Lakukan pengujian pada kode yang Anda tulis contohnya dengan menggunakan console.log() untuk memastikan hasil sesuai dengan yang Anda harapkan. Gunakan tombol Jalankan.
 </p>
 
```plantuml
/**
 * TODO:
 * Buatlah variabel firstName, lastName, age, isMarried dengan ketentuan:
 *  - firstName: bertipe data string, dengan nilai nama depan Anda.
 *  - lastName: bertipe data string, dengan nilai nama belakang Anda.
 *  - age: bertipe data number, dengan nilai umur Anda.
 *  - isMarried: bertipe data boolean, dengan bebas Anda tentukan.
 */
let firstName = "Yenni";
console.log(typeof(firstName));
let lastName = "Syafitri";
console.log(typeof(lastName));
let age = 26;
console.log(typeof(age));
let isMarried = false;
console.log(typeof(isMarried))
// TODO
/**
 * Hiraukan kode di bawah ini
 */
module.exports = {
  firstName, lastName, age, isMarried,
};
```

|Output : |
| :--     | 
| string</br>string</br>number</br>boolean |

```plantuml
/**
 * Buatlah logika if untuk mengevaluasi nilai score dengan ketentuan:
 *  1. Jika nilai score lebih atau sama dengan 90
 *      - Isi variabel result dengan nilai: 'Selamat! Anda mendapatkan nilai A.'
 *  2. Jika nilai score ada di antara 80 hingga 89
 *      - Isi variabel result dengan nilai: 'Anda mendapatkan nilai B.'
 *  3. Jika nilai score ada di antara 70 hingga 79
 *      - Isi variabel result dengan nilai: 'Anda mendapatkan nilai C.'
 *  4. Jika nilai score ada di antara 60 hingga 69:
 *      - Isi variabel result dengan nilai: 'Anda mendapatkan nilai D.'
 *  5. Jika nilai score di bawah 60:
 *      - Isi variabel result dengan nilai: 'Anda mendapatkan nilai E.'
 *  Note: - Mohon untuk tidak menghapus kode yang sudah ada sebelumnya.
 *        - Anda tidak perlu membuat variabel result dan score secara manual.
 *          Gunakan variabel yang sudah disediakan.
 */
function scoreChecker(score) {
  let result;
  // TODO  
if (score >= 90) {
  result = 'Selamat! Anda mendapatkan nilai A.';
} 
      else if (score >= 80) {
        result = 'Anda mendapatkan nilai B.';
}
    else if (score >= 70) {
          result = 'Anda mendapatkan nilai C.';
}
      else if (score >= 60 ) {
        result = 'Anda mendapatkan nilai D.';
}     else {
        result = 'Anda mendapatkan nilai E.';
      }  
  // Jangan hapus kode ini
  return result;
}
console.log(scoreChecker(89));
/**
 * Hiraukan kode di bawah ini
 */
module.exports = scoreChecker;
//Kode sudah berjalan sesuai arahan, mohon bimbingannya
```

|Output : |
| :--     | 
| Anda mendapatkan nilai B. |



### Rangkuman Materi
<p align="justify">Pada modul ini kita telah mempelajari logika dan sintaksis dasar JavaScript sebelum membuat aplikasi yang lebih kompleks ke depannya.Beberapa hal yang telah kita bahas pada modul ini, antara lain: </p>
<ol align="justify"><li>Gunakan comments untuk memberitahu interpreter supaya mengabaikan kode atau teks yang kita tulis. Ini akan berguna untuk membuat dokumentasi atau penjelasan atas kode yang kita tulis.</li>
<li>Kita dapat menyimpan suatu nilai ke dalam variabel. ES6 mengenalkan dua cara baru untuk mendefinisikan variabel, yaitu let dan const. Gunakan const untuk menyimpan nilai yang tidak akan berubah setelah diinisialisasi. Gunakan let apabila nilai di dalam variabel bisa berubah atau diinisialisasi ulang.
<li>Terdapat tujuh (7) tipe data primitif yang mendefinisikan suatu nilai dalam JavaScript. Ketujuh nilai tersebut antara lain: Undefined, Number, BigInt, String, Boolean, Null, dan Symbol.</li>
<li>JavaScript memiliki beragam operator yang memberi tahu interpreter untuk melakukan operasi matematika, relasional, atau logika untuk memberikan hasil akhir.
Pengambilan keputusan adalah hal yang penting dalam pemrograman. Kita bisa memanfaatkan if-else statement atau switch-case untuk memilih satu opsi berdasarkan kondisi yang diberikan.</li>
<li>Pemrograman juga membantu kita untuk melakukan pekerjaan yang berulang. Dengan kode for atau while, kita bisa melakukan perulangan terhadap suatu kode sebanyak ratusan bahkan ribuan kali hanya dengan beberapa baris saja.</li></ol>

### Object
<p align="justify">Kali ini kita akan berkenalan dengan tipe data object. Sebuah tipe data yang sangat berguna dalam pengembangan aplikasi dengan JavaScript. Object mampu menyimpan nilai dari beragam tipe data dan membentuk data yang lebih kompleks. Untuk menetapkan objek pada sebuah variabel kita gunakan tanda kurung kurawal {}. </p>

```plantuml
const user = {};
```

<p align="justify">Object berisi pasangan key dan value yang juga dikenal dengan property. Key berperan mirip seperti nama variabel yang menyimpan sebuah nilai. Sementara, value berisi nilai dengan tipe data apa pun termasuk objek lain. Key dan value di dalam object dituliskan seperti berikut:
 </p>
 
```plantuml
let object = {key1: "value1", key2: "value2", key3: "value3"}
```

<p align="justify">Kemudian untuk mengakses nilai dari properti object, kita dapat memanggil nama object lalu tanda titik dan diikuti nama propertinya. Contoh:
 </p>

```plantuml
const user = {
    firstName: "Luke",
    lastName: "Skywalker",
    age: 19,
    isJedi: true,
};
console.log(`Halo, nama saya ${user.firstName} ${user.lastName}`);
console.log(`Umur saya ${user.age} tahun`);
```

|Output : |
| :--     | 
| Halo, nama saya Luke Skywalker</br>Umur saya 19 tahun |

<p align="justify">Untuk mengakses key yang memiliki spasi atau karakter khusus lainnya maka kita perlu menggunakan bracket seperti di atas.
 </p>

```plantuml
const user = {
    firstName: "Luke",
    lastName: "Skywalker",
    age: 19,
    isJedi: true,
    "home world": "Tattooine"
};
console.log(`Halo, nama saya ${user.firstName} ${user.lastName}`);
console.log(`Umur saya ${user.age} tahun`);
console.log(`Saya berasal dari ${user["home world"]}`);
```

|Output : |
| :--     | 
| Halo, nama saya Luke Skywalker</br>Umur saya 19 tahun</br>Saya berasal dari Tattooine |


<p align="justify">Setelah mempelajari bagaimana membuat object dan menampilkan property di dalamnya, selanjutnya kita akan memodifikasi sebuah object. Untuk mengubah nilai properti di dalam object kita gunakan assignment operator (=).
 </p>

```plantuml
const spaceship = {
    name: "Millenium Falcon",
    manufacturer: "Corellian Engineering Corporation",
    maxSpeed: 1200,
    color: "Light gray"
};
spaceship.color = "Glossy red";
spaceship["maxSpeed"] = 1300;
console.log(spaceship);
```

|Output : |
| :--     | 
| { </br>name: 'Millenium Falcon', </br>manufacturer: 'Corellian Engineering Corporation',</br> maxSpeed: 1300,</br>color: 'Glossy red'</br>} |

<p align="justify">Ketika kita mengubah object menggunakan assignment operator dan property/key-nya sudah ada, maka nilai di dalamnya akan tergantikan dengan nilai yang baru. Sedangkan, jika property dengan nama key yang ditentukan tidak ditemukan, maka property baru akan ditambahkan ke object.
 </p>


```plantuml
const spaceship = {
    name: "Millenium Falcon",
    manufacturer: "Corellian Engineering Corporation",
    maxSpeed: 1200,
    color: "Light gray"
};
spaceship.color = "Glossy red";
spaceship["maxSpeed"] = 1300;
spaceship.class = "Light freighter";
console.log(spaceship);
```

|Output : |
| :--     | 
| { </br>name: 'Millenium Falcon', </br>manufacturer: 'Corellian Engineering Corporation', </br>maxSpeed: 1300, </br>color: 'Glossy red',</br> class: 'Light freighter' </br>} |

<p align="justify">Kita juga dapat menghapus property pada object menggunakan keyword delete seperti berikut:
 </p>

```plantuml
const spaceship = {
    name: "Millenium Falcon",
    manufacturer: "Corellian Engineering Corporation",
    maxSpeed: 1200,
    color: "Light gray"
};
spaceship.color = "Glossy red";
spaceship["maxSpeed"] = 1300;
delete spaceship.manufacturer;
console.log(spaceship);
```

|Output : |
| :--     | 
| { name: 'Millenium Falcon', maxSpeed: 1300, color: 'Glossy red' } |

### Array
<p align="justify">Array merupakan tipe data yang dapat mengelompokkan lebih dari satu nilai dan menempatkannya dalam satu variabel. Contoh:
 </p>

```plantuml
let myArray = ["Cokelat", 42.5, 22, true, "Programming"];
console.log(myArray);
```

|Output : |
| :--     | 
| [ 'Cokelat', 42.5, 22, true, 'Programming' ] |

<p align="justify">Perbedaan array dengan object adalah data pada array disusun secara berurutan dan diakses menggunakan index. Untuk mengakses nilai di dalam array, kita gunakan tanda kurung siku [] yang di dalamnya berisi angka yang merupakan posisi nilai yang ingin diakses.
 </p>

```plantuml
let myArray = ["Coklat", 42.5, 22, true, "Programming"];
console.log(myArray[1]);
```

|Output : |
| :--     | 
| 42.5|


<p align="justify">Lalu, apa yang akan terjadi jika kita berusaha mengakses index di luar ukuran array-nya? Jika kita mengakses nilai array lebih dari index-nya, maka hasilnya akan undefined. Index terakhir array selalu jumlah nilai array - 1.
 </p>

```plantuml
let myArray = ["Coklat", 42.5, 22, true, "Programming"];
console.log(myArray[0]);
console.log(myArray[1]);
console.log(myArray[2]);
console.log(myArray[3]);
console.log(myArray[4]);
console.log(myArray[5]);
console.log("Panjang nilai myArray adalah " + myArray.length + ".");
```

|Output : |
| :--     | 
| Coklat</br>42.5</br>22</br>true</br>Programming</br>undefined</br>Panjang nilai myArray adalah 5. |

<p align="justify">Sejauh ini kita baru belajar menginisialisasi dan mengakses elemen dari sebuah array. Pastinya Anda bertanya, “Bagaimana kita memanipulasi data pada array tersebut?” Nah, untuk menambahkan data ke dalam array, kita bisa menggunakan metode push(). Fungsi push ini akan menambahkan data di akhir array.
 </p>

```plantuml
const myArray = ["Coklat", 42.5, 22, true, "Programming"];
myArray.push('JavaScript');
console.log(myArray);
```

|Output : |
| :--     | 
|[ 'Coklat', 42.5, 22, true, 'Programming', 'JavaScript' ] |

<p align="justify">Sedangkan untuk mengeluarkan data atau elemen terakhir dari array, kita bisa gunakan metode pop().
 </p>

```plantuml
const myArray = ["Orange", 42.5, 22, true, "Programming"];
myArray.pop();
console.log(myArray);
```

|Output : |
| :--     | 
| [ 'Orange', 42.5, 22, true ] |

<p align="justify">Metode lain yang bisa kita gunakan untuk memanipulasi data pada array adalah shift() dan unshift(). Metode shift() digunakan untuk mengeluarkan elemen pertama dari array, sementara unshift() digunakan untuk menambahkan elemen di awal array.
 </p>

```plantuml
const myArray = ["Cokelat", 42.5, 22, true, "Programming"];
myArray.shift();
myArray.unshift("Apple");
console.log(myArray);
```

|Output : |
| :--     | 
| [ 'Apple', 42.5, 22, true, 'Programming' ] |

<p align="justify">Lalu bagaimana jika kita ingin menghapus data dari array? Sama seperti object, kita bisa menggunakan keyword delete.
 </p>

```plantuml
const myArray = ["Cokelat", 42.5, 22, true, "Programming"];
delete myArray[1];
console.log(myArray);
```

|Output : |
| :--     | 
| [ 'Cokelat', &lt;1 empty item&gt;, 22, true, 'Programming' ] |

<p align="justify">Namun, perhatikan di sini bahwa keyword delete hanya menghapus data pada index yang ditentukan lalu membiarkan posisi tersebut kosong. Untuk menghapus elemen, gunakan metode splice() seperti ini:
 </p>

```plantuml
const myArray = ["Cokelat", 42.5, 22, true, "Programming"];
myArray.splice(2, 1);   // Menhapus dari index 2 sebanyak 1 elemen
console.log(myArray);
```

|Output : |
| :--     | 
| [ 'Cokelat', 42.5, true, 'Programming' ] |

### Spread Operator
<p align="justify">fitur ini digunakan untuk menyebarkan nilai array atau lebih tepatnya iterable object menjadi beberapa elemen. Spread operator dituliskan dengan tiga titik (...). Mari kita lihat contoh kode berikut:
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
console.log(favorites);
```

|Output : |
| :--     | 
| [ 'Seafood', 'Salad', 'Nugget', 'Soup' ] |

<p align="justify">Pada kode tersebut hasil yang dicetak adalah sebuah array (ditunjukkan dengan tanda [ ]), karena memang kita mencetak nilai favorites itu sendiri. Nah, dengan menggunakan spread operator kita dapat menyebarkan nilai-nilai dalam array tersebut.
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
console.log(...favorites);
```

|Output : |
| :--     | 
|Seafood Salad Nugget Soup |

<p align="justify">Spread operator dapat digunakan untuk menggabungkan dua buah array ke dalam array baru. Jika tidak menggunakan spread operator ini maka hasilnya akan seperti ini:
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
const others = ["Cake", "Pie", "Donut"];
const allFavorites = [favorites, others];
console.log(allFavorites);
```

|Output : |
| :--     | 
| [ </br>[ 'Seafood', 'Salad', 'Nugget', 'Soup' ],</br>[ 'Cake', 'Pie', 'Donut' ]</br>] |

<p align="justify">Nilai array tidak akan tergabung. Alih-alih menggabungkan nilainya, variabel allFavorites menjadi array baru yang menampung dua array di dalamnya. Nah, lantas bagaimana jika kita mencoba menggunakan spread operator?
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
const others = ["Cake", "Pie", "Donut"];
const allFavorites = [...favorites, ...others];
console.log(allFavorites);
```

|Output : |
| :--     | 
| [ 'Seafood', 'Salad', 'Nugget', 'Soup', 'Cake', 'Pie', 'Donut' ]|

### Destructuring Object & Array
<p align="justify">Destructuring dalam JavaScript merupakan sintaksis yang dapat mengeluarkan nilai dari array atau properties dari sebuah object ke dalam satuan yang lebih kecil. Secara tidak sadar mungkin kita pernah melakukan destructuring. Namun, sebelum ES6 hal tersebut dilakukan dengan cara seperti ini:
 </p>

<p align="justify">Array  </p>

```plantuml
const foods = ['Pie', 'Cake', 'Honey']
const myFood = foods[0]
const yourFood = foods[1]
const ourFood = foods[2]
console.log(myFood, yourFood, ourFood)
```

|Output : |
| :--     | 
| Pie Cake Honey |

<p align="justify">Object </p>

```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
}
const firstName = profile.firstName
const lastName = profile.lastName
const age = profile.age
console.log(firstName, lastName, age)
```

|Output : |
| :--     | 
| John Doe 18 |


### Destructuring Object
<p align="justify">Penulisan sintaksis destructuring object pada ES6 menggunakan object literal ({ }) di sisi kiri dari operator assignment.
 </p>
 
```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
}
const {firstName, lastName, age} = profile;
console.log(firstName, lastName, age);
```

|Output : |
| :--     | 
| John Doe 18|


<p align="justify">kita telah melakukan destructuring object pada deklarasi variabel. Namun, pada kasus tertentu mungkin kita perlu melakukannya pada variabel yang sudah dideklarasikan.
 </p>

```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
}
 
let firstName = "Dimas";
let age = 20;
 
// menginisialisasi nilai baru melalui object destruction
({firstName, age} = profile);
 
console.log(firstName);
console.log(age);
```

|Output : |
| :--     | 
| John</br>18 |


### Default Values
<p align="justify">Ketika kita mendestruksikan objek dan menetapkan variabel dengan nama yang bukan merupakan properti dari objek, maka nilai dari variabel tersebut menjadi undefined. Contohnya:
 </p>


```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
}
const {firstName, age, isMale} = profile;
console.log(firstName)
console.log(age)
console.log(isMale)
```

|Output : |
| :--     | 
| John </br>18</br>undefined |

<p align="justify">Alternatifnya, kita bisa secara opsional mendefinisikan nilai default pada properti tertentu jika tidak ditemukan. Untuk melakukanya, tambahkan tanda assignment (=) setelah nama variabel dan tentukan nilai default-nya seperti ini:
 </p>

```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
} 
const {firstName, age, isMale = false} = profile;
console.log(firstName)
console.log(age)
console.log(isMale)
```

|Output : |
| :--     | 
| John </br>18 </br>false |

### Assigning to Different Local Variable Names


<p align="justify">ES6 menyediakan sintaksis tambahan yang membuat kita dapat melakukan hal tersebut. Penulisannya mirip seperti ketika kita membuat properti beserta nilainya pada object. Contohnya seperti ini:
 </p>

```plantuml
const profile = {
    firstName: "John",
    lastName: "Doe",
    age: 18
}
const {firstName: localFirstName, lastName: localLastName, age: localAge} = profile;
console.log(localFirstName);
console.log(localLastName);
console.log(localAge);
```

|Output : |
| :--     | 
| John </br>Doe </br>18 |

<p align="justify">Destructuring array serupa dengan destructuring object. Object menggunakan tanda kurung kurawal { } sedangkan array menggunakan tanda kurung siku [ ]. Perbedaan lainnya adalah destructuring array bekerja berdasarkan posisi daripada penamaan propertinya. Berikut contoh dari destructuring array pada ES6:
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
const [firstFood, secondFood, thirdFood, fourthFood] = favorites; 
console.log(firstFood);
console.log(secondFood);
console.log(thirdFood);
console.log(fourthFood);
```

|Output : |
| :--     | 
| Seafood</br>Salad</br>Nugget</br>Soup |


<p align="justify">jika ingin mengambil nilai ketiga dari array, kita tidak perlu menyiapkan variabel lokal untuk menampung nilai array pertama, kedua, atau pun keempat. Kita bisa melakukannya dengan membiarkan index array yang tidak kita inginkan tetap kosong (tanpa menulis variabel lokal). Lebih lanjut, tanda koma (,) tetap diperlukan untuk menunjukkan posisi index-nya seperti ini:
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"];
const [, , thirdFood ] = favorites; 
console.log(thirdFood);
```

|Output : |
| :--     | 
| Nugget |


<p align="justify">Kita juga bisa melakukan destructuring assignment pada array. Namun, tidak seperti object, kita tidak perlu membungkusnya dengan tanda kurung. Contohnya seperti berikut:
 </p>

```plantuml
const favorites = ["Seafood", "Salad", "Nugget", "Soup"]; 
let myFood = "Ice Cream";
let herFood = "Noodles"; 
[myFood, herFood] = favorites; 
console.log(myFood);
console.log(herFood);
```

|Output : |
| :--     | 
| Seafood </br>Salad |

<p align="justify">Array destructuring assignment sangat berguna ketika kita hendak menukar nilai antara dua variabel. Sebelum ES6, untuk melakukan hal ini kita menggunakan cara manual menggunakan algoritma sorting seperti ini:
 </p>

```plantuml
var a = 1;
var b = 2;
var temp; 
console.log("Sebelum swap");
console.log("Nilai a: " + a);
console.log("Nilai b: " + b); 
temp = a;
a = b;
b = temp;
console.log("Setelah swap");
console.log("Nilai a: " + a);
console.log("Nilai b: " + b);
```

|Output : |
| :--     | 
| Sebelum swap</br>Nilai a: 1</br>Nilai b: 2</br>Setelah swap</br>Nilai a: 2</br>Nilai b: 1 |

<p align="justify">Dengan array destructuring assignment, kita bisa menukar nilai variabel dengan mudah tanpa membuat variabel tambahan
 </p>

```plantuml
let a = 1;
let b= 2; 
console.log("Sebelum swap");
console.log("Nilai a: " + a);
console.log("Nilai b: " + b); 
[a, b] = [b, a] 
console.log("Setelah swap");
console.log("Nilai a: " + a);
console.log("Nilai b: " + b);
```

|Output : |
| :--     | 
| Sebelum swap</br>Nilai a: 1</br>Nilai b: 2</br>Setelah swap</br>Nilai a: 2</br>Nilai b: 1 |

<p align="justify">Ketika melakukan destructuring array, tetapi terdapat variabel yang posisinya tidak dapat terjangkau oleh array, maka variabel tersebut akan bernilai undefined. Contohnya:
 </p>

```plantuml
const favorites = ["Seafood"];
const [myFood, herFood] = favorites 
console.log(myFood);
console.log(herFood);
```

|Output : |
| :--     | 
| Seafood </br> undefined|

<p align="justify">Sama seperti object, pada destructuring array kita juga dapat memberikan nilai default pada variabel yang tidak dapat terjangkau oleh array, sehingga nilai pada variabel tidak akan menjadi undefined.
 </p>

```plantuml
const favorites = ["Seafood"]; 
const [myFood, herFood = "Salad"] = favorites 
console.log(myFood);
console.log(herFood);
```

|Output : |
| :--     | 
| Seafood </br>Salad |

### Map
<p align="justify">Map adalah tipe data yang menyimpan koleksi data dengan format key-value layaknya Object. Yang membedakan adalah Map memperbolehkan key dengan tipe data apa pun, dibandingkan Object yang hanya mengizinkan key bertipe String atau Symbol. Untuk mendefinisikan Map gunakan constructor seperti di bawah ini:
 </p>

```plantuml
const myMap = new Map([
    ['1', 'a String key'],
    [1, 'a number key'],
    [true, true]
]);
console.log(myMap);
```

|Output : |
| :--     | 
| Map(3) { '1' => 'a String key', 1 => 'a number key', true => true } |

<p align="justify">kita bisa mendapatkan nilainya berdasarkan key tertentu dengan metode get(). Lalu, untuk menambahkan pasangan key-value baru gunakan metode set().
 </p>

```plantuml
const capital = new Map([
    ["Jakarta", "Indonesia"],
    ["London", "England"],
    ["Tokyo", "Japan"]
]);
console.log(capital.size);
console.log(capital.get("London"));
capital.set("New Delhi", "India");
console.log(capital.size);
console.log(capital.get("New Delhi"));
```

|Output : |
| :--     | 
| 3</br>England</br>4</br>India |

<p align="justify">Ketika kita menetapkan nilai map seperti di atas, data akan disimpan sebagai generic object. Ini akan mengakibatkan data tidak tersimpan dalam Map query dan tidak bisa menggunakan fitur dari Map seperti .has atau .delete.
 </p>

```plantuml
const wrongMap = new Map();
wrongMap["My Key"] = "My Value";
console.log(wrongMap.has("My Key"));
console.log(wrongMap.delete("My Key"));
```

|Output : |
| :--     | 
| false</br>false |

### Set
<p align="justify">Struktur data yang akan kita bahas berikutnya adalah Set. Set sederhananya merupakan kumpulan nilai (set of values). Hal yang membedakan Set dengan struktur data yang lain adalah data pada Set tidak berurutan dan juga tidak diindeks. Selain itu, data di dalam Set juga bersifat unik dan tidak ada duplikasi. Perhatikan contoh deklarasi Set di bawah ini:
 </p>

```plantuml
const numberSet = new Set([1, 4, 6, 4, 1]);
console.log(numberSet);
```

|Output : |
| :--     | 
| Set(3) { 1, 4, 6 }|

<p align="justify">Pada kode di atas terdapat beberapa angka yang duplikat, yaitu angka 1 dan 4. Secara otomatis Set akan membuang angka yang sama, sehingga nilai yang tersimpan adalah {1, 4, 6}. Untuk menambahkan data ke dalam Set kita bisa memanfaatkan fungsi add().
 </p>


```plantuml
const numberSet = new Set([1, 4, 6, 4, 1]);
numberSet.add(5);
numberSet.add(10);
numberSet.add(6);
console.log(numberSet);
```

|Output : |
| :--     | 
| Set(5) { 1, 4, 6, 5, 10 } |

<p align="justify">Fungsi add() hanya menerima satu argumen. Jika Anda memasukkan array, maka array tersebut akan dianggap sebagai satu elemen sendiri. Nilai yang duplikat akan diabaikan.
 </p>

```plantuml
const numberSet = new Set([1, 4, 6, 4, 1]);
numberSet.add(5);
numberSet.add(10);
numberSet.add(6);
numberSet.delete(4);
console.log(numberSet);
```

|Output : |
| :--     | 
| Set(4) { 1, 6, 5, 10 }|

### WeakMap and WeakSet
<p align="justify">WeakMap merupakan varian dari Map yang mendukung garbage collection. Garbage collection adalah proses di mana interpreter JavaScript mengambil kembali memori yang tidak lagi “dapat dijangkau” dan tidak dapat digunakan oleh program[3]. Garbage collection di JavaScript dilakukan secara otomatis dan bukan menjadi urusan dari developer.</br>Yang dimaksud weak dalam WeakMap adalah referensi terhadap nilai yang disimpan. Apabila suatu nilai yang disimpan di WeakMap sudah tidak terjangkau atau tidak bisa lagi diakses, maka referensi ke memorinya akan dihapus.
 </p>

Berikut ini adalah beberapa hal yang membedakan antara Map dan WeakMap:
<ul align="justify">
<li>Key dari WeakMap harus berupa object atau array. Nilai primitif tidak bisa digunakan sebagai key karena tidak mendukung garbage collection.</li>
<li>WeakMap memiliki methodget(), set(), has(), dan delete(). Namun, WeakMap tidak termasuk kategori iterable sehingga tidak memiliki method keys(), values(), atau forEach().</li>
<li>WeakMap juga tidak memiliki property size. Ini karena ukuran WeakMap dapat berubah karena proses garbage collection.</li></ul>

```plantuml
let visitsCountMap = new Map(); // Menyimpan daftar user
function countUser(user) {
    let count = visitsCountMap.get(user) || 0;
    visitsCountMap.set(user, count + 1);
} 
let jonas = { name: "Jonas" };
countUser(jonas);                // Menambahkan user "Jonas" 
jonas = null;                    // Data object "Jonas" dihapus 
console.log(visitsCountMap);
```

|Output : |
| :--     | 
| Map(1) { { name: 'Jonas' } => 1 } |

<p align="justify">Ketika nilai jonas sudah tidak bisa dijangkau, object jonas akan dihapus dari memori termasuk informasi yang disimpan di dalam WeakMap.
 </p>

```plantuml
let visitsCountMap = new WeakMap(); // Menyimpan daftar user
function countUser(user) {
    let count = visitsCountMap.get(user) || 0;
    visitsCountMap.set(user, count + 1);
}
let jonas = { name: "Jonas" };
countUser(jonas);                // Menambahkan user "Jonas"
jonas = null;                    // Data object "Jonas" dihapus
console.log(visitsCountMap);
```

|Output : |
| :--     | 
| WeakMap { <items unknown> } |

Seperti halnya WeakMap, WeakSet adalah versi weak reference dari Set. Perbedaan antara WeakSet dan Set antara lain:
<ul align="justify"><li>
WeakSet tidak bisa menyimpan nilai primitif.</li>
<li>WeakSet bukan iterable dan hanya memiliki method add(), has(), dan delete().</li>
<li>WeakSet tidak memiliki properti size.</li>
</ul>

### Kuis Coding: Object
<p align="justify">Untuk menguji kemampuan praktikal Anda dalam memahami materi object di JavaScript, silakan selesaikan kuis berikut.
 </p>

```plantuml
/**
 *TODO
 *1. Buatlah variabel dengan nama restaurant yang object dengan ketentuan berikut:
 *- Memiliki properti bernama "name"
 *- Bertipe data string
 *- Bernilai apa pun, asalkan tidak string kosong atau null.
 *- Memiliki properti bernama "city"
 *- Bertipe data string
 *- Bernilai apa pun, asalkan tidak string kosong atau null.
 *- Memiliki properti "favorite drink"
 *- Bertipe data string
 *- Bernilai apa pun, asalkan tidak string kosong atau null.
 *- Memiliki properti "favorite food"
 *- Bertipe data string
 *- Bernilai apa pun, asalkan tidak string kosong atau null.
 *- Memiliki properti "isVegan"
 *- Bertipe data boolean
 *- Bernilai boolean apa pun.
 *
 * 2. Buatlah variabel bernama name.
 *    Kemudian isi dengan nilai name dari properti object restaurant
 * 3. Buatlah variabel bernama favoriteDrink.
 *    Kemudian isi dengan nilai "favorite drink" dari properti object restaurant
 */
const restaurant = {
    name : "Yenni Syafitri",
    city : "Kota Dumai",
    "favorite drink" : "Es teh",
    "favorite food" : "Nasi kucing", 
    isVegan : false,
};
const name = restaurant.name;
const favoriteDrink = restaurant["favorite drink"];
// TODO
/**
 * Hiraukan kode di bawah ini
 */
module.exports = { restaurant, name, favoriteDrink };
```

### Pertanyaan

```plantuml
Diberikan sejumlah elemen yang harus disimpan secara berurutan. Manakah struktur data yang akan Anda gunakan?
a. Map
b. Object
c. Set
d. Array
Jawaban yang benar d ,  Berikut adalah penjelasannya:
Data yang disimpan pada array diindeks dan diakses melalui index urutannya.
```

### Functions
<p align="justify">Fungsi merupakan bagian penting dalam bahasa pemrograman. Tanpa sadar, sebenarnya kita sudah menggunakan sebuah fungsi pada contoh kode yang ada sebelumnya. log() pada console.log() merupakan sebuah function yang berguna untuk menampilkan data pada konsol. Tapi sebenarnya apa itu function? Bagaimana ia bisa bekerja?</br>Mirip dengan fungsi pada matematika, fungsi dalam pemrograman juga digunakan untuk menghasilkan output berdasarkan input tertentu.
 </p>
 <p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330132056241306402771d7676d8fe698555a0239.png" width="350" title="hover text">
</p>
<p align="justify">Namun, fungsi juga bisa digunakan sebagai blok kode atau prosedur yang dapat digunakan secara berulang. Dalam arti lain, kita dapat berpikir bahwa function merupakan sebuah variabel yang berisi blok logika. Blok logika tersebut akan dieksekusi ketika variabelnya dipanggil.</br>
Semua fungsi memiliki struktur yang sama. Fungsi dideklarasikan dengan keyword function dan nama fungsinya. Nama fungsi selalu diikuti dengan tanda kurung (parentheses) tanpa spasi, lalu terdapat sepasang kurung kurawal yang berisi logika dari fungsi tersebut.
 </p>
 <p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103301322142b4107804a5df13e0d205e7e07fa75fb.png" width="350" title="hover text"> </p>
 <p align="justify">Terkadang di dalam tanda kurung kita membutuhkan sebuah informasi tambahan yang disebut dengan parameter. Parameter merupakan data yang digunakan pada fungsi untuk diproses di dalamnya. Sebagai contoh, fungsi console.log() dapat menerima argument berupa string atau data lain untuk ditampilkan ke konsol.</br>
Berikut merupakan ilustrasi dari struktur fungsi dengan parameter:
 </p>
  <p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103301326359fac677eea8d73a094f207553eae77ed.png" width="350" title="hover text"> </p>
 
 ### Parameter & Argument
 <p align="justify">Di dalam fungsi kita akan banyak bertemu istilah parameter & argument. Penggunaan istilah ini sering kali tertukar, bahkan di kalangan developer.Perbedaan mendasar antara keduanya antara lain:</br>
Parameter merupakan variabel yang didefinisikan sebagai inputan dari sebuah fungsi. Contoh:</br>
 </p>
 
 ```plantuml
function multiply(a, b) {
    return a * b;
}
```

<p align="justify">Argument merupakan nilai atau expression yang dimasukkan ke dalam fungsi. Contohnya:
 </p>
 
```plantuml
multiply(3, 4);
```

<p align="justify">Setelah membuat fungsi kita dapat memanggilnya dengan menuliskan nama fungsi diikuti tanda kurung dan memasukkan argumen di dalamnya (jika ada).
 </p>

```plantuml
function greeting() {
    console.log("Good Morning!")
}
greeting();
```

|Output : |
| :--     | 
|Good Morning!|


<p align="justify">Untuk menambahkan parameter pada fungsi, tambahkan variabel di dalam tanda kurung fungsi. Namun, variabel tersebut tidak memerlukan keyword var, let, ataupun const. Kita juga bisa menambahkan lebih dari satu parameter dengan memberikan tanda koma antar variabel parameternya. Contohnya fungsi greeting akan kita tambahkan parameter name dan language seperti ini:
 </p>

```plantuml
function greeting(name, language) {
    if(language === "English") {
        console.log(`Good Morning ${name}!`);
    } else if (language === "French") {
        console.log(`Bonjour ${name}!`);
    } else {
        console.log(`Selamat Pagi ${name}!`);
    }
}
```

<p align="justify">Sehingga dalam memanggilnya pun kita perlu mengirimkan dua buah nilainya sebagai argumen:
 </p>

```plantuml
function greeting(name, language) {
    if(language === "English") {
        console.log(`Good Morning ${name}!`);
    } else if (language === "French") {
        console.log(`Bonjour ${name}!`);
    } else {
        console.log(`Selamat Pagi ${name}!`);
    }
}
greeting("Harry", "French");
```

|Output : |
| :--     | 
|Bonjour Harry!|

<p align="justify">Function dapat menghasilkan output atau mengembalikan sebuah nilai. Dengan nilai kembalian, kita dapat membuat function yang berfungsi untuk melakukan perhitungan matematika dan hasilnya dapat kita masukkan ke dalam sebuah variabel. Contohnya seperti ini:
 </p>

```plantuml
function multiply(a, b) {
    return a * b;
}
let result = multiply(10, 2)
console.log(result)
```

|Output : |
| :--     | 
| 20 |

<p align="justify">Agar fungsi bisa mengembalikan nilai, gunakan keyword return diikuti dengan nilai yang akan dikembalikan. Nilai kembalian tidak hanya number, bisa juga berupa string, boolean, object, array, atau tipe yang lain. Seperti inilah fungsi greeting() jika kita ubah agar mengembalikan nilai string:
 </p>

```plantuml
function greeting(name, language) {
    if(language === "English") {
        return `Good Morning ${name}!`
    } else if (language === "French") {
        return `Bonjour ${name}!`;
    } else {
        return `Selamat Pagi ${name}!`;
    }
}
let greetingMessage = greeting("Harry", "French");
console.log(greetingMessage);
```

|Output : |
| :--     | 
| Bonjour Harry! |

### Expression Function
<p align="justify">Cara lain untuk membuat sebuah fungsi pada JavaScript adalah expression function. Ingat kembali bahwa expression adalah kode atau instruksi yang mengembalikan nilai, sehingga expression function bisa disimpan dalam sebuah variabel.</br>
Pada expression function umumnya kita tidak perlu menuliskan nama fungsinya. Fungsi yang tidak bernama juga dikenal dengan anonymous function. Berikut ini merupakan contoh penulisan expression function:
 </p>

```plantuml
const greeting = function(name, language) {
    if(language === "English") {
        return "Good Morning " + name + "!";
    } else if (language === "French") {
        return "Bonjour " + name + "!";
    } else {
        return "Selamat Pagi " + name + "!";
    }
}

console.log(greeting('Ron', 'English'));
```

|Output : |
| :--     | 
| Good Morning Ron! |

### Arrow Function
<p align="justify">ES6 memperkenalkan fungsi baru yang dinamakan arrow function expression atau lebih dikenal sebagai arrow function. Arrow function mirip seperti regular function secara perilaku, tetapi berbeda dalam penulisannya. Sesuai namanya, fungsi didefinisikan menggunakan tanda panah atau fat arrow ( => ). Tentunya penulisan arrow function ini akan lebih singkat.</br>
Selain perbedaan sintaksis, terdapat perbedaan perilaku antara arrow function dan regular function. Regular function dapat berupa function declaration dan function expression. Namun, arrow function hanya berupa expression function saja. Itu sebabnya arrow function memiliki nama lengkap “arrow function expression”.
 </p>

### Regular function

```plantuml
// function declaration
function sayHello(greet) {
    console.log(`${greet}!`);
}
 
// function expression
const sayName = function (name) {
    console.log(`Nama saya ${name}`)
}
```

### Arrow function

```plantuml
// function expression
const sayHello = (greet) => {
    console.log(`${greet}!`)
}
 
const sayName = (name) => {
    console.log(`Nama saya ${name}`)
}
```

<p align="justify">Pada arrow function kita tidak perlu menuliskan keyword function setiap membuat fungsi. Kita tetap menuliskan parameter di dalam tanda kurung lalu diikuti dengan tanda panah (=>) sebelum kurung kurawal.
 </p>

```plantuml
const sayName = (name) => {
    console.log(`Nama saya ${name}`)
}
```

<p align="justify">Apabila fungsi hanya memiliki satu parameter, maka kita bisa menghapuskan tanda kurung seperti berikut:
 </p>

```plantuml
const sayName = name => {
    console.log(`Nama saya ${name}`)
}
sayName("Leia");
```

|Output : |
| :--     | 
| Nama saya Leia |

<p align="justify">Namun, jika kita sama sekali tidak membutuhkan parameter, maka kita tetap menuliskan tanda kurung namun kosong seperti ini:
 </p>

```plantuml
const sayHello = () => {
    console.log("Selamat pagi semuanya!")
};
sayHello();
```

|Output : |
| :--     | 
| Selamat pagi semuanya! |

<p align="justify">Satu hal yang menarik, ketika body dari function hanya terdiri dari satu baris, kita bisa menghapus tanda kurung kurawal. Tentunya ini akan menghemat baris kode yang kita tulis.
 </p>

```plantuml
const sayName = name => console.log(`Nama saya ${name}`);
sayName("Leia");
const sayHello = () => console.log("Selamat pagi semuanya!");
sayHello();
```

|Output : |
| :--     | 
| Nama saya Leia</br>Selamat pagi semuanya! |

<p align="justify">Ketika sebuah fungsi perlu mengembalikan nilai, kita tidak perlu lagi menuliskan return (hanya bekerja untuk fungsi satu baris).
 </p>

```plantuml
const multiply = (a, b) => a * b;
console.log(multiply(3, 4));
```

|Output : |
| :--     | 
| 12 |

### Variable Scope
<p align="justify">Variabel JavaScript menggunakan fungsi untuk mengelola cakupannya. Jika variabel didefinisikan di luar fungsi, maka variabel tersebut bersifat global. Jika variabel didefinisikan di dalam fungsi, maka variabel bersifat lokal dan cakupannya hanya pada fungsi tersebut beserta turunannya.</br>
Berikut ini merupakan contoh scoping dalam kode:
 </p>

```plantuml
// global variable, dapat diakses pada parent() dan child()
const a = 'a'; 
 
function parent() {
    // local variable, dapat diakses pada parent() dan child(), tetapi tidak dapat diakses di luar dari fungsi tersebut.
    const b = 'b'; 
    
    function child() {
        // local variable, dapat diakses hanya pada fungsi child().
        const c = 'c';
    }
}
```

<p align="justify">Kita harus berhati-hati dalam mendefinisikan variabel di dalam fungsi. Pasalnya, kita bisa mendapatkan hasil yang tidak diperkirakan, contohnya seperti berikut:
 </p>

```plantuml
function multiply(num) {
    total = num * num;
    return total;
}

let total = 9;
let number  = multiply(20);

console.log(total)
```

|Output : |
| :--     | 
| 400 |

### Closure
<p align="justify">Setelah mempelajari tentang scope pada materi selanjutnya, kali ini kita akan membahas seputar closure. Sebelumnya kita telah tahu bahwa fungsi dapat didefinisikan dalam lingkup global atau di dalam fungsi lain. Suatu fungsi yang dapat mengakses variabel di dalam lexical scope-nya disebut dengan closure. Lexical scope berarti pada sebuah fungsi bersarang, fungsi yang berada di dalam memiliki akses ke variabel di lingkup induknya.
 </p>

```plantuml
function init() {
    var name = 'Obi Wan';   // Variabel lokal di dalam scope fungsi init
    
    function greet() {      // Inner function, merupakan contoh closure
        console.log(`Halo, ${name}`);   // Memanggil variabel yang dideklarasikan di parent function
    }

    greet();
}

init();

```

|Output : |
| :--     | 
| Halo, Obi Wan |

<p align="justify">Fungsi init() memiliki variabel lokal name dan fungsi greet(). Fungsi greet() adalah inner function yang didefinisikan di dalam init() dan hanya bisa diakses dari dalam fungsi init(). Perhatikan bahwa fungsi greet() tidak memiliki variabel lokal. Namun, karena inner function memiliki akses ke variabel di parent function-nya, sehingga greet() dapat mengakses variabel name. Itulah yang dimaksud dengan lexical scope. </br>Sekarang perhatikan contoh kode berikut:
 </p>

```plantuml
unction init() {
    var name = 'Obi Wan';

    function greet() {
        console.log(`Halo, ${name}`);
    }

    return greet;
}

let myFunction = init();
myFunction();

```

|Output : |
| :--     | 
| Halo, Obi Wan |


<p align="justify">JavaScript tidak memiliki cara untuk mendeklarasikan suatu fungsi atau variabel menjadi private seperti bahasa Java. Sehingga sebuah fungsi atau variabel bisa diakses dari mana pun. Kenapa kita membutuhkan private method? Salah satunya adalah untuk membatasi akses ke fungsi atau variabel. Perhatikan contoh berikut:
 </p>

```plantuml
let counter = 0;

let add = () => {
    return ++counter;
}

console.log(add());
console.log(add());
counter = 23;
console.log(add());
```

|Output : |
| :--     | 
| 1</br>2</br>24 |

<p align="justify">Closure memungkinkan kita membuat fungsi dan variabel seolah menjadi private. Seperti inilah contoh program counter yang dibuat dengan closure:
 </p>


```plantuml
let add = () => {
    let counter = 0;
    return () => {
        return ++counter;
    };
}

let addCounter = add();

console.log(addCounter());
console.log(addCounter());
console.log(addCounter());
```

|Output : |
| :--     | 
| 1</br>2</br>3 |


### Kuis Coding: Function
<p align="justify">Mohon untuk membaca secara seksama perintah, kriteria, atau soal pada komentar kode yang diberi tanda TODO. 
 </p>


```plantuml
/**
 * TODO:
 * 1. Buatlah fungsi bernama minimal dengan ketentuan berikut:
 *    - Menerima dua buah argumen number, a dan b.
 *    - Mengembalikan nilai terkecil antara a atau b.
 *    - Bila nilai keduanya sama, maka kembalikan dengan nilai a
 *
 *    contoh:
 *    minimal(1, 4) // 1
 *    minimal(3, 2) // 2
 *    minimal(3, 3) // 3
 *
 * 2. Buatlah fungsi bernama power dengan ketentuan berikut:
 *    - Menerima dua buah argumen number, a dan b.
 *    - Mengembalikan nilai dari hasil perkalian a * a sebanyak b (fungsi kuadrat).
 *
 *    contoh:
 *    power(7, 3) // 343
 *    power(3, 3) // 27
 *    power(4, 0.5) // 2
 */
// TODO
const minimal = (a,b) => a==b ? a : a<b ? a:b
const power = (a,b) => a**b
console.log(minimal(3,2))
console.log(power(7,3))
/**
 * Hiraukan kode di bawah ini
 */
module.exports = { minimal, power };
```

|Output : |
| :--     | 
| 2</br>343 |


<p align="justify"><b>Rangkuman Materi</b></br>Untuk membuat kode yang bersih dan mudah dipahami, salah satu cara yang bisa kita lakukan adalah dengan menggunakan function. Beberapa hal yang telah kita bahas pada modul ini, antara lain:
</p>
<ol align="justify"><li>
 Function/fungsi adalah blok atau kumpulan kode yang memungkinkan untuk dipanggil berkali-kali.</li>
<li>Penamaan fungsi harus mendeskripsikan fungsi dengan jelas. Penamaan yang bagus akan langsung memberi kita pemahaman tentang apa yang dilakukan atau dikembalikan.</li>
<li>Function dapat menerima masukan nilai melalui parameter.</li>
<li>Fungsi dapat mengembalikan nilai. Jika tidak, maka hasilnya adalah undefined.</li>
<li>Karena fungsi berupa nilai, fungsi dapat ditetapkan atau dideklarasikan di setiap tempat kode, termasuk variabel atau parameter dari fungsi lain.</li></ol>

<p align="justify"><b>Pertanyaan</b></br>
Berapa banyak parameter yang bisa dimiliki oleh suatu function?</p>
 <ol type='a'><li>
Bisa satu atau dua</li>
<li> Hanya satu</li>
<li> Minimal tiga</li>
<li> Sesuai kebutuhan</li></ol>
<details>
  <summary>Jawaban Benar</summary>
  d.Sesuai kebutuhan</br>
  Berikut adalah penjelasannya:
Kita bisa menentukan jumlah parameter sesuai kebutuhan fungsi yang kita buat.
</details>

<p align="justify"><b>Object-Oriented Programming (OOP)</b></br>
<b>Object Oriented Programming atau OOP</b> adalah salah satu paradigma pemrograman yang sangat umum digunakan oleh developer di dunia. Paradigma OOP berdasarkan pada konsep objek yang memiliki atribut serta dapat melakukan operasi atau prosedur tertentu.Meskipun JavaScript bukan bahasa pemrograman yang berbasis class seperti Java.Java sepenuhnya mengusung paradigma OOP, tetapi JavaScript tetap bisa menerapkan dan memanfaatkan fitur OOP.</p>

<p align="justify"><b>Introduction to OOP</b></br>
Object Oriented Programming (OOP) adalah salah satu paradigma dalam dunia pemrograman komputer. Ia adalah pendekatan berbasiskan objek, di mana suatu objek terdiri dari kumpulan atribut dan method di dalamnya. Di dalam JavaScript, atribut adalah variable, yang digunakan untuk menyimpan nilai. Sementara method adalah fungsi, yang digunakan untuk menjalankan suatu proses.</br></br>
Untuk lebih mudah memahami apa itu OOP, kita bisa menggunakan pemodelan hal-hal dunia nyata ke dalam program yang kita buat. Ambil contoh Kucing, ia berperan sebagai objek.
Kita ibaratkan ada seekor yang kucing memiliki karakteristik bulunya berwarna kuning, tinggi badan 23 cm, dan juga berat badan 4kg. Kucing tersebut juga memiliki kemampuan khusus yaitu mampu berlari, melompat, dan juga tidur. </br></br>
Nah, dalam konteks OOP, karakteristik kucing (warna bulu, tinggi badan, dan berat badan) merupakan atribut dari suatu objek kucing, ia adalah nilai-nilai yang dimiliki oleh seekor kucing. Sedangkan kemampuan (berlari, melompat, tidur) adalah method dari seekor kucing, ia adalah suatu aktivitas yang bisa dilakukan oleh seekor kucing.
JavaScript memiliki kapabilitas untuk membuat program dengan menerapkan paradigma OOP. Meskipun ada beberapa perbedaan dan perdebatan mengenai OOP di JavaScript dengan yang ada di bahasa pemrograman lain.</br></br>
Sebelumnya kita sudah mengenal dan mempelajari object. Di mana object dapat merepresentasikan sebuah layer data. Jika string dianalogikan sebagai kata (kumpulan karakter), number sebagai angka, dan boolean sebagai pernyataan benar atau salah; object dianalogikan sebagai sebuah benda yang lebih kompleks. OOP-pun sama, namun lebih kompleks lagi karena di dalam paradigma OOP terdapat 4 pilar utama, yaitu encapsulation, abstraction, inheritance, dan polymorphism.</br></br>
Sebagai contoh, kita memiliki sebuah data object bernama mail seperti contoh di bawah ini.</p>


```plantuml
const mail = {
    from: "pengirim@dicoding.com",
  sendMessage: function(msg, to) {
    console.log(`you send: ${msg} to ${to} from ${this.from}`);
  } 
};
console.log(mail.from);
mail.sendMessage('apakabar', 'penerima@dicoding.com');
```

|Output : |
| :--     | 
| you send: apakabar to penerima@dicoding.com from pengirim@dicoding.com |

<p align="justify">Object di atas memiliki atribut dengan tipe data string (from) dan sebuah fungsi atau method untuk mengirim pesan (sendMessage). Selain itu kita juga dapat mengubah isi dari salah satu atribut dari objek tersebut. Contohnya:
 </p>

```plantuml
mail.from = "pengirim2@dicoding.com";
```

<p align="justify">Atau, menambahkan sebuah fungsi baru bernama saveContact. </p>

```plantuml
mail.saveContact = function(addr) {
  console.log('email saved:', addr);
}
```

<p align="justify">Contoh di atas adalah penulisan dengan gaya format object literal, yaitu penulisan object dengan langsung menuliskan key dan value-nya dalam Object yang dibuat. Hal-hal tersebut belum sepenuhnya merangkum konsep object dalam OOP.</br></br>
Misalkan akan ada pertanyaan: </p><ol align="justify"><li>
Bagaimana jika saya ingin membuat objek baru bernama mail2 dengan atribut yang sama namun value yang berbeda dengan mail? Apakah harus mendefinisikan attribute dan function/method yang sama secara berulang?</li>
<li>Bagaimana jika saya ingin membuat mail2 tanpa attribute saveContact?</li>
<li>Bagaimana jika saya ingin menambahkan fungsi tambahan pada mail2?</li></ol>
<p align="justify">Dari sedikit pertanyaan di atas, maka fungsi paradigma OOP dapat menjadi solusi dikarenakan memiliki 4 pilar yang sudah disebutkan sebelumnya, di mana sederhananya kita akan membuat base template dari sebuah object, kemudian dari base tersebut kita dapat meng-instansiasi dalam bermacam bentuk objek. Di bawah ini adalah gambaran di mana Mail adalah base template dan sms, email, mailgroup adalah instansiasi dari Mail.</p>

 <p align="justify"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/2021033109272405b54a1be326c130d0120c59bff3361a.png" >
</p>

 <p align="justify">
Contoh lainnya, misalkan base template dari sebuah object adalah Animal dan dapat merepresentasikan berbagai bentuk misalkan aves, mamalia, pisces, dll. Untuk membuat base template tersebut maka kita akan mempelajari Class terlebih dahulu.</p>

 <p align="justify"><b>Class</b>
Class adalah hal yang sangat penting dalam pemrograman berorientasi objek. Hal itu karena class menyediakan informasi tentang suatu object. Jadi dapat dikatakan object adalah instance dari sebuah class. Class sendiri dalam paradigma OOP secara teknis merupakan sebuah blueprint dalam mendefinisikan karakteristik dari sebuah objek. Sebagai contoh, misalkan terdapat blueprint untuk mendefinisikan objek Mail. Yang mana sms dan postman adalah object dari class Mail.</p>

|      Nama      |              Class	Mail   |
|    :--         |                :--          |
|Karakteristik   |pengirim, penerima, isi pesan|
|Kapabilitas/aksi|kirim pesan, terima pesan    |

 <p align="justify">Penulisan kelas di JavaScript sendiri bisa menggunakan sintaks class ataupun fungsi.</p>

```plantuml
// Cara 1
class YourClassName{}
class YourAnotherClassName{
    constructor(property1, property2) {}
}
// Cara 2
function YourClassName() {}
function YourAnotherClassName(property1, property2) {}
// pemanggilannya
const nameOfObject = YourClassName();
const nameOfObject2 = new YourAnotherClassName('value of property', 123);
```

<p align="justify">Sebagai contoh, kita akan membuat blueprint untuk Mail, yang mana memiliki attribute from dan method sendMessage.</p>

<p align="justify">function</p>

```plantuml
function Mail() {
    this.from = 'pengirim@dicoding.com';
    this.sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    };
};
 
const mail1 = new Mail();
mail1.sendMessage('hallo', 'penerima@dicoding.com');
```

|Output : |
| :--     | 
| you send: hallo to penerima@dicoding.com from pengirim@dicoding.com |


```plantuml
class Mail{
  from = 'pengirim@dicoding.com';
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    };
}
 
const mail1 = new Mail();
mail1.sendMessage('hallo', 'penerima@dicoding.com');
```


|Output : |
| :--     | 
| you send: hallo to penerima@dicoding.com from pengirim@dicoding.com |


<p align="justify">Kedua cara di atas adalah contoh penulisan dan instansiasi object dari sebuah Class.</br></br><b>Property & Method
Property</b></br>Property adalah atribut dari sebuah objek, property sendiri dapat berupa tipe data primitive--seperti yang sebelumnya dibahas-- bahkan bisa juga berbentuk object dan fungsi. Misalkan isi pesan, list penerima, data pengirim, perintah kirim, dll. Sebagai contoh
 </p>

```plantuml
// cara 1
class Mail{
  from = 'pengirim@dicoding.com';
    contacts = [];
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    this.contacts.push(to); // menyimpan kontak baru
    };
}
// cara 2
function Mail() {
    this.from = 'pengirim@dicoding.com';
    this.contacts = [];
    this.sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    this.contacts.push(to); // menyimpan kontak baru
    };
};
```

<p align="justify">Contoh class di atas memiliki 3 (tiga) property dan method. Yang perlu diingat adalah, this merupakan representasi bahwasanya field yang ditunjuk adalah field global dan dapat diakses dari method ataupun property di dalam kelas tersebut dengan menambahkan this di depannya. Sebagai gambaran, kita akan coba ubah kode di atas menjadi seperti berikut ini:
 </p>

```plantuml
class Mail{
  from = 'pengirim@dicoding.com';
	contacts = [];
	sendMessage = function(msg, to, from) {
		console.log('you send:', msg, 'to', to, 'from', from); // from di sini merujuk ke `from` parameter, bukan ke `from` dari global value yaitu pengirim@dicoding.com
    this.contacts.push(to);
	};
}

const mail1 = new Mail();
mail1.sendMessage('hallo', 'penerima@dicoding.com', 'aku@gmail.com');

/**
you send: hallo to penerima@dicoding.com from aku@gmail.com
**/
```


|Output : |
| :--     | 
| you send: hallo to penerima@dicoding.com from aku@gmail.com |


<p align="justify">Contoh di atas menunjukan bahwa ketika kita ingin menginisialisasi ataupun mengakses sebuah attribute global dari sebuah kelas, maka harus menggunakan this.attributeName. Dalam OOP sendiri, properti dibagi menjadi 2: </p>
<ol  align="justify"><li>
Internal interface : method dan property yang dapat diakses oleh method lain namun tidak bisa diambil/dijalankan di luar kelas tersebut.</li>
<li>External interface : method dan property yang dapat diakses di luar kelas itu sendiri.</li></ol>
<p align="justify">Sedangkan di dalam JavaScript sendiri terdapat 2 jenis akses identifier untuk sebuah field:</p>
<ol  align="justify"><li>Public : dapat diakses dari mana pun.</li>
<li>Private : hanya dapat diakses dari dalam kelas itu sendiri.</li></ol>

<p align="justify">Secara default, semua atribut yang didefinisikan adalah public. Sehingga semua attribute tersebut dapat diakses oleh objek yang telah meng-instansiasi kelas tersebut. Sebagai contoh</p>


```plantuml
const mail1 = new Mail();
mail1.from; // 'pengirim@dicoding.com'
mail1.contacts; // ['penerima@dicoding.com']
mail1.sendMessage('hallo', 'penerima@dicoding.com'); // method mengirim pesan
```

<p align="justify">Dari contoh tersebut, bagaimana jika kita ingin mengubah attribute contacts yang tidak dapat diakses langsung oleh objek yang telah meng-instansiasi. Kita perlu mengubah sedikit pada kode class Mail yang kita miliki:
 </p>

```plantuml
/** 
cara 1, menggunakan var (hanya dapat digunakan pada penulisan kelas menggunakan statement `function`)
**/
var contacts = [];
// contoh
function Mail(){
  this.from = 'pengirim@dicoding.com';
    var contacts = [];
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
                      contacts.push(to);
    };
}
 
 
/**
cara 2, cara ini dapat digunakan pada penulisan kelas menggunakan statement `function` dan `class`
**/
_contacts = []
// contoh
class Mail{
  from = 'pengirim@dicoding.com';
    _contacts = [];
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    this._contacts.push(to);
    };
}
/** 
cara 3, menambahkan prefix # , cara ini dapat digunakan pada penulisan kelas menggunakan statement `class` saja 
  **/
#contacts = [];
// contoh
class Mail{
  from = 'pengirim@dicoding.com';
    #contacts = [];
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
    this.#contacts.push(to);
    };
}
```

<p align="justify">Dari contoh di atas, ketika kita ingin mengakses attribute contacts secara langsung melalui objek yang menginisiasi maka return-nya adalah undefined. Ketiga cara tersebut juga dapat digunakan pada sebuah method atau function.
 </p>
 
 ```plantuml
const mail = new Mail();
mail.contacts; // undefined
```
 
 <p align="justify"><b>Class Method</b></br>
Class Method adalah function atau method yang ada di dalam sebuah object. Untuk menggunakannya, sebuah class harus di-instantiate terlebih dahulu menjadi object baru bisa dijalankan. Contoh class mail di atas, kita akan menggunakan method sendMessage maka kita harus meng-instantiate Mail terlebih dahulu.
 </p>
 
 ```plantuml
const mail1 = new Mail();
mail1.sendMessage('hallo', 'penerima@dicoding.com');
```
 
|Output : |
| :--     | 
| you send: hallo to penerima@dicoding.com from pengirim@dicoding.com|

<p align="justify">Kita tidak dapat langsung mengakses sendMessage tanpa melakukan instansiasi terlebih dahulu, misalkan:
 </p> 

```plantuml
Mail.sendMessage('hallo', 'penerima@dicoding.com');
```

|Output : |
| :--     | 
| TypeError: Mail.sendMessage is not a function |

<p align="justify"><b>Static Method</b></br>
Static method adalah function atau method yang sama seperti class method, akan tetapi untuk mengaksesnya tidak perlu meng-instantiate class, kita cukup menuliskan nama kelas dan nama method-nya secara langsung (NamaClass.namaMehod()).</br></br>
Sebagai contoh, kita menambahkan sebuah method untuk memeriksa apakah sebuah input adalah nomor handphone:
 </p>

```plantuml
class Mail{
  static isValidPhone(phone) {
    return typeof phone === 'number';
  }
}
```

<p align="justify">Dari contoh di atas, kita dapat memanggil fungsi tersebut tanpa membuat instance kelas Mail terlebih dahulu.
 </p>

```plantuml
Mail.isValidPhone(089000000000) //true
```

<p align="justify"><b>Constructor</b></br>
Ketika kita membuat sebuah objek, adakalanya karakteristik dari blueprint yang kita buat harus sudah didefinisikan bersamaan dengan sebuah objek saat pertama kali diinisiasi. Constructor adalah sebuah method/function yang dijalankan pertama kali ketika object dibuat. Dari contoh kelas yang kita buat sebelumnya, kita akan membuat from sebagai sebuah value yang harus ditulis ketika sebuah objek di inisiasi. Maka dalam JavaScript ada dua cara, yaitu:
 </p>

```plantuml
// cara 1, jika kita menggunakan statement class
class YourClassName{
  constructor(params1, params2, ....) {
    // do something here
  };
} 
// cara 2, jika kita menggunakan statemen function
function Mail(params1, params2, ....) {
    this.yourPropertyName = params1;
  // do something here
}
```

<p align="justify">Contoh penerapannya sebagai berikut:
 </p>

```plantuml
// cara 1
class Mail{
  constructor(author) {
    this.from = 'pengirim@dicoding.com';
    console.log('is instantiated', author);
  };
}
// cara 2
function Mail(author) {
    this.from = author;
  console.log('is instantiated', author);
}
```

<p align="justify">Dari contoh constructor di atas, maka cara pemanggilannya menjadi seperti di bawah ini:
 </p>

```plantuml
const mail1 = new Mail("emailku@dicoding.com");
```

<p align="justify">Karena JavaScript bukan bahasa dengan dukungan static type maka sebenarnya kita dapat melakukan instansiasi dengan parameter sesuka kita:
 </p>

```plantuml
const mail1 = new Mail(085000111222); // misalkan untuk SMS
const mail2 = new Mail("emailku@dicoding.com"); // misalkan untuk Email
```

<p align="justify"><b> 4 Pilar OOP</b>
Seperti yang sempat kita singgung pada awal modul OOP, terdapat empat pilar dalam OOP, yaitu encapsulation, abstraction, inheritance, dan polymorphism.</br></br>
<b>Encapsulation</b>
Enkapsulasi adalah kondisi di mana attribute atau method di dalam class dibungkus dan bersifat privat. Artinya objek lain tidak bisa mengakses atau mengubah nilai dari property secara langsung. Pada contoh kasus Mail kita tidak bisa langsung mengubah daftar contact, namun kita bisa menambahkannya melalui fungsi saat kirim pesan atau mengambil data tersebut melalui method showAllContacts.
 </p>

<p align="justify"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/2021033110152837f7fc725e54468b736219807f4a2b2f.png"></p>

```plantuml
class Mail{
    _contacts = [];
    constructor(author) {
        this.from = author;
    }
    sendMessage = function(msg, to) {
        console.log('you send:', msg, 'to', to, 'from', this.from);
        this._contacts.push(to);
    }
    showAllContacts() {
        return this._contacts;
    }
}
```

<p align="justify"><b>Abstraction</b></br>
Abstraksi dapat dikatakan merupakan penerapan alami dari enkapsulasi. Abstraksi berarti sebuah objek hanya menunjukkan operasinya secara high-level. Misalnya kita cukup tahu bagaimana bagaimana pesan dikirim atau diterima, namun kita tidak perlu tahu seperti apa proses enkripsi dan deskripsi isi pesan, atau bagaimana sebuah daftar  contact dapat bertambah.</br></br>
<b>Inheritance</b></br>
Beberapa objek bisa memiliki beberapa karakteristik atau perilaku yang sama, tetapi mereka bukanlah objek yang sama. Di sinilah inheritance atau pewarisan berperan. SMS dan jenis pesan lainnya memiliki karakteristik umum yang dimiliki juga oleh jenis pesan lainnya, seperti memiliki konten pesan, alamat/nomor pengirim, alamat/nomor penerima, dsb. Maka dari itu Email sebagai objek turunan (subclass) mewarisi semua sifat dan perilaku dari objek induknya (superclass) Mail. Begitu juga dengan objek Whatsapp juga mewarisi sifat dan perilaku yang sama, namun whatsapp bisa membuat grup, mengirim broadcast message sedangkan Email tidak (*misalkan).
 </p>
<p align="justify"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210331101812f297bf560a9a74da5feaa334a070eeab.png"></p>
<p align="justify">Dari contoh di atas, misalkan kita ingin membuat 2 (dua) child class yaitu WhatsApp dan Email. Maka dalam JavaScript cara menuliskan pewarisan terdapat 2 cara, yaitu sebagai berikut:</p>


```plantuml
// cara 1: menggunakan keyword `extends` jika menggunakan statement `class`
class ChildClassName extends ParentClassName{}
// cara 2: menggunakan `prototype` jika menggunakan statement `function` / `class`
ChildClassName.prototype = new ParentClassName()
```

<p align="justify">Misalkan kita akan membuat sebuah child class bernama WhatsApp yang mewarisi kelas Mail. Maka contoh kodenya adalah sebagai berikut:
 </p>

```plantuml
class Mail{
  _contacts = [];
         constructor(author) {
                     this.from = author;
           };
	sendMessage = function(msg, to) {
		console.log('you send:', msg, 'to', to, 'from', this.from);
                     this._contacts.push(to);
	};
	showAllContacts() {
    return this._contacts;
  }
}

class WhatsApp extends Mail{
           username = 'dicoding';
	isBussinessAccount = true;
	
	myProfile = function() {
                   return `my name ${this.username}, is ${this.isBussinessAccount? 'Business': 'Personal'}`;
            };
}

const wa1 = new WhatsApp(080111000222);
console.log(wa1.myProfile());
// my name dicoding, is Business
```

|Output : |
| :--     | 
| my name dicoding, is Business |

<p align="justify">Kita juga dapat mengakses attribute maupun method dari parent class yang Accessible. Misalkan:
 </p>

```plantuml
wa1.sendMessage('halo', 089000999888);
```

<p align="justify"><b>Polymorphism</b></br>
Polymorphism dalam bahasa Yunani berarti “banyak bentuk.” Sederhananya objek dapat memiliki bentuk atau implementasi yang berbeda-beda pada satu metode yang sama. Semua jenis Mail dapat mengirim pesan, namun whatsapp, email, sms tentunya memiliki cara yang berbeda dalam mengirim pesan, misalkan: whatsapp dapat mengirim pesan suara sedangkan yang lainnya tidak, email dapat menyaring konten spam saat mengirim pesan sedangkan yang lain tidak. Perbedaan bentuk atau cara mengirim pesan tersebut merupakan contoh dari polymorphism.</br></br>
<b>Overriding Method</b></br>
Overriding adalah teknik untuk kita melakukan perombakan (baik total ataupun tidak) pada sebuah method ataupun constructor yang dimiliki oleh parent class sehingga dapat disesuaikan dengan behavior di child class.</br></br>
<b>Overriding Constructor</b></br>
Sebelumnya kita telah mempelajari tentang constructor dan juga pewarisan. Pada contoh kasus di inheritance atau pewarisan, kita menemukan kasus seperti di bawah ini.
 </p>

```plantuml
class WhatsApp extends Mail{
  username = 'dicoding';
    isBussinessAccount = true;
  ....
}
//pemanggilan
const wa1 = new WhatsApp(080111000222);
```

<p align="justify">Sekarang bagaimana jika kita menambahkan username dan isBussinessAccount ke dalam constructor? Jika kita membuat constructor baru kodenya akan seperti ini:
 </p>

```plantuml
class WhatsApp extends Mail{
    constructor(username, isBussinessAccount, phone) {
        this.from=phone;
    this.username = username;
    this.isBussinessAccount = true;
    }
}
 
const wa1 = new WhatsApp('dicoding', true, 089989090898);
/** 
Error:
Must call super constructor in derived class before accessing 'this' or returning from derived constructor
**/
```

<p align="justify">Akan terjadi error tersebut dikarenakan constructor pada kelas parent gagal dieksekusi, meskipun kita telah menggunakan operator this.nameOfProperty. Solusinya kita menggunakan operator super() untuk mengeksekusi method parent-nya. Sehingga constructor pada kelas WhatsApp menjadi seperti ini.
 </p>

```plantuml
constructor(username, isBussinessAccount, phone) {
  super(phone);
  this.username = username;
  this.isBussinessAccount = true;
}
```

<p align="justify">Overriding Method
Hampir sama dengan overriding constructor, namun yang di-override di sini adalah method-method yang ada pada parent class. Pada dasarnya semua method yang ada pada kelas parent dapat diakses langsung di child kelasnya (as is).
 </p>

```plantuml
super.methodName();
```

<p align="justify">Kadang kita tidak menggunakan sebuah method seutuhnya sama seperti parent kelasnya. namun dapat menambahkan perintah tertentu ataupun menguranginya. Berikut merupakan contoh override pada method sendMessage.
 </p>

```plantuml
class WhatsApp extends Mail{
  constructor(username, isBussinessAccount, phone) {
    super(phone);
    this.username = username;
    this.isBussinessAccount = true;
  }
    
  // Overriding method => Melakukan Override Total
  sendMessage = function(msg, to) {
    console.log('Send by WA');
  }
}
```

<p align="justify">Dari contoh tersebut, ketika kita memanggil method sendMessage hanya akan mengeksekusi kode yang ada pada child class.
 </p>

```plantuml
const wa1 = new WhatsApp('di', true, 089000999888);
wa1.sendMessage('halo', 089000999888);
```

|Output : |
| :--     | 
| Send by WA|


<p align="justify">Untuk tetap melakukan eksekusi kode pada parent class maka perlu menggunakan operator super.methodName().
 </p>

```plantuml
sendMessage = function(msg, to) {
    super.sendMessage(msg, to);
    console.log('Send by WA');
}
```

<p align="justify"><b>Catatan:</b></br>
super(...) digunakan untuk memanggil constructor parent, dan hanya dapat digunakan di constructor.</br>
super.methodName(...) digunakan untuk memanggil parent method.
 </p>

<p align="justify"><b>Object Composition</b></br>
Setelah konsep dari OOP kita pelajari, pasti sudah ada gambaran terkait dengan bagaimana membuat sebuah Parent Class kemudian membuat berbagai Child Class yang mana mewarisi sifat-sifat dari Parent nya, serta dapat menambahkan, mengubah, bahkan merombak setiap method yang ada.</br>
Perlu diketahui bahwasanya sebuah paradigma OOP akan menghasilkan hirarki, di mana semakin besar software yang kita buat maka akan semakin besar dan rumit juga hirarkinya.
 </p>

<p align="justify"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210331102921eb2aa008d7687e65a8eb5fcd5e77f661.png"></p>

<p align="justify">Coba bayangkan saja jika kita ingin membuat Child Class bernama PersonalEnterpriseWhatsApp di mana blueprint kelas tersebut kita ingin menggunakan method dan attribute yang ada di PersonalWhatsApp dan BussinessWhatsApp.  Dapat dibayangkan kita akan merombak kembali kelas-kelas parent-nya hanya untuk membuat sebuah kelas baru. Nah, pendekatan object composition di sini berperan.</br></br>
Object composition adalah prinsip komposisi dari sebuah alur bisnis tanpa perlu melakukan pewarisan dari parent-nya. Prinsip ini didasarkan di mana kita telah mendefinisikan kumpulan-kumpulan perilaku (method/function) sehingga ketika kita ingin membuat alur bisnis lain dengan beberapa perilaku (method) yang sama, kita dapat menggunakan yang sudah ada tanpa melakukan inheritance/pewarisan.</br></br>
Pada dasarnya konsep yang harus dilakukan adalah:</br>
1. Memisahkan fungsi-fungsi umum yang biasa digunakan
 </p>

```plantuml
const yourGenericAction = params => ({
  actionA: () => { /** do action A **/},
  actionB: () => { /** do action B **/},  
});
```

<p align="justify">2. Membuat Class seperti biasa.
 </p>

```plantuml
const YourClassName = (paramA, paramB) => {
}
```

<p align="justify">3. Kita dapat menyimpan attribute yang kita punya ke dalam sebuah object, biasanya seorang engineer menggunakan konstanta dengan nama self atau state untuk menampung attribute.
 </p>

```plantuml
const YourClassName = (paramA, paramB) => {
  const self = {
    paramsA,
    paramsB
  };
}
```

<p align="justify">4. Menambahkan perilaku (method/function) yang hanya ada pada kelas tersebut.
 </p>

```plantuml
const YourClassName = (paramA, paramB) => {
  const self = {
    paramsA,
    paramsB
  };
  
  const yourSpecificActions = self => ({
    specificActinA: { /** do action A **/},
  });
}
```

<p align="justify">5. Membuat kumpulan attribute, generic method, dan spesific method menjadi satu objek
 </p>

```plantuml
const YourClassName = (paramA, paramB) => {
  const self = {
    paramsA,
    paramsB
  };
  
  const yourSpecificActions = self => ({
    specificActinA: { /** do action A **/},
  });
  
  return Object.assign(self, yourGenericAction(self), yourSpecificActions(self))
}
```


<p align="justify">Sebagai contoh, dari hirarki Mail yang sudah kita buat sebelumnya. kita akan merombak dan membuatnya dengan pendekatan Object composition.
 </p>

```plantuml
// [1] list of abstractions
const canSendMessage = self => ({
    sendMessage: () => console.log('send message:', self.message)
  });

const checkIsValidPhone = self => ({
    isValid: () => console.log('valid phone', self.from)
  });

// [2] crate object composition
const personalEnterprise = (from, message, store) => {
  // [3] attributes
  const self = {
    from,
    message,
    store
  };
  // [4] method
  const personalEnterpriseBehaviors = self => ({
    createCatalog: () => console.log('Catalog has created: ', self.store)
  });
  
  // [5] create object composition
  return Object.assign(self, personalEnterpriseBehaviors(self), canSendMessage(self), checkIsValidPhone(self));
};

const pe1 = personalEnterprise('pengirim@gmail.com', 'hei produk baru nih', 'Dicoding Store');
pe1.createCatalog(); //Catalog has created:  Dicoding Store
pe1.sendMessage(); //send message: hei produk baru nih
```

|Output : |
| :--     | 
| Catalog has created:  Dicoding Store</br>send message: hei produk baru nih |

<p align="justify">Penjabaran kode di atas: </p>
<ol align="justify"><li>
Kita membuat sebuah abstraksi untuk method-method yang umum digunakan (di sini misalkan method mengirim pesan, dan validasi nomor hp).</li>
<li>Kita membuat sebuah kelas baru dengan nama personalEnterprise, di mana seperti biasa kita dapat menggunakan parameter yang akan digunakan.</li>
<li>Pada  object composition ini, penggunaan parameter biasa digunakan untuk mendaftarkan attribute-attribute dari kelas tersebut. Pada contoh di atas, kita mengumpulkan attribute tersebut pada konstanta bernama self atau state.</li>
<li>Method, kita dapat juga menambahkan method/fungsi yang spesifik hanya ada pada kelas tersebut (kapabilitasnya hanya pada kelas tersebut / tidak umum).</li>
<li>Proses pembuatan object dengan perintah Object.assign(attribute, method1, method2, methodN).</li></ol>
<p align="justify">Dari contoh kode di atas maka kita dapat membuat sebuah object dengan nama personalEnterprise tanpa harus melakukan pewarisan.</br></br>
<b>Built-in Class</b></br>
Dalam JavaScript sendiri terdapat built-in Object bawaan, misalkan Date, Object, Array, Math, dan String yang dapat digunakan untuk memanipulasi data-data terkait dengan array, perintah matematik, manipulasi karakter, dan manipulasi objek.</br></br>
Date merupakan core object bawaan dari bahasa pemrograman JavaScript yang digunakan untuk utilitas terkait tanggal dan waktu. Ini sangat membantu kita ketika dalam program yang kita buat terdapat penggunaaan dan manipulasi tanggal dan waktu.</br></br>
Untuk menggunakannya kita dapat me-instansiasi Date object tersebut dengan 4 cara:	
 </p>

```plantuml
// #1 tanpa parameter, yang berarti `myDate` akan berisi tanggal dan waktu saat ini
const myDate = new Date(); 
// #2 parameter tanggal dalam bentuk string, misal  "January 01, 2021" 
const myDate = new Date(dateString); 
// #3 parameter dalam bentuk number, misal 87400000
const myDate = new Date(miliseconds);  
// #4 parameter tanggal dalam bentuk number (7 parameter), [hour,minute,second,millisecond] bersifat opsional
const myDate = new Date(year,month,date,hour,minute,second,millisecond); 
```

<p align="justify">Dalam object Date terdapat beberapa method yang dapat kita gunakan. Berikut adalah daftar method yang umum digunakan.
 </p>

<table><tr><td>Methods </td><td>	Penjelasan</td><td>	Contoh penggunaan</td></tr>
<tr><td>getMonth()	</td><td>Nilai kembaliannya adalah bulan dalam bentuk angka (0 sampai 11), 0 berarti Januari.	</td><td>myDate.getMonth()</td></tr>
<tr><td>getFullYear()	</td><td>Nilai kembaliannya adalah tahun, misalkan 2021.	</td><td>myDate.getFullYear()</td></tr>
<tr><td>getDate()	</td><td>Nilai kembaliannya adalah tanggal dari 1 sampai 31.	</td><td>myDate.getDate()</td></tr>
<tr><td>getHours()	</td><td>Nilai kembaliannya adalah jam dari 0 sampai 23	</td><td>myDate.getHours()</td></tr>
<tr><td>getMinutes()	</td><td>Nilai kembaliannya adalah menit dari 0 sampai 59 Nilai kembaliannya	</td><td>myDate.getMinutes()</td></tr>
<tr><td>getSeconds()	</td><td>Nilai kembaliannya adalah detik dari 0 sampai 59	</td><td>myDate.getSeconds()</td></tr>
<tr><td>getMilliseconds()</td><td>Nilai kembaliannya adalah mili-detik dari 0 to 999	</td><td>myDate.getMilliseconds()</td></tr>
<tr><td>getTime()</td><td>Nilai kembaliannya adalah waktu dalam bentuk epoch mili-detik (dimulai dari 1 January, 1970 yang berarti 0)	</td><td>myDate.getTime()</td></tr>
<tr><td>getDay()</td><td>Nilai kembaliannya adalah hari dalam seminggu dari 0 sampai 6. 0 berarti minggu	</td><td>myDate.getDay()</td></tr>
</table>

<p align="justify">Selain itu, juga terdapat static method yang dapat digunakan tanpa perlu melakukan instansiasi, yaitu: </p>

<table><tr><td>Method	Penjelasan</td><td>	Contoh Penggunaan</td></tr>
parse(datestring)	</td><td>digunakan untuk merubah tanggal dalam format string, menjadi epoch miliseconds	</td><td>Date.parse("2021-01-01")</td></tr>
UTC(year, [..params])	</td><td>digunakan untuk merubah tanggal dalam format string, menjadi epoch miliseconds	</td><td>Date.UTC(2021, 01, 01)</td></tr>
</table>

<p align="justify"><b>Date String Format</b>
ketika kita menggunakan tanggal dan waktu, kita perlu memahami format yang dipakai oleh standar dunia. Ini berguna dan memudahkan kita untuk melakukan konversi dan manipulasi sebuah tanggal. Format date string sendiri, secara umum terdiri dari:</p>

<table><tr><td>Format	</td><td>Penjelasan</td></tr>
<tr><td>YYYY	</td><td>4 digit tahun, misalkan : 2021</td></tr>
<tr><td>MM	</td><td>2 digit bulan, misalkan : 01 berarti Januari</td></tr>
<tr><td>DD	</td><td>2 digit tanggal 0 sampai 31</td></tr>
<tr><td>HH	</td><td>2 digit jam 0 sampai 23</td></tr>
<tr><td>mm	</td><td>2 digit menit 0 sampai 59</td></tr>
<tr><td>ss	</td><td>2 detik detik 0 sampai 49</td></tr>
<tr><td>sss	</td><td>3 digit milidetik 0 sampai 999</td></tr>
<tr><td>-	</td><td>Pemisah untuk tanggal</td></tr>
<tr><td>:	</td><td>Pemisah untuk waktu</td></tr>
<tr><td>Z	</td><td>Berarti tanggal akan diatur sebagai UTC</td></tr>
	</table>
	
	
<p align="justify">Dari tabel format di atas, ketika misalnya kita akan melakukan parsing baik dari string ke milliseconds ataupun sebaliknya, kita dapat memanfaat format di atas. Untuk Date Object javascript sendiri, nilai epoch dimulai dari 0 untuk tanggal 1 January, 1970, 00:00:00 UTC</br></br>
<b>Contoh Penggunaan Date</b></br>
Berikut ini adalah kode misalkan kita ingin menghitung berapa umur kita dengan memanfaatkan object date.</p>

```plantuml
// parameter birthday dapat berupa miliseconds ataupun date string
const myAge = birthday => {
  const birtday = new Date(birthday);
  const today = Date.now(); // today menghasilkan nilai miliseconds saat ini
  
  const diff_ms = today - birtday.getTime(); // menghitung selisih nilai miliseconds hari ini dan tanggal lahir
  const diffDate = new Date(diff_ms);
  return diffDate.getFullYear() - 1970; // 1970 adalah representasi 0 dari miliseconds
};
myAge('2000-01-22'); // 21 tahun
```

<p align="justify">Selain Date, kita juga dapat menggunakan built-in class javascript yang lainnya.
 </p>

```plantuml
const listOfContent = [1,2,”President”, {}];
console.log(Array.isArray(listOfContent)); 
// result is true
const splitText = "12:20:00".split(':');
// result is [ '12', '20', '00' ]
```

<p align="justify"><b>Rangkuman Materi</b></br>
Kita telah berada di akhir dari modul Object Oriented Programming. Mari kita uraikan materi yang sudah Anda pelajari.</p>
<ol align="justify"><li>OOP merupakan paradigma yang berdasarkan pada konsep objek yang memiliki atribut serta dapat melakukan operasi atau prosedur tertentu.</li>
<li>Terdapat 4 (empat) pilar dalam object oriented programming, antara lain: encapsulation, abstraction, inheritance, dan polymorphism.</li>
<li>Class merupakan blueprint untuk mendefinisikan karakteristik dari sebuah objek.</li>
<li>Object composition memungkinkan penyusunan kumpulan perilaku/method untuk menghindari pewarisan dan hirarki yang kompleks.</li></ol>


<p align="justify"><b>Pertanyaan</b></br>
Di antara pilihan berikut manakah yang tepat untuk menjadi method dari class Vehicle?</p>
<ol type='a'>
<li>Accelerate & numberOfSeats</li>
<li>Color & numberOfTyres</li>
<li>NumberOfTyres & brake</li>
<li>TurnLeft & turnRight</li></ol>
<details>
  <summary>Jawaban Benar</summary>
  d.turnLeft & turnRight</br>
  Berikut adalah penjelasannya:
Kita bisa menentukan jumlah parameter sesuai kebutuhan fungsi yang kita buat.
</details>


<p align="justify"><b>Functional Programming</b></br>
Seperti yang sudah disampaikan di awal, JavaScript adalah bahasa yang mendukung multiparadigm. Artinya, selain merupakan bahasa pemrograman berorientasi objek, penulisan syntax JavaScript juga menggunakan gaya functional programming. Sebelumnya kita telah mempelajari tentang paradigma OOP, kali ini kita akan melanjutkan dengan pendekatan paradigma yang lain, yakni Functional Programming.</br></br>
Kita juga telah membahas mengenai Object Composition. Di mana konsep ini cukup membantu ketika membuat sebuah kelas tanpa harus melakukan proses pewarisan. Ia akan memecah-mecah fungsi yang umum digunakan agar dapat digunakan kembali (reusable) tanpa proses pewarisan.
Nah, Functional Programming adalah pendekatan yang lebih dalam dari konsep tersebut.</br></br>
<b>Pengenalan Functional Programming</b></br>
Paradigma Functional Programming adalah paradigma pemrograman di mana proses komputasi didasarkan pada fungsi matematika murni. Functional Programming (selanjutnya akan kita singkat menjadi FP) ditulis dengan gaya deklaratif yang berfokus pada “what to solve” dibanding “how to solve” yang dianut oleh gaya imperatif.</br></br>
Sebagai gambaran buat Anda yang belum tahu apa itu deklaratif dan imperatif lebih jauh, silakan simak contoh kode berikut.
 </p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];
const newNamesWithExcMark = [];
for(let i = 0; i < names.length; i++) {
  newNamesWithExcMark.push(`${names[i]}!`);
}
console.log(newNamesWithExcMark);
```


|Output : |
| :--     | 
| [ 'Harry!', 'Ron!', 'Jeff!', 'Thomas!' ]|

<p align="justify">Contoh kode di atas merupakan salah satu gaya penulisan kode imperatif. Di mana proses pengisian nilai array baru (newNames) berdasarkan array lama (names) dilakukan secara manual. Inilah maksud dari “how to solve”, di mana kita perlu memikirkan bagaimana cara melakukan perulangannya (for); kapan perulangannya harus berhenti (i < names.length); bagaimana cara memasukkan nilai baru ke dalam array (newNamesWithExcMark.push). Huft, sangat melelahkan!</br></br>
Lantas bagaimana dengan gaya deklaratif? Mari kita lihat kode dengan fungsi yang sama namun dengan gaya deklaratif.
 </p>


```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];

const newNamesWithExcMark = names.map((name) => `${name}!`);

console.log(newNamesWithExcMark);
```

|Output : |
| :--     | 
| [ 'Harry!', 'Ron!', 'Jeff!', 'Thomas!' ] |

<p align="justify">Konsep-Konsep Functional Programming
Setelah Anda memiliki sedikit gambaran tentang bagaimana paradigma FP dapat membuat kode yang Anda tuliskan lebih mudah dibaca dan ringkas, kini saatnya Anda ketahui, apa saja konsep-konsep dasar yang ada di dalam paradigma FP.</br></br>
Di sini kita akan membahas 3 konsep besar yang ada di FP. Yakni Pure Function, Immutability, dan High-Order Function.</br></br>
<b>Pure Function</b></br>
Salah satu konsep besar dari paradigma FP adalah Pure Function. Apa artinya? Pure Function merupakan konsep dari pembuatan fungsi yang mengharuskan fungsi untuk tidak bergantung terhadap nilai yang berada di luar fungsi atau parameternya. Sehingga mau seperti apa keadaanya, fungsi yang dibuat selalu menghasilkan sesuatu yang sama, terkecuali bila fungsi tersebut diberikan nilai parameter yang berbeda.</br></br>
Untuk lebih jelasnya, simak kode berikut:
 </p>

```plantuml
let PI = 3.14;

const hitungLuasLingkaran = (jariJari) => {
  return PI * (jariJari * jariJari); 
}

console.log(hitungLuasLingkaran(4)); // 50.24

PI = 5; // tidak sengaja nilai PI berubah

console.log(hitungLuasLingkaran(4)); // 80
```

|Output : |
| :--     | 
| 50.24 </br>80|


<p align="justify">Menurut Anda, apakah fungsi hitungLuasLingkaran merupakan pure function atau impure function (lawan dari pure function)? Jika Anda menjawab impure function, Anda tepat sekali!</br></br>
Fungsi tersebut tidak bisa dikatakan pure function karena ia membutuhkan nilai yang berada di luar dari fungsinya, yakni nilai PI. Bila nilai PI berubah, maka penggunaan fungsi menghasilkan nilai yang berbeda walaupun diberikan nilai parameter yang sama.</br></br>
Lantas, bagaimana cara membuat fungsi tersebut menjadi pure? Mudah!
 </p>

```plantuml
const hitungLuasLingkaran = (jariJari) => {
  return 3.14 * (jariJari * jariJari); 
}

console.log(hitungLuasLingkaran(4)); // 50.24
console.log(hitungLuasLingkaran(4)); // 50.24
console.log(hitungLuasLingkaran(8)); // 200.96
console.log(hitungLuasLingkaran(8)); // 200.96
```

|Output : |
| :--     | 
| 50.24</br> 50.24</br>200.96</br>200.96 |

<p align="justify">Dengan memindahkan nilai PI secara konstan di dalam fungsi, maka dapat dipastikan nilai tersebut tidak akan berubah atau tak sengaja diubah. Dengan begitu fungsi selalu menghasilkan nilai yang sama bila nilai parameter yang diberikan sama.</br></br>
Selain dilarang untuk bergantung terhadap nilai luar, pure function juga dilarang keras untuk mengubah nilai yang berada di luar baik secara sengaja atau tidak sengaja. Pure function tidak boleh menimbulkan efek samping (no side effect) ketika digunakan.</br></br>
Untuk lebih jelasnya, coba lihat contoh kode berikut:
 </p>


```plantuml
const createPersonWithAge = (age, person) => {
  person.age = age;
  return person;
};

const person = {
  name: 'Bobo'
};

const newPerson = createPersonWithAge(18, person);

console.log({
  person,
  newPerson
});
```

|Output : |
| :--     | 
| {</br>person: { name: 'Bobo', age: 18 },</br>newPerson: { name: 'Bobo', age: 18 }</br>}|

<p align="justify">Fungsi createPersonWithAge bertujuan untuk membuat objek person baru dengan tambahan properti age dari objek person yang ada. Namun alih-alih hanya membuat objek baru, ia juga malah mengubah nilai dari objek lama. Nah, hal inilah yang menyebabkan fungsi createPersonWithAge bukanlah pure function.</br></br>
Lalu bagaimana cara membuat fungsi tersebut menjadi pure? Mudah, kita manfaatkan destructuring object daripada mengubah objek tersebut secara langsung.
 </p>


```plantuml
const createPersonWithAge = (age, person) => {
  return { ...person, age };
};

const person = {
  name: 'Bobo'
};

const newPerson = createPersonWithAge(18, person);

console.log({
  person,
  newPerson
});

```

|Output : |
| :--     | 
| { person: { name: 'Bobo' }, newPerson: { name: 'Bobo', age: 18 } } |


<p align="justify"><b>Immutability</b></br>
Konsep yang kedua adalah immutability. Immutable berarti sebuah objek tidak boleh diubah setelah objek tersebut dibuat. Kontras dengan mutable yang artinya objek boleh diubah setelah objek tersebut dibuat.</br></br>
Konsep immutability sangat kental pada paradigma FP. Anda bisa lihat sebelumnya pada contoh penggunaan array map. Ketika menggunakan array.map(), alih-alih ia mengubah nilai dari array itu sendiri, malah ia membuat atau menghasilkan array baru.
 </p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];

const newNamesWithExcMark = names.map((name) => `${name}!`);

console.log({
    names,
    newNamesWithExcMark,
});
```

|Output : |
| :--     | 
|{</br>names: [ 'Harry', 'Ron', 'Jeff', 'Thomas' ],</br>newNamesWithExcMark: [ 'Harry!', 'Ron!', 'Jeff!', 'Thomas!' ]</br>}|

<p align="justify">Lantas, bagaimana bila kita benar-benar perlu mengubah nilai dari sebuah objek? Contohnya seperti ini:
 </p>


```plantuml
const user = {
    firstname: 'Harry',
    lastName: 'Protter', // ups, typo!
}
const renameLastNameUser = (newLastName, user) => {
    user.lastName = newLastName;
}
renameLastNameUser('Potter', user);
console.log(user);
```

|Output : |
| :--     | 
| { firstname: 'Harry', lastName: 'Potter' } |


<p align="justify">Yap! Tujuan Anda memang tercapai namun itu bukanlah konsep dari paradigma FP. Bila Anda ingin menerapkan FP sepenuhnya, hindari cara seperti di atas. Lantas bagaimana solusinya? Sama seperti fungsi array map(), alih-alih mengubah nilai objek secara langsung, terapkan perubahan tersebut pada nilai return dalam objek baru.
 </p>

```plantuml
const user = {
    firstname: 'Harry',
    lastName: 'Protter', // ups, typo!
}
const createUserWithNewLastName = (newLastName, user) => {
    return { ...user, lastName: newLastName }
}
const newUser = createUserWithNewLastName('Potter', user);
console.log(newUser);
```

|Output : |
| :--     | 
| { firstname: 'Harry', lastName: 'Potter' }|


<p align="justify">Hasilnya sama kan? Selain itu, Anda juga bisa menyesuaikan nama fungsinya dari renameLastNameUser menjadi createUserWithNewLastName. Hal itu perlu untuk mengindikasikan bahwa fungsi mengembalikan atau menghasilkan objek user baru.</br></br>
<b>Higher-Order Function</b></br>
JavaScript memiliki kemampuan First Class Functions, karena itu fungsi pada JavaScript dapat diperlakukan layaknya sebuah data. Kita bisa menyimpan function dalam variabel, memberikan function sebagai parameter pada fungsi lainnya, hingga mengembalikan function di dalam function.
 </p>

```plantuml
const hello = () => {
  console.log('Hello!')
};

const say = (someFunction) => {
  someFunction();
}

const sayHello = () => {
    return () => {
        console.log('Hello!');
    }
}
hello();
say(hello);
sayHello()();
```

|Output : |
| :--     | 
| Hello!</br>Hello!</br>Hello! |

<p align="justify">Karena dengan kemampuan First Class Functions-nya itu, kita dapat membuat Higher-Order Function secara mudah. Tunggu, tunggu. Apa itu Higher-Order Function?
Higher-Order Function menjadi bagian konsep pada paradigma FP. Higher-Order Function merupakan fungsi yang dapat menerima fungsi lainnya pada argumen; mengembalikan sebuah fungsi; atau bahkan keduanya.</br></br>
Teknik Higher-Order Function biasanya digunakan untuk:</p>

<ol align="justify"> <li>Mengabstraksi atau mengisolasi sebuah aksi, event, atau menangani alur asynchronous menggunakan callback, promise, dan lainnya.</li>
<li>Membuat utilities yang dapat digunakan diberbagai tipe data.</li>
<li>Membuat teknik currying atau function composition.</li>
<li>Array map() merupakan salah satu contoh Higher-Order Function yang ada di JavaScript. Karena dalam penggunaanya, ia menerima satu buah argumen yang merupakan sebuah function.</li></ol>

<p align="justify">Dengan mengetahui adanya Higher-Order Function, Anda bisa membuat fungsi map() versi Anda sendiri!
 </p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];
const arrayMap = (array, fn) => {
    const newArray = [];
    
    for(let i = 0; i < array.length; i++) {
        newArray.push(fn(array[i]));
    } 
    return newArray;
}
const newNames = arrayMap(names, (name) => `${name}!` );
console.log({
    names,
    newNames,
});
```

|Output : |
| :--     | 
| {</br>names: [ 'Harry', 'Ron', 'Jeff', 'Thomas' ],</br>newNames: [ 'Harry!', 'Ron!', 'Jeff!', 'Thomas!' ]</br>}|

<p align="justify"><b>Reusable Function</b></br>
Dengan menerapkan konsep-konsep yang ada di dalam paradigma FP, fungsi yang Anda buat akan bersifat reusable. Karena fungsi yang Anda buat merupakan pure function sehingga tidak akan dipengaruhi ataupun mempengaruhi keadaan di/dari luar. Hal ini tentu membuat fungsi dapat digunakan berkali-kali tanpa khawatir mendapatkan hasil di luar dari yang Anda ekspektasikan.</br></br>
Pada materi kali ini kita tidak akan fokus bagaimana membuat banyak reusable function di JavaScript. Kami percaya, dengan memahami konsep functional programming secara matang, Anda dapat membuatnya sendiri sesuai kebutuhan Anda. Alih-alih membuatnya sendiri, kita akan coba membahas dan menggunakan beberapa reusable function yang sudah ada di JavaScript. Khususnya beberapa Higher-Order Function yang dimiliki array, seperti map, filter, dan forEach.</br></br>
<b>Array Map</b></br>
Fungsi array.map() merupakan fungsi bawaan dari array yang sangat berguna dan banyak sekali digunakan. Fungsi ini dapat dipanggil dari sebuah data bertipe array dan menerima satu buah callback function.
 </p>

```plantuml
['Harry', 'Ron', 'Jeff', 'Thomas'].map(() => { });
```

<p align="justify">Callback function tersebut akan dipanggil sebanyak jumlah panjang array dan akan memiliki akses pada index array sesuai dengan iterasinya.
 </p>

```plantuml
['Harry', 'Ron', 'Jeff', 'Thomas'].map((name) => { });
```

<p align="justify">Seperti yang Anda ketahui di awal, fungsi map akan mengembalikan array baru. Nilai tiap item pada array yang dikembalikan, dihasilkan dari kembalian callback function-nya. Karena callback function dapat mengakses item array, biasanya Developer menggunakannya untuk menghasilkan nilai baru.
 </p>

```plantuml
const newArray = ['Harry', 'Ron', 'Jeff', 'Thomas'].map((name) => { return `${name}!`});
console.log(newArray);
```

|Output : |
| :--     | 
| [ 'Harry!', 'Ron!', 'Jeff!', 'Thomas!' ] |

<p align="justify"><b>Array Filter</b></br>
Sama seperti array.map(), fungsi array.filter() merupakan fungsi bawaan dari data yang bertipe array di JavaScript. Sesuai namanya, fungsi ini sangat berguna untuk melakukan proses penyaringan (filtering) terhadap nilai array yang ada. Bila Anda memiliki kasus di mana Anda ingin menghilangkan beberapa item di array berdasarkan spesifikasi tertentu, fungsi ini sangatlah cocok Anda gunakan.</br></br>
Cara kerja fungsi ini mirip seperti array.map(). Namun, callback function dari fungsi ini harus mengembalikan boolean. Di mana nilai boolean ini digunakan untuk menentukan apakah item array lolos saring atau tidak. Sama seperti fungsi map(), fungsi filter() juga akan mengembalikan array yang telah disaring dalam bentuk array baru. Contoh penggunaan ketika Anda ingin menghilangkan seluruh nilai falsy pada array:
 </p>

```plantuml
const truthyArray = [1, '', 'Hallo', 0, null, 'Harry', 14].filter((item) => Boolean(item));
console.log(truthyArray);
```

|Output : |
| :--     | 
|[ 1, 'Hallo', 'Harry', 14 ]|

<p align="justify">Contoh lain, penggunaan filter untuk menyaring array dari objek siswa yang layak mendapatkan beasiswa berdasarkan nilai skor yang didapat.
 </p>

```plantuml
const students = [
  {
    name: 'Harry',
    score: 60,
  },
  {
    name: 'James',
    score: 88,
  },
  {
    name: 'Ron',
    score: 90,
  },
  {
    name: 'Bethy',
    score: 75,
  }
];

const eligibleForScholarshipStudents = students.filter((student) => student.score > 85);

console.log(eligibleForScholarshipStudents);
```

|Output : |
| :--     | 
| [ { name: 'James', score: 88 }, { name: 'Ron', score: 90 } ]|

<p align="justify"><b>Array forEach</b></br>
Array forEach merupakan fungsi bawaan dari array yang berfungsi untuk memanggil fungsi callback pada setiap iterasi index array. Berbeda dari fungsi array lain yang sudah kita bahas, fungsi ini tidak mengembalikan nilai apa pun. Jadi fungsi ini secara harfiah hanya berfungsi untuk memanggil fungsi callback-nya saja, tak lebih dari itu. Melalui fungsi ini, Anda dapat mengubah sintaks perulangan berdasarkan jumlah array secara imperatif menjadi deklaratif.
 </p>

<p align="justify">Cara imperatif</p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];
 
for(let i = 0; i < names.length; i++) {
  console.log(`Hello, ${names[i]}!`);
}
```

|Output : |
| :--     | 
| Hello, Harry!</br>Hello, Ron!</br>Hello, Jeff!</br>Hello, Thomas! |

<p align="justify">Cara deklaratif </p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];
names.forEach((name) => {
  console.log(`Hello, ${name}`);
});
```

|Output : |
| :--     | 
| Hello, Harry!</br>Hello, Ron!</br>Hello, Jeff!</br>Hello, Thomas! |

<p align="justify">Namun, ketahuilah bahwa ketika menggunakan forEach, kita tidak bisa menggunakan operator break atau continue pada proses perulangan (Anda bisa melakukannya pada perulangan for). Hal ini juga berlaku ketika pada fungsi map dan filter.
 </p>

```plantuml
const names = ['Harry', 'Ron', 'Jeff', 'Thomas'];
 
for(let i = 0; i < names.length; i++) {
  if(names[i] === 'Jeff') continue; // Bisa!
  
  console.log(`Hello, ${names[i]}!`);
}
 
names.forEach((name) => {
  if(names[i] === 'Jeff') continue; // Tidak Bisa!
  console.log(`Hello, ${name}`);
});
```


<p align="justify"><b>Kuis Coding: Functional Programming</b>
 </p>

```plantuml
/**
 * TODO:
 * Buatlah variabel greatAuthors yang merupakan array
 * berdasarkan hasil filter() dan map() dari books:
 *   - Gunakan fungsi filter untuk mengembalikan nilai item books
 *     yang hanya memiliki nilai sales lebih dari 1000000.
 *   - Gunakan fungsi map pada books yang sudah ter-filter,
 *     untuk mengembalikan nilai string dengan format:
 *     - `${author} adalah penulis buku ${title} yang sangat hebat!`
 *
 * Catatan: Jangan ubah nilai atau struktur dari books
 */

const books = [
  { title: 'The Da Vinci Code', author: 'Dan Brown', sales: 5094805 },
  { title: 'The Ghost', author: 'Robert Harris', sales: 807311 },
  { title: 'White Teeth', author: 'Zadie Smith', sales: 815586 },
  { title: 'Fifty Shades of Grey', author: 'E. L. James', sales: 3758936 },
  { title: 'Jamie\'s Italy', author: 'Jamie Oliver', sales: 906968 },
  { title: 'I Can Make You Thin', author: 'Paul McKenna', sales: 905086 },
  { title: 'Harry Potter and the Deathly Hallows', author: 'J.K Rowling', sales: 4475152 },
];
// TODO
let greatAuthors=books.filter((books) => books.sales>1000000).map((item)=>{
  let author = item.author;
  let title = item.title;
  return `${author} adalah penulis buku ${title} yang sangat hebat!`
})
/**
 * Hiraukan kode di bawah ini
 */
module.exports = { books, greatAuthors };
```



<p align="justify"><b>Pertanyaan</b></br>
Berikut ini yang bukan merupakan karakteristik dari functional programming, adalah...
 </p>
 <ol type='a'><li>Pure Function</li>
<li>Immutability</li>
<li>Higher-order</li>
<li>Polymorphism</li></ol>
<details>
  <summary>Jawaban Benar</summary>
  d.Polymorphism</br></br>
  Berikut adalah penjelasannya:
Polymorphism merupakan karakteristik dari OOP dan bukan karakterisitik FP.
</details>


<p align="justify"><b>Text Editor</b></br>
Dalam mengembangkan aplikasi, kita akan banyak menuliskan kode. Maka dari itu, tools yang wajib kita miliki adalah sebuah <b>text editor</b>. Beberapa sistem operasi sebenarnya sudah menyediakan text editor bawaan. Contohnya Windows memiliki Notepad, Linux memiliki Text Editors, dan Mac OS memiliki TextEdit. Ketiga aplikasi tersebut bisa kita gunakan untuk belajar membuat aplikasi dengan JavaScript, meskipun masih banyak alternatif text editor lainnya selama masih dapat menyimpan sebuah plain text dengan format .js.</br></br></br>
Perlu diperhatikan bahwa kode yang kita tulis merupakan sebuah plain text. Pastikan Anda menggunakan text editor yang tepat. Jangan pernah gunakan Microsoft Word untuk menuliskan sebuah kode. Ini penting karena aplikasi tersebut menampilkan teks yang telah diformat atau biasa disebut dengan rich text.
Selain text editor bawaan dari sistem operasi, ada beberapa teks editor lain yang memang dirancang khusus untuk menulis kode pemrograman. Teks editor ini umumnya dilengkapi dengan banyak fitur berguna yang mendukung kita dalam mengembangkan aplikasi.</br></br>
Tutorial dan contoh di kelas ini selanjutnya akan menggunakan teks editor Visual Studio Code. Visual Studio Code merupakan text editor yang dikembangkan oleh Microsoft. Dalam Visual Studio Code terdapat fitur debugging, Git control, syntax highlighting, code completion, snippets, dan code refactoring. Visual Studio Code tersedia untuk sistem operasi Windows, Mac, maupun Linux. Selain itu, text editor ini bisa kita gunakan secara gratis. Untuk mengunduhnya, silakan kunjungi website berikut: https://code.visualstudio.com/.</br></br>
<b>Terminal</b></br>
Pada materi selanjutnya kita akan sering menuliskan command line untuk menjalankan program menggunakan Node.js. Tentunya command line dituliskan dalam sebuah terminal. Sebenarnya Anda tidak perlu menyiapkan atau mengunduh aplikasi apa pun untuk ini, karena sistem operasi baik Windows, MacOS, dan Linux sudah menyediakan Terminal usungannya masing-masing. Untuk menuliskan command line pada Linux dan MacOS, gunakan aplikasi yang bernama “Terminal.” Pada Windows kita bisa menuliskannya melalui “CMD” atau “PowerShell”.</br></br>
<b>JavaScript Runtime</b></br>
Sesuai yang telah dijelaskan pada modul-modul awal, JavaScript mulanya hanya digunakan pada lingkungan web browser. Saat ini pun browser masih merupakan lingkungan eksekusi yang paling umum untuk kode JavaScript [4]. Lingkungan web browser memungkinkan kode JavaScript untuk menerima inputan dari mouse dan keyboard pengguna. Selain itu, JavaScript juga dapat menampilkan output kepada pengguna melalui HTML dan CSS.</br></br>
Salah satu cara termudah untuk menjalankan kode JavaScript di lingkungan browser adalah menggunakan browser itu sendiri. Kita dapat menggunakan developer tools yang disediakan oleh browser. Developer tools bisa kita akses melalui shortcut ctrl + shift + i atau klik kanan -> Inspect Element. Setelah itu pilih tab console. Developer tools ini dilengkapi dengan interpreter yang akan menjalankan kode yang kita tulis.</p>

<p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/2021033023344410b356d490abee14fbef6be09af43201.jpeg"></p>
  
<p align="justify">Selain browser, terdapat runtime lain yang bisa menjalankan JavaScript, yaitu Node.js. Node.js memungkinkan JavaScript dapat berjalan di berbagai platform, tidak hanya browser. Itulah kenapa JavaScript yang awalnya terkenal sebagai bahasa untuk front-end web, kini mulai merambah juga ke ranah back-end dari website.</br></br>
Node memberikan akses JavaScript ke seluruh sistem operasi, memungkinkan program JavaScript dapat membaca dan menulis file; mengirim dan menerima data melalui jaringan; serta membuat dan melayani permintaan HTTP. Selanjutnya kita akan fokus untuk pengembangan program JavaScript pada lingkungan Node. Tentunya kita perlu menginstal Node.js terlebih dulu. Penasaran bagaimana caranya? Kita akan bahas pada materi selanjutnya.</br></br>
<b>Node.js</b></br>
Node.js adalah runtime environment untuk JavaScript yang bersifat open-source dan cross-platform. Dengan Node.js kita dapat menjalankan kode JavaScript di mana pun, tidak hanya terbatas pada lingkungan browser. Node.js menjalankan V8 JavaScript engine (yang juga merupakan inti dari Google Chrome) di luar browser. Ini memungkinkan Node.js memiliki performa yang tinggi. Node.js juga menyediakan banyak library/module JavaScript yang membantu menyederhanakan pengembangan aplikasi web. Berikut ini adalah beberapa fitur penting dari Node.js yang menjadikannya pilihan utama dalam pengembangan aplikasi:</p>
<ol align="justify"><li>
Asynchronous & Event-driven</br>
Semua API dari Node.js bersifat asynchronous, artinya tidak memblokir proses lain sembari menunggu satu proses selesai. Server Node.js akan melanjutkan ke ke pemanggilan API berikutnya lalu memanfaatkan mekanisme event notification untuk mendapatkan respon dari panggilan API sebelumnya.</li>
<li>Very Fast</br>
Eksekusi kode dengan Node.js sangat cepat karena berjalan pada V8 JavaScript Engine dari Google Chrome.</li>
<li>Single Threaded but Highly Scalable</br>
Node.js menggunakan model single thread dengan event looping. Mekanisme ini membantu server untuk merespon secara asynchronous dan menjadikan server lebih scalable dibandingkan server tradisional yang menggunakan banyak thread untuk menangani permintaan.
Node.js dirancang untuk aplikasi dengan proses I/O yang intensif seperti network server atau backend API. Pemrograman dengan multithreading relatif lebih berat dan sulit untuk dilakukan. Jika kita ingin membuat web server yang bisa menangani ratusan request bersamaan, menggunakan ratusan thread akan membutuhkan memori yang besar. Oleh karena itu, karakteristik Node yang asynchronous dan single thread dirancang untuk memungkinkan implementasi server yang dapat menangani banyak request pada waktu yang sama.</li></ol>

<p align="justify">Bagaimana jika langsung mencoba Node.js pada perangkat kita? Kita akan mulai dengan langkah instalasi Node.js pada materi berikutnya.</br></br>
<b>Instalasi Node</b></br>
Untuk bisa menjalankan Node pada perangkat lokal, kita perlu menginstal Node.js. Node.js memiliki dua versi rilis, yaitu LTS dan current. LTS merupakan kepanjangan dari Long Term Support. Artinya, versi tersebut mendapat dukungan dalam jangka waktu yang lama, sehingga lebih disarankan menggunakan versi ini. Sementara, versi current berisi fitur-fitur baru yang dirilis untuk Node.js.</br></br>
<b>Windows</b></br>
Jika Anda menggunakan sistem operasi Windows, kunjungi situs https://nodejs.org/ lalu unduh Node.js versi LTS.</p>
<p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103302338003b4c7e291c774db3340e0f090cefb3ef.jpeg"></p>

<p align="justify">Setelah berhasil mengunduh, buka berkas yang baru saja diunduh dan ikuti instruksi yang diberikan.	</p>
<p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330233822ac64eba0c4d13fa6c8ceca466699677a.jpeg"></p>
<p align="justify">Jika Anda ingin mengubah lokasi instalasi, Anda bisa menentukan lokasi yang Anda inginkan.</p>
<p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330233840403fa2cd98ab0fa47872670e460b8c85.jpeg"></p>

<p align="justify">Pada bagian selanjutnya, kita juga dapat melihat komponen apa saja yang akan diterapkan (bundling) dalam pemasangan node.js ini.</p>
<p align="center">
  <img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330233904ba06737816dc936710f9aed14471fda9.jpeg"></p>
  
  <p align="justify">Lalu ikuti instruksi selanjutnya dan tunggu proses instalasi hingga selesai. Jika instalasi selesai dan berhasil, maka pesan seperti ini akan tampil.</p>
 <p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330233925675ea80c3be4c19da83b4d0b322fc9dc.jpeg"></p>
  
  <p align="justify"><b>  Membuat Project JavaScript</b></br>
Setelah berhasil menginstal text editor dan juga Node.js di komputer, artinya peralatan “perang” kita sudah siap.</br></br>
Sebenarnya kita bisa membuat berkas atau project JavaScript secara manual dengan membuat folder dan meletakkan berkas berekstensi .js di dalamnya. Namun, untuk memudahkan pengembangan ke depannya, kita akan membuat proyek menggunakan Node Package Manager (NPM). NPM digunakan untuk mengelola package tambahan untuk mempermudah kita mengembangkan aplikasi. Akan ada modul tersendiri yang membahas lebih rinci terkait NPM. Untuk saat ini, kita baru akan menggunakan NPM untuk membuat proyek Node.js.</br></br>
Pada direktori komputer Anda, buatlah folder baru sebagai folder utama dari proyek yang akan kita buat. Di sini kita beri nama folder tersebut dengan “CoffeeMachine”. Kemudian buka folder tersebut menggunakan Visual Studio Code. Anda dapat melakukannya dengan memilih menu File → Open Folder … → Lalu pilih folder project Anda.</p
<p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330234708bff755c85f94965d94892d3ce27d1f33.jpeg"></p>
<p align="justify">
Lalu buka terminal/command prompt pada project tersebut dengan memilih menu Terminal → New Terminal. Ketika terminal muncul jalankan perintah:</p>

```plantuml 
npm init
```

<p align="justify">Selanjutnya Anda akan diberikan beberapa pertanyaan untuk mengisi nilai package name, version, description, dsb. Semua itu merupakan informasi dasar tentang aplikasi yang kita buat.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330234821e2129a309167e41fcd68ab054946ac1b.jpeg"></p>
  <p align="justify">Nilai yang berada di dalam tanda kurung merupakan nilai default. Jika nilai default tersebut sudah cocok dengan yang diharapkan, kita dapat menggunakan nilainya dengan langsung menekan tombol enter. Setelah mengisi seluruh pertanyaan yang diberikan, kita akan diminta untuk melihat dan memverifikasi informasi yang akan disimpan.</p>
 <p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330234842357b0b736b54f1cbeb48212f7fa04a5d.jpeg"></p>
<p align="justify">
Jika nilai yang ditampilkan sudah sesuai, tekan tombol enter. Nilai tersebut akan tersimpan dalam berkas package.json. Jika, berkas package.json dibuka, hasilnya terlihat seperti gambar di bawah ini.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103302349129b91e31846b3f8cd3ee7acae9d876211.jpeg"></p>
<p align="justify">
Berkas tersebut digunakan untuk menyimpan informasi aplikasi yang kita buat. Untuk membuat berkas package.json, sebenarnya kita dapat membuatnya sendiri layaknya membuat berkas baru pada umumnya. Namun, cara tersebut bukan pendekatan yang baik. Dalam membuat berkas package.json, sebaiknya gunakan perintah npm init pada Terminal di dalam project yang kita buat.</p>
 <p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330235057d6419a63ca8267c4de1a7669d1bbbcc7.gif"></p>
<p align="justify">Pada berkas inilah kita bisa mulai menuliskan kode JavaScript. Sebagai permulaan, cetak sejumlah proses pembuatan kopi dari mesin kopi kita. Tambahkan kode berikut ke dalam file index.js:	</p>

```plantuml 
console.log("Menyalakan mesin kopi");
console.log("Menggiling biji kopi");
console.log("Memanaskan air");
console.log("Mencampurkan air dan kopi");
console.log("Menuangkan kopi ke dalam gelas");
console.log("Menuangkan susu ke dalam gelas");
console.log("Kopi Anda sudah siap!");
```

<p align="justify">Untuk menjalankan file JavaScript di atas juga cukup mudah, cukup jalankan perintah berikut pada terminal:</p>
	
```plantuml 
node index.js
```

<p align="justify">Node.js akan mengeksekusi setiap baris kode yang kita tulis lalu menampilkannya ke konsol terminal.</p>
 <p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103302351436547577bcbfdd87d8bf4127417997c83.gif"></p>
<p align="justify"><b>Run Scripts</b></br>
Pada berkas package.json terdapat beberapa object yang penting untuk kita perhatikan, salah satunya adalah object scripts. Secara default object tersebut akan terbentuk ketika package.json dibuat menggunakan perintah init. Nilai default dari scripts adalah seperti ini:</p>

```plantuml 
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

<p align="justify">Object scripts merupakan objek yang mengandung kumpulan script di dalamnya. Script tersebut dapat dijalankan kapan saja pada proyek kita. Untuk menjalankan script, gunakan perintah npm run <script-name> yang dapat Anda tulis seperti di bawah ini:</p>
	
```plantuml 
npm run test
```

<p align="justify">Dengan menjalankan script test, artinya kita mengeksekusi kode yang berada di dalam nilai test, yaitu:</p>

```plantuml 
"echo \"Error: no test specified\" && exit 1"
```

<p align="justify">Sehingga, pada terminal akan menghasilkan output seperti berikut:</p>
<p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/202103302353102bac9853ccb0912d2c3a5a3f5c432d81.jpeg"></p>
<p align="justify">Pada object scripts biasanya kita menetapkan script yang sering digunakan secara berkala, seperti menjalankan aplikasi (selama proses development), compiling source code ke tahap produksi, atau melakukan testing.</br></br>
Untuk menetapkan nilai baru pada object scripts, kita tuliskan nama script sebagai properti. Kemudian tuliskan perintah yang akan dieksekusi sebagai nilai dari properti tersebut. Mari kita buat script baru untuk menjalankan kode dari berkas index.js.</br></br>
Pada object scripts, tuliskan nilai baru dengan properti bernama start, kemudian tambahkan perintah untuk mengeksekusi berkas sebagai nilainya:</p>

```plantuml 
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js"
  },
```

<p align="justify">Kini kita bisa menjalankan program dengan perintah npm run start seperti di bawah ini</p>
<p align="center"><img src="https://github.com/yenysyafitry/Dicoding-Belajar-Dasar-Pemrograman-JavaScript/blob/main/20210330235401d8067fab72ef881f9f39997d80af2808.jpeg"></p>

```plantuml
  Kategori: Set Environment

1.Bagaimana cara memeriksa versi NPM yang terinstal saat ini?
  A. npm --version
  B. npm help
  C. npm --ver
  D.semua salah
```

|Output : |
| :--     | 
|A. npm --version |

```plantuml
2.Bagaimanakah karakteristik API pada Node.js?
  A. Asynchronous
  B. Synchronous
  C. Semua Benar
  D. Semua Salah
```

|Output : |
| :--     | 
|A. Asynchronous|


<p align="justify"><b>Export & Import</b></br>
Modul bekerja dengan cara exporting dan importing nilai. Baik itu nilai variabel, fungsi, array, object, atau class agar bisa digunakan pada berkas JavaScript lain. Satu berkas JavaScript terdiri dari satu module yang dapat kita export menjadi lebih dari satu nilai.</br></br>
Dalam environment Node.js, gunakan perintah module.exports untuk melakukan proses export module. Setiap berkas JavaScript yang berjalan pada Node, memiliki objek module lokal yang memiliki properti exports. Properti tersebut digunakan untuk mendefinisikan nilai apa yang akan diekspor dari berkas tersebut.</br></br>
Buatlah berkas baru bernama state.js pada project Anda. Kode di bawah ini merupakan contoh bagaimana melakukan export nilai menggunakan module.exports.</p>

```plantuml
const coffeeStock = {
  arabica: 100,
  robusta: 150,
  liberica: 200
}
module.exports = coffeeStock;
```

<p align="justify">Kode module.exports = coffeeStock membuat object coffeeStock ditetapkan sebagai nilai dari module.exports. Nilai properti exports ini nantinya bisa di-import dan digunakan pada berkas JavaScript lain. Jika Anda mencoba melihat nilai module yang ada pada berkas state.js dengan menambahkan kode console.log(module) di akhir berkas, maka kita akan melihat object coffeeStock menjadi nilai dari properti exports.</p>

```plantuml
Module {
  id: '.',
  path: '/home/dicoding/Playground/javascript/CoffeeMachine',
  exports: { arabica: 100, robusta: 150, liberica: 200 },
  parent: null,
  filename: '/home/dicoding/Playground/javascript/CoffeeMachine/state.js',
  loaded: false,
  children: [],
  paths: [
    '/home/dicoding/Playground/javascript/CoffeeMachine/node_modules',
    '/home/dicoding/Playground/javascript/node_modules',
    '/home/dicoding/Playground/node_modules',
    '/home/dicoding/node_modules',
    '/home/node_modules',
    '/node_modules'
  ]
}
```

<p align="justify">Lalu bagaimana caranya untuk melakukan import atau menggunakan object yang sudah di-export? Caranya adalah menggunakan method require().</br></br>index.js
</p>

```plantuml
const coffeeStock = require('./state');
console.log(coffeeStock);
```

|Output : |
| :--     | 
|{ arabica: 100, robusta: 150, liberica: 200 }|

<p align="justify">state.js</p>

```plantuml
const coffeeStock = {
    arabica: 100,
    robusta: 150,
    liberica: 200
};
 
module.exports = coffeeStock;
```

|Output : |
| :--     | 
|{ arabica: 100, robusta: 150, liberica: 200 }|


<p align="justify">Dalam inisialisasi variabel coffeeStock (nama variabel bebas kita tentukan), kita gunakan method require() dengan memberikan parameter lokasi berkas state.js. Dengan begitu variabel coffeeStock akan memiliki nilai module.exports yang sama pada berkas state.js. Setelah mendapatkan nilainya, kita bebas menggunakannya seperti variabel lokal pada umumnya.</p>

```plantuml
const coffeeStock = require('./state');
const makeCoffee = (type, miligrams) => {
    if (coffeeStock[type] >= miligrams) {
        console.log("Kopi berhasil dibuat!");
    } else {
        console.log("Biji kopi habis!");
    }
}
makeCoffee("robusta", 80);
```

|Output : |
| :--     | 
|Kopi berhasil dibuat!|

<p align="justify">Lalu untuk mendapatkan nilai yang diekspor melalui named export, kita gunakan destructuring object.</p>

```plantuml
import { coffeeStock, isCoffeeMachineReady } from './state.js';
console.log(coffeeStock);
console.log(isCoffeeMachineReady);
```

|Output : |
| :--     | 
|{ arabica: 100, robusta: 150, liberica: 200 } </br>true|

<p align="justify"><b>Kuis Coding : Module</b></p>

```plantuml
import { coffeeStock, isCoffeeMachineReady } from './state.js';
console.log(coffeeStock);
console.log(isCoffeeMachineReady);
```

|Output : |
| :--     | 
|{ arabica: 100, robusta: 150, liberica: 200 } </br>true|

<p align="justify"><b>Kuis Coding : Module</b></p>
<p align="justify"><b>1. main.js</b></p>

```plantuml
/**
 * TODO 1 (Tiger.js):
 * Ekspor nilai dari class Tiger
 *
 * TODO 2 (Wolf.js)
 * Ekspor nilai dari class Wolf
 *
 * TODO 3 (main.js)
 * Impor class Tiger dan Wolf
 *
 * TODO 4 (main.js)
 * Ekspor fungsi fight, myTiger, myWolf, dan result
 *
 */

// TODO 3
const Tiger = require("./Tiger.js");
const Wolf = require("./Wolf.js");
const fight = (tiger, wolf) => {
  if (tiger.strength > wolf.strength) {
    return tiger.growl();
  }
  if (wolf.strength > tiger.strength) {
    return wolf.howl();
  }
  return 'Harimau dan serigala sama-sama kuat!';
};
const myTiger = new Tiger();
const myWolf = new Wolf();
const result = fight(myTiger, myWolf);
// TODO 4
module.exports= {fight,myTiger,myWolf,result};
console.log(module.exports);
```

<p align="justify"><b>2. Tiger.js</b></p>

```plantuml
class Tiger {
  constructor() {
    this.strength = Math.floor(Math.random() * 100);
  }
  growl() {
    return 'grrrrrrr';
  }
}
// TODO: 1
module.exports = Tiger;
```

<p align="justify"><b>3. Wolf.js</b></p>

```plantuml
class Wolf {
  constructor() {
    this.strength = Math.floor(Math.random() * 100);
  }
  howl() {
    return 'Auuuuuuuuu';
  }
}
// TODO 2
module.exports = Wolf;
```


|Output main.js, Tiger.js, Wolf.js: |
| :--     | 
|{</br>fight: [Function: fight],</br>myTiger: Tiger { strength: 7 },</br>myWolf: Wolf { strength: 79 },</br>result: 'Auuuuuuuuu'</br>}|


<p align="justify"><b>Try and Catch</b></br>
Untuk menangani eror pada JavaScript, gunakan try dan catch. Penulisan kode try-catch untuk menangani eror adalah seperti ini:</p>

```plantuml
try {
    // kode
} catch (error) {
    // error handling
}
```

<p align="justify">Taruh kode yang berpeluang menimbulkan eror di dalam blok try. Apabila terjadi eror di dalam blok kode try, maka ia akan ditangkap dan ditangani oleh blok kode catch. Sementara, jika tidak terjadi eror pada kode, maka blok catch akan diabaikan.</p>

```plantuml
try {
    console.log("Awal blok try");
    console.log("Akhir blok try");
} catch (error) {
    console.log("Tidak terjadi eror, maka kode ini diabaikan");
}
```

|Output : |
| :--     | 
|Awal blok try</br>Akhir blok try|

<p align="justify">Kode di dalam blok try di atas tidak akan menghasilkan eror, sehingga kode di dalam blok catch akan diabaikan dan tidak dijalankan. Berikut ini adalah contoh kode yang menghasilkan eror:</p>

```plantuml
try {
    console.log("Awal blok try");   // (1)
    errorCode;                      // (2)
    console.log("Akhir blok try");  // (3)
} catch (error) {
    console.log("Terjadi error!");  // (4)
}
```

|Output : |
| :--     | 
|Awal blok try</br>Terjadi error!|

<p align="justify">Baris kode (2) akan menghasilkan eror. Eksekusi kode di dalam blok try akan dihentikan, sehingga baris kode (3) tidak akan tereksekusi. Kemudian kode akan dilanjutkan ke baris (4) atau blok catch. Selamat! Anda telah berhasil menangani eror dan menghindarkan aplikasi dari crash (Cobalah untuk menghapus sintaks try-catch dan melihat bagaimana aplikasi akan crash). Namun, bagaimana kita bisa tahu apa yang menyebabkan suatu program mengalami eror? Jika ada informasi yang jelas tentunya akan sangat membantu kita atau pengguna nantinya bukan?</br>
Sekarang perhatikan blok catch. Di sana catch memiliki satu parameter bernama error (nama variabel bisa diubah). Variabel error tersebut merupakan sebuah object yang menyimpan detail informasi dari error yang terjadi.Object error memiliki beberapa properti utama di dalamnya, yaitu:</p>
<ol align="justify"><li>name : Nama error yang terjadi.</li>
<li>message : Pesan tentang detail error.</li>
<li>stack : Informasi urutan kejadian yang menyebabkan error. Umumnya digunakan untuk debugging karena terdapat informasi baris mana yang menyebabkan error.</li></ol>
<p align="justify">Sekarang mari kita coba untuk mengubah kode dan menampilkan properti error di atas.</p>

```plantuml
try {
    console.log("Awal blok try");   // (1)
    errorCode;                      // (2)
    console.log("Akhir blok try");  // (3)
} catch (error) {
    console.log(error.name);
    console.log(error.message);
    console.log(error.stack);
}
```

|Output : |
| :--     | 
|Awal blok try</br>ReferenceError</br>errorCode is not defined</br>ReferenceError: errorCode is not defined</br> at file:///home/dicoding/Playground/javascript/CoffeeMachine/error.js:3:5</br> at ModuleJob.run (internal/modules/esm/module_job.js:152:23)</br>at async Loader.import (internal/modules/esm/loader.js:166:24)</br>at async Object.loadESM (internal/process/esm_loader.js:68:5)|


<p align="justify">Dari informasi di atas, kita bisa tahu bahwa error yang muncul adalah ReferenceError karena errorCode dianggap sebagai sebuah variabel atau nilai yang tidak terdefinisi.</br></br>
<b>try-catch-finally</b></br>
Selain try dan catch, ada satu blok lagi yang ada dalam mekanisme error handling pada JavaScript, yaitu finally. Blok finally akan tetap dijalankan tanpa peduli apa pun hasil yang terjadi pada blok try-catch.</p>


```plantuml
try {
    console.log("Awal blok try");
    console.log("Akhir blok try");
} catch (error) {
    console.log("Baris ini diabaikan");
} finally {
    console.log("Akan tetap dieksekusi");
}
```

|Output : |
| :--     | 
|Awal blok try</br>Akhir blok try</br>Akan tetap dieksekusi|

--->
