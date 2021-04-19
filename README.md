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

```ruby 
JavaScript adalah bahasa pemrograman tingkat tinggi yang pada awalnya dikembangkan untuk membuat website menjadi lebih “hidup”. Bersama dengan HTML dan CSS, 

JavaScript menjadi bahasa pemrograman paling populer untuk mengembangkan aplikasi berbasis web. Bahasa ini mampu memberikan logic ke dalam website, sehingga website tersebut memiliki fungsionalitas tambahan dan lebih interaktif.

Awalnya JavaScript dibuat supaya dapat berjalan di lingkungan browser dan membuat website menjadi lebih interaktif. Namun, saat ini Anda sebagai developer dapat menggunakan bahasa pemrograman JavaScript di berbagai lingkungan pengembangan. Sehingga, tidak hanya sebatas browser/client, namun JavaScript juga bisa berjalan di server menggunakan Node.js.

JavaScript termasuk ke dalam kategori scripting language. Apa maksudnya? Salah satu ciri-ciri utama dari bahasa scripting adalah kode tidak perlu dikompilasi agar bisa dijalankan. Scripting language menggunakan interpreter untuk menerjemahkan kode atau perintah yang kita tulis supaya dimengerti oleh mesin.
```

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
||||	Operator atau (or). Logika akan menghasilkan nilai true apabila ada salah satu kondisi terpenuhi (bernilai true).|
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
<ul><li>
<li>Pertama, variabel i sebagai index iterasi. Pada variabel ini kita menginisialisasi nilai awal dari perulangan.</li>
<li>Kedua, operasi perbandingan. Pada bagian ini, JavaScript akan melakukan pengecekan kondisi apakah perulangan masih perlu dilakukan. Jika bernilai true, maka kode di dalam blok for akan dijalankan.</li>
<li>Ketiga, increment/decrement. Di sini kita melakukan penambahan atau pengurangan variabel iterasi. Jadi, pada contoh di atas variabel i akan ditambah dengan 1 di setiap akhir perulangan. Perubahan nilai ini penting karena jika kita mengubah nilainya, proses perulangan dapat berjalan selamanya karena kondisi akan terus terpenuhi.</br></li>
JIka diartikan, maka kode di atas bisa dimaknai dengan “Jika i kurang dari 5, maka tampilkan nilai i.”
 </p>
 
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

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |



```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |

<p align="justify">
 </p>


```plantuml

```
|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```

|Output : |
| :--     | 
| </br> |


<p align="justify">
 </p>

```plantuml

```
|Output : |
| :--     | 
| </br> |

