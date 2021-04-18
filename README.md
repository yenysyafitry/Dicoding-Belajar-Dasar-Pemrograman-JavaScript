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
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

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
<details>
<summary markdown="span">Output :</summary>
Skywalker
</details>

### Data Type
<p align="justify"> Nilai yang kita tetapkan pada variabel pasti memiliki tipe data. Tipe data merupakan pengklasifikasian data berdasarkan jenisnya. Pada JavaScript terdapat beberapa tipe data sebagai berikut: </p>
<ul align="justify"><li><b> Undefined </b></br>
Tipe data ini terbentuk ketika sebuah variabel tidak memiliki nilai. Artinya, ketika kita mendeklarasikan variabel tanpa menginisialisasikan nilainya, variabel tersebut menjadi undefined.</li></ul>

```plantuml
   let x;
   console.log(typeof(x));
```
</br>
<details>
<summary markdown="span">Output :</summary>
undefined </br></br>
Pada contoh kode di atas, kita mendeklarasikan variabel x, tetapi kita tidak menginisialisasikan dengan nilai apa pun. Ketika kita memastikan tipe data dengan menggunakan fungsi typeof(), ia akan menghasilkan output undefined. <b>Fungsi typeof()</b> digunakan untuk memastikan tipe data pada variabel dengan mengembalikan tipe data tersebut dalam bentuk teks.
</details>

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

<details>
<summary markdown="span">Output :</summary>
21</br>
3</br>
108</br>
1.3333333333333333</br>
3
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```


<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
```plantuml

```
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```


<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
```plantuml

```
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```


<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
```plantuml

```
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```


<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
```plantuml

```
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>


```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>

```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```

<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```


<details>
<summary markdown="span">Output :</summary>
Hello, World!
</details>
```plantuml

```
```plantuml

```

