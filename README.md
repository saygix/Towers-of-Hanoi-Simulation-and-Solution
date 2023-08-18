# Towers-of-Hanoi-Simulation-and-Solution
solving Hanoi recursively
-----------------------------------------------------------------------------
Bu proje, Towers of Hanoi bulmacasını simüle eden ve çözen bir görsel programın kodunu içerir. Towers of Hanoi, üç çubuk ve birkaç disk kullanarak diskleri bir çubuktan diğerine taşıma mantığına dayanan bir bulmaca oyunudur. Projenin amacı, bu bulmacanın çözümünü simüle etmek ve sonunda çözülüp çözülmediğini kontrol etmektir.

Proje içeriği şu bileşenleri içerir:

sprites: Bu bölüm, görsel öğelerin (sprite'ların) oluşturulduğu bir kütüphaneyi içerir. Sprite'lar, diskleri, çubukları ve tabloyu temsil eden grafik nesnelerdir. Her bir nesne, pozisyonları, boyutları ve diğer özellikleri ile birlikte tanımlanmıştır.

objects: Bu bölüm, projenin ana mantığını içerir. Peg (çubuk), Disk (disk) ve Table (tablo) gibi nesneleri oluşturur. Diskler çubuklar arasında hareket edebilir ve bulmacanın çözümünü simüle eder.

convertLetterToPeg: Bu fonksiyon, harfle temsil edilen çubukları ilgili çubuk nesnesine dönüştürür.

moveDisk: Bu fonksiyon, bir diskin bir çubuktan diğerine taşınmasını simüle eder. Ayrıca geçersiz hareketleri engellemek için gerekli kontrolleri yapar.

getSparePeg: Bu fonksiyon, verilen iki çubuktan hareket eden diskler için üçüncü bir çubuğun adını döndürür.

isSolved: Bu fonksiyon, bulmacanın çözülüp çözülmediğini kontrol eder.

solveHanoi: Bu fonksiyon, Towers of Hanoi bulmacasının tam çözümünü sağlar. İleri bir rekürsif yöntem kullanarak diskleri çubuklar arasında taşır.

Projenin tamamı, JavaScript tabanlı bir programlama ortamında çalışmaktadır ve görüntülemesi, simülasyonu ve sonuçları görüntülemek için kullanılabilecek grafiksel öğeler içerir.
