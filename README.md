# EH V1

Tujuan dari latihan daily arsip React JS ini adalah untuk ISENG. YA ISENG. BECAUSE I WANT :)

## TODO LIST

- [ ] [Refresh Javascript Knowlegde](#REACT)
- [ ] Pemahaman Fitur Basic
- [ ] Komponen React
- [ ] Simple Project
- [ ] Advance Komponen React
- [ ] Advance Project
- [ ] HTTP/AJAX
- [ ] Lengkapi Documentation


## REACT
Soem note that i want to wrtie. React is a JavaScript library for building user interfaces.

### Let & Const

let = Variable values.
const = Constat values.

```js
let namaku = 'Adli';
const phi = 3.14;
```

### Function 
Fungsi Biasa

```js
function namaku(nama){
    console.log(nama);
}
namaku('Adli');
```

Fungsi Arrow

```js
const namalu = (nama) => {
    console.log(nama);
}
namalu('WHatever');
```

Short version 

```js
const namalu = nama => nama;
console.log(namalu('Adli'));
```

### Exports and Imports
In React you split your code across multiple JavaScript files - so-called modules. You do this, to keep each file/module focused and manageable.

Ada 2 tipe dari export , yaitu default  dan named exports : 

- default

```js
import namaApa from './path/ke/file.js';
```
- named

```js
import {data} from './path/ke/file.js';
```


### Class

Class merupakan fitur yang menggantikan fungsi constructor dan prototype. Contoh Class 
```js
class Manusia {
  constructor(){
    this.jk = 'laki-laki';
  }
  printJK(){
    console.log(this.jk);
  }
}
```

Contoh Inheritance menggunakan class 

```js
class Manusia {
  constructor(){
    this.jk = 'laki-laki';
  }
  printJK(){
    console.log(this.jk);
  }
}

class Orang extends Manusia {
  constructor(){
    super();
    this.nama = 'Adli';
    this.jk = 'perempuan';
  }
  printNama(){
    console.log(this.nama);
  }
}

const orang = new Orang();
orang.printNama();
orang.printJK();

```

### Class , Properties dan Methods
Class juga dapat digunakan seperti ini 

```js
class Manusia {
  jk = 'laki-laki';

  printJK = () => {
    console.log(this.jk);
  }
}

class Orang extends Manusia {
    nama = 'Adli';
    jk = 'perempuan';

  printNama = () => {
    console.log(this.nama);
  }
}

const orang = new Orang();
orang.printNama();
orang.printJK();

```

### Spread & Rest Operator
Spread digunakan untuk split Array atau property dalam sebuah objek.
```js

//Array
const nomor = [1,2,3];
const nomor1 = [...nomor, 4];

console.log(nomor1); // Output [1,2,3,4]

//Object
const orang = {
  nama: 'Adli'
};

const newOrang = {
  ...orang,
  umur:28
}

console.log(newOrang); // Output nama:"Adli" , umur:28
```
Rest digunakan untuk Merge list dari argumen sebuah fungsi menjadi array.
```js
const y = (...args) => {
  return args.filter(el => el === 1);
}

console.log(y(1,2,3)); // Output 1

```
### Destructuring
Digunakan untuk extract elemen dari sebuah array atau object dan menyimpannya kedalam sebuah variabel.

Array Destructuring

```js
const nomor = [1,2,3];
[no1,no2] = nomor;
console.log(no1,no2); //Output 1 2 
```

Object Destructuring

```js
{nama} = {nama:'Adli',umur:23}
console.log(nama); // Output Adli
console.log(umur); // Output 23
```

### Catatan Fungsi Array (Little Important) //Havent Read Yet <- Remove This when u read it alreayd>

- map() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map

- find() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find

- findIndex() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex

- filter() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter

- reduce() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce?v=b

- concat() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat?v=b

- slice() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice

- splice() https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice





## About me

SynthPX

[<img alt="SyntpX" src="https://avatars1.githubusercontent.com/u/25601493?s=460&u=c2b4e683d917003c1af50087cd5b5ce10953077a&v=4" width="117">](https://github.com/SynthpX)


<!-- Note: The table above get generated with the following commands -->
<!-- npm install -g github-contributors-list -->
<!-- githubcontrib --owner NativeScript --repo docs --cols 6 --sortOrder desc | pbcopy -->

