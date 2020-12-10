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

### SLet & Const

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
### Spread & Rest Operator
### Destructuring
### Referefce
### Fungsi Array




## About me


[<img alt="SyntpX" src="https://avatars1.githubusercontent.com/u/25601493?s=460&u=c2b4e683d917003c1af50087cd5b5ce10953077a&v=4" width="117">](https://github.com/SynthpX)


<!-- Note: The table above get generated with the following commands -->
<!-- npm install -g github-contributors-list -->
<!-- githubcontrib --owner NativeScript --repo docs --cols 6 --sortOrder desc | pbcopy -->

