Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
  ---InsertionSort---
[22,27,16,2,18,6]

[22,27,16,2,18,6] ->Step-1
[2,27,16,22,18,6] ->Step-2
[2,6,16,22,18,27] ->Step-3
[2,6,16,18,22,27] ->Step-4

---Big O---
n*(n-1)/2    -->O(n^2)

Average case:O(n^2)
Worst case:O(n^2)
Best case:O(n)

(18) sayısı average case kapsamına girer.

  ---InsertionSort_2---
[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6] ->Step-1
[2,3,4,8,7,9,5,15,6] ->Step-2
[2,3,4,5,7,9,8,15,6] ->Step-3
[2,3,4,5,6,9,8,15,7] ->Step-4
