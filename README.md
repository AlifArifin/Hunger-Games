# Hunger Games
By : ayo kita semangat

Role-playing game with plot like Hunger Games.

## Cara Penggunaan
pada awal permainan hanya dapat menggunakan start\0 atau loadGame\1

### fungsi 'start\0'

digunakan untuk memulai permainan

```
> start.
```

### fungsi 'loadGame\1'

digunakan untuk men-load data yang telah di-save

loadGame(NamaFile). NamaFile harus diberi petik

```
'save.txt'
```

```
> loadGame('save.txt').
```

### fungsi 'save\1'

digunakan untuk menyimpan data game saat ini.

save(NamaFile), Sama seperti loadGame. Nama dari namafile harus pakai ' (petik)

```
> save('save.txt').
```

--> dengan NamaFile merupakan nama file yang menyimpan data yang sebelumnya telah di-save atau yang mau di-save

### fungsi 'w/e/s/n\0'.

digunakan untuk pergerakan (untuk lebih lengkapnya bisa dilihat di laporan)

```
> w.
```

### fungsi 'use\1'

digunakan untuk menggunakan sesuatu

```
> use(apple)
```

### fungsi 'take\1'

digunakan untuk mengambil sesuatu di tanah

```
> take(apple).
```

### fungsi 'drop\1'

digunakan untuk membuang barang yang ada diinventori ke tanah

```
> drop(apple).
```

### fungsi 'status\0'

digunakan untuk melihat status pemain

```
> status.
```

### fungsi 'attack\0'

digunakan untuk menyerang musuh namun harus dengan senjata yang telah diuse sebelumbya (use senjata tidak perlu setiap mau menyerang asalkan sudah ada senjata yang pernah diuse penyerangan sudah bisa dilakukan)

```
> attack.
```

### fungsi 'map\0'

digunakan untuk melihat peta namun harus memiliki radar di inventory

```
> map.
```

### fungsi 'look\0'

digunakan untuk melihat sekitar

```
> look.
```

### fungsi 'surrender\0'

digunakan untuk menyetah dan 'auto lose' permainan

```
> surrender.
```

### fungsi 'makedonut\0'

digunakan untuk membuat donat namun pembuatan hanya bisa di kampus dan mengurangi thrist sebesar 10 poin.

```
> makedonut.
```

### fungsi 'quit\0'

digunakan untuk keluar dari program

```
> quit.
```

## Eksekusi Program

Penjalanan program dapat dilakukan pada OS apapun asalakan support [GNU Prolog](http://www.gprolog.org/) (sejauh ini saya tau OS yang support adalah, windows, macOs dan linux).

Program dapat dijalankan dengan 'mendouble click' file atau lewat 'consult' file 
```
consult(<namafile>)
> consult('HungerGames.pl')
```

atau dengan gplc command

```
gplc <nama file>
gplc HungerGames.pl
```

## Penting

untuk penggunaan nama konstanta yang memiliki spasi wajib menggunakan ' (petik)

```
misal : take('canned soup').
```

## Dibangun dengan

**[GNU Prolog 1.4.4](http://www.gprolog.org)** - Compiler

## Kontributor
**Rahmat Nur Ibrahim Santosa** - *Mapping, Look* - [rnsantosa](https://github.com/rnsantosa)

**Muhammad Alif Arifin** - *Start, Food, Enemy, Water, Weapon, Medicine, Status, Take, Move, Surrender, Makedonut, Attack, Map* - [AlifArifin](https://github.com/AlifArifin/)

**Rabbi Fijar Mayoza** - *Plot, Save, Load* - [Pollycarpus](https://github.com/Pollycarpus)

**Hafiz Maulana** - *Help, Drop, Use*
