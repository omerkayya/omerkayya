Patika.dev Veri Yapıları ve Algoritmalar projeleri

Insertion Sort Projesi

1) [22,27,16,2,18,6] sayılarını insertion sorta göre sıralayınız.
[22,27,16,2,18,6],[2,27,16,22,18,6],[2,6,16,22,18,27],[2,6,16,18,22,27]

2) Big O gösterimi
O(n^2)

3)Time compexlity 
Avarage case : aranan sayıının ortada olması
Wort case : aranan sayının sonda olması [27,22,18,16,6,2]
Best case : aranan sayının başta olması [2,6,16,18,22,27]

4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız
[2,6,16,18,22,27] dizi bu hali alır. 18 sayısı ortada olduğundan avarage case halini alır.

5)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]


Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.

1) 16,21,11,8,12,22
[16]  [21,11]   [8] [12,22]
[16] [21] [11]  [8] [12] [22] 
[11,16] [21]    [8,12] [22]
  [11,16,21,8,12,22]
  
2) Big O gösterimi
Big O : O(nlogn)

Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3                            
        / \
       2   4     




www.patika.dev
