# Hanoi Bulmacası Görselleştirme ve Çözme Kütüphanesi

Bu kütüphane, Hanoi kuleleri bulmacasını görselleştirmek ve çözmek için kullanılır. Aşağıda, kütüphanenin temel işlevleri ve nasıl kullanılacağına dair bilgiler bulunmaktadır.

## Kütüphane İşlevleri

### Kütüphane, aşağıdaki temel işlevlere sahiptir:

1. moveDisk(fromPeg, toPeg): Bu işlev, `fromPeg`'den `toPeg`'e en üstteki diski taşır
2. getSparePeg(fromPeg, toPeg): Bu işlev, `fromPeg` ve `toPeg`'den farklı olan üçüncü bir peg'i döndürür.
3. isSolved(toPeg): Bu işlev, bulmacanın çözülüp çözülmediğini kontrol eder ve `toPeg`'de çözülmüşse `true`, aksi takdirde `false` döndürür.

## Kullanım

Aşağıda, kütüphanenin kullanımına dair temel örnekler bulunmaktadır:

### Örnek 1: Disk Taşıma
```python
// Diski A'dan B'ye taşı
hanoi.moveDisk("A", "B");
```

### Örnek 2: Boş Pega Bulma
```python
// A ve B'den farklı olan üçüncü peg
var sparePeg = hanoi.getSparePeg("A", "B");
```
### Örnek 3: Çözüm Kontrolü
```python
// B peg'inde bulmaca çözülmüş mü?
var solved = hanoi.isSolved("B");
if (solved) {
    console.log("Bulmaca çözüldü!");
} else {
    console.log("Bulmaca çözülmedi.");
}
```
### Örnek Uygulama
Aşağıda, kütüphanenin bir örnek uygulaması bulunmaktadır:
```python
// Hanoi bulmacasını çöz
hanoi.solveHanoi(5, "A", "B");

// Bulmaca B peg'inde çözüldü mü?
var isSolved = hanoi.isSolved("B");
if (isSolved) {
    console.log("Bulmaca çözüldü!");
} else {
    console.log("Bulmaca çözülmedi.");
}

```
## Ekran Alıntısı

![Ekran Alıntısı](https://github.com/saygix/Towers-of-Hanoi-Simulation-and-Solution/assets/139467552/046089dc-e465-4075-ba49-4c9701f14a6f)
