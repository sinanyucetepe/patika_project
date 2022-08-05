Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


Soru 1) 

1.sıradaki 22 2.sıradaki ile karşılaştırılır küçük olduğu için bir değişiklik yapılmaz
[22,27,16,2,18,6]
2.adım 27 ile 16 karşılaştırılır 
[22,16,27,2,18,6]
3.adım
[16,22,27,2,18,6]
4.adım
[16,22,2,27,18,6]
5.adım
[16,2,22,27,18,6]
6.adım
[2,16,22,27,18,6]
7.adım
[]2,16,18,22,27,6]
8.adım
[2,16,18,22,6,27]
9.adım
[2,16,18,6,22,27]
10.adım
[2,16,6,18,22,27]
11.adım
[2,6,16,18,22,27]

Soru 2)

n+(n-1)+(n-2)+..+1  ==> n*(n+1)/2=((n^2)+n)/2   Big-O gösterimi O(n^2)

Soru 3)

Time Complexity: 
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Soru 4)

Avarage case aranan sayı yapının ortasında yer alacağından



[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım [7,3,5,8,2,9,4,15,6]
2.adım [3,7,5,8,2,9,4,15,6]
3.adım [3,5,7,8,2,9,4,15,6]
4.adım [3,5,7,8,2,9,4,15,6]
