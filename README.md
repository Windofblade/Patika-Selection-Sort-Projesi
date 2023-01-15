# Patika-Selection-Sort-Projesi
Selection Sort Projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

1-[2,27,16,22,18,6] <--En küçük ile en soldakini yer değiştir.(n eleman)

2-[2,6,16,22,18,27] <--Sonraki küçük ile 2. elemanı yer değiştirir.(n-1)

3-[2,6,16,18,22,27] <--Sonraki küçük ile 3. elemanı yer değiştirir.(n-2) 

Küçükten büyüğe sıralama bitti.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Big-O gösterimini yazınız.

1.Durum (n) eleman 2.durum (n-1) eleman 3.durum (n-2) eleman vardır.
Formül--> n+(n-1)+(n-2)+...+1= n(n+1) /2
n^2+n /2 elde ettik. n^2 yi alıyoruz.
Sonuç--> O(n^2)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevabımız: Avarage case olacak çünkü 18 sayısı verilerin ortasında kalıyor, başta kalsaydı best case, sonda kalsaydı worst case diyebilirdik.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1-[2,3,5,8,7,9,4,15,6] <-- En küçük sayı olan 2 en sol tarafa geçerek 7 ile yer değiştirdi.
2-[2,3,4,8,7,9,5,15,6] <-- 4 sayısı 5 sayısı ile yer değiştirdi.
3-[2,3,4,5,7,9,8,15,6] <-- 5 sayısı 8 ile yer değiştirdi.
4-[2,3,4,5,6,9,8,15,7] <-- 6 sayısı 7 ile yer değiştirdi.
