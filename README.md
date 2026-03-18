# Insertion Sort
# 1. Proje: Insertion Sort

[22, 27, 16, 2, 18, 6] dizisinin Insertion Sort aşamaları:
Dizinin elemanlarına sırayla bakarız ve baktığımız eleman en küçük elemandan küçükse en başa,en son baktığımız eleman gelir.

1. Adım: `[22, 27, 16, 2, 18, 6]` (27, 22'den büyük olduğu için yeri değişmez)
2. Adım: `[16, 22, 27, 2, 18, 6]` (16, en küçük olduğu için başa gelir)
3. Adım: `[2, 16, 22, 27, 18, 6]` (2, en küçük olduğu için en başa gelir)
4. Adım: `[2, 16, 18, 22, 27, 6]` (18, 16 ile 22'nin arasına girer)
5. Adım: `[2, 6, 16, 18, 22, 27]` (6, 2 ile 16'nın arasına girer ve dizi sıralanır)

 Big-O Gösterimi
Insertion Sort algoritmasının Big-O gösterimi: O(n^2)

 Time Complexity
Dizi sıralandıktan sonra şu hali alır: `[2, 6, 16, 18, 22, 27]`
Aradığımız sayı olan 18, dizinin ortasında yer almaktadır. Ne en başta (Best Case) ne de en sondadır (Worst Case). Bu nedenle 18 sayısı AVERAGE CASE kapsamına girer.

---

2. Proje: Selection Sort

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı:

1. Adım: `[2, 3, 5, 8, 7, 9, 4, 15, 6]` (Tüm dizideki en küçük sayı 2'dir, en baştaki 7 ile yer değiştirir.)
2. Adım: `[2, 3, 5, 8, 7, 9, 4, 15, 6]` (İkinci sıradan sonrasındaki en küçük sayı 3'tür, zaten 2. sırada olduğu için yeri değişmez.)
3. Adım: `[2, 3, 4, 8, 7, 9, 5, 15, 6]` (Üçüncü sıradan sonrasındaki en küçük sayı 4'tür, 3. sıradaki 5 ile yer değiştirir.)
4. Adım: `[2, 3, 4, 5, 7, 9, 8, 15, 6]` (Dördüncü sıradan sonrasındaki en küçük sayı 5'tir, 4. sıradaki 8 ile yer değiştirir.)
