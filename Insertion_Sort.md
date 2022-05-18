# Başlangıç Seviye Veri Bilimi Patikası
## Proje 1

[22,27,16,2,18,6] -> Insertion Sort

### 1 - Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

### Insertion sort algoritmasında, elemanın değeri kendinden önceki elemanlarla karşılaştırılır. Önceki değerden büyük olan elemanlar dizide sağa doğru kaydırılır. Böylelikle boşta kalan kısıma o an sıralanmakta olan eleman yerleştirilir. Dizi küçükten büyüğe doğru sıralanana kadar bu işlem devam eder. 

İlk değer (22) kendi başına sıralıdır yani bir elemanlıdır. Bu nedenle ikinci elemandan başlayacağız. İkinci elemanın (27) soluna bakıyoruz. 22 < 27 olduğu için bir değişiklik yapmıyoruz.

[22,27,16,2,18,6]

Bu sefer 3. elemana bakıyoruz, 27 > 16 olduğu için yer değiştirme işlemi yapıyoruz.

[22,16,27,2,18,6]

tekrar sola baktığımız zaman 22 > 16 olduğu için yine yer değiştirme işlemi yapıyoruz.

[16,22,27,2,18,6]

Bundan sonraki adımlarda da aynı mantık üzerinden hareket edilecektir.

[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]
[2,16,22,18,27,6]
[2,16,18,22,27,6]
[2,16,18,22,27,6]
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]

Insertion Sort ile sıralanmış hali : [2,6,16,18,22,27]

### 2 - Big-O gösterimini yazınız.

Genel olarak sorting algoritmalarında Quadratic Complexity ile karşılaşıldığı için Big- O gösterimi N*N sonucu ile O(N²) 'dir.


### 3 - Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average case = Dizimizin sort türüne göre sıralanmadan önceki karmaşık halini düşünelim. n(n-1)'den O(N²) 'dir.
Worst case = Dizimizin tersten sıralı olma durumunu düşünelim. n(n-1)'den  O(N²) 'dir.
Best Case = Dizimizin sıralanmış halini düşünelim. Hiçbir değişim yapılmıyor. (n-1)'den O(N)'dir.

#### 4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı dizinin ortasında bulunduğu için average case kapsamındadır.

##### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Birinci sorunun cevabında açıklanmış olan mantık uygulanacaktır.

1. Adım : [3,7,5,8,2,9,4,15,6]
2. Adım : [3,5,7,8,2,9,4,15,6]
3. Adım : [3,5,7,8,2,9,4,15,6]
4. Adım : [3,5,7,2,8,9,4,15,6]






