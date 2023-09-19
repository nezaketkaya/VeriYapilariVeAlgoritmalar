## [22,27,16,2,18,6] -> Insertion Sort
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Answer:
[22, 27, 16, 2, 18, 6] (27'i 22'nin sağına taşı)
[22, 27, 16, 2, 18, 6] (27 ile 22 yer değiştirir)
[22, 27, 16, 2, 18, 6] (16'yı 27'nin soluna taşı)
[22, 16, 27, 2, 18, 6] (27 ile 16 yer değiştirir)
[16, 22, 27, 2, 18, 6] (22 ile 16 yer değiştirir)
[16, 22, 27, 2, 18, 6] (2'yi 27'nin soluna taşı)
[16, 22, 2, 27, 18, 6] (27 ile 2 yer değiştirir)
[16, 2, 22, 27, 18, 6] (22 ile 2 yer değiştirir)
[2, 16, 22, 27, 18, 6] (16 ile 2 yer değiştirir)
[2, 16, 22, 27, 18, 6] (18'i 27'nin soluna taşı)
[2, 16, 22, 18, 27, 6] (27 ile 18 yer değiştirir)
[2, 16, 18, 22, 27, 6] (22 ile 18 yer değiştirir)
[2, 16, 18, 22, 27, 6] (16 ile 2 yer değiştirir)
[2, 6, 16, 18, 22, 27] (6 ile 18, ardından 6 ile 16 yer değiştirir)

### Big-O gösterimini yazınız.
Answer: O(n^2)

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.
   
Answer: Average case: Aradığımız sayının ortada olması


### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Answer:
Dizinin en küçük elemanını bulmak için tarama yapılır. Minimum değer 2'dir (dizi indeksi 4).
Minimum değeri başlangıçta 2. eleman (5) olarak kabul ederiz.

Minimum değer ile ilk eleman (7) değiştirilir, böylece dizi şu şekilde olur: [5, 3, 7, 8, 2, 9, 4, 15, 6]
Minimum değer güncellenir ve artık 2. eleman (3) olarak kabul edilir.

Minimum değer ile 2. eleman (3) ile sonraki elemanlar karşılaştırılır ve minimum değer güncellenir. En küçük değer 2'dir (dizi indeksi 4).
Minimum değer ile 2. eleman (3) değiştirilir, böylece dizi şu şekilde olur: [5, 2, 7, 8, 3, 9, 4, 15, 6]
Minimum değer güncellenir ve artık 5. eleman (3) olarak kabul edilir.

Minimum değer ile 5. eleman (3) ile sonraki elemanlar karşılaştırılır ve minimum değer güncellenir. En küçük değer 2'dir (dizi indeksi 7).
Minimum değer ile 5. eleman (3) değiştirilir, böylece dizi şu şekilde olur: [5, 2, 4, 8, 7, 9, 3, 15, 6]
Minimum değer güncellenir ve artık 7. eleman (3) olarak kabul edilir.


