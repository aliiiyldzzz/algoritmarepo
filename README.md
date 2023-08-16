# algoritmarepo

Soru 1 - Selection Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması. . [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

#Insertion Sort
Verilen dizi [22, 27, 16, 2, 18, 6] için Insertion Sort adımları:

[22, 27, 16, 2, 18, 6]
[22, 27, 16, 2, 18, 6]
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]


#Big-O Gösterimi
N elemanlı bir diziyi sıralamak için:

1 + 2 + ... + (n-1) + n

= (n * (n+1)) / 2

= (n² + n) / 2

= O(n²)

#Time Complexity
Average case: Aradığımız sayının ortada olması



[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisi için Selection Sort:
Selection Sort adımları (ilk 4 adım):

[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
Soru 2 - Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Diziyi ortadan ikiye böleriz.
[16, 21, 11] | [8, 12, 22]
Her iki yarı diziyi aynı işlemle tekrar böleriz.
[16] | [21, 11]
[16] | [21] | [11]
[8, 12] | [22]
[8] | [12]
[8] | [12, 22]
Bölünmüş dizileri sıralı bir şekilde birleştiririz.
[16] | [11, 21]
[11, 16, 21]
[8] | [12, 22]
[8, 12, 22]
İki sıralı yarı diziyi birleştirerek sonuç dizisini elde ederiz.
[11, 16, 21] | [8, 12, 22]
[8, 11, 12, 16, 21, 22]
Big-O Gösterimi
Big-O gösterimi O(n * logn)'dir

Soru 3 - Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

7 root'tur.
5, 7'nin solunda yer alır.
1, 7'nin solunda yer alır.
8, 7'nin sağındadır.
3, 5'in sağındadır.
6, 7'nin sağındadır.
0, 1'in solunda yer alır.
9, 8'in sağındadır.
4, 5'in sağındadır.
2, 1'in sağındadır.
