Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Insertation Sort

[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

Merge Sort

[22,27,16,2,18,6]

[22,27,16] [2,18,6]

[22] [27,16] [2,18] [6]

[22] [27] [16] [2] [18] [6]

[22] [16,27] [2,18] [6]

[16,22,27] [2,6,18]

[2,6,16,18,22,27]

Quick Sort

[22,27,16,2,18,6] Pivot 18

[16,2,6] [18] [22,27]

[2] [6] [16] pivot 6 [18] [22] [27] pivot 22

[2,6,16,18,22,27]

Big-O gösterimini = O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Average Case


PROJE 2----

#[16,21,11,8,12,22] -> Merge Sort

##Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. 11,16,21,8,12,22

2. 8,11,12,16,21,22


##Big-O gösterimini yazınız.

O(nLog(n))

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

