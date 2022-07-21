Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Cevap: Öncelikle en küçük sayı bulunur ve ilk sıradaki sayı ile yer değiştirir. Örüntü tüm sayılar küçükten büyüğe oluncaya dek devam eder.
[22,27,16,2,18,6] 
--> En küçük sayı: 2 [2,27,16,22,18,6]
--> 6 [2,6,16,22,18,27]
--> 16 (Herhangi bir değişiklik yapılmadan) [2,6,16,18,22,27]
--> 18 [2,6,16,18,22,27]
--> 22 (Herhangi bir değişiklik yapılmadan) [2,6,16,18,22,27]
--> 27 (Herhangi bir değişiklik yapılmadan) [2,6,16,18,22,27]

2- Big-O gösterimini yazınız.
O(n²) = O(6²) = O(36)

3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi düzgün biçimde Insertion Sort a göre sıralandığında 18 sayısı ortada olacağından Avarage case'e girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [2,3,5,8,7,9,4,15,6] --> 7 ile 2 yer değiştirir.
2. [2,3,5,8,7,9,4,15,6] --> 2. sıradaki 3 rakamı en küçük, değişiklik yapılmadan devam eder.
3. [2,3,4,8,7,9,5,15,6] --> 5 ile 4 yer değiştirir.
4. [2,3,4,5,7,9,8,15,6] --> 8 ile 5 yer değiştirir.